# SWING 事件监听器

事件监听器代表负责处理事件的接口。Java 提供了各种事件监听器类，但我们将讨论更频繁使用的那些事件监听器类。一个事件监听器的每个方法有一个参数作为一个对象，该对象是 EventObject 类的子类。例如，鼠标事件监听器的方法将接受 MouseEvent 的实例，其中 MouseEvent 是 EventObject 派生的。

## EventListner 接口

它是一个标记接口，每一个监听器接口必须扩展它。这个类定义在 java.util 包中。

## 类声明

下面是 **java.util.EventListener** 接口的声明：

```
public interface EventListener
```

## SWING 事件监听器接口：

下面是常用的事件监听器列表。

<table class="table table-bordered">
<tr><th class="fivepct">Sr. No.</th><th>控件 & 描述</th></tr>
<tr><td>1</td><td><b>ActionListener</b><br>这个接口用于接收动作事件。</td></tr>
<tr><td>2</td><td><b>ComponentListener</b><br>这个接口用于接收组件事件。</td></tr>
<tr><td>3</td><td><b>ItemListener</b><br>这个接口用于接收项目事件。</td></tr>
<tr><td>4</td><td><b>KeyListener</b><br>这个接口用于接收按键事件。</td></tr>
<tr><td>5</td><td><b>MouseListener</b><br>这个接口用于接收鼠标事件。</td></tr>
<tr><td>6</td><td><b>WindowListener</b><br>这个接口用于接收窗口事件。</td></tr>
<tr><td>7</td><td><b>AdjustmentListener</b><br>这个接口用于接收调整事件。</td></tr>
<tr><td>8</td><td><b>ContainerListener</b><br>这个接口用于接收容器事件。</td></tr>
<tr><td>9</td><td><b>MouseMotionListener</b><br>这个接口用于接收鼠标移动事件。</td></tr>
<tr><td>10</td><td><b>FocusListener</b><br>这个接口用于接收焦点事件。</td></tr>
</table>
