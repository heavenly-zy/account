<template>
  <nav>
    <hr />
    <router-link to="/money" class="item">
      <Icon name="money" />记账
    </router-link>
    <router-link to="/labels" class="item">
      <Icon name="label" />标签
    </router-link>
    <router-link to="/statistics" class="item">
      <Icon name="statistics" />统计
    </router-link>
  </nav>
</template>

<script lang="ts">
export default {
  name: "Nav"
};
</script>

<style lang="scss" scoped>
nav {
  display: flex;
  font-size: 12px;
  > .item {
    padding: 2px 0;
    width: 33.333333%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    border: 1px solid red;
    .icon {
      width: 32px;
      height: 32px;
    }
  }
}
</style>