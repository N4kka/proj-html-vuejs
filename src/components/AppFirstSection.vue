<template>
  <section>
    <div class="quote">
      <h3>Do You Have a Construction Project We Can Help With?</h3>
      <button>GET A FREE QUOTE</button>
    </div>
    <div class="description">
      <h3>Special <span>In Modern Co</span>nstruction</h3>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua ut enim ad minim
        veniam
      </p>
      <div class="description__specs">
        <div class="building" v-for="(item, index) in description" :key="index">
          <i :class="item.icon"></i>
          <h4>{{ item.title }}</h4>
          <p>
            {{ item.text }}
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AppFirstSection",
  data() {
    return {
      description: [
        {
          icon: "far fa-building",
          title: "Buildings",
          text: "Quis autem vel eum iure reprendit qui in ea voluptate elit esse quam nihil molestiae consequatur.",
        },
        {
          icon: "fas fa-redo-alt",
          title: "Renovate",
          text: "Quis autem vel eum iure reprendit qui in ea voluptate elit esse quam nihil molestiae consequatur.",
        },
        {
          icon: "fas fa-home",
          title: "Construct",
          text: "Quis autem vel eum iure reprendit qui in ea voluptate elit esse quam nihil molestiae consequatur.",
        },
        {
          icon: "fas fa-truck",
          title: "Exclusive",
          text: "Quis autem vel eum iure reprendit qui in ea voluptate elit esse quam nihil molestiae consequatur.",
        },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
.quote {
  height: 150px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #fed23f;

  h3 {
    font-weight: 300;
  }

  button {
    padding: 10px 30px;
    border: 1px solid white;
    position: absolute;
    bottom: -170px;
    color: white;
    background-color: #31312f;
  }
}

.description {
  height: 600px;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  font-weight: 300;

  &__specs {
    width: 85%;
    margin-top: 5rem;
    display: flex;
    justify-content: center;
    text-align: center;

    div {
      margin-right: 1rem;
    }

    i {
      border: 1px solid gray;
      border-radius: 50%;
      padding: 15px;
      color: gray;
    }

    h4 {
      margin: 1rem;
    }
  }

  h3 {
    margin-bottom: 2rem;
  }

  span {
    border-bottom: 2px solid #fed23f;
  }
}
</style>