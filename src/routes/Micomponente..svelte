<script>
    let {mensajito, color} = $props()
</script>


<h1>
    Este es el componente <span style="color: {color}">{mensajito}</span>
</h1>

<style>
    h1 {
        color: red;
    }
</style>