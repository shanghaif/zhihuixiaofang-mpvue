## 信息

小程序后台
url: https://mp.weixin.qq.com
user: anquanyongdian_an_xcx@huajiesolar.com
pwd: Xiaomi#2018

标签：安全用电云，华杰电气，智能用电，智慧用电

测试账号信息：
登录名：test_mp;
密码：518001

开放平台的账号
https://open.weixin.qq.com
user: wxopen@huajiesolar.com
pwd:gongzhonghao#2017

## wux-weapp

wux-weapp组件中修改的地方有：
### filterbar 筛选栏中的高亮颜色值
```scss
.wux-filterbar__icon--sort {
  /* background-position: 0 -52rpx; */
  /* background-size: 18rpx 72rpx; */
  background-size: 28rpx 28rpx;
  background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAATCAYAAACQjC21AAAA7klEQVQ4jc3UPUoDQRjG8d8aK5tcwCvkBloLouktFBQvkfjRiO4lgoIW9lEEa71BruAF0tiFtXkFd9lxZ7s8MAzzvM/892Vmd1l3FW3m5OKqaW1jhnN8/S2Utze14EbGQ4d4w17Mw//CXcAtvGAU6xFew+8NHOAZuw1/J/xBH2CBe4wT9TEetNxBCniHk0TtV8eRq2kzEZ7E6K3W16aqqnxAUUe0dji9vO7TVE2pMyxRZYwyFzjFY0czT5HLAlY4wzxRn+M0cllAWOEIHw3/M/xV26auT+8bh1jEeoGD8FuV83NYYh/vMS8z9qyxfgDZwi+MOVVfzAAAAABJRU5ErkJggg==);
  /* background-image: url(data:image/png;base64,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); */

}
.wux-filterbar__icon--sort-desc {
  /* background-position: 0 4rpx; */
  background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAATCAYAAACQjC21AAAA7UlEQVQ4jc3UMUrEQBjF8V9cK5u9gFfYG2gtiG5voaAIniGKlWguIQpa2K8iWOsN9gpWdtvYLbH5BBMyZtLtg2GY973552MmCauuosssLy7b1iZucYrPv4Xq+qoRXMt46Biv2Il5/F+4D7iBZ0xiPcFL+IOBIzxhu+VvhT8aAixwh2miPsW9jjtIAW9wlKj96jByDa0nwmWMwep8beq6zgcUTURnh2fl15CmGkqdYYU6Y1S5wHM89DTzGLksYI0TzBL1GY4jlwWEJQ7w3vI/wl92ber79L6xj3ms59gLv1M5P4cFdvEW8yJjzwrrB8bUL+LI50opAAAAAElFTkSuQmCC);
}
.wux-filterbar__icon--sort-asc {
  /* background-position: 0 -24rpx; */
  background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAATCAYAAACQjC21AAAA7klEQVQ4jc3UMUoDQRjF8d8aK5uUNl4hN9BaEE1voaCIZ9AglsYziChoYR9FsNYb5Ao2lmnswtp8grvMmNkuD4Zh3vfmvx8zu8uyq0qZp2dfbWsDtzjB59/CzfV6I7hS8NA+XrEdc/+/8CLgGp4xiPUAL+F3BvbwhK2Wvxl+rwuwwh2GmfoQ9xJ3kANe4TBT+9VB5BpazYTPY3RW8rWp67ocUDURyQ5HF5ddmmood4Zj1AVjXAoc4WFBM4+RKwLWOMYkU5/gKHJFQJhjH+8t/yP8eWrTok/vG3uYxnqK3fCTKvk5zLCDt5hnBXuWWD/oii+MNGEa3gAAAABJRU5ErkJggg==);

}
```


### floatingButton 浮动按钮的 click点击事件， 修改为iclick事件

### card 组件的 .wux-card__content 类的flex属性值由1改为2;

### 如何开发

开发时， 如果此时， dist目录下的文件夹是发布时产生的文件，则必须删掉 除miniprogram_npm， node_modules 文件夹之外的所有的文件， 直接打开命令行 输入 npm run dev 命令即可，该命令会在项目根目录下 生成dist文件夹，并监控文件修改，使用微信开发者工具打项目文件夹即可。

#### 开发时会出包的大小大于2M导致无法上传开发版的问题。
./src/ignore.json 内部的数据结构同 app.json。但只包含pages，subPackages属性，可以填写具体需要排除的分包项， 此时 运行 npm run dev 时，则不会排除 ignore.json 内部所写的分包。当开发时需要排除ignore.json指定的分包和页面时，运行 npm run dev true，即可。

### 如何发布

1. 直接打开命令行 输入 mpm run build 命令即可，该命令会在项目根目录下的dist文件夹下生成文件。
2. 打开微信开发者工具，打开该项目，点击右上角的上传按钮。填写版本号，以及项目描述
3. 登录小程序后台
url: https://mp.weixin.qq.com
user: anquanyongdian_an_xcx@huajiesolar.com
pwd: Xiaomi#2018
4. 点击版本管理，可看到开发版本，审核版本，线上版本。
   1. 开发版本为刚刚开发者工具提交的版本。点击提交审核会弹出新页面，让你添加相关信息如图, ![审核页面](审核页面.png)
   2. 提交后的版本会出现在审核版本中如图，![](审核版本页面.png)
5. 当提交审核遇到腾讯视频插件过期时，需要在 src/app.json 里的plugins对象内更改 版本号为该插件最新的版本号。腾讯视频插件最新版本号可点击下图红色框的详情查看 ![](设置页面.png) 然后重新编译上传，提交审核。


### 接口相关文档地址
接口文档相关地址：http://www.huajiecloud.com:8000/index.php?s=/11&page_id=725

 