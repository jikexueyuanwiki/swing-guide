# SWING - 环境安装

本节将指导你如何在你的机器上下载和设置 Java。请按照以下步骤来设置环境。

在链接 [**Download Java**](http://java.sun.com/javase/downloads/index_jdk5.jsp) 上, Java SE 免费提供的。所以你根据你的操作系统下载一个版本。

在你的机器上，按照说明下载 java 和运行 **.exe** 来安装 Java。一旦在你的机器上安装了 Java，你将需要设置环境变量来指向正确的安装目录：

## 设置 windows 2000/XP 的路径：

假设你已经在 *c:\Program Files\java\jdk* 目录上安装了 Java：

- 右击 ‘我的电脑’，并且选择 ‘属性’。

- 点击 ‘高级’ 标签下的 ‘环境变量’ 按钮。

- 现在更改 ‘路径’ 变量，以便它也包含 Java 可执行文件的路径。例如，如果路径当前设置为 ‘C:\WINDOWS\SYSTEM32’，然后更改你的路径为  ‘C:\WINDOWS\SYSTEM32;c:\Program Files\java\jdk\bin’。

## 设置 windows 95/98/ME 的路径：

假设你已经在 *c:\Program Files\java\jdk* 目录上安装了 Java：

- 编辑 ‘C:\autoexec.bat’ 文件，并且在最后添加下行：
'SET PATH=%PATH%;C:\Program Files\java\jdk\bin'

## 设置 Linux，UNIX，Solaris，FreeBSD 的路径：

环境变量路径应该设置为指向 java 二进制文件已经安装的位置。如果你在这方面遇到困难，参考你的 shell 文档。

例如，如果你使用 *bash* 作为你的 shell，然后你将添加下行到最后 ‘.bashrc: export PATH=/path/to/java:$PATH’

## 流行的 Java 编辑器：

为了编写 java 程序，你将需要一个文本编辑器。在市场上有甚至更复杂的可用 IDE。但是现在，你可以考虑下列之一：

- **Notepad：** 在 Windows 机器上，你可以使用任何简单的文本编辑器，如 Notepad（本教程推荐），TextPad。

- **Netbeans：**是一个开源而且免费的 Java IDE，它可以从 [http://www.netbeans.org/index.html](http://www.netbeans.org/index.html) 下载。

- **Eclipse：** 也是一个 java IDE，它是由 eclipse 开源社区开发的，可以从 [http://www.eclipse.org/](http://www.eclipse.org/) 下载。
