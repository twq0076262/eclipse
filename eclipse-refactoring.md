# Eclipse 重构菜单
* * *

## 使用Eclipse重构

在项目开发中我们经常需要修改类名，但如果其他类依赖该类时，我们就需要花很多时间去修改类名。

但 Eclipse 重构功能可以自动检测类的依赖关系并修改类名，帮我们节省了很多时间。

可用过以下方式打开重构菜单：

* 在 Package Explorer 视图中右击 Java 元素并选择Refactor(重构)菜单项
![class-refactor][1]
* 在 Java 编辑器中鼠标右击 Java 元素并选择Refactor(重构)菜单项
* 在 Package Explorer 视图中选择 Java 元素并按下 Shift + Alt + T

下图中我们在Java 编辑器中选中了 HelloWorld 类：

![refactor][2]

在选择 Rename 后会提示输入新的类名并按回车结束修改：

![refactor-rename][3]

在修改完成按下回车键后，会弹出将将会修改的类：

![will-refactor][4]

你只需点击 Continue 按钮即可完成操作。