<template>
  <!-- Provides the application the proper gutter -->
  <v-container>

    <!-- メインビジュアル -->

    <!-- 予定している撮影会・イベント -->

    <!-- 私の理念、一番大切にしていること（へのリンク） -->

    <!-- SNSへのリンク -->

    <!-- 問い合わせフォーム（へのリンク？） -->
    <!-- 直接フォームおいてもいいかも -->

    <h1 class="title">web-s365</h1>
    <p class="subtitle">
      Webフォントで見栄えするサイトに。
    </p>
    <v-row>
      <v-col cols="12">
      <v-btn dark x-large color="#318053">
        詳細はこちら
        <v-icon right>mdi-chevron-right</v-icon>
      </v-btn>
      </v-col>
    </v-row>
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
  font-size: 2rem;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 1.5rem;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
