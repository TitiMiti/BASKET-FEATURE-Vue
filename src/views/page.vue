<template>
  <div class="page-container">
    <div class="page-container1">
      <span class="page-text">Alpha-ÑÐµÑÑ</span>
      <span class="page-text1">
        <span>
          ÐÐ° Ð´Ð°Ð½Ð½ÑÐ¹ Ð¼Ð¾Ð¼ÐµÐ½Ñ BASKET FEATURE Ð½Ð°ÑÐ¾Ð´Ð¸ÑÑÑ Ð½Ð° ÑÑÐ°Ð¿Ðµ ÑÐ°Ð·ÑÐ°Ð±Ð¾ÑÐºÐ¸ Ð¸ Ð´Ð¾ÑÑÑÐ¿ Ðº
          Ð¿ÑÐ¸Ð»Ð¾Ð¶ÐµÐ½Ð¸Ñ Ð¾Ð³ÑÐ°Ð½Ð¸ÑÐµÐ½.
        </span>
      </span>
      <span class="page-text3">
        ÐÐ°Ð¿Ð¸ÑÐ¸ÑÐµÑÑ Ð½Ð° Beta ÑÐµÑÑÐ¸ÑÐ¾Ð²Ð°Ð½Ð¸Ðµ, ÑÑÐ¾Ð±Ñ Ð¾Ð´Ð½Ð¸Ð¼ Ð¸Ð· Ð¿ÐµÑÐ²ÑÑ Ð¾Ð¿ÑÐ¾Ð±Ð¾Ð²Ð°ÑÑ BASKET
        FEATURE Ð´Ð¾ Ð¾ÑÐ¸ÑÐ¸Ð°Ð»ÑÐ½Ð¾Ð³Ð¾ ÑÐµÐ»Ð¸Ð·Ð°
      </span>
      <input type="text" placeholder="placeholder" class="input" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'Page',
  metaInfo: {
    title: 'Page - BASKET FEATURE',
    meta: [
      {
        name: 'description',
        content:
          'ÐÑÑÐ¸ÑÑÐµÐ½Ñ Ð±Ð°ÑÐºÐµÑÐ±Ð¾Ð»ÑÐ½Ð¾Ð³Ð¾ ÑÑÐµÐ½ÐµÑÐ° Ð´Ð»Ñ\nÑÐ±Ð¾ÑÐ°, Ð¿Ð¾Ð´ÑÑÐµÑÐ° Ð¸ Ð°Ð½Ð°Ð»Ð¸Ð·Ð° ÑÑÐ°ÑÐ¸ÑÑÐ¸ÐºÐ¸',
      },
      {
        property: 'og:title',
        content: 'Page - BASKET FEATURE',
      },
      {
        property: 'og:description',
        content:
          'ÐÑÑÐ¸ÑÑÐµÐ½Ñ Ð±Ð°ÑÐºÐµÑÐ±Ð¾Ð»ÑÐ½Ð¾Ð³Ð¾ ÑÑÐµÐ½ÐµÑÐ° Ð´Ð»Ñ\nÑÐ±Ð¾ÑÐ°, Ð¿Ð¾Ð´ÑÑÐµÑÐ° Ð¸ Ð°Ð½Ð°Ð»Ð¸Ð·Ð° ÑÑÐ°ÑÐ¸ÑÑÐ¸ÐºÐ¸',
      },
    ],
  },
}
</script>

<style scoped>
.page-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.page-container1 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: var(--dl-color-gray-black);
}
.page-text {
  color: var(--dl-color-gray-white);
  align-self: center;
}
.page-text1 {
  color: var(--dl-color-gray-white);
  align-self: center;
}
.page-text3 {
  color: var(--dl-color-gray-white);
}
</style>
