<template>
  <div class="row gx-0">
    <div class="col-12 m-0">
      <div class="main mt-5">
        <div class="bener">
          <div class="text-center pt-5 title">
            <img src="../assets/sub.png" alt="subtitle" />
          </div>
          <div class="search">
            <div class="input-search">
              <input type="search" placeholder="Search" />
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="pages">
      <div class="col-12 container">
        <div class="text mt-5 d-flex justify-content-between">
          <h3>Popular things to do</h3>
          <p>See all</p>
        </div>
      </div>
      <div class="container my-5">
        <div class="row">
          <div class="col-4">
            <img src="../assets/Link.png" alt="test" />
          </div>
          <div class="col-8">
            <div class="img1">
              <img src="../assets/Link (1).png" alt="" class="me-4" />
              <img src="../assets/Link (2).png" alt="" />
            </div>
            <div class="img2 mt-4">
              <img src="../assets/Link (3).png" alt="" class="me-4" />
              <img src="../assets/Link (4).png" alt="" class="me-4" />
              <img src="../assets/Link (5).png" alt="" />
            </div>
          </div>
          <div class="why mt-5">
            <h3>Why choose Tourz</h3>
            <div class="content-card mt-5">
              <div class="content1">
                <img src="../assets/icon (1).png" alt="" />
                <div class="text"></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // **WAJIB**: beri nama multi‑word yang sama dengan file
  name: "NavbarMain",
  // props, data, methods, etc.
};
</script>

<style scoped>
.bener {
  width: 100%;
  height: 56rem !important;
  background-image: url(../assets/Frame.png);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  margin: 0;
  padding: 0;
}
.search {
  width: 100%;
  display: flex;
  justify-content: center;
  margin-top: 3rem !important;
}
.input-search {
  width: 30%;
  height: 4rem !important;
  background-color: #ffff;
  border-radius: 10rem !important;
  overflow: hidden;
}
.input-search input {
  width: 100%;
  height: 100%;
  outline: none;
  border: none;
  padding: 0 2rem !important;
  font-size: 1.2rem !important;
  color: rgb(161, 166, 166);
}

.pages {
  width: 100%;
  background-color: white;
}
/* content icon */
.content1 {
  width: 17rem;
  height: 15rem;
  background-color: red;
}
</style>
