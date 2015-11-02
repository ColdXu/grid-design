栅格化设计约定
=================

如今随着H5的普及，一个页面可以在电脑、pad、手机多种不同设备上完美展示。

栅格化布局,可以做为响应式布局的一种，也是最高效通用的。

栅格化设计 是把网页分格成相同宽度的区域，列出很多排列组合可能性，在不同设备屏幕上可以很容易达到完整展现的目的。

![ABC](https://raw.githubusercontent.com/ColdXu/grid-design/master/img/11.gif) 
这是12列栅格布局，页面整体很有规则性，内容按照栅格排列。


约定
=================

通常我们会把网页分成12等分，会有4种适用于不同尺寸设备屏幕的方案，设计师只要遵循以下网页宽度运用栅格化方式设计就可以。
![ABC](https://raw.githubusercontent.com/ColdXu/grid-design/master/img/icon.gif) 

1.超小屏幕 手机 = 320px</br>
2.小屏幕 平板 = 720px</br>
3.中等屏幕 桌面显示器 = 940px</br>
4.大屏幕 大桌面显示器 = 1140px</br>
<code>这里的宽度是指页面实际内容宽度</code>



实例
=================
用12列栅格设计四种不同设备尺寸。</br>
<code>grid = 栅格数,蓝色区域画出栅格数</code>
</br>
-大屏幕 大桌面显示器1140px尺寸下。
<!-- <a href="https://raw.githubusercontent.com/ColdXu/grid-design/master/img/1.gif" target="_blank">查看</a> -->
-中等屏幕 桌面显示器940px尺寸，由于宽度变小，头部导航栏grid为7。
<!-- <a href="https://raw.githubusercontent.com/ColdXu/grid-design/master/img/2.gif" target="_blank">查看</a> -->
-小屏幕 平板720px尺寸。头部栅格数变化，文字部分grid为12,两列为一列。
<!-- <a href="https://raw.githubusercontent.com/ColdXu/grid-design/master/img/3.gif" target="_blank">查看</a> -->
-超小屏幕 手机320px尺寸。导航栏文字过多，替换成了按钮。

<a href="https://raw.githubusercontent.com/ColdXu/grid-design/master/img/设计.gif" target="_blank">整体对比图</a>
<a href="https://raw.githubusercontent.com/ColdXu/grid-design/master/img/设计2.gif" target="_blank">栅格线视图对比图</a>

例子中利用栅格数量的变化，使得布局发生改变，达到适应屏幕布局的目的。

<code>设计师一定确保内容不得超出栅格线以外，确定内容块所暂用栅格数，这样前端有依据在不同尺寸下用控制栅格数，达到自适应的目的。</code>

<!-- <a href="https://raw.githubusercontent.com/ColdXu/grid-design/master/img/4.gif" target="_blank">查看</a> -->




