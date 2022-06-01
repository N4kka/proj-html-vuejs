<template>
  <section class="jumbotron">
    <div class="jumbotron__text">
      <h2>BUILDING INSPIRING SPACES</h2>
      <h4>We Build Inspiring Residential & Commercial Spaces</h4>
      <div class="jumbotron__btn">
        <button class="dark-btn">EXPLORE RECENT WORK</button>
        <button class="yellow-btn">GET A QUOTE TODAY</button>
      </div>
      <div class="jumbotron__demo">DEMOS</div>
      <div class="jumbotron__price">
        <i class="fas fa-dollar-sign"></i> <span>39</span>
        <p>On Sale</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AppJumbotron",
};
</script>

<style scoped lang="scss">
.jumbotron {
  height: calc(100vh - 120px);
  background-image: url(../assets/images/home-slider-62528242.jpg);

  &__text {
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }

  &__demo {
    width: 70px;
    height: 70px;
    border-radius: 5%;
    text-align: center;
    line-height: 100px;
    position: absolute;
    top: 150px;
    right: 15px;
    background-color: white;
  }

  &__price {
    width: 70px;
    height: 70px;
    border-radius: 5%;
    text-align: center;
    position: absolute;
    top: 225px;
    right: 15px;
    color: green;
    background-color: white;

    span {
        font-size: 24px;
    }

    p {
        color: black,
    }
  }

  h2 {
    color: white;
    font-size: 3rem;
  }

  h4 {
    color: #f9d03f;
  }

  &__btn {
    display: flex;
    font-size: 1.3rem;
    margin-top: 2.5rem;

    .dark-btn {
      padding: 10px 30px;
      border: 0;
      margin-right: 1rem;
      color: white;
      background-color: #31312f;
    }

    .yellow-btn {
      padding: 10px 25px;
      border: 0;
      color: #39454c;
      background-color: #f9d03f;
    }
  }
}
</style>