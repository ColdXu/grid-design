栅格化设计约定
=================

栅格化设计 是把网页分格成相同宽度的区域，列出很多排列组合可能性，在不同设备屏幕上可以很容易达到完整展现的目的。
下面是一个12列栅格布局，页面整体很有规则性，内容按照栅格排列。
![ABC](https://raw.githubusercontent.com/ColdXu/grid-design/master/img/11.gif) 



约定
=================

通常我们会把网页分成12等分，会有4种适用于不同尺寸设备屏幕的方案，设计师只要遵循以下网页宽度运用栅格化方式设计就可以。
![ABC](https://raw.githubusercontent.com/ColdXu/grid-design/master/img/icon.gif) 

1.超小屏幕 手机 = 750px(参考retina屏解决方案)</br>
2.小屏幕 平板 = 720px</br>
3.中等屏幕 桌面显示器 = 940px</br>
4.大屏幕 大桌面显示器 = 1140px</br>
<code>这里的宽度是指页面实际内容宽度</code>



实例
=================

下面的页面用12列栅格设计四种不同设备尺寸。
<code>grid = 栅格数,蓝色区域画出栅格数</code>
<a href="https://raw.githubusercontent.com/ColdXu/grid-design/master/img/设计.gif" target="_blank">整体对比图</a>
&nbsp;&nbsp;｜&nbsp;&nbsp;
<a href="https://raw.githubusercontent.com/ColdXu/grid-design/master/img/设计2.gif" target="_blank">栅格线视图对比图</a>
</br>

-大屏幕 大桌面显示器1140px尺寸下。

-中等屏幕 桌面显示器940px尺寸
由于宽度变小，头部导航栏grid为7。

-小屏幕 平板720px尺寸
头部栅格数变化，文字部分grid为12,两列为一列。

-超小屏幕 手机375px尺寸
导航栏文字过多，替换成了按钮。


例子中利用栅格数量的变化，使得布局发生改变，达到适应屏幕布局的目的。
设计师一定确保内容不得超出栅格线以外，确定内容块所暂用栅格数，这样前端有依据在不同尺寸下用控制栅格数，达到自适应的目的。

<!-- <a href="https://raw.githubusercontent.com/ColdXu/grid-design/master/img/4.gif" target="_blank">查看</a> -->
适应retina(高清屏)解决方案
=================

手机端设计稿基准尺寸为375px，普通屏显示正常，但在retina屏幕下会出现图片模糊问题。
对于retina屏幕，为了达到高清效果，视觉稿的画布大小会是基准的2倍，也就是说像素点个数是原来的4倍（对iphone6而言：原先的375×667，就会变成750×1334）。所以手机端设计稿尺寸是750px。
<a href="https://raw.githubusercontent.com/ColdXu/grid-design/master/img/设计2.gif" target="_blank">栅格线视图对比图</a>

