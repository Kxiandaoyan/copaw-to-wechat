# 微信 Channel for CoPaw

用的是模拟点击,速度很快.   
得电脑一直挂着微信,不hook,不外挂,基本上不会被封.   

我测试的版本是 4.1.7.33   

编译好的,只支持windows,用python打包的,比较大.   

## 特性

- ✅ 接收微信消息并转发给CoPaw
- ✅ 接收CoPaw主动消息并发送到微信
- ✅ 消息去重
- ✅ 定时重开窗口防止错误
- ✅ 随机确认符号

## 注意，要把配置文件后面的//注释都删掉，才能正常运行。这个注释只是为了让你了解

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



