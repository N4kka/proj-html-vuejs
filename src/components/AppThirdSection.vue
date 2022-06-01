<template>
  <section class="owners">
    <div class="owners__description">
      <h2>Our <span>Home Owners</span> Say</h2>
      <img
        src="../assets/images/home-testimonial-113165296.jpg"
        alt="A mom with her son"
      />
      <p>
        "No man but feels more of a man in the world if we have but a bit of a
        ground that he can call his own. However small it is on the surface, it
        is four housand miles deep; and that is a very handsome property."
      </p>
      <h3>Harry Smith &middot; new home owner</h3>
      <div class="options">
        <i class="fas fa-circle"></i>
        <i class="far fa-circle gray-circle"></i>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AppThirdSection",
};
</script>

<style scoped lang="scss">
.owners {
  background-image: url(../assets/images/home-parallax-144609983.jpg);
  margin-bottom: 4rem;

  &__description {
    width: 50%;
    height: 50%;
    margin: 5rem auto;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    font-weight: 200;
    text-align: center;
    color: white;

    img {
      border-radius: 50%;
    }

    h2 {
      margin: 3rem;
    }

    span {
      border-bottom: 2px solid #fed23f;
    }

    h3 {
      text-transform: uppercase;
    }

    p {
      margin: 2rem;
    }

    .gray-circle {
      padding-left: 15px;
      color: gray;
    }
  }
}
</style>