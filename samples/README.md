# OkHttp samples

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) sends a real GET request to the included [local server](local_server.py), reads the response body, and closes the response. It is a standalone consumer with its own `Module module()` dependency.

From the repository root, start the local server and run the Norm sample in another terminal:

```sh
python samples/local_server.py
```

```sh
norm run samples/hello.norm
```

Expected output:

```text
200
Hello from local server
```

Stop the server with Ctrl+C. It only listens on `127.0.0.1:18765`. [module.norm](../okhttp/client/module.norm) pins the Java artifact and defines the public API.
