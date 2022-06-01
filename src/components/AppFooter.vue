<template>
  <footer>
    <div class="avada-info">
      <img src="../assets/images/footer-logo.png" alt="footer logo avada" />
      <p>
        We are specialists in the construction of unique and exclusive
        properties. Our work inspires. We pride ourselves on delivering
        outstanding quality and design for leading clients across the world.
      </p>
      <button>LEARN MORE</button>
    </div>
    <div class="tweets">
      <h3>LATEST TWEETS</h3>
      <h4>ThemeFusion</h4>
      <div class="last-tweet">
        <img
          src="../assets/images/3a74ce3d0532b7773b174c45ca3bd05a_normal.png"
          alt=""
        />
        <p>@Theme_Fusion</p>
      </div>
      <img src="" alt="" />
      <p>
        Do you need sublime WordPress hosting for your next website? Take
        advantage of exclusive partners offers that we have secured just for
        you, & launch your site in seconds with <span>#avada</span>on WP Engine
        hosting & get 30% Off this Black Friday
        <a>bit.ly/3kjLLE2 </a>
        <span>#BlackFriday2020</span>
      </p>
      <img src="" alt="" />
    </div>
  </footer>
</template>

<script>
export default {
  name: "AppFooter",
};
</script>

<style scoped lang="scss">
footer {
  display: flex;
  background-color: #1e1e1e;

  .avada-info {
    width: 25%;
    height: 100%;
    padding: 5rem 0;
    display: flex;
    flex-direction: column;
    justify-content: center;

    img {
      width: 75%;
    }

    p {
      margin: 2rem 1rem;
    }

    button {
      padding: 10px 25px;
      border: 0;
      margin-left: 1rem;
      background-color: #fed23f;
    }
  }

  .tweets {
    width: 25%;
    color: white;

    h3 {
      color: #fed23f;
    }
  }
}
</style>