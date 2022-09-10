<template>
    <div class="NavBar">
        <ul class="NavBarOptions">
            <li class="NavBarOption">
                <router-link to="/">HOME</router-link>
            </li>
            <li class="NavBarOption">
                <router-link to="/posts">POSTS</router-link>
            </li>
            <li class="NavBarOption">
                <router-link to="/about">ABOUT</router-link>
            </li>
        </ul>
    </div>
</template>

<script>

</script>

<style scoped>
.NavBar {
    width: 100%;
    height: 4vw;
    background-color: #262626;
    position: fixed;
    overflow: hidden;
}
.NavBarOptions {
    list-style-type: none;
    margin: 0;
    margin-top: 1vw;
    padding: 0;
    padding-left: 3vw;
    display: flex;
}

.NavBarOption {
    font-size: 1.4vw;
    font-weight: 500;
    color: white;
    margin-right: 2vw;
}

a {
    color: white;
    text-decoration: none;
}
</style>