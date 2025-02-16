=== WP Miaotixing ===
Contributors: 喵叔
Tags: miaotixing, 喵提醒, 提醒, 通知, 短信, 微信, 语音, 评论通知, 注册通知, 评论提醒, 注册提醒
Requires at least: 4.0
Tested up to: 5.0
Stable tag: trunk
License: GPLv2 or later

喵提醒，将博客动态发送提醒通知到您的手机上（微信，短信或语音电话方式）。

== Description ==

需配合第三方微信公众号【喵提醒】（以下简称“喵提醒”）使用。喵提醒是一个提供基于事件驱动的提醒服务商，详见喵提醒官方网站 https://miaotixing.com。
使用本插件前，请您先在微信内搜索并关注公众号：喵提醒，注册后创建一个提醒，将提醒的喵码填写到插件内，即可在博客动态推送到手机上接收。注册是免费的。

本插件将通过Wordpress的钩子（hook）技术截获您博客的动态信息，并将相关信息通过喵提醒API接口 http://miaotixing.com/trigger 提交，再由喵提醒将提醒推送到您手机。
目前支持以下事件的提醒推送并将向上述API提交以下内容：
1.有新用户注册时推送提醒，提交内容：新用户注册的邮箱；
2.有新的评论提交时推送提醒，提交内容：文章id和评论正文；
本插件不会保存或上传您任何隐私资料，上述功能也可在插件设置界面中开关。

您必须知晓并同意上述服务与功能才能使用本插件。

== Installation ==

上传插件目录到您的博客的 wp-content\plugins\ 目录下，使用管理员登录博客并在博客后台激活本插件，即可使用。

== Changelog ==

= 1.0.0 =
*发布日期2019年2月21日

* 新增有新用户注册时发送提醒通知；
* 新增有新的评论提交时发送提醒通知。