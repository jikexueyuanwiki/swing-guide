# SWING 布局

## 引言

布局意味着容器内组件的安排。我们可以说，用其他方式在容器的特定位置放置组件。布局控件的任务是由布局管理器自动完成的。

## 布局管理器

布局管理器自动放置容器内的所有组件。如果我们不使用布局管理器，然后组件也能由默认的布局管理器放置。手工布局控件也是可能的，但是由于以下两个原因，它变得非常困难。

- 在容器内处理大量的控件是非常繁琐的。

- 通常当我们需要安排组件时，没有给出该组件的宽度和高度信息，。

Java 为我们提供了各种布局管理器来放置控件。属性如大小，形状和排列从一个布局管理器到其他的布局管理器变化。当小应用程序或应用程序窗口的大小改变时，组件的大小，形状和排列的组件也相应的变化，即布局管理器适应小应用程序视图或应用程序窗口的尺寸。

布局管理器与每一个容器对象相关联。每一个布局管理器是实现布局管理接口的类的一个对象。

下面是接口定义的布局管理器的功能。

<table class="table table-bordered">
<tr><th class="fivepct">序号</th><th>接口 & 描述</th></tr>
<tr><td>1</td><td><b>LayoutManager</b><br> LayoutManager 接口声明那些需要由类来实现的方法，这些类的对象将充当一个布局管理器。</td></tr>
<tr><td>2</td><td><b>LayoutManager2</b><br>LayoutManager2 是 LayoutManager 的子接口。这个接口是为那些知道如何基于布局约束对象来布局容器的类。</td></tr>
</table>

## AWT 布局管理器类：

下面是当使用 AWT 设计 GUI 时常用的控件列表。

<table class="table table-bordered">
<tr><th class="fivepct">序号</th><th>布局管理器 & 描述</th></tr>
<tr><td>1</td><td><b>BorderLayout</b><br>Borderlayout 安排组件适应于五个地区：东、西、北、南和中心。</td></tr>
<tr><td>2</td><td><b>CardLayout</b><br>CardLayout 对象把容器中的每一个组件看成一个卡片。一次只有一个卡片是可见的。</td></tr>
<tr><td>3</td><td><b>FlowLayout</b><br>FlowLayout 是默认的布局。它用定向流动来布局组件。</td></tr>
<tr><td>4</td><td><b>GridLayout</b><br>GridLayout 用一个矩形网格形式来管理组件。</td></tr>
<tr><td>5</td><td><b>GridBagLayout</b><br>这是最灵活的布局管理器类。在不需要相同大小的组件的情况下，GridBagLayout 对象垂直、水平或沿着它们的基线来排列组件。</td></tr>
<tr><td>6</td><td><b>GroupLayout</b><br>GroupLayout 分层次地归类组件，为了在一个容器中放置它们。</td></tr>
<tr><td>7</td><td><b>SpringLayout</b><br>SpringLayout 根据一组约束安置与它相关的容器的孩子。</td></tr>
</table>
