<template>
  <section class="recent">
    <div class="recent__work">
      <h2>EXP<span>LORE RECENT W</span>ORK</h2>
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Tempora et
        voluptatem magni hic eveniet quaerat sed, sapiente ipsa, quos
        necessitatibus atque.
      </p>
    </div>
    <div class="projects-img">
      <img
        src="../assets/images/project2-featured-15013609-400x400.jpg"
        alt=""
      />
      <img
        src="../assets/images/project1-featured-294276386-400x400.jpg"
        alt=""
      />
      <img
        src="../assets/images/project3-featured-189023420-400x400.jpg"
        alt=""
      />
    </div>
    <div class="all-projects">
      <p>VIEW ALL PROJECTS</p>
    </div>
  </section>
</template>

<script>
export default {
  name: "AppSecondSection",
};
</script>

<style scoped lang="scss">
.recent__work {
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
.projects-img {
  display: flex;
  justify-content: center;

  img {
    width: 20%;
    margin: 20px;
  }
}

.all-projects {
  margin-bottom: 5rem;

  p {
    text-align: center;
    margin-top: 2.5rem;
  }
}
</style>