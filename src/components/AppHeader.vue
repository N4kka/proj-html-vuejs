<template>
  <header>
    <div class="logo-image">
      <img src="../assets/images/construction_logo.png" alt="" />
    </div>
    <div class="header-menu">
      <i class="fa-solid fa-angle-down"></i>
      <ul class="menu-list">
        <li v-for="(item, index) in menu" :key="index">{{ item.services }}</li>
      </ul>
      <button>GET QUOTE</button>
    </div>
  </header>
</template>

<script>
export default {
  name: "AppHeader",
  data() {
    return {
      menu: [
        { services: "home" },
        { services: "about" },
        { services: "services" },
        { services: "work" },
        { services: "articles" },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
header {
  height: 120px;
  padding: 1rem 5rem;
  display: flex;
  justify-content: space-between;
  background-color: white;

  .header-menu {
    display: flex;
    align-items: center;
    font-weight: 200;
    color: gray;

    button {
      width: 150px;
      height: 40px;
      border: 0;
      color: gray;
      background-color: #fed23f;
    }
  }

  .menu-list {
    display: flex;
    list-style: none;

    li {
      padding: 0 20px;
      text-transform: uppercase;
    }
  }
}
</style>
