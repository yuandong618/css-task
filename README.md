# Task Description

---

### task0-实现一个自适应布局

已知HTML结构和效果图如下:

![自适应布局](http://7xj8b6.com1.z0.glb.clouddn.com/task0.png)

要求如效果图中标注，两栏间距为10px，请写出这个两列布局的CSS。

[task0-demo](http://yuandong.im/css-demo/task0-two-col-layout.html)

### task1-实现一个tab

默认第一个Tab为选中状态。
补充说明：实现静态效果即可，不用实现点击切换。

![tab效果图](http://7xj8b6.com1.z0.glb.clouddn.com/task1.png)

[task1-demo](http://yuandong.im/css-demo/task1-tab.html)

### task2-实现一个弹窗

![弹窗效果图](http://7xj8b6.com1.z0.glb.clouddn.com/task2.png)

要求如下：

- 总体：弹窗相对于浏览器窗口固定（即滚动条拖动时不影响弹窗位置）且水平垂直居中，弹窗总宽度302px，高度未知（由内容区的内容决定），圆角半径为5px，边框为1px的实线，边框颜色为#cccccc。
- 标题栏：左右留白20px，高度为40px，文字为14px的微软雅黑且垂直居中，只显示单行文字且超出隐藏并显示“...”，背景色为#eeeeee。
- 内容区：由一个段落和一个按钮组成，四周留白20px，背景为白色，段落与按钮距离20px，字体均为12px的宋体。
- 段落：行高1.5倍。
- 按钮：水平居中、宽80px、高30px、蓝底、白字、文字居中、圆角半径为5px。
- 关闭：宽10px、高10px、距离上边框10px，距离右边框10px，鼠标为手型，假设关闭图标相对css的路径为“../x.png”

[task2-demo](http://yuandong.im/css-demo/task2-popup-center.html)

###task3-实现一个幻灯片效果

如下图所示:

![幻灯片效果](http://7xj8b6.com1.z0.glb.clouddn.com/task3-slide.png)



已知结构如下：

```
<div class="slide">
	<!-- 图片省略 -->
	<!-- 以下是指示器 -->
	<div class="pointer"><i class="current"></i><i></i><i></i></div>
</div>
```
要求如效果图中标注，幻灯（slide）宽200px，高100px，指示器（pointer）在右下角，距离右边10px距离下边10px，指示器中的三个圆直径为10px，背景为黑色，间距为5px，当前选中项（current）为白色背景，请完成CSS，需要兼容低版本IE。

[task3-demo](http://yuandong.im/css-demo/task3-slide.html)


###task4-实现一个登录框

如下图所示:

![登录框](http://7xj8b6.com1.z0.glb.clouddn.com/login-form.png)

现需求如下：

- 手机号不能为空，为以1起始的11位数字。
- 密码为大于6位字符。
- 输入框失去焦点时做输入验证。
- 输入框验证失败时，添加invalid样式
- 输入框获取焦点时，去除invalid样式。
- 点击登录按钮，做输入框验证，验证通过后，先禁用按钮再提交表单。
按钮禁用时，添加disabled样式(背景色为"#ddd", 光标为"default")。

[task4-demo](http://yuandong.im/css-demo/task4-login-form.html)

