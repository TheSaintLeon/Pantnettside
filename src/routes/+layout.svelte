<script>
    import "../global.css";
    import "@fontsource-variable/overpass";
    import Navbar from "./Navbar.svelte";
    import { onMount } from "svelte";

    onMount(() => {
        const audio = new Audio("/HOAMP3.mp3");

        //audio.play();

        audio.loop();
    });
</script>

<Navbar />
<slot />
