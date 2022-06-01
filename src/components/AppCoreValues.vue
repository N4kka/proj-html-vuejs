<template>
  <section>
    <div class="core-values">
      <h2>O<span>ur Core Value</span>s</h2>
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Tempora et
        voluptatem magni hic eveniet quaerat sed, sapiente ipsa, quos
        necessitatibus atque.
      </p>
    </div>
    <div class="values">
      <div
        class="values-description"
        v-for="(item, index) in values"
        :key="index"
      >
        <i :class="item.icon"></i>
        <p>{{ item.title }}</p>
        <p>{{ item.text }}</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AppCoreValues",
  data() {
    return {
      values: [
        {
          icon: "fas fa-home skye-blue",
          title: "Great Services",
          text: "Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consecutur adipisci velit, sed quia.",
        },
        {
          icon: "fas fa-cog blue",
          title: "Highest Standards",
          text: "Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consecutur adipisci velit, sed quia.",
        },
        {
          icon: "fas fa-users orange",
          title: "Professional Team",
          text: "Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consecutur adipisci velit, sed quia.",
        },
        {
          icon: "far fa-lightbulb green",
          title: "Creative Solutions",
          text: "Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consecutur adipisci velit, sed quia.",
        },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
.core-values {
  width: 50%;
  height: 50%;
  margin: 5rem auto;
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
}

.values {
  width: 75%;
  margin: 0 auto 3rem;
  display: flex;

  .values-description {
    margin: 0 25px;
    text-align: center;

    i {
      padding: 20px;
      border-radius: 50%;
      font-size: 4rem;
      color: white;
    }

    .skye-blue {
      background-color: #4ea4a5;
    }

    .blue {
      background-color: #4e6da5;
    }

    .orange {
      background-color: #f6722a;
    }

    .green {
      background-color: #a7cf47;
    }
  }
}
</style>