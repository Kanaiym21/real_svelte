<script>
import Title from '$lib/title.svelte'
import '../styles/global.css'
</script>

<header>
    <!-- svelte-ignore missing-declaration -->
    <Title title="Svelte Guides" />
</header>

<main>
<slot></slot>
</main>

<footer>
    <p>Copyright 2023 Kanaiym Abdigaparova</p>
</footer>

<style>
    header {
        display: flex;
        justify-content: center;
    }
    main {
        max-width: 960px;
        margin: 20px auto;
    }
    footer {
        text-align: center;
    }
</style>