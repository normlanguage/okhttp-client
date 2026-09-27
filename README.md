# OkHttp

[English](README.md) | [简体中文](README.zh-CN.md)

The adapter declaration and runnable example are in `okhttp/client`. It pins the JVM artifact OkHttp 5.5.0 and publishes as `okhttp:client:1`. The public API covers client and timeout configuration, request construction, synchronous calls, responses, response bodies, headers, URLs, and resource closing.

Standalone NAR consumption, transitive Kotlin and Okio dependencies, a real local HTTP request, response-body reading, and the `Closeable` lifecycle are covered by `OkHttpBindingIntegrationTest`. The complete API census and reasons for unsupported APIs are in the NAR's `binding/java-api.json`.
