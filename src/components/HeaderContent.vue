<template>
  <div class="app">
    <div class="container-fluid" :style="image">
      <div class="container">
        <div class="row">
          <div class="col-6">
            <ul class="d-flex text-center justify-center">
              <li class="items"><a href="#">Home</a></li>
              <li class="items"><a href="#">Document</a></li>
              <li class="items"><a href="#">Pages</a></li>
              <li class="items"><a href="#">Blog</a></li>
              <li class="items"><a href="#">Contact</a></li>
            </ul>
          </div>
          <div class="col-2"></div>
          <div class="col-4" data-bs-theme="dark">
            <div class="form-check form-switch mx-4">
              <input
                class="form-check-input p-2"
                type="checkbox"
                role="switch"
                id="flexSwitchCheckChecked"
                checked
                @click="myFunction()"
              />
              <button class="btn bg-primary text-white">Login</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      image: {
        backgroundImage:
          "url(https://png.pngtree.com/thumb_back/fh260/background/20230615/pngtree-landscape-landscape-photo-image_2902263.jpg",
      },
    };
  },
  methods: {
    myFunction() {},
  },
};
</script>

<style>
.items {
  margin-left: 50px;
  padding: 5px;
}
</style>
