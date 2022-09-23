<template>
  <div class="pageWrap">
    <div class="pageBody">
      <TitleCard class="blocks" />
      <div class="blocks" style="width: max-content">
        <p>This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. </p>
        <p>This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. </p>
        <p>This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. </p>
        <p>This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. </p>
        <p>This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. </p>
        <p>This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. </p>
        <p>This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. </p>
        <p>This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. </p>
        <p>This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. </p>
        <p>This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. </p>
        <p>This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. </p>
        <p>This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. </p>
        <p>This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. </p>
        <p>This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. </p>
        <p>This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. </p>
        <p>This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. </p>
        <p>This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. This is a place holder for testing. </p>
      </div>
      <Footer class="blocks" />
      <!--
        recent posts
        music tier list
        movie tier list
        footer
      -->
    </div>
  </div>
</template>

<script>
import TitleCard from './TitleCard.vue';
import Footer from './Footer.vue';

export default {
    components: {
      TitleCard,
      Footer
    },
    data () {
        return {
            
        }
    }
}
</script>

<style scoped>
.pageBody {
    width: 100%;
    max-width: 1440px;
    padding-top: 3.5rem;
    overflow: hidden;
}

.pageWrap {
    display: flex;
    justify-content: center; 
    align-items: center;
}

.blocks {
    margin-top: 4rem;
    margin-bottom: 4rem;
    display: block; 
    margin-left: auto; 
    margin-right: auto;
}
</style>
