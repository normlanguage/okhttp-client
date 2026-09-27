# OkHttp

[English](README.md) | [简体中文](README.zh-CN.md)

适配声明与可运行示例位于 `okhttp/client`，固定 JVM 制品 OkHttp 5.5.0，发布坐标见 [module.norm](okhttp/client/module.norm)。公开面覆盖客户端与超时配置、请求构造、同步调用、响应、响应体、Headers、URL 和资源关闭。

独立 NAR 消费、Kotlin 与 Okio 传递依赖、真实本地 HTTP 请求、响应体读取和 `Closeable` 生命周期由 `OkHttpBindingIntegrationTest` 验收。完整 census 与未支持原因位于 NAR 的 `binding/java-api.json`。

[示例](samples/README.zh-CN.md)提供独立的 Norm 客户端与本地 HTTP 服务，可实际发送请求。
