<template>
  <nav class="global-nav">
    <div class="navbar-content">
      <ul class="nav-list">
        <li class="nav-link logo"></li>
        <li class="nav-link">Store</li>
        <li class="nav-link">Mac</li>
        <li class="nav-link">iPad</li>
        <li class="nav-link">iPhone</li>
        <li class="nav-link">Watch</li>
        <li class="nav-link">AirPods</li>
        <li class="nav-link">TV & Maison</li>
        <li class="nav-link">Exclusivités Apple</li>
        <li class="nav-link">Accessoires</li>
        <li class="nav-link">Assistance</li>
        <li class="nav-link search"></li>
        <li class="nav-link bag"></li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.global-nav {
  background-color: #000;

  .navbar-content {
    max-width: 980px;
    height: 44px;
    margin: 0 auto;

    .nav-list {
      display: flex;
      justify-content: space-between;
      margin: 0;
      height: 100%;
      color: #fff;
      padding: 0;

      .nav-link {
        list-style: none;
        font-size: 12px;
        height: 100%;
        cursor: pointer;
        padding: 0 8px;
        background-repeat: no-repeat;
        transition-duration: 200ms;
        font-weight: normal;
        font-family: "SF Pro Text";
        opacity: 0.8;
        line-height: 44px;

        &:hover {
          transition-duration: 200ms;
          opacity: 1;
        }

        &.logo {
          width: 14px;
          background-image: url("../assets/apple-logo.svg");
          background-size: 14px 44px;
          background-position: center center;
        }

        &.search {
          width: 15px;
          background-image: url("../assets/search-icon.svg");
          background-size: 15px 88px;
        }

        &.bag {
          background-image: url("../assets/bag-icon.svg");
          background-size: 13px 44px;
          background-position: center center;
          width: 13px;
        }
      }
    }
  }
}
</style>
