<template>
  <div class="hello">
    <h1>{{ title }}</h1>
    <ul class="full-list">
      <li>
        <span class="name">
          Cilantro
        </span>
        <span>
          <img src="/static/images/cilantro.png" alt="Illustration of Cilantro">
        </span>
      </li>
      <li>
        <span class="name">
          Mint
        </span>
        <span>
          <img src="/static/images/mint.png" alt="Illustration of Mint">
        </span>
      </li>
      <li>
        <span class="name">
          Thyme
        </span>
        <span>
          <img src="/static/images/thyme.png" alt="Illustration of Thyme">
        </span>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      title: 'Herbs & Spices'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>

.full-list {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  li {
    list-style: none;
    border: 1px solid rgba(123, 123, 123, 0.4);
    width: 124px;
    height: 124px;
    display: flex;
    flex-direction: column;
    border-radius: 13px;
    box-shadow: 0px 0px 10px rgba(123, 123, 123, 0.1);
    .name {
      font-size: 18px;
      margin: 10px 0;
    }
    img {
      width: 40px;
    }
  }
}
</style>
