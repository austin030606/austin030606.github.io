<template>
    <div class="NavBar">
        <ul class="NavBarOptions">
            <li>
                <router-link to="/" class="NavBarOption">HOME</router-link>
            </li>
            <li>
                <router-link to="/posts" class="NavBarOption">POSTS</router-link>
            </li>
            <li>
                <router-link to="/about" class="NavBarOption">ABOUT</router-link>
            </li>
        </ul>
    </div>
</template>

<script>

</script>

<style scoped>
.NavBar {
    height: max-content;
    width: 100%;
    background-color: #262626;
    position: fixed;
    overflow: hidden;
    display: flex;
    justify-content: center; 
    align-items: center;
}
.NavBarOptions {
    width: 100%;
    max-width: 1440px;
    list-style-type: none;
    padding-left: 2rem;
    display: flex;
    margin: 0;
    margin-top: 1rem;
}

.NavBarOption {
    text-align: center;
    font-size: 1.2rem;
    font-weight: 400;
    color: white;
    padding-bottom: 0.8rem;
    padding-left: 1rem;
    padding-right: 1rem;
}

.router-link-active, .router-link-exact-active {
    font-weight: bold;
    padding-bottom: 0.5rem;
    border-bottom: 0.3rem solid #26BEE8;
}

a {
    color: white;
    text-decoration: none;
}

li {
    width: 6rem;
    display: flex;
    justify-content: center; 
    align-items: center;
}
</style>