<script setup lang="ts">
const handleClick = () => {
  console.log('click')
  alert('请稍后再查询')
}
</script>

<template>
  <div class="page">
    <div class='header'>
      <div class='line'></div>
      <div class='title'>河南社保电子表单在线验证平台</div>
      <div class='line'></div>
    </div>
    <img
      class='img'
      src='@/assets/img.jpg'
      alt='img'
    />
    <div>
      <input type="text" class='input' disabled value='1561hrwdf48wy257thrw36ftrgdr7y34e' />
      <div>
        <input type="text" class='input' placeholder='请输入验证吗' />
      </div>
    </div>
    <button class='btn' @click=handleClick>查询</button>
  </div>
</template>

<style lang="scss" scoped>
.page {
  background: #fff;
  width: 100vw;
  height: 100vh;
  color: black;
  text-align: center;
  padding: 0 15px;
}

.header {
  display: flex;
  justify-content: center;
  align-items: center;
  padding-top: 16px;
  height: 50px;
  margin-bottom: 45px;
  //margin: 45px 0;
}

.title {
  width: 35.625rem;
  text-align: center;
  font-size: 1.375rem;
  color: #f36d00;
  font-weight: 700;
}

.line {
  /*width: 10rem;*/
  /*height: 1px;*/
  /*background: #999;*/
}

.img {
  margin: 0 auto;
  max-width: 100%;
  height: auto;
}

.input {
  max-width: 675px;
  padding: 0 15px;
  width: 100%;
  height: 32px;
  line-height: 32px;
  background: #f8f8f8;
  margin: 15px 0;
  border: 1px solid #cbcbcb;
}

.btn {
  background: #FF6600;
  border-radius: 30px;
  color: #fff;
  text-align: center;
  line-height: 36px;
  width: 160px;
  font-weight: 700;
  margin-top: 65px;
  border: none;
}
</style>