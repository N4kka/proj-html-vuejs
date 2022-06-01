<template>
  <section class="stats">
    <div class="stats__description" v-for="(item, index) in stats" :key="index">
      <i :class="item.icon"></i>
      <h4>{{ item.number }}</h4>
      <p>
        {{ item.text }}
      </p>
    </div>
  </section>
</template>

<script>
export default {
  name: "AppStats",
  data() {
    return {
      stats: [
        {
          icon: "fas fa-suitcase fa-4x",
          number: "3534",
          text: "PLANNING APPLICATIONS",
        },
        {
          icon: "far fa-building fa-4x",
          number: "896",
          text: "COMPLETED PROJECTS",
        },
        {
          icon: "fas fa-users fa-4x",
          number: "172",
          text: "TRAINED PROFERSSIONALS",
        },
        {
          icon: "fas fa-globe fa-4x",
          number: "19",
          text: "ITERNATIONAL OFFICES",
        },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
.stats {
  height: 400px;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  background-image: url(../assets/images/home-244125289.jpg);
  background-position: left;

  &__description {
    color: #fed23f;
    text-align: center;

    h4 {
      margin-top: 15px;
      font-size: 3rem;
    }

    p {
      color: white;
    }
  }
}
</style>