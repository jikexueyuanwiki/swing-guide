# SWING 容器

容器是 SWING GUI 组件的组成部分。一个容器提供了一个可以放置组件的空间。在 AWT 中，一个容器是组件本身，并且它增加了功能来添加组件本身。下面是需要考虑的注意事项。

- 容器的子类被称为容器。例如 JPanel，JFrame 和 JWindow。

- 容器可以仅仅添加组件到自身。

- 一个默认的布局使用 setLayout 方法来呈现在每个可以被重写的容器中。

## SWING 容器：

下面是当使用 SWING 设计 GUI 事件时常用的容器列表。

<table class="table table-bordered">
<tr><th class="fivepct">序号</th><th>容器 & 描述</th></tr>
<tr><td>1</td><td><b>Panel</b><br> JPanel 是一个最简单的容器。它提供了任何其他组件可以被放置的空间，包括其他面板。</td></tr>
<tr><td>2</td><td><b>Frame</b> <br>JFrame 是一个带有标题和边界的顶层窗口。</td></tr>
<tr><td>3</td><td><b>Window</b> <br>JWindow 对象是一个没有边界和菜单条的顶层窗口。</td></tr>
</table>
