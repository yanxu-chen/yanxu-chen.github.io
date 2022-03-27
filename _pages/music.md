---
layout: archive
title: "Music"
permalink: /music/
author_profile: true
redirect_from:
  - /wordpress/blog-posts/
---

{% include base_path %}

I play Guqin, which is a seven-string instrument. 

<img src="https://github.com/yanxu-chen/yanxu-chen.github.io/raw/master/images/Qin.JPG" width="500" height="300">

Some pieces
======
1. 酒狂(Drunken Ecstasy)
<html>
 <body>
  <audio id="myAudio" autoplay loop>
  <source src="https://github.com/yanxu-chen/yanxu-chen.github.io/raw/master/media/Jiukuang_2021.mp3" type="audio/mpeg">
  This HTML5 player is not supported by your browser
  </audio>
  <button type="button" onclick="aud_play_pause()">Play/Pause</button>
  <script>
  function aud_play_pause() {
   var myAudio = document.getElementById("myAudio");
   if (myAudio.paused) {
     myAudio.play();
   } else {
     myAudio.pause();
   }
  }
  </script>
 </body>
</html>




