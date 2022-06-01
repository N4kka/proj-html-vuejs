<template>
  <section class="partners">
    <h2>Tr<span>usted Partner</span>s</h2>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Tempora et
      voluptatem magni hic eveniet quaerat sed, sapiente ipsa, quos
      necessitatibus atque.
    </p>
    <div class="partners__img">
      <div class="images" v-for="(item, index) in partners" :key="index">
        <img :src="require(`../assets/images/${item.img}`)" alt="" />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AppFifthSection",
  data() {
    return {
      partners: [
        {
          img: "home-logo11-219096700-320x202.png",
        },
        {
          img: "home-logo10-219096700-320x202.png",
        },
        {
          img: "home-logo2-219096700-320x202.png",
        },
        {
          img: "home-logo1-219096700-320x202.png",
        },
        {
          img: "home-logo9-219096700-320x202.png",
        },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
.partners {
  width: 50%;
  height: 50%;
  margin: 1rem auto;
  display: flex;
  flex-direction: column;
  justify-content: center;
  font-weight: 200;
  text-align: center;

  h2 {
    margin-bottom: 2rem;
  }

  span {
    border-bottom: 2px solid #fed23f;
  }

  p {
    margin-bottom: 2rem;
  }

  &__img {
    display: flex;

    img {
      width: 100%;
      margin-bottom: 2rem;
    }
  }
}
</style>