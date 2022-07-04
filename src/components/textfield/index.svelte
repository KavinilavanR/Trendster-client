<script>
    export let name;
    export let placeholder = "";
    export let required = false;
    export let disabled = false;
    export let classes = "text";
    let value = "100px";
</script>
<style>
   
    input[type =text] {
        
        border-radius:5px;
        height:40px;
        margin: 10px 20px;
    }
    .search{
        width:329px;
    }
</style>
<input class ={classes} type =text bind:value = {name} placeholder = {placeholder} required = {required} disabled = {disabled}>