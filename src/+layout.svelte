<script>
    import "./app.css"
    import { onMount } from "svelte";

    onMount(()=>{
        window.location.replace("/login")
    })
</script>
<slot/>


<p>redireccionandote guapo(a)</p>