<template>
  <div class="hero">
    <img src="../assets/Frame.png" alt="" />
    <div class="blur-overlay"></div>
  </div>
</template>

<style scoped>
.hero {
  width: 100%;
  height: 60rem;
  position: relative;
  overflow: hidden;
  margin-bottom: 20rem;
}

.hero img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

/* Blur bagian bawah */
.blur-overlay {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 150px;
  background: inherit;
  backdrop-filter: blur(20px); /* efek blur nyata */
  mask-image: linear-gradient(to top, black, transparent);
  -webkit-mask-image: linear-gradient(to top, black, transparent);
  pointer-events: none;
}
</style>
