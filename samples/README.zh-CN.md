# OkHttp 示例

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) 向仓库内的[本地服务](local_server.py)发送真实 GET 请求，读取响应正文，并关闭响应资源。它通过自己的 `Module module()` 声明依赖，是独立的模块消费者。

在仓库根目录启动本地服务，再在另一个终端运行 Norm 示例：

```sh
python samples/local_server.py
```

```sh
norm run samples/hello.norm
```

预期输出：

```text
200
Hello from local server
```

按 Ctrl+C 停止服务。服务仅监听 `127.0.0.1:18765`。[module.norm](../okhttp/client/module.norm) 指定 Java 制品版本并定义公开 API。
