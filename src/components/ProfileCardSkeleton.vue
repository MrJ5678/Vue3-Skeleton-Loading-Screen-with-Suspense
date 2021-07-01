<!--
 * @Author: hhhhhq
 * @Date: 2021-07-01 10:42:56
 * @LastEditors: hhhhhq
 * @LastEditTime: 2021-07-01 10:55:51
 * @Description: file content
-->
<template>
  <div class="profile-card">
    <div class="profile-image">
      <img />
    </div>
    <div class="profile-info">
      <span />
      <h3 />
      <p />
    </div>
  </div>
</template>

<style scoped>
.profile-image img {
  width: 100%;
  padding-top: 100%;
  background-color: #eee;
  animation: pulse-bg 1s infinite;
}

.profile-info span {
  width: 100%;
  height: 16px;
  display: block;
  animation: pulse-bg 1s infinite;
}

.profile-info h3 {
  width: 250px;
  height: 24px;
  animation: pulse-bg 1s infinite;
}

.profile-info p {
  width: 80%;
  height: 16px;
  animation: pulse-bg 1s infinite;
}

@keyframes pulse-bg {
  0% {
    background: #eee;
  }
  50% {
    background: #eaeaea;
  }
  100% {
    background: #eee;
  }
}
</style>
