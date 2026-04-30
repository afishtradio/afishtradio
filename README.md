## Hi there 👋

<!--
**afishtradio/afishtradio** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!--PLAYER - Блок расположения плеера. Плееры: default, lite, energy или custom (свой плеер) (можно несколько) -->
<div id="my_player" class="my_player" data-player="energy" data-skin="blue" data-width=200 data-autoplay=1 data-volume=70 data-streamurl="https://myradio24.org/55119"></div>
<!--END PLAYER-->

<!--VISUALIZER - Блок расположения визуализации. Цвета: rgb, red, blue или green  (можно несколько) -->
<canvas class="my_visualizer" width=320 height=128 data-size=64 data-revert=0 data-color="rgb"></canvas>
<!--END VISUALIZER-->

<!--INFOS - Информация о радио -->
<div data-myinfo="logo" style="width:300px; height:80px; background-size:cover;"></div>
<div data-myinfo="img" style="width:300px; height:300px; background-size:cover;"></div>
<br>
<b data-myinfo="song"></b><br>
<br>
🎧 <b data-myinfo="listeners"></b> <span data-myinfo="isonline"></span> - <span data-myinfo="kbps"></span> kbps
<a href="https://myradio24.org/55119.m3u" target="_blank"><img src="https://myradio24.com/img/wmp.gif" /></a>
<a href="https://myradio24.com/ru/player/55119" onclick="window.open(this.href,'player','width=300,height=30'); return false;"><img src="https://myradio24.com/img/open.gif" /></a>
<br>
<b data-myinfo="streamname"></b><br>
<div data-myinfo="htmlavatar"></div>
<a href="#" target="_blank" data-myinfo="url"></a><br>
<br><br>
<!--END INFOS-->


<!--Этот скрипт должен располагаться в самом низу после всех блоков и не должен повторяться на странице. -->
<script src="https://myradio24.com/player/player.js?v3.31" data-radio="55119" data-interval=15 data-vmid=55119 data-lang="ru"></script>
