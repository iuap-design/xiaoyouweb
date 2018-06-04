# 小友智能机器人


## 示例体验

请访问：[http://design.yonyoucloud.com/static/xiaoyouweb/1.2.0/xiaoyou-demo.html](http://design.yonyoucloud.com/static/xiaoyouweb/1.2.0/xiaoyou-demo.html)

## 获取小友 web JS-SDK

[http://design.yonyoucloud.com/static/xiaoyouweb/1.2.0/xiaoyouweb-website.min.js](http://design.yonyoucloud.com/static/xiaoyouweb/1.2.0/xiaoyouweb-website.min.js)

## 如何配置小友 SDK

```
// 1、配置参数，在此之前你需要去先开通小友租户。
var xiaoyouConfig = {
    "name": "xiaoyou",
    "tenantid": "xiaoyouweb",
    "appcode": "xiaoyoutest",
    "token": "751417cc-7204-4735-ac33-8adeb4583863",
    "initQuestion": true, //是否有初始问题
    "positionConfig": {
        'right':'20px',
        'bottom':'50px'
    },
    "themeColor": '' //主题颜色
}

// 2、初始化
var xiaoyou = new xiaoyouSDK( xiaoyouConfig );

// 3、调用 API
xiaoyou.open();
xiaoyou.close();

```

## 如何开通你的专属小友的租户，并建立知识库

请访问这里：https://ai.yonyoucloud.com/robot/login.html


## 获取帮助

1、guoyff@yonyou.com 郭永峰
2、jinjya@yonyou.com 金基勇

