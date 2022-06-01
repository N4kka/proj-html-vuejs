<template>
  <section class="latest">
    <div class="latest__news">
      <h2><span>Latest News</span></h2>
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Tempora et
        voluptatem magni hic eveniet quaerat sed, sapiente ipsa, quos
        necessitatibus atque.
      </p>
    </div>
    <div class="news-img">
      <img src="../assets/images/blog-post-134132600-400x241.jpg" alt="" />
      <img src="../assets/images/blog-post-92486644-400x241.jpg" alt="" />
      <img src="../assets/images/blog-post-332773904-400x241.jpg" alt="" />
    </div>
    <div class="description">
      <div class="img-description">
        <h3>Redeveloping Florida's Remote Southern Coast</h3>
        <p class="sm-text">December 7th 2015</p>
        <p>
          Tecnology is Here to Stay Lorem ipsum dolor sit amet consectetur
          adipisicing elit. Eos ipsum officia ut porro totam, iure veniam
          asperiores quo possimus? In quo corrupti repudiandae quaerat earum
          veritatis hic laudantium quod? Minus?
        </p>
      </div>
      <div class="img-description">
        <h3>How We Manage Large Constructions Projects</h3>
        <p class="sm-text">December 7th 2015</p>
        <p>
          Tecnology is Here to Stay Lorem ipsum dolor sit amet consectetur
          adipisicing elit. Eos ipsum officia ut porro totam, iure veniam
          asperiores quo possimus? In quo corrupti repudiandae quaerat earum
          veritatis hic laudantium quod? Minus?
        </p>
      </div>
      <div class="img-description">
        <h3>Future Proofing a modern home</h3>
        <p class="sm-text">December 6th 2015</p>
        <p>
          Tecnology is Here to Stay Lorem ipsum dolor sit amet consectetur
          adipisicing elit. Eos ipsum officia ut porro totam, iure veniam
          asperiores quo possimus? In quo corrupti repudiandae quaerat earum
          veritatis hic laudantium quod? Minus?
        </p>
      </div>
    </div>
    <div class="all-articles">
      <p>VIEW ALL ARTICLES</p>
    </div>
  </section>
</template>

<script>
export default {
  name: "AppFourthSection",
};
</script>

<style scoped lang="scss">
.latest {
  &__news {
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
  }
  .news-img {
    display: flex;
    justify-content: center;

    img {
      width: 20%;
      margin: 20px;
    }
  }

  .description {
    width: 75%;
    display: flex;
    margin: 0 auto;

    .img-description {
      font-size: 14px;
      font-weight: 200;

      h3 {
        font-weight: 200;
      }

      p {
        font-size: 11px;
      }
    }
  }

  .all-articles {
    margin-bottom: 5rem;
    font-weight: 200;

    p {
      text-align: center;
      margin-top: 2.5rem;
    }
  }
}
</style>