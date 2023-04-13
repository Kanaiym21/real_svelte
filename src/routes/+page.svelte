<script>
let title  = 'Svelte starter'

const updateTitle = () => {
    title = "different"
}
</script>

<div class = "index">
    <h2>{title}</h2>
    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam maxime sunt blanditiis excepturi cupiditate ea? Minus dolorem commodi ducimus explicabo quasi, sapiente nulla alias nihil laudantium. Obcaecati impedit tempora veniam?
    </p>
    <button on:click={updateTitle}>change title</button>
    <input type="text" bind:value={title}>
</div>

<style>
    .index {
        text-align: center;
        display: block;
        margin: 20px auto;
    }
</style>