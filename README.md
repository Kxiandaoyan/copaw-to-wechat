# 微信 Channel for CoPaw

标准的CoPaw channel实现，支持双向通信。

## 特性

- ✅ 接收微信消息并转发给CoPaw
- ✅ 接收CoPaw主动消息并发送到微信
- ✅ 消息去重
- ✅ 定时重开窗口防止错误
- ✅ 随机确认符号


## 配置

编辑 `config.json`:

```json
{
  "copaw_url": "http://127.0.0.1:8088",
  "friend": "yesu",
  "reopen_interval_minutes": 10
}
```


## 主动消息

CoPaw可以通过 `to_handle="wechat:好友名"` 主动发送消息到微信。
