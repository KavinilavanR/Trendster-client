<script>
    
    import Input from "../../components/textfield/index.svelte"
    import SearchIcon from "../../assets/icons8-search.svg"
    let value

</script>

<div class ='navbar'>
<Input bind:name = {value}/>
<img  class = 'search-icon' src = {SearchIcon} alt = 'shriram neethanda kaaranam' >

</div>  