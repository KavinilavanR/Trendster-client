
<script>
    
    import Input from "../../components/textfield/index.svelte"
    import SearchIcon from "../../assets/icons8-search.svg"
    let value =""

</script>
<style>
    .navbar{
        display: flex;
        flex-direction: row;
        height: 60px;
        /* gap: 16px; */
        flex-wrap: wrap;
        background-color: aquamarine;
    }

    
</style>
<link rel ='stylesheet' href ='/style.css'>
<div class ='navbar'>
<Input bind:name = {value} placeholder="search" classes = 'search'/>

<i class="fa-solid fa-arrow-right-to-bracket"></i> 

<img  class = 'search-icon' src = {SearchIcon} heigth = "40px" width="25px" alt = 'shriram neethanda kaaranam' >

</div>  

