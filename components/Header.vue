<template>
    <header>
        <div class="title">
            <nuxt-link to="/">My Blog</nuxt-link>
        </div>
        <nav>
            <nuxt-link to="/">Home</nuxt-link>
            <nuxt-link to="/about">About</nuxt-link>
        </nav>
    </header>
</template> 

<script>
export default {
    
}
</script>

<style>
header{
    padding: 15px 30px;
    background-color: aqua;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.1);
}
header .title {
    color: rgb(112, 112, 112);
    font-size: 24px;
    font-weight: 900;
    text-transform: uppercase;
}

nav {
    display: flex;
    align-items: center;
    margin: 0 -15px;
}
nav a{
    display: block;
    margin: 0 15px;
    color: #9f25cf;
    font-weight: 400;
    background-color: aquamarine;
    padding: 10px;
    border-radius: 10px;
    
}
nav a:hover{
    background-color: rgb(64, 241, 182);
    
}
</style>