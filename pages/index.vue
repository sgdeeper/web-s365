<template>
  <!-- Provides the application the proper gutter -->
  <v-container fluid>
    <h1 class="title">web-s365</h1>
    <p class="subtitle">
      Webフォントで見栄えするサイトに。
    </p>
    <div>
      <button class="button">詳細はこちら</button>
    </div>
    <div>
      <button class="button--accent">予定しているイベントを見る</button>
    </div>
  </v-container>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>

.title {
  display: block;
  font-weight: 300;
  font-size: 10rem;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 4.2rem;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
