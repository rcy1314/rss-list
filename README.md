# RSS

> :tada: 定时更新 RSS 订阅信息

## 配置

配置存放于 `config.json` 文件，书写格式如下：

```json
[
    {
        "url": "http://example.com/feed",
        "limit": 10
    },
    {
        "url": "https://blog.yfun.top/atom.xml",
        "limit": 0
    }
]
```

> `url`: RSS Feed 地址。
>
> `limit`: 限制数，`0` 不限制。

## 自动化

自动化由 GitHub Action 实现
