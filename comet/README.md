## 介绍
comet和ajax都是为了解决HTTP请求中存在的一些问题，comet跟ajax不同的地方在于，ajax是主动’拉’服务端的内容，而comet是服务端主动’推’内容给客户端。实现成本及其简单，比起ajax模拟的 间隔一段去查询服务端内容的方式在性能等各方面都要好。

## 优点
* 实现很简单。
* 实时性好，消息延迟小。

## 缺点
* 超霸道，只说话，不听话，不像 websocket，仔细听，听了还会回答。
* 既然提到 websocket了，那么如果想要更强大的话，建议还是 websocket，有种 jquery 跟 angular 衡量的意思。
* 很适合小数据传输，但是不适合大数据。

## 用途
* 聊天室啦
* 股票什么的

## 原文
https://cnodejs.org/topic/5463840472f405c829029f62
