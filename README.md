本程序完全使用小程序云开发实现

![微信搜索小程序【找啊】访问](https://github.com/WaneGi/zhaoa/blob/master/miniprogram/images/Mini Programs.jpg)
![截图](/miniprogram/images/Mini Programs.jpg)

# 云开发 基础能力

- 数据库：一个既可在小程序前端操作，也能在云函数中读写的 JSON 文档型数据库
- 云函数：在云端运行的代码，微信私有协议天然鉴权，开发者只需编写业务逻辑代码

## 关于注销登录

本小程序将登陆信息异步存储到了缓存当中，一次登陆之后再次访问都无需再授权登录。如果想取消授权，可以在微信中将本小程序长按拖动到底部删除，然后再次搜索或者扫码访问本小程序，就会要求重新授权登陆。

## 弹窗显示图片

扫码打赏的二维码，要求必须是网络图片，使用本地图片点击会弹出黑屏！

## 关于刷题记录

由于云开发数据库一次最多查询20条数据，为了方便，没有将所有历史数据检索下来。

## python题库助力

python题库本来就有，但想写的是java相关的刷题小程序，若首页的助力条点满，后续即将开放python相关的练习

