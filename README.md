# reactNativeCalculator
react native 计算器实现
为安卓端可运行代码

clone 下来后 cd进入文件夹
运行前提为已在官网上面按照要求搭建完基础运行环境

react-native 的版本兼容问题做的不太好 所以安装过程可能会很困难且npm要连接美国服务器
而且千万不要用cnpm 按照官网的介绍，cnpm会有一些比较怪异的地址问题 亲测后的确不可以
所以只能死磕npm进行漫长的等待或者找一些翻墙工具解决问题

执行命令react-native run-android
尽量连接手机，查看真机运行效果
连接手机需要打开手机的开发者模式  建议各自上网查一下自己手机的打开方式 
数据线连接电脑
adb devices 查看是否连接成功，是否有连接设备 如果adb报错可能是你没有安装或者没有配置环境变量 上网查一下配置一下即可
如果一次安装不成功就再试一次 （因为网慢）  或者如果遇到版本问题可以搜一搜错误原因
如果安装成功后建议设置连接本机服务器 而且是通过数据线连接本机的方式 
连接方法是 晃动手机或者一些安卓机有菜单按钮 进入开发者菜单 选择setting 配置连接地址为localhost:8081即可连接成功
