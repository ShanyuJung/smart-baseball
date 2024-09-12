---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: 聰明看棒球
info: |
  ## Smart Baseball: The Story Behind the Old Stats That Are Ruining the Game, the New Ones That Are Running It, and the Right Way to Think About Baseball
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
---

# 聰明看棒球

<h3 class='sub-title'>賽伯計量學如何打破舊思維，改變棒球傳統文化</h3>

<style>
  .sub-title{
    width: 75%;
    opacity: 0.7;
    margin: auto;
  }
</style>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# 魔球之後的現代棒球

<br>
<br>
<h4> 麥可．路易士<span>《魔球》</span>問世至今已經過了二十年，被稱為<span>「賽伯計量學」（sabermetrics）</span>的進階數據，在美國職棒大聯盟（MLB）各球隊已是標準配備，哪支球隊還沒運用<span>數據分析建軍</span>，就會失去競爭優勢，被革命潮流淹沒。然而，儘管進階數據更聰明、更有用，球迷卻依舊感到困惑，因為棒球界的部分人仍然遵循舊傳統，用些過時的數據，例如說打擊率、勝投和守備率，或是無法言說的「靈性」，來<span>評估球員的天賦、能力、貢獻及職業生涯</span>。這群守舊的人士認為，棒球應該由人來管理，而不是由數據來管理。</h4>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
span{
  color: #FFC300;
}
</style>

---

# 想成為「專業」的球迷、球評、球隊管理者前，你必須知道──

- X 別再用<span v-mark.red="1">打擊率</span>、<span v-mark.red="1">勝投</span>、<span v-mark.red="1">救援成功</span>和<span v-mark.red="1">守備率</span>這些無用的垃圾數據了。
- X 關鍵時刻可以開無雙的打者、後位打者可以保護前位打者，都是棒球文化中的迷思。
- ◎ <span v-mark.red="2">wOBA</span>、<span v-mark.red="2">wRC</span>是評判一名打者好壞的最佳依據。
- ◎ 常「煮粥」不代表守備差，<span v-mark.red="3">UZR</span>、<span v-mark.red="3">dRS</span>是更好的判準。
- ◎ 問天不用怕，<span v-mark.red="4">FIP</span>會比防禦率更能看出投手的本事。
- ◎ 想戰誰是「薪水小偷」或「勞工之恥」，看<span v-mark.red="5">WAR</span>和<span v-mark.red="5">WPA</span>就對了

---

# 傳統數據 vs 進階數據

<br>
<br>
<div v-click>
  <h2> 傳統數據: 能很好的表現結果 </h2>
</div>
<br>

<div v-click>

## 進階數據: 更能表現一個球員實際的貢獻

</div>

---

# 所以傳統數據真的沒意義嗎？ 難道以前的人真的不懂數據嗎？

<br>
<br>
<div v-click>
  <h2> 過去時代幾乎沒有<span v-mark.circle.orange="2">長打</span>跟<span v-mark.circle.orange="2">保送</span>，所以打擊率幾乎就代表一個打者的攻擊能力 </h2>
</div>

<div v-click>
  <h2> 過去時代幾乎由<span v-mark.circle.orange="4">一個投手</span>完成整場比賽，所以勝投衡量投手能力的意義相對大很多 </h2>
</div>

---
