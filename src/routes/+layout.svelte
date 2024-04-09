<script>
    import "../app.css"
    import "@fontsource/nunito";
</script>

<style>
    nav {
        @apply
            fixed
            left-0
            top-0
            w-24
            h-full
            flex
            flex-col
            bg-blue-800
            p-4
            text-white
            text-sm
            font-semibold
            space-y-2
    }
</style>

<nav>
    <h5>Contents</h5>
    <div>Characters</div>
    <div>Races</div>
    <div>Classes</div>
</nav>

<slot />