
可读流是对提供数据的来源的一种抽象。

可读流的例子包括：

* [客户端上的 HTTP 响应][http-incoming-message]
* [服务器上的 HTTP 请求][http-incoming-message]
* [fs 读取的流][fs read streams]
* [zlib 流][zlib]
* [crypto 流][crypto]
* [TCP socket][TCP sockets]
* [子进程 stdout 与 stderr][child process stdout and stderr]
* [`process.stdin`][]

所有的[可读流]都实现了 `stream.Readable` 类上定义的接口。

