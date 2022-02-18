<script>
    import NavBar from "$lib/NavBar.svelte";
    import BookingButton from "$lib/BookingButton.svelte";
</script>

<div class="home">
    <NavBar />

    <section class="landing">
        <h1 class="text">Welcome to Healing Coast Chiropractic</h1>
        <p class="text">We really need some style..</p>
    </section>
</div>




<style>
    @import url('https://fonts.googleapis.com/css2?family=Arimo&display=swap');

    /* :global(html) {
        max-width: 100%;
        overflow-x: hidden;
    } */

    .home {
        max-width: 100%;
        overflow-x: hidden; 
    }


    .landing {
        height: 100vh;
        width: 100vw;
        background-color: bisque;
        
    }

    .text {
        font-family: Armio, sans-serif;
        /* margin: 15px; */
    }
    .landing h1 {
        font-size: 2rem;
    }

    .landing p {
        font-size: 1.2rem;
    }
</style>