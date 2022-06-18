<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNavAltMarkup"
          aria-controls="navbarNavAltMarkup"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
      </a>

      <div class="navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <a class="nav-link active" aria-current="page" href="#">全部</a>
          <a class="nav-link" href="#">
            <!-- <form class="d-flex"> -->
            <!-- <input class="form-control me-1" type="search" placeholder="請輸入商品名稱" aria-label="請輸入商品名稱"> -->
            <font-awesome-icon icon="fa-solid fa-magnifying-glass" />
            <!-- </form> -->
          </a>
          <div>
            <a class="nav-link" href="#"><font-awesome-icon icon="fa-solid fa-user" />登入/註冊</a>
          </div>
          <div>
            <a class="nav-link" href="#"><font-awesome-icon icon="fa-solid fa-heart" />追蹤清單</a>
          </div>
          <div>
            <a class="nav-link" href="#"><font-awesome-icon icon="fa-solid fa-cart-shopping" />購物車</a>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {

}
</script>

<style scoped>

</style>