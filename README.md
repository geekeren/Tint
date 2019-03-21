# Tinection
WordPress开源博客CMS模板，带扩展的用户中心以及虚拟物品贩卖模板

# === Tinection-Pro ===

*Theme Name: Tincetion
*Theme URI: http://www.zhiyanblog.com/store/goods/tinection-pro.html
*Description: Tinection主题，WordPress多模板主题，知言博客自用主题
*Version: 1.1.9
*Date: 2015.9.25
*Author: Zhiyan
*Author URI: http://www.zhiyanblog.com/
*Copyright: (c) 2014-2015 Tinection@Zhiyanblog

主题介绍：http://www.zhiyanblog.com/tinection-pro-intro-and-suggestion.html

主题购买地址：http://www.zhiyanblog.com/store/goods/tinection-pro.html

主题激活授权: http://www.zhiyanblog.com/cdn/tinection/authorize.php

# 更新
========================================
2015.6.9 v1.1.8.1
========================================
1.主题自带代码高亮的制表符排版优化，正确显示Tab制表符[不再全部居左对齐]
2.注册邮箱验证模式可选黑白名单模式
3.搜索框的响应式修正


修改文件列表
- @admin/theme-options.php
- @functions.php
- @includes/css/responsive.c


========================================
2015.5.27 v1.1.8
========================================
1.添加注册验证码
2.修复WordPress4.2的一些bug，如表情无法显示，头像2倍大小
3.修复投稿无法上传图片错误，同时修正前台图片上传面板一些样式问题
4.商品展示页固定链接模式现在可以选择POST ID或POST NAME任一模式，归档页链接后缀可自由设置
5.添加延迟加载开关选项
6.修复远程图片保存到本地问题，并可以设置第一张为特色图
7.友情链接小工具添加评分限制，通过评分控制首页展示友情链接
8.添加分类瀑布流模板，并简化设定模板方式为后台选项
9.添加微信登录功能，需要自行申请开发者KEY
10.添加注册邮箱类型白名单过滤，有效防止垃圾注册



修改文件列表
- @admin/theme-options.php
- @style.css
- @header.php
- @header-simple.php
- @functions.php
- @functions-customize.php
- @includes/author-info.php
- @includes/related.php
- @includes/sitenews.php
- @includes/slider-nar.php
- @includes/breadcrumbs.php
- @includes/loginbox.php
- @includes/store/product.php
- @includes/js/function.js
- @includes/js/theme.js
- @includes/js/theme.min.js
- @includes/css/responsive.css
- @functions/open-social.php
- @functions/auto-save-image.php
- @functions/shop.php
- @functions/widgets/tin-posts-h.php
- @functions/widgets/tin-posts.php
- @functions/widgets/tin-tabs.php
- @functions/widgets/tin-bookmark.php
- @functions/widgets/tin-bookmark-h.php

添加文件列表
- @includes/captcha.php
- @includes/category-block.php
- @includes/category-fluid.php


========================================
2015.3.12 v1.1.7
========================================
1.重新修改了高级版主题的加密授权方式，取消ZendGuard加密，无需服务器安装ZendGuard Loader以及特定PHP版本要求
2.登录界面美化,采用Bing每日壁纸
3.前台投稿开启媒体上传功能
4.订单前台输出管理(可选)
5.商品会员价格系统优化(可选)
6.添加延迟加载的开关选项
6.添加支付宝POST方式赞助收款
7.添加支付宝赞助小工具与幻灯小工具
8.CMS布局幻灯片提供非全宽和全宽选项
9.增加若干短代码与编辑器快捷代码按钮
10.修正meta-box相关错误
11.部分JS文件合并
12.添加禁用Gravatar选项，采用用户上传头像或QQ、新浪微博等第三方登录获取的头像或默认头像
13.评论添加顶/踩功能，TABS小工具相应优化，文章喜欢添加cookie限制，防止刷数量
14.为含embed视频或指定特色视频的视频类型文章的缩略图和幻灯添加前台弹出视频支持
15.解决WP上传中文名图片错误问题
16.修改原有外链转内链跳转方式，不再使用单独页面模板
17.添加SMTP发送邮件选项
18.修复商品页链接不支持中文名的问题

其他一些微小的改动

修改文件列表
- @author.php
- @functions.php
- @footer.php
- @style.css
- @tin-config.php(可选)
- @admin/theme-options.php
- @functions/membership.php(可选)
- @functions/shop.php(可选)
- @functions/user-page.php
- @functions/shortcode.php
- @functions/meta-box.php
- @functions/mail.php
- @functions/widgets/tin-tabs.php
- @includes/focus.php
- @includes/thumbnail.php
- @inlcudes/like-collect.php
- @includes/js/theme.js
- @includes/js/my_quicktags.js
- @includes/store/product.php(可选)
- @includes/stickys.php

添加文件列表
- @includes/css/login.css
- @includes/js/function.js
- @includes/slider-nar.php
- @functions/widgets/tin-donate.php
- @functions/widgets/tin-slider.php

删除文件列表
- @page-redirect.php
- @includes/js/ajax-sign-script.min.js
- @includes/js/comments-ajax.js
- @includes/js/lazyload.js
- @includes/js/slider.js
- @includes/js/zh-cn-tw.js
- @includes/js/prettify.js
- @includes/js/jquery.prettyPhoto.js

========================================
2015.2.10 v1.1.6
========================================
1.添加用户积分排行榜小工具
2.添加用户中心小工具
3.移动端登录采用PC弹出框
4.导航菜单优化
5.添加删除文章自动删除特色图及图片附件功能
6.商品页描述添加wpautop处理(可选)
7.会员管理操作-添加手动提升会员
8.已登录评论用户评论区链接改为个人中心页
9.添加积分签到功能

修改文件列表
- @author.php
- @functions.php
- @footer.php
- @style.css
- @includes/css/responsive.css
- @inlcudes/head-login-mobile.php
- @inlcudes/product.php(可选)
- @functions/credit.php
- @functions/comment.php
- @functions/shop.php(可选)
- @functions/membership.php(可选)
- @functions/user-page.php

添加文件列表
- @functions/widgets/tin-creditsrank.php
- @functions/widgets/tin-ucenter.php
- @footer-simple.php



========================================
2015.1.30 v1.1.5
========================================
1.添加自动保存远程图片功能
2.avatar添加ssl获取方式
3.图片灯箱用prettyPhoto替换
4.升级jQuery至1.10.2
5.添加jQuery源选项，可选择本地jQuery或新浪托管jQuery
6.Blocks布局添加不等高瀑布流模式
7.添加电台模板，电台待完善
8.添加文章中心模板
9.添加通横栏友情链接小工具，放置于文章主体下方
10.优化菜单显示
11.添加积分充值功能和优惠码管理功能(可选)


修改文件列表
- @author.php
- @header.php
- @functions.php
- @footer.php
- @style.css
- @admin/theme-options.php
- @includes/js/theme.js
- @includes/css/responsive.css
- @functions/shop.php
- @functions/alipay/alipayapi.php
- @functions/alipay/notify.php

添加文件列表
- @page-radio.php
- @page-articles.php
- @function-customize.php
- @functions/auto-save-image.php
- @functions/widgets/tin-bookmark-h.php
- @includes/js/jquery.prettyPhoto.js
- @includes/js/jquery.masonry.js
- @images/prettyPhoto/*

删除文件列表
- @images/pirobox/*
- @includes/js/pirobox.js


========================================
2015.1.22 v1.1.4
========================================
1.前台注册表单验证优化
2.文章图片自动添加alt和title信息
3.修复导航条关注小工具邮件订阅跳转错误
4.评论和文章内容外链转内链
5.添加启用主题自动创建一些功能页面功能,需要重新启用一次主题
6.文章缩略图高度做一定限制,防止在未使用裁剪功能条件下大量超出内容框架导致样式错误
7.移动设备现在强制使用Blog布局
8.优化WP函数，替换一些过期或不再推荐使用的函数
9.自带prettify.js代码高亮,使用<pre></pre>标签或[php][/php]短代码
10.删除了一些不再需要的插件推荐
11.取消了页面滚轮平滑滚动
12.删除了一些移动设备相关选项，移动设备浮动小工具仅包含回到顶部按钮，不再显示边栏
13.添加热门搜索小工具
14.添加短链接功能，美化长链接为（域名/go/链接缩写名）的形式
15.添加商品资源积分兑换购买功能(可选)
16.添加商品资源支付宝支付购买功能(可选)

修改文件列表
- @style.css
- @author.php
- @header.php
- @footer.php
- @function.php
- @sidebar.php
- @functions/shortcode.php
- @includes/focus.php
- @includes/seo.php
- @inlcudes/breadcrumbs.php
- @inlcudes/related.php
- @includes/floatbutton.php
- @includes/js/theme.js
- @includes/js/ajax-sign-script.min.js
- @includes/js/my_quicktags.js
- @includes/css/responsive.css

添加文件列表
- @page-redirect.php
- @functions/widgets/tin-hotsearch.php
- @functions/shop.php(可选)
- @functions/membership.php(可选)
- @functions/alipay/* (可选)
- @includes/store/product.php(可选)
- @includes/store/product-archives.php(可选)

删除文件列表
- @fonts/opensans/*
- @includes/css/slider.css
- @includes/plugins/crayon-syntax-highlighter.zip
- @includes/plugins/woo-cmp-flash-video-player.zip

========================================
2015.1.9 v1.1.3
========================================
1.增加下载页边栏自定义选项
2.增加文章置顶区
3.优化前台登录，添加前台注册功能
4.添加文章分页功能
5.导航条添加关注按钮和弹窗
6.重新调整导航栏配色，请务必至后台主题设置的配色选项卡还原各颜色默认值
7.重新调整了Blog模板的样式
8.添加了一个新的分类模板,category-num.php,欲使用该模板，请用对应分类ID替换num以获得可使用分类模板
9.头像上传以用户ID区分，防止用户多次上传占用网站空间
10.网站未开启注册时导航栏不显示注册按钮，同时登录弹窗无法切换注册
11.折叠板短代码支持嵌套短代码
12.低版本IE兼容优化
13.必要的样式修正

修改文件列表
- @style.css
- @author.php
- @archive.php
- @content.php
- @category.php
- @tag.php
- @header.php
- @function.php
- @single.php
- @footer.php
- @admin/theme-options.php
- @functions/shortcode.php
- @includes/breadcrumbs.php
- @includes/css/customcss.php
- @includes/css/responsive.css
- @includes/js/theme.js
- @includes/seo.php
- @includes/index-cms.php
- @includes/index-blog.php
- @includes/head-login.php
- @includes/loginbox.php
- @includes/page-download.php

添加文件列表
- @category-num.php
- @includes/stickys.php
- @includes/focus.php
- @includes/css/iefix.css
- @includes/css/kill-ie6.css
- @includes/js/ajax-sign-script.min.js
- @includes/js/css3-mediaqueries.js
- @includes/js/kill-IE6.js
- @includes/js/PIE.js

删除文件列表
- @includes/css/error.css

========================================
2015.1.3 v1.1.2
========================================
1.后台添加选项-是否开启Timthumb裁剪缩略图
2.添加自定义头像上传功能
3.添加自定义配色
4.添加移除分类链接中category字符选项
5.后台编辑器添加文章版权meta-box，方便自定义每篇文章的版权
6.后台编辑器添加页面关键词与描述meta-box，优化页面SEO
7.修改了评论浏览器图标以及IP显示方式(Tooltip)
8.添加了一个全宽音乐模板，基于网易云音乐插件(已打包在主题includes/plugins目录下，可以通过后台主题设置按钮下方插件安装按钮进行安装)
9.替换了随机缩略图图片
10.替换修改幻灯
11.必要的样式修改

修改文件列表
- @content.php
- @function.php
- @author.php
- @header.php
- @footer.php
- @style.css
- @admin/theme-options.php
- @includes/thumbnail.php
- @includes/slider.php
- @includes/related.php
- @includes/css/slider.css
- @includes/js/themem.css
- @functions/meta-box.php
- @functions/widgets/tin-tabs.php
- @functions/widgets/tin-posts.php
- @functions/widgets/tin-posts-h.php

添加文件列表
- @includes/css/customcss.php
- @functions/no_category_base.php
- @page-music.php

========================================
2014.12.24 v1.1.1
========================================
1.文章标题设置新窗口中打开
2.后台编辑器文本模式添加短代码快捷按钮
3.添加移动终端检测，方便显示移动广告
4.添加了标签云集页面模板
5.评论等多处头像支持QQ和微博头像
6.设置空搜索不返回任何结果
7.搜索页面关键词高亮
8.幻灯改用eislider
9.文章内容标签文字自动添加标签链接，并附加鼠标提示效果
10.小工具样式的修改
11.404页面模板修改
12.评论框样式修改
13.添加移动设备侧边栏不显示选项
14.添加文章页是否显示缩略图选项
15.添加过滤纯英文和日文评论选项
16.首页文章输出优先手动摘要,文章页将会输出手动摘要作为文章前导语
17.摘要过滤短代码标签
18.后台编辑器添加预览样式，与前台一致
19.修正Widgets中评论内容过滤隐私评论
20.上版本遗留的模板错位等问题修复以及必要的样式修改

修改文件列表
- @author.php
- @header.php
- @index.php
- @category.php
- @functions.php
- @footer.php
- @sidebar.php
- @page-archives.php
- @page-links.php
- @page-tags.php
- @style.css
- @admin/theme-options.php
- @includes/breadcrumbs.php
- @includes/index-cms.php
- @includes/slider.php
- @includes/smiley.php
- @includes/css/responsive.css
- @includes/css/slider.css
- @includes/js/theme.js
- @functions/comment.php
- @functions/widgets/tin-tabs.php
- @functions/widgets/tin-posts.php

添加文件列表
- @page-sort.php
- @includes/slider.php
- @includes/js/jquery.eislideshow.js
- @includes/js/my_quicktags.js
- @includes/css/error.css
- @includes/css/sgallery.css
- @inlcudes/css/editor-style.css
- @functions/mobile_detect.php


删除文件列表
- @includes/estroslider.php
- @includes/js/jquery.pixelentity.kenburnsSlider.min.js


========================================
2014.12.17 v1.1.0
========================================
1.布局的重要调整，CMS、Blocks、Blog三种布局同等切换，CMS、Blog布局包含边栏，块状布局不包含边栏
2.添加了两个新的CMS布局分类列表模板，其中一个作为分类超过6个时的强制使用模板，以优化页面响应
3.后台设置的调整：
  主题添加英文语言包(不完全，请自行优化/languages内语言包文件)，并在后台添加切换设置
  添加了下载演示及邮件周刊页面的链接设置选项，免去修改代码
  主题设置数据现可以导入导出以便还原和备份
4.多个页面模板的重要调整，现添加页面链接整合菜单，新添加了sort page模板，需要显示页面整合菜单的页面需要采用该模板，友情链接、文章归档页面自带菜单整合，要设置菜单中链接，请至后台-外观-菜单中设置 页面整合菜单项的条目
5.前台用户中心页面、友情链接页面的样式优化
6.评论样式的调整优化
7.后台字体的优化，现为英文consolas字体，中文微软雅黑字体
8.幻灯右侧置顶推荐文章列表将根据自动补齐文章类型设置来选择显示热度或评论数
9.JS下拉菜单效果循环执行错误修正

修改文件列表
- 涉及文件较多，不再列出

========================================
2014.12.09 v1.0.9
========================================
1.CMS布局添加可选边栏设置选项
2.CMS布局分类模板丰富，目前提供5中模板可选，并可在后台为任意分类自定义模板(暂时只对带边栏布局有效)
3.CMS布局的分类排序可以自定义
4.添加分类及文章ID对照表，方便设置主题相关选项
5.修复上一版本改动过程遗留样式问题
6.下载页面的SEO优化
7.Tabs小工具点击切换改为鼠标悬停切换
8.修复块状时间排序布局的功能样式错误
9.一些必要的样式修改及优化

修改文件列表
- @header.php
- @index.php
- @category.php
- @functions.php
- @style.css
- @admin/theme-options.php
- @includes/seo.php
- @includes/css/responsive.css
- @includes/js/theme.js

增加文件列表
- @includes/index-blocks.php
- @includes/index-cms.php
- @includes/index-cmssidebar.php
- @includes/catlist_bar_1.php
- @includes/catlist_bar_2.php
- @includes/catlist_bar_3.php
- @includes/catlist_bar_4.php
- @includes/catlist_bar_5.php

========================================
2014.12.07 v1.0.8
========================================
1.修复幻灯右侧推荐区标题过长重叠问题
2.修复幻灯右侧推荐区候补文章数量在一定条件错误问题
3.用户登录后若有未读消息将在登录区添加新消息提醒
4.清除底部链接中备案以及统计未设置时的多余字符
5.添加在移动设备浏览时隐藏右下角浮动小工具选项
6.导航菜单随鼠标滚轮滚动而相应地显示与隐藏
7.博客布局模板也可以排除指定分类文章
8.一些必要的样式修改及优化

修改文件列表
- @header.php
- @functions.php
- @footer.php
- @style.css
- @admin/theme-options.php
- @includes/head-login.php
- @includes/index-blog.php
- @includes/breadcrumbs.php
- @includes/floatbutton.php
- @includes/head-login-mobile.php
- @includes/estroslider.php
- @includes/css/responsive.css
- @includes/js/theme.js


========================================
2014.12.05 v1.0.7
========================================
1.修改响应式菜单弹出方式为左侧滑（原为下拉）
2.响应式顶部通栏添加搜索按钮，点击弹出搜索框
3.一些必要的样式修改

修改文件列表
- @header.php
- @footer.php
- @function.php
- @style.css
- @admin/theme-options.php
- @includes/sitenews.php
- @includes/css/responsive.css
- @includes/js/theme.js

增加文件列表
- @includes/head-login-mobile.php

========================================
2014.12.04 v1.0.6
========================================
1.响应式布局针对多种不同分辨率进行优化
2.重新调整首页一些部件以优化响应式体验

修改文件列表
- @admin/theme-options.php
- @includes/catlist.php
- @includes/catlist-1.php
- @includes/contentsmall.php
- @includes/css/responsive.css
- @category.php
- @category-1.php
- @header.php
- @index.php
- @style.css

========================================
2014.12.02 v1.0.5
========================================
1.采用jQuery重写了菜单的下拉效果
2.缩略图添加悬停放大动画效果
3.修复了用户非首次评论仍需填写未显示的验证码的问题
4.修复页首右侧推荐文章候补文章与置顶文章重复问题
5.一些必要的样式修改

修改文件列表
- @admin/theme-options.php
- @includes/js/theme.js
- @includes/css/responsive.css
- @functions/comment.php
- @functions/comments-ajax.php
- @functions.php
- @header.php
- @style.css

========================================
2014.12.01 v1.0.4
========================================
1.修改后台文章编辑区下载资源meta-box输入框行数，优化显示
2.增加若干选项，评论输出现在可以选择是否输出评论者VIP等级，浏览器信息以及IP真实地址
3.评论IP数据来源增加在线API调用方法，默认为该方法，可以后台开启使用更详细的本地数据文件QQwry.dat，该文件已移除，请自行下载
4.文章输出页标签位置移动到文章内容尾部
5.文章内容图片未添加超链接标签a时也能被抓取并添加a标签以及pirobox类，从而实现暗箱效果
6.修复pirobox添加类与sgallery重复问题
7.现在默认不移除文章内容自动p标签，以免已发布的内容布局错误，需要开启的请至functions.php取消“去除正文P标签包裹”一项下的注释
8.添加取消收藏功能，用户现在可以在用户资料页查看自己的收藏并选择取消收藏
9.修改若干样式

修改文件列表
- @admin/theme-options.php
- @functions/meta-box.php
- @functions/comment.php
- @includes/like_collect_meta.php
- @includes/js/pirobox.js
- @includes/css/responsive.css
- @single.php
- @functions.php
- @header.php
- @style.css

删除文件列表
- @includes/QQwry.dat

========================================
2014.11.30 v1.0.3
========================================
1.优化页首幻灯样式
2.取消图片幻灯显示置顶文章，置顶文章默认显示在右侧文字推荐列表中
3.修复了页首幻灯右侧推荐列表在一定设置条件下不能自动补充文章问题
4.修复了查询消息数在多个类型条件下错误的问题
5.修改了CMS布局各分类排序为乱序
6.修复邮件订阅页面的流量统计无法更新问题
7.邮件订阅边栏小工具添加空或不正确邮箱判断并提醒
8.优化评论显示，普通评论与ping类型评论区分显示
9.修复ping评论无邮箱时用户VIP等级错误显示问题
10.优化了浮动小工具显示，浮动小工具底部将不会超出文章内容主体

修改文件列表
- @includes/estroslider.php
- @includes/js/theme.js
- @functions/message.php
- @functions/comment.php
- @functions/widgets/tin-subscribe.php
- @comments.php
- @index.php
- @page-newsletter.php

========================================
2014.11.28 v1.0.2
========================================
1.修改了几处样式错误
2.修改了响应式导航菜单，支持二级菜单折叠显示
3.修复了评论ua显示功能文件的图像链接错误
4.压缩了主题Screenshot图片大小
5.优化新订阅用户邮件通知
6.修复了作者页面未读消息统计错误问题
7.修复了tin-posts widget显示错误问题
8.修复了资源购买错误消息未及时清除问题
9.增加下载积分奖励以及资源出售返回售价积分给发布者
10.优化精简下载模板页面，广告代码移至后台设置选项中，集合下载相关函数至专用文件functions/download.php

修改文件列表
- @author.php
- @header.php
- @function.php
- @style.css
- @admin/theme-options.php
- @includes/css/responsive.css
- @includes/js/theme.js
- @functions/ua.php
- @functions/newsletter.php
- @functions/widgets/tin-posts.php
- @screenshot.png
- @page-download.php

增加文件列表
- @functions/download.php

========================================
2014.11.26 v1.0.1
========================================
1.添加和修正了几处样式问题
2.精简整理了主题文件
3.AJAX评论js文件移到js专用文件夹，并修复评论丢失输入文件错误
4.Gravatar头像采用多说服务器来源，解决被墙问题

修改文件列表
- @style.css
- @index.php
- @function.php
- @single.php
- @heaader.php
- @footer.php
- @admin/theme-options.php
- @includes/css/slider.css
- @includes/js/comments-ajax.js
- @includes/download.php
- @includes/js/theme.js
- @functions/comments-ajax.php
- @functions/newsletter.php

========================================
2014.11.25 v1.0.0
========================================
1.Tinection主题首次发布，详细介绍见http://www.zhiyanblog.com/tinection.html
