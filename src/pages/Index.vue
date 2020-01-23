<template>
  <Layout class="main">
    <video autoplay muted loop id="myVideo">
      <source src="https://res.cloudinary.com/tonipanoche/video/upload/v1579822012/transition_j5cj2u.mp4" type="video/mp4">
    </video>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Transition Institute'
  }
}
</script>

<style lang="scss">
body {
  margin: 0;
  padding: 0;
}
#myVideo {
  position: fixed;
  right: 0;
  bottom: 0;
  width: 100vw;
  height: 100vh;
  margin: 0;
  padding: 0;
}
</style>
