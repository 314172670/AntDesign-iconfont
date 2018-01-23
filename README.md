## Ant Design——iconfont字体库拓展

#### 1、登陆http://www.iconfont.cn（ant design默认使用的字体库） ####

![](https://github.com/314172670/AntDesign-iconfont/blob/master/image/1.png?raw=true)


#### 2、将需要的图标字体加入购物车 ####

![](https://github.com/314172670/AntDesign-iconfont/blob/master/image/2.jpg?raw=true)

![](https://github.com/314172670/AntDesign-iconfont/blob/master/image/3.jpg?raw=true)

#### 3、点击右上角的购物车标志 ####

![](https://github.com/314172670/AntDesign-iconfont/blob/master/image/4.jpg?raw=true)

#### 4、将图标添加到新项目 ####

![](https://github.com/314172670/AntDesign-iconfont/blob/master/image/5.jpg?raw=true)

#### 5、编辑项目,FontClass/Symbol设置为anticon（由于ant默认字体图标也是anticon开头），Font Family为自定义的图标库名称（此处我定义为anticon_user,注意在之后有使用） ####

![](https://github.com/314172670/AntDesign-iconfont/blob/master/image/6.jpg?raw=true)

![](https://github.com/314172670/AntDesign-iconfont/blob/master/image/9.jpg?raw=true)

#### 6、修改图标的Unicode，修改不是e6开头就行，由于ant图标大多是以es6开头，为了防止冲突 ####

![](https://github.com/314172670/AntDesign-iconfont/blob/master/image/12.png?raw=true)

![](https://github.com/314172670/AntDesign-iconfont/blob/master/image/13.png?raw=true)


#### 7、选择font class,更新代码，下载代码到本地 ####

![](https://github.com/314172670/AntDesign-iconfont/blob/master/image/7.jpg?raw=true)

![](https://github.com/314172670/AntDesign-iconfont/blob/master/image/8.png?raw=true)


#### 8、将下载的部分文件整合到项目中 ####

![](https://github.com/314172670/AntDesign-iconfont/blob/master/image/10.jpg?raw=true)

![](https://github.com/314172670/AntDesign-iconfont/blob/master/image/11.png?raw=true)

#### 9、打开iconfont.css，可以看到font-family即项目编辑中的Font Family，图标前缀则是项目编辑中的FontClass/Symbol 前缀，对比第5步的图 ####

![](https://github.com/314172670/AntDesign-iconfont/blob/master/image/14.jpg?raw=true)

#### 10、在App.less中引入上面下载的iconfont.css，设置字体优先级，anticon是ant的默认字体图标，antion_user是我们上面编辑项目时自定义的图标库名称，此处要对应iconfont.css中的font-family名称。此处优先选择我们自定义的字体图标，若没有找到则选择Antd默认的字体图标，起到拓展的作用 ####

![](https://github.com/314172670/AntDesign-iconfont/blob/master/image/15.png?raw=true)

**11、设置到这我们就可以使用自定义的图标了，如下：**

![](https://github.com/314172670/AntDesign-iconfont/blob/master/image/16.png?raw=true)

效果如下：

![](https://github.com/314172670/AntDesign-iconfont/blob/master/image/17.png?raw=true)

