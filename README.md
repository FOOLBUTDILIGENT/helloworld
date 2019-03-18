# helloworld
This is my first andriod APP。
展示生命周期
Helloworld的创建
创建没什么好说的，普通的按照File—》NEW—》NEW project 打开创建新工程的界面后，照自己需求输入相关信息后一路next直到finish。
![创建界面](https://raw.githubusercontent.com/FOOLBUTDILIGENT/images/master/helloworld/%E5%9B%BE%E7%89%871.png)
完成后会出现一个工程，其中许多文件andriod studio已经帮我们生成，初学andriod studio我们最需要关注的是两个文件，即res->layout下的activity_main.xml与java->cn.itcast.helloworld下的Mainactivity.java。.

![3](https://raw.githubusercontent.com/FOOLBUTDILIGENT/images/master/helloworld/%E5%9B%BE%E7%89%872.png)
打开activity_main.xml，在TextView中添加一段android:text="Hello World!"
如下

![4](https://raw.githubusercontent.com/FOOLBUTDILIGENT/images/master/helloworld/%E5%9B%BE%E7%89%873.png)
之后运行模拟器

![5](https://raw.githubusercontent.com/FOOLBUTDILIGENT/images/master/helloworld/%E5%9B%BE%E7%89%874.png)
再运行工程

![6](https://raw.githubusercontent.com/FOOLBUTDILIGENT/images/master/helloworld/%E5%9B%BE%E7%89%875.png)
打开模拟器中的对应app就成功了


![8](https://raw.githubusercontent.com/FOOLBUTDILIGENT/images/master/helloworld/%E5%9B%BE%E7%89%877.png)
验证生命周期
打开这个app后，我们想要知道这个软件什么时候启动什么时候结束，什么时候在后台运作
就需要在Mainactivity.java中做文章。
首先，在其中按下图输入代码：

![9](https://raw.githubusercontent.com/FOOLBUTDILIGENT/images/master/helloworld/%E5%9B%BE%E7%89%878.png)

![10](https://raw.githubusercontent.com/FOOLBUTDILIGENT/images/master/helloworld/%E5%9B%BE%E7%89%879.png)
这时我们再在模拟器中打开hellowrld app，并打开下面栏目中的Logcat发现：

![11](https://raw.githubusercontent.com/FOOLBUTDILIGENT/images/master/helloworld/%E5%9B%BE%E7%89%8710.png)
那么，使用home键呢

![12](https://raw.githubusercontent.com/FOOLBUTDILIGENT/images/master/helloworld/%E5%9B%BE%E7%89%8711.png)
按退出键呢 

![13](https://raw.githubusercontent.com/FOOLBUTDILIGENT/images/master/helloworld/%E5%9B%BE%E7%89%8712.png)
本次实验就是这样了。
