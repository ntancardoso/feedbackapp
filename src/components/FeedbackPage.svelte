<script>
    import {Link} from 'svelte-routing'
    import FeedbackForm from './FeedbackForm.svelte'
    import FeedbackList from './FeedbackList.svelte'
    import FeedbackStats from './FeedbackStats.svelte'
</script>
<div class="container">
    <FeedbackForm />
    <FeedbackStats />
    <FeedbackList />

    <Link to="/">
        <button class="button" >Home</button>
    </Link>
</div>
