<template>
  <section>
      <img src="https://images.unsplash.com/photo-1472289065668-ce650ac443d2?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1169&q=80" alt="">
      <div class="banner-text">
        <h1>This is an Hero Heading</h1>
        <h4>and this is a Sub Heading, because, why not!?</h4>
      </div>
  </section>
</template>

<script>
export default {
    name: 'Hero',
}
</script>

<style scoped>
    section {
        width: 100vw;
        height: 550px;
        position: relative;
        display: flex;
        align-items: center;
        justify-content: center;
        background-color: red;
        margin: 20px 0 20px 0;
        color: black;
    }

    section img {
        filter: brightness(80%);
        width: 100vw;
        height: 100%;
        object-fit: cover;
        object-position: top left;
    }

    section .banner-text {
        position: absolute;
        right: 150px;
    }

    .banner-text h1 {
        font-size: 55px;
    }

    .banner-text h4 {
        font-size: 20px;
        text-align: right;
        transform: translateY(10px);
    }
</style>