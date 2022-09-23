<template>
    <div style="width: max-content">
        <div class="titlecard">
            <div class="text">
                <p>
                    Hi, I'm Austin.
                </p>
                <p>
                    I'm a university student studying computer science at <a style="color: #26BEE8; font-weight: bold;" href="https://www.cs.nycu.edu.tw/" target="_blank">NYCU</a>.
                </p>
                <p>
                    You have reached my personal blog where I write about stuff. (´･Д･)」
                </p>
            </div>
            <div class="img">
                <img src="/public/meme.jpg" style="width: inherit"/>
                <p style="margin: 0;">
                    哈哈笑死這根本就是我
                </p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    components: {
    },
    data () {
        return {
        }
    }
}
</script>

<style scoped>
.titlecard {
    width: max-content;
    display: flex;
    justify-content: center; 
    align-items: center;
}

.text {
    font-size: 2rem;
    font-weight: 500;
    margin: 0;
    width: 36rem;
    margin-right: 6rem;
}

.img {
    width: 20rem;
    height: 17rem;
}

p {
    margin: 0.8rem;
}
</style>