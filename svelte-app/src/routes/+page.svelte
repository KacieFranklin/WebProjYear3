<svelte:head><title>Home</title></svelte:head>


<script>
    import { onMount } from 'svelte';

    onMount(() => {
        console.log("Home Page Loaded");
    });

</script>

<title>Home Page</title>
<body>

    <div id="page-content">
    <h1>Hi:</h1>

    <div class="formButton">
        <form action="https://altered-strains.itch.io/god-is-dead">
    
        
                <button type="submit">Go To Itch.io Page</button>
        

        </form>
    </div>

</div>
</body>



<style>

    body {
  font-family: 'Jersey 15', system-ui;
}
  
</style>