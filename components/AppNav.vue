<template>
  <div class="nav">
    <ul>
      <li>
        <nuxt-link exact to="/">
          International Living
        </nuxt-link>
      </li>
      <li>
        <nuxt-link to="/about">About</nuxt-link>
      </li>
    </ul>
  </div>
</template>

<script>
import AppIcon from "@/components/AppIcon.vue";

export default {
  components: {
    AppIcon
  }
};
</script>

<style lang="scss" scoped>
.nav {
  background: #152d6e;
  color: #fff;
  padding: 1em 10vw;
  font-size: 20px;

  a {
    color: #fff;
    opacity: 0.8;
    padding: 0.8rem 0rem;
    &:hover {
      opacity: 1;
    }
  }
}

div {
  align-items: center;
  display: flex;
  height: 100%;
  width: 100%;
}

ul {
  padding-left: 0;

  li {
    display: inline-block;
    margin-bottom: 0.5rem;
    margin-right: 0.5rem;
  }
}
</style>
