# My-View
My first view <br>
### * 线性布局<br>
1. 采用嵌套线性布局，首先创建垂直方向的线性布局，接着创建四个水平方向的线性布局。大体的布局便创建完毕<br>
2. 在drawable中创建button.xml文件，旨在为设计按钮形式。此处采用分层的方法，最外层为黑色，次外层为白色，最内层为黑色。按照一定比例调整他们的范围，从而达到图示的按钮形式。<br>
3. 直接在xianxing.xml中引用button.xml，背景颜色设置为黑色，创建相应按钮，在AndroidManifest的activity标签中键入 android:screenOrientation="landscape"达到横屏演示。最终得到下图成果：<br>
![mage text](https://github.com/IYuanM/My-View/blob/main/picture/1.PNG)
### * 约束布局<br>
1. 创建xml文件选择androidx.constraintlayout.widget.ConstraintLayout<br>
2. 首先创建两个边角的按钮，让他们相对于边框固定，接着创建橙色的按钮，同时相对于上下边框和左右两个按钮固定。接着创建粉色按钮，相对于上下左右边框固定，接着创建蓝色边框，相对于橙色和粉色按钮达成垂直约束，然后相对左右边框固定，最后创建绿色和紫色按钮，相对于蓝色按钮达成水平约束，相对于粉色按钮和橙色按钮达成垂直约束。最后调整他们的距离达成最终成果。<br>
![mage text](https://github.com/IYuanM/My-View/blob/main/picture/3.PNG)
### * 表格布局
1. 表格布局其实延续了线性布局，我调整了按钮权重和按钮中字体的方位，加了一个view标签做成实线。通过调整布局做成下图效果：<br>
![mage text](https://github.com/IYuanM/My-View/blob/main/picture/2.PNG)
