<!--
 * @Author: 19994643173 1075005842@qq.com
 * @Date: 2024-01-28 15:10:16
 * @LastEditors: 19994643173 1075005842@qq.com
 * @LastEditTime: 2024-01-28 16:37:33
 * @FilePath: \vangle\packages\docs\examples\button\basic.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<template>
  <div class="mb-4">
    <van-button>Default</van-button>
    <el-button type="success">elbu</el-button>
    <van-button type="primary">Primary</van-button>
    <van-button type="success">Success</van-button>
    <van-button type="info">Info</van-button>
    <van-button type="warning">Warning</van-button>
    <van-button type="danger">Danger</van-button>
  </div>
  <div class="mb-4">
    <van-button plain>Plain</van-button>
    <van-button type="primary" plain>Primary</van-button>
    <van-button type="success" plain>Success</van-button>
    <van-button type="info" plain>Info</van-button>
    <van-button type="warning" plain>Warning</van-button>
    <van-button type="danger" plain>Danger</van-button>
  </div>

  <div class="mb-4">
    <van-button round>Round</van-button>
    <van-button type="primary" round>Primary</van-button>
    <van-button type="success" round>Success</van-button>
    <van-button type="info" round>Info</van-button>
    <van-button type="warning" round>Warning</van-button>
    <van-button type="danger" round>Danger</van-button>
  </div>

  <div>
    <van-button icon="search" circle />
    <van-button type="primary" icon="edit" circle />
    <van-button type="success" icon="check" circle />
    <van-button type="info" icon="message" circle />
    <van-button type="warning" icon="star" circle />
    <van-button type="danger" icon="delete" circle />
  </div>
</template>

<style>
.mb-4 {
  margin-bottom: 20px;
}
</style>