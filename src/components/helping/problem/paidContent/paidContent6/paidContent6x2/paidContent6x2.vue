<template>
  <article class="problem-guide-article">
    <div class="article-nav">
      <router-link class="article-link" :to="{ name: 'paidContent6', query: {routerTitleIndex: '2', routerContentIndex: '5'} }">会员</router-link>
      <span>&nbsp;/&nbsp;&nbsp;详情</span>
    </div>
    <h2 class="article-title">会员排序</h2>
    <p class="article-time">2017-12-22 21:35:39</p>
    <br>

    <h3 class="article-content-title">一，会员排序</h3>
    <p class="article-paragraph">您可以自主设定会员排列顺序，重要的会员前排展示，创造更好地用户体验。</p>
    <p class="article-paragraph">Step1：登录管理后台，进入会员列表页面，选择单品，点击【排序】</p>
    <img class="article-img" src="./1.png" alt="小鹅通会员教程步骤-1">
    <p class="article-paragraph">Step2：输入排位</p>
    <p class="article-paragraph">Step3：选择单品，点击【确定】</p>
    <img class="article-img" src="./2.png" alt="小鹅通会员教程步骤-2">
    <h3 class="article-content-title">二，会员内商品排序</h3>
    <p class="article-paragraph">在会员内您可以自主设定专栏或单品排列顺序，重要内容前排展示，创造更佳用户体验。</p>
    <p class="article-paragraph">Step1：登录管理后台，进入会员列表页面，找到需自主排序的会员</p>
    <p class="article-paragraph">Step2：点击会员【详情】</p>
    <p class="article-paragraph">Step3：选择单品，点击【排序】</p>
    <img class="article-img" src="./3.png" alt="小鹅通会员教程步骤-3">
    <img class="article-img" src="./4.png" alt="小鹅通会员教程步骤-4">
    <p class="article-paragraph">Step4：输入排序序号后点击【确定】</p>
  </article>
</template>

<script>
import '@/assets/css/problem-desc.css'
export default {
}
</script>
