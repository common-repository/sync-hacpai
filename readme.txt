=== sync hacpai ===
Contributors: zhaofengshu33
Tags: hacpai
Requires at least: 4.1
Tested up to: 4.9.9
Stable tag: 1.40
Requires PHP: 5.2.4
License: MIT
License URI: https://opensource.org/licenses/MIT

黑客派社区实时同步插件 For Wordpress

== Description ==

B3log is an open source community blog-forum mixer in mainland China. 
It provides Web API to synchronize personal blogs from and to the central community server. 
This project implements a plugin for WordPress blog which supports this kind of synchronization for common WordPress users.

== Installation ==


1. Upload the plugin files to the `/wp-content/plugins/sync-hacpai` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress
1. Use the Settings->Hacpai Sync Wordpress Plugin screen to configure the plugin


== Frequently Asked Questions ==

= Why my synchronization failed =

There are many reasons for failed synchronization.

== Screenshots ==

1. Setting Page

== Changelog ==

= 1.40 =
1. 删除查看最近10次同步结果的功能

= 1.30 =
1. 更新 API 使其可用
2. 增强安全性

= 1.20 =
1. 记录日志到文件
2. 配置面板显示日志

= 1.10 =
1. 社区评论同步到博客内容，改为$comment->contentHTML
2. 社区评论同步到博客记录原始IP
3. 移除同步分类选项,细分同步选项



