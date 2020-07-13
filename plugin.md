# Gitbook插件

gitbook plugins info stores in `book.json`

gitbook-plugin-donate
gitbook-plugin-github-buttons
gitbook-plugin-edit-link 


book.json
```
{
    "title": "编写gitbook电子书教程",
    "description": "gitbook电子书教程",
    "author": "sphard",
    "language": "zh-hans",
    "root": ".",

    "plugins": [
        "donate",
        "github-buttons@2.1.0",
        "edit-link"
    ],

    "pluginsConfig": {
        "donate": {
            "wechat": "https://sphard.com/images/wechatpay.jpg",
            "alipay": "https://sphard.com/images/alipay.jpg",
            "title": "",
            "button": "赏金",
            "alipayText": "支付宝打赏",
            "wechatText": "微信打赏"
        },
        "github-buttons": {
            "repo": "darrenliuwei/gitbook",
            "types": [
                "star"
            ],
            "size": "small"
        },
        "edit-link": {
            "base": "https://github.com/darrenliuwei/gitbook/edit/master",
            "label": "Edit This Page"
        }
    }
}
```

$ gitbook install
安装book.json上的插件

$ gitbook serve
重启服务器


