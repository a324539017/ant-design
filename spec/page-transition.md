# 互动转换

- category: 动画
- order: 1

---

## 响应互动

响应交互一般是指我们在浏览页面时，点击元素时动画给我们视觉上的反馈，每个交互动效都能给我们带来不同视觉效果。

比如：按钮上的 hover 或 click 效果，随着你的鼠标事件而改变自身或增加元素在按钮上，或者折叠面板和弹出框，点击后给你呈现新加入的信息元素。

### 按钮反馈

<div class="video-player">
  <video preload loop><source src="https://t.alipayobjects.com/images/rmsweb/T1yHhhXfxkXXXXXXXX.webm" type="video/webm"><source src="https://t.alipayobjects.com/images/rmsweb/T15IXhXlXbXXXXXXXX.mp4" type="video/mp4"></video>
</div>


## 转换动画

### 视觉连贯性三元素

- Adding:  新加入的信息元素应被告知如何使用，从页面转变的信息元素需被重新识别。

- Receding:  与当前页无关的信息元素应采用适当方式移除。

- Normal: 指那些从转场开始到结束都没有发生变化的信息元素。

### 可折叠面板

对于信息元素内容区域的延伸，显示信息元素和进一步内容对象之间的直接连接。

 - 被展开的信息区域内容按照一定的路径依次进场。


<link rel="stylesheet" href="/static/motionDemo.css">
<div class="video-player">
  <video preload loop><source src="https://t.alipayobjects.com/images/rmsweb/T12I8gXexdXXXXXXXX.webm" type="video/webm"><source src="https://t.alipayobjects.com/images/rmsweb/T1e0hgXcpdXXXXXXXX.mp4" type="video/mp4"></video>
</div>


### 弹出框动效

从一个触发点触发一个弹出框时，弹框从所触发区域弹出，且触发区域视觉上基本保持不变。这样让触发区域和弹出区域有所关联，提高用户对新内容的认知。

<div class="video-player">
  <video preload loop><source src="https://t.alipayobjects.com/images/rmsweb/T1br0gXghtXXXXXXXX.webm" type="video/webm"><source src="https://t.alipayobjects.com/images/rmsweb/T1lcRgXb4gXXXXXXXX.mp4" type="video/mp4"></video>
</div>


### 页面转场

从内容A到内容B的转变过程时能有效的吸引用户注意力，突出视觉中心，提高整体视觉效果。

 - 大页面转场可采用左出右入的形式。

 - 小的信息元素排布或块状较多的情况下，根据一定的路径层次依次进场，区分维度层级，来凸显量级，来指引用户的视觉轨迹。

<script src="/static/TweenMax.min.js"></script>
<script src="/static/motion.js"></script>

<div class="video-player">
  <video preload loop><source src="https://t.alipayobjects.com/images/rmsweb/T14q0hXbBdXXXXXXXX.webm" type="video/webm"><source src="https://t.alipayobjects.com/images/T1qWNhXkpeXXXXXXXX.mp4" type="video/mp4"></video>
</div>

> 参考我们的进场组件案例。查看[进场动画组件](/components/enter-animation/)
