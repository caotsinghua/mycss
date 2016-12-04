# mycss

wing是一个非常轻量的纯css框架，使用起来也非常简单。

但是感觉wing的样式有些不合心意，便略加修改，以便在一些小页面上使用。


具体改动的地方有：
1、去除了body的margin

2、去除了h1-h6的margin

3、添加了container-fluid类，
```
.container-fluid{
  width:100%;
  padding:0 10px;
  box-sizing:border-box;
}
```

4、把btn-outline-inverted的类名改成btn-outline，去除了原本的btn-outline。所以这里只有两种button样式
5、改变了a的颜色和hover
6、增加了clearfix类，代码参照bootstrap

ps：如以后有自己的需求再自行添加
