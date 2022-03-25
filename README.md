# 帮助中心

## 青狮阅卷

## 开放平台

* [开发必读](/openapi/test.md)

### 添加视频

#### 添加mp4链接视频

{% raw %}
<video id="my-video" class="video-js" controls preload="auto" width="100%"
poster="//zhangjikai.com/resource/poster.jpg" data-setup='{"aspectRatio":"16:9"}'>
  <source src="//zhangjikai.com/resource/demo.mp4" type='video/mp4' >
  <p class="vjs-no-js">
    To view this video please enable JavaScript, and consider upgrading to a web browser that
    <a href="http://videojs.com/html5-video-support/" target="_blank">supports HTML5 video</a>
  </p>
</video>
{% endraw %}


#### 添加保利视频
{% raw %}
<div id="player"></div>
<script src="//player.polyv.net/script/player.js"></script>
<script>
var player = polyvPlayer({
    wrap: '#player',
    width: 800,
    height: 533,
    vid: '88083abbf5bcf1356e05d39666be527a_8',
});

player.on('s2j_onPlayerInitOver', () => { //订阅播放器初始化完毕事件
  console.info('播放器初始化完毕');
});
</script>
{% endraw %}

