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

        <br>
        <br>

        <img src="TitleScreens.png" alt="A game start screen with a skull in the middle and eyes surrounding it, the text press start at the bottom of it." width="300" height="300">

        <p>God Is Dead is a roguelike, turn-based combat, boss rush game.</p>
        <p>You must fight ten creations of a fallen god to claim the throne as the new god.</p>
        <p>Death is a choice or punishment, where the you will be reborn again at the begining of the game.</p>
        <p>Take the attacks from your foes to build your moveset...or don't.</p>
        <p>The choice is yours.</p>
        <p>Talk with the creations to uncover more about the fallen god.</p>

        <br>
        <br>
        <br>

        <div class="formButton">
            <form action="https://altered-strains.itch.io/god-is-dead">
    
        
                    <button type="submit">Go To Itch.io Page</button>
        

            </form>
    </div>

</div>

<br>
<br>

</body>



<style>

    body {
  font-family: 'Jersey 15', system-ui;
}
  
</style>