# ShuttleSMS(短信门神)
My first android java app developed on  Dec 2011.  
Project homepage - https://github.com/zixia/shuttle-sms

## 设计理念
1. 当一个不在手机通讯录中的号码发来短信，系统先hold住此短信；
1. 系统自动按照模板回复给此号码一个验证短信；
1. 对方收到系统自动发出的短信或者验证链接，按要求格式回复或点击；
1. 系统再次收到此号码或服务器回复的验证短信，根据所回复内容判断是否把之前收到的短信和此验证短信移动到收件夹，让用户看到。

## Challenge-Response
目前通过短信，暂时没有网络链接验证。因为短信可以保证任何人都可以进行验证。（有些用户手机也许无法上网）

验证短信目前也会让用户看到，因为可以让用户看到未知号码的机主姓名是谁。

## Use Case
 * Challenge：“对不起，您的短信未能送达，因为号码不在机主通讯录中。请回复短信'短信门神#您的姓名'，进行验证。验证成功后您的短信将会投递给机主，谢谢”；
 * Response：“短信门神#李卓桓”。

## Contribute
半成品。能运行，但是界面不完整。
