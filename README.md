# 031ssm流浪狗领养系统
031ssm流浪狗领养系统

#### 项目介绍
```
我国的动物管理正处于起步阶段，注册在线的宠物数量非常有限，信息也很封闭。
因此必须发挥民间力量扩容，加强宠物信息的宣传力度，使更多爱护动物的好心人可以领养宠物。
同时也就收纳有家宠物信息，以防宠物丢失，恶性伤人的事件发生。
由此可见，建立一个规范化，科学化的流浪狗领养系统是非常必要的。
```

源码获取：[点此获取](http://www.shuyue.fun/index.php?type=productinfo&id=132)

#### 环境需要
```
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目
6.数据库：MySql 5.7版本；
```

#### 技术栈
```
1. 后端：Spring SpringMVC MyBatis
2. 前端：JSP+Bootstrap+JQuery
```

#### 使用说明
```
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 将项目中yml配置文件中的数据库配置改为自己的配置
3. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;
若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
4.修改DogController.java中第86行及第147行左右的uploadDB，根据自己的系统打开对应代码；
5. 运行项目，输入localhost:8088/ssm-adopt 登录
```

## 注意事项
1.tomcat中配置项目路径必须为/ssm-adopt,否则会造成项目路径有误；
2.前台展示地址：http://localhost:8080/ssm-adopt/frontPage,先退出原有账号，再登录
普通用户登录账号：java  密码：123

3.后台展示地址为：http://localhost:8080/ssm-adopt/
管理员用户名：2018   密码：123

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/091053_1d5a8a83_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/091109_19b421d8_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/091126_e9c800d9_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/091140_371121eb_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/091210_b1d4a6f8_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/091221_5b639bcc_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/091231_dc2dff52_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/091244_795192ec_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/091439_4a5a299b_863230.jpeg "20210310235054_83575.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/091532_9dcc3d26_863230.jpeg "20210310235546_17948.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/091548_b3844dba_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/091601_b46a16b6_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/091611_7e41411d_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/091621_0f93564f_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/091630_ad8e80e6_863230.png "屏幕截图.png")
