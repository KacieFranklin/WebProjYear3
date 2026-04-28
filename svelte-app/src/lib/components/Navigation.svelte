<script>
    import { base } from '$app/paths';
</script>

    <nav>
        <ul>
            <li><a href="{base}/">Home</a></li>
            <li><a href="{base}/story">Story</a></li>
            <li><a href="{base}/characters">Characters</a></li>
            <li><a href="{base}/moves">Moves</a></li>
        </ul>
    </nav>

<style>

    nav ul {
        
        list-style: none;
        background: fixed;
        background-color: var(--background-color);
        padding:60px;
        margin:0;
        display: flex;
        justify-content: right;
    }

    nav ul li {
        margin: 0 15px;
    }

    nav ul li :hover {
        text-decoration: underline;
        color: var(--primary-color);
        font-weight: bold;
    }

</style>