<template>
  <div>
    <input type="text" name="" id="" v-bind:value="userId" readonly />
    <br />
    <input type="text" name="" id="" :value="userName" readonly />
    <br />
    <img :src="imgSrc" alt="" style="width: 100px; height: auto" />
    <br />
    <input type="search" name="" id="" v-model="txt1" />
    <button :disabled="txt1 === ''">조회</button>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      userId: 'kijun.lee.2022.08',
      userName: '이기준',
      imgSrc: 'https://cdn.mhns.co.kr/news/photo/202203/523953_634618_3856.jpg',
      txt1: ''
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
