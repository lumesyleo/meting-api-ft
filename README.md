# meting-api

## 注

此仓库在[injahow/meting-api](https://github.com/injahow/meting-api)的基础上补充部分`type=search`参数和自定义服务器功能。目前主要测试 netease 和 Tencent 音乐源。

## Descriptions

- 这是基于 [Meting](https://github.com/metowolf/Meting) 创建的 APlayer API
- 灵感源于 https://api.fczbl.vip/163/
- 部分参考 [Meting-API](https://github.com/metowolf/Meting-API)

## Use

将仓库中的文件 Clone 下来，上传到服务器即可使用。

调用方法示例：

```
https://www.example.com/api?server=netease&type=search&id=周杰伦
```

如果需要部署在 Vercel 环境中，需要将目录设置成类似这样的形式（将本仓库的文件放到 api 目录下，并创建与 api 目录同级的`vercel.json`）：
```
project
├── api
│   ├── public
│   ├── src
│   └── index.php
└── vercel.json
```

之后，编辑`index.php`，按照情况作适当调整。

## Thanks

- [APlayer](https://github.com/DIYgod/APlayer)
- [Meting](https://github.com/metowolf/Meting)
- [MetingJS](https://github.com/metowolf/MetingJS)

## Requirement

PHP 5.4+ and BCMath, Curl, OpenSSL extension installed.

## License

MIT