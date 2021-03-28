---
title: 我不知道
date: 2021-02-27 21:26:36
tags:
 - 梁博
categories: 
 - 我是唱作人
---

<script src="https://cdn.jsdelivr.net/npm/hls.js"></script>
<video id="video1" preload controls loop style="height: 100%;width: 100%;object-fit: cover;"></video>
<script>
  if (Hls.isSupported()) {
    var video1 = document.getElementById('video1');
    var hls = new Hls();
    hls.loadSource('https://cdn.jsdelivr.net/gh/ql-isaac/collection-videos-1/我不知道/我不知道.m3u8');
    hls.attachMedia(video1);
    hls.on(Hls.Events.MANIFEST_PARSED,function() {
      video.play();
  });
  }
</script>

