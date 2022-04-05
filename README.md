<<<<<<< HEAD
# 帮助中心

=======
>>>>>>> 52490b3eacaa480ff8f2714232bf1a81d2f47945
## 青狮阅卷

## 开放平台

<<<<<<< HEAD
* [开发必读](/openapi/guide.md)
=======
* [开发必读](/openapi/test.md)
>>>>>>> 52490b3eacaa480ff8f2714232bf1a81d2f47945

### 添加视频

#### 添加mp4链接视频

<<<<<<< HEAD
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

=======
<video id="my-video" class="video-js" controls preload="auto" width="100%"
poster="http://r9neyyvo2.hn-bkt.clouddn.com/001.png" data-setup='{"aspectRatio":"16:9"}'>
<source src="http://r9neyyvo2.hn-bkt.clouddn.com/test-video.mp4" type='video/mp4' >
</video>

Info styling
> **[info] For info**
>
> Use this for infomation messages.

Warning styling
> **[warning] For warning**
>
> Use this for warning messages.

Danger styling
> **[danger] For danger**
>
> Use this for danger messages.

Success styling
> **[success] For info**
>
> Use this for success messages.
>>>>>>> 52490b3eacaa480ff8f2714232bf1a81d2f47945
