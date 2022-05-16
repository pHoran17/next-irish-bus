<script>

</script>

<template>
    <div class="MenuContainer">
        <div class="MenuButton">
            <img src="./assets/menu-regular-24.png">
        </div>
        <div class="searchBar">
            <input type="text" placeholder="Search Route"/>
            <img src="./assets/search-alt-2-regular-24.png" id="searchImage"/>
        </div>
    </div>
</template>

<style>
    .MenuContainer
    {
    padding: 20px;
    background-color: orange;
    width:100%;
    max-width: 1920px;

    }

    .MenuButton
    {
    width:20px;
    height: 20px;
    /* position: relative; */
    display: inline;
    left:0px;
    margin-right: 200px;
    }
    .searchBar
    {
    display: inline;
    position: absolute;
    right:0px;
    width: 400px;
    /* height: 40px; */
    margin-left: 200px;
    }
    #searchImage
    {
    margin-left: 10px;
    margin-right: 10px;
    }
</style>