# 起源
该主题借鉴了Pavel Makhov的 [jekyll-clean-dark](https://github.com/streetturtle/jekyll-clean-dark)，将其内容做了hexo适配，并增加了属于自己的东西。

# 效果
如果想查看效果，可以在[我的博客](http://www.howardliu.cn/)中查看效果。
如果想查看手机效果，可以扫下面的二维码。

![http://www.howardliu.cn/](http://www.howardliu.cn/images/qr-code/howardliu-qrcode.png)

![http://www.howardliu.cn/](http://www.howardliu.cn/images/clean-dark.png)

# 使用
## 1. 安装
```sh
$ git clone https://github.com/howardliu-cn/hexo-theme-clean-dark.git themes/hexo-theme-clean-dark
```

## 2. 配置
修改hexo根目录下的 _config.yml，将theme值改为hexo-theme-clean-dark。

到这一步就可以使用该主题了，不过通常我们都想进行个性化定制，那就继续下面的内容。

## 3. 个性化定制(themes/hexo-theme-clean-dark/_config.yml)
### 3.1 评论
valine评论: comment.valine

### 3.2 阅览量
valine阅览量: comment.valine

### 3.3 分析
百度分析：baidu_analytics
谷歌分析：google_analytics

### 3.4 个性化图标favicon
修改 favicon 的值，指向自己的个性化图标的位置

### 3.5 邮箱email
email 值为自己的邮箱地址，用于在底部和seo中显示邮箱内容。

### 3.6 菜单menu
可以自定义menu是否显示，和增加自己更多的菜单。

### 3.7 右侧挂件widgets
这是一些小工具挂件，在widgets中配置是否显示。其中包括目录categories、标签云tagcloud、标签tags、归档archives、最近更新recent_posts、最近评论recent_comments、友情链接links。

### 3.8 社交内容social
这是用于在底部显示的内容，目前包括github、StackOverflow。

### 3.9 友情链接links
这部分是显示友链的部分，title是用于显示，url表示链接位置。

# TODO
- 搜索
- 标签云
