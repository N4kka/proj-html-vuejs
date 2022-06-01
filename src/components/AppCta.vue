<template>
  <section class="cta">
    <div class="cta__text">
      <h2><span>Building Insp</span>iring Spaces</h2>
      <h4>
        Vivamus sed consectetur tellus dolor sit amet, consectetur adipisicing
        lorem elit sadip ipsum ets ficilis uns.
      </h4>
    </div>
    <div class="cta__quote">
      <button>GET A FREE QUOTE</button>
      <p>Only takes a few seconds!</p>
    </div>
  </section>
</template>

<script>
export default {
  name: "AppCta",
};
</script>

<style scoped lang="scss">
.cta {
  padding: 5rem 0;
  border-bottom: 10px solid #6b6868;
  display: flex;
  color: white;
  background-image: url(../assets/images/about-call-to-action-57862405.jpg);
  background-position: center;

  &__text {
    width: 50%;
    height: 100%;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  h2 {
    margin-bottom: 4rem;
  }

  span {
    padding-bottom: 25px;
    border-bottom: 2px solid #fed23f;
  }

  h4 {
    font-size: 1rem;
  }

  &__quote {
    width: 25%;
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;

    button {
      padding: 10px 25px;
      border: 0;
      margin-bottom: 1rem;
      color: gray;
      background-color: #fed23f;
    }
  }
}
</style>