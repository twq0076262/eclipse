# Eclipse 浏览(Navigate)菜单

## 浏览 Eclipse 工作空间

浏览(Navigate)菜单提供了多个菜单可以让你快速定位到指定资源。

![](images/eclipse-navigation/navigation_menu.jpg) 

上图中 Open Type, Open Type in Hierarchy 和 Open Resource 三个菜单项是非常有用的。

## Open Type

Open Type 菜单项可以打开一个对话框，对话框中可以查找 Java 类型文件。

你可以在输入框中输入类名查找。 '*' 号表示 0 个或多个字母，'?' 号表示单个字母可用于指定模式。对话框中将显示所有匹配的模式。

![](images/eclipse-navigation/navigation_open_type.jpg) 

你列表中选择你查找的文件即可。

Eclipse 将打开一个编辑器，显示所选择的类型。如果所选类型不能显示源代码，将使用类文件编辑器显示所选类型的字节码。

![](images/eclipse-navigation/navigation_class_editor.jpg) 

你可以点击 Attach Source 按钮来查看类文件对应的源码。

源代码位于 Java 主目录中的 src.zip 压缩文件中。

## Open Type in Hierarchy

Open Type in Hierarchy 菜单允许用户在 Type Hierarchy 视图中查看类的继承层次。

![](images/eclipse-navigation/navigation_oth.jpg) 

Type Hierarchy视图中选择指定的类就可以看到类的定义信息，包含对应的属性和方法：

![](images/eclipse-navigation/navigation_thv.jpg) 

## Open Resource

open resource(打开资源)菜单可用于查找工作空间中的文件。

'*' 号表示 0 个或多个字母，'?' 号表示单个字母可用于指定模式。对话框中将显示所有匹配的模式。

![](images/eclipse-navigation/navigation_open_res.jpg) 

选择你要打开的文件并点击 OK 按钮。
