<script>
    export let name;
    export let placeholder = "";
    export let required = false;
    export let disabled = false;
</script>

<input type =text bind:value = {name} placeholder={placeholder} required= {required} disabled ={disabled}>