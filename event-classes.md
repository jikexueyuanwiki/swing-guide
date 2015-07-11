# SWING 事件类

事件类代表事件。Java 提供各种事件类，但是我们将讨论更频繁使用的那些事件类。

## EventObject 类

它是派生所有事件状态对象的根类。所有事件都是用对象，**源**的引用来构造的，即逻辑上认为是问题最初发生的事件的对象。这个类定义在 java.util 包中。

## 类声明

下面是 **java.util.EventObject** 类的声明：

```
public class EventObject
   extends Object
      implements Serializable
```

## 字段

下面是 **java.util.EventObject** 类的字段：

- **protected Object source** –- 事件最初发生的对象。

## 类构造函数

<table class="table table-bordered">
<tr><th class="fivepct">S.N.</th><th>构造函数 & 描述</th></tr>
<tr><td>1</td><td><b>EventObject(Object source)</b><br> 构造一个典型的事件。</td></tr>
</table>

## 类方法

<table class="table table-bordered">
<tr><th class="fivepct">S.N.</th><th>方法 & 描述</th></tr>
<tr><td>1</td><td><b>Object getSource()</b><br> 事件最初发生的对象。</td></tr>
<tr><td>2</td><td><b>String toString()</b><br>返回这个 EventObject 的字符串表示。</td></tr>
</table>

## 方法继承

这个类从下面的类中继承方法：

- java.lang.Object

## SWING 事件类：

下面是常用的事件类。

<table class="table table-bordered">
<tr><th class="fivepct">Sr. No.</th><th>控件 & 描述</th></tr>
<tr><td>1</td><td><b>AWTEvent</b><br>它是所有 SWING 事件的根事件类。这个类和它的子类取代了最初的 java.awt.Event 类。</td></tr>
<tr><td>2</td><td><b>ActionEvent</b><br>当单击按钮或双点击列表的项时，生成 ActionEvent。</td></tr>
<tr><td>3</td><td><b>InputEvent</b><br>InputEvent 类是所有组件层输入事件的根事件类。</td></tr>
<tr><td>4</td><td><b>KeyEvent</b><br>在按下一个字符时，按键事件生成。</td></tr>
<tr><td>5</td><td><b>MouseEvent</b><br>这个事件表明一个鼠标动作发生在一个组件中。</td></tr>
<tr><td>6</td><td><b>WindowEvent</b><br>这个类的对象代表一个窗口状态的变化。</td></tr>
<tr><td>7</td><td><b>AdjustmentEvent</b><br>这个类的对象代表由可调整的对象发出的调整事件。</td></tr>
<tr><td>8</td><td><b>ComponentEvent</b><br>这个类的对象代表一个窗口状态的变化。</td></tr>
<tr><td>9</td><td><b>ContainerEvent</b><br>这个类的对象代表一个窗口状态的变化。</td></tr>
<tr><td>10</td><td><b>MouseMotionEvent</b><br>这个类的对象代表一个窗口状态的变化。</td></tr>
<tr><td>11</td><td><b>PaintEvent</b><br>这个类的对象代表一个窗口状态的变化。</td></tr>
</table>
