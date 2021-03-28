---
title: 如果当时2020
date: 2021-03-07 12:02:46
tags:
 - 许嵩
categories: 
 - 不曾遗忘的符号
---

<script src="https://cdn.jsdelivr.net/npm/hls.js"></script>
<video id="video1" preload controls loop style="height: 100%;width: 100%;object-fit: cover;"></video>
<script>
  if (Hls.isSupported()) {
    var video1 = document.getElementById('video1');
    var hls = new Hls();
    hls.loadSource('https://cdn.jsdelivr.net/gh/ql-isaac/collection-videos-1/如果当时2020/如果当时2020.m3u8');
    hls.attachMedia(video1);
    hls.on(Hls.Events.MANIFEST_PARSED,function() {
      video.play();
  });
  }
</script>