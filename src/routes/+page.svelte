<script>
    import Micomponente from "./Micomponente..svelte";

    let color = "brown";

    function cambia() {
        if(color === "brown") {
            color = "red";
        } else if(color === "red") {
            color = "brown";
        }
    }
</script>

<h2>
    Habla de mi pagina principla
</h2>

<h1>
    Este es un H1 de la pagina principal
</h1>
<Micomponente mensajito="Melina" color="blue"/>

<Micomponente mensajito="Hola" color={color} />

<Micomponente mensajito="Adios" color="purple" />  

<Micomponente mensajito="Como estas" color="yellow" />

<button onclick={cambia}>Melina</button>
