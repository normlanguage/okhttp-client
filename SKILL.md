# okhttp.client Skill

Use this skill to work with Norm module `okhttp.client` version 3. Use only declarations listed below.

## `okhttp.client`

Source: `Call.norm`

### `Call`

```norm
interface Call extends Cloneable
```

#### `cancel`

```norm
Void cancel()
```

Returns: `Void`

#### `execute`

```norm
Response? execute()
```

Returns: `Response?`

#### `isCanceled`

```norm
Boolean isCanceled()
```

Returns: `Boolean`

#### `isExecuted`

```norm
Boolean isExecuted()
```

Returns: `Boolean`

#### `request`

```norm
Request? request()
```

Returns: `Request?`

## `okhttp.client`

Source: `Call_Factory.norm`

### `Call_Factory`

```norm
interface Call_Factory
```

## `okhttp.client`

Source: `Headers.norm`

### `Headers`

```norm
class Headers implements Iterable<JavaPair<?, ?>>, KMappedMarker
```

#### `Headers`

```norm
Headers(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `byteCount`

```norm
Long byteCount()
```

Returns: `Long`

#### `get`

```norm
String? get(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

#### `name`

```norm
String? name(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `String?`

#### `names`

```norm
JavaSet<String>? names()
```

Returns: `JavaSet<String>?`

#### `newBuilder`

```norm
Headers_Builder? newBuilder()
```

Returns: `Headers_Builder?`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

#### `value`

```norm
String? value(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `String?`

#### `values`

```norm
JavaList<String>? values(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `JavaList<String>?`

## `okhttp.client`

Source: `Headers_Builder.norm`

### `Headers_Builder`

```norm
class Headers_Builder
```

#### `Headers_Builder`

```norm
Headers_Builder(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `okhttp.client`

Source: `HttpUrl.norm`

### `HttpUrl`

```norm
class HttpUrl
```

#### `HttpUrl`

```norm
HttpUrl(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `encodedPath`

```norm
String? encodedPath()
```

Returns: `String?`

#### `host`

```norm
String? host()
```

Returns: `String?`

#### `isHttps`

```norm
Boolean isHttps()
```

Returns: `Boolean`

#### `port`

```norm
Integer port()
```

Returns: `Integer`

#### `query`

```norm
String? query()
```

Returns: `String?`

#### `resolve`

```norm
HttpUrl? resolve(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `HttpUrl?`

#### `scheme`

```norm
String? scheme()
```

Returns: `String?`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

### `httpUrlGet`

```norm
HttpUrl? httpUrlGet(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `HttpUrl?`

### `httpUrlParse`

```norm
HttpUrl? httpUrlParse(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `HttpUrl?`

## `okhttp.client`

Source: `JavaArrays.norm`

### `JavaByteArray`

```norm
class JavaByteArray
```

#### `JavaByteArray`

```norm
JavaByteArray(JavaByteArrayBindingToken token)
```

Parameters:

- `token`: `JavaByteArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
Integer get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `Integer`

#### `set`

```norm
Void set(Integer index, Integer value)
```

Parameters:

- `index`: `Integer`
- `value`: `Integer`

Returns: `Void`

### `javaByteArrayNew`

```norm
JavaByteArray javaByteArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaByteArray`

## `okhttp.client`

Source: `MediaType.norm`

### `MediaType`

```norm
class MediaType
```

#### `MediaType`

```norm
MediaType(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `mediaTypeGet`

```norm
MediaType? mediaTypeGet(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `MediaType?`

## `okhttp.client`

Source: `OkHttpClient.norm`

### `OkHttpClient`

```norm
class OkHttpClient implements Call_Factory, WebSocket_Factory
```

#### `OkHttpClient`

```norm
OkHttpClient(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `callTimeoutMillis`

```norm
Integer callTimeoutMillis()
```

Returns: `Integer`

#### `connectTimeoutMillis`

```norm
Integer connectTimeoutMillis()
```

Returns: `Integer`

#### `followRedirects`

```norm
Boolean followRedirects()
```

Returns: `Boolean`

#### `newBuilder`

```norm
OkHttpClientBuilder? newBuilder()
```

Returns: `OkHttpClientBuilder?`

#### `newCall`

```norm
Call? newCall(Request? arg0)
```

Parameters:

- `arg0`: `Request?`

Returns: `Call?`

#### `readTimeoutMillis`

```norm
Integer readTimeoutMillis()
```

Returns: `Integer`

#### `retryOnConnectionFailure`

```norm
Boolean retryOnConnectionFailure()
```

Returns: `Boolean`

#### `writeTimeoutMillis`

```norm
Integer writeTimeoutMillis()
```

Returns: `Integer`

### `okHttpClientNew`

```norm
OkHttpClient okHttpClientNew()
```

Returns: `OkHttpClient`

## `okhttp.client`

Source: `OkHttpClientBuilder.norm`

### `OkHttpClientBuilder`

```norm
class OkHttpClientBuilder
```

#### `OkHttpClientBuilder`

```norm
OkHttpClientBuilder(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `build`

```norm
OkHttpClient? build()
```

Returns: `OkHttpClient?`

#### `callTimeout`

```norm
OkHttpClientBuilder? callTimeout(Duration? arg0)
```

Parameters:

- `arg0`: `Duration?`

Returns: `OkHttpClientBuilder?`

#### `connectTimeout`

```norm
OkHttpClientBuilder? connectTimeout(Duration? arg0)
```

Parameters:

- `arg0`: `Duration?`

Returns: `OkHttpClientBuilder?`

#### `fastFallback`

```norm
OkHttpClientBuilder? fastFallback(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `OkHttpClientBuilder?`

#### `followRedirects`

```norm
OkHttpClientBuilder? followRedirects(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `OkHttpClientBuilder?`

#### `followSslRedirects`

```norm
OkHttpClientBuilder? followSslRedirects(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `OkHttpClientBuilder?`

#### `readTimeout`

```norm
OkHttpClientBuilder? readTimeout(Duration? arg0)
```

Parameters:

- `arg0`: `Duration?`

Returns: `OkHttpClientBuilder?`

#### `retryOnConnectionFailure`

```norm
OkHttpClientBuilder? retryOnConnectionFailure(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `OkHttpClientBuilder?`

#### `writeTimeout`

```norm
OkHttpClientBuilder? writeTimeout(Duration? arg0)
```

Parameters:

- `arg0`: `Duration?`

Returns: `OkHttpClientBuilder?`

### `okHttpClientBuilderNew`

```norm
OkHttpClientBuilder okHttpClientBuilderNew()
```

Returns: `OkHttpClientBuilder`

## `okhttp.client`

Source: `Request.norm`

### `Request`

```norm
class Request
```

#### `Request`

```norm
Request(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `header`

```norm
String? header(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

#### `headers`

```norm
Headers? headers()
```

Returns: `Headers?`

#### `headers`

```norm
JavaList<String>? headers(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `JavaList<String>?`

#### `isHttps`

```norm
Boolean isHttps()
```

Returns: `Boolean`

#### `method`

```norm
String? method()
```

Returns: `String?`

#### `newBuilder`

```norm
RequestBuilder? newBuilder()
```

Returns: `RequestBuilder?`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

#### `url`

```norm
HttpUrl? url()
```

Returns: `HttpUrl?`

## `okhttp.client`

Source: `RequestBody.norm`

### `RequestBody`

```norm
class RequestBody
```

#### `RequestBody`

```norm
RequestBody(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `requestBodyCreate`

```norm
RequestBody? requestBodyCreate(String? arg0, MediaType? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `MediaType?`

Returns: `RequestBody?`

## `okhttp.client`

Source: `RequestBuilder.norm`

### `RequestBuilder`

```norm
class RequestBuilder
```

#### `RequestBuilder`

```norm
RequestBuilder(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `addHeader`

```norm
RequestBuilder? addHeader(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `RequestBuilder?`

#### `build`

```norm
Request? build()
```

Returns: `Request?`

#### `get`

```norm
RequestBuilder? get()
```

Returns: `RequestBuilder?`

#### `head`

```norm
RequestBuilder? head()
```

Returns: `RequestBuilder?`

#### `header`

```norm
RequestBuilder? header(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `RequestBuilder?`

#### `post`

```norm
RequestBuilder? post(RequestBody? arg0)
```

Parameters:

- `arg0`: `RequestBody?`

Returns: `RequestBuilder?`

#### `removeHeader`

```norm
RequestBuilder? removeHeader(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `RequestBuilder?`

#### `url`

```norm
RequestBuilder? url(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `RequestBuilder?`

### `requestBuilderNew`

```norm
RequestBuilder requestBuilderNew()
```

Returns: `RequestBuilder`

## `okhttp.client`

Source: `Response.norm`

### `Response`

```norm
class Response implements Closeable
```

#### `Response`

```norm
Response(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `body`

```norm
ResponseBody? body()
```

Returns: `ResponseBody?`

#### `close`

```norm
Void close()
```

Returns: `Void`

#### `code`

```norm
Integer code()
```

Returns: `Integer`

#### `header`

```norm
String? header(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

#### `headers`

```norm
Headers? headers()
```

Returns: `Headers?`

#### `headers`

```norm
JavaList<String>? headers(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `JavaList<String>?`

#### `isRedirect`

```norm
Boolean isRedirect()
```

Returns: `Boolean`

#### `isSuccessful`

```norm
Boolean isSuccessful()
```

Returns: `Boolean`

#### `message`

```norm
String? message()
```

Returns: `String?`

#### `receivedResponseAtMillis`

```norm
Long receivedResponseAtMillis()
```

Returns: `Long`

#### `request`

```norm
Request? request()
```

Returns: `Request?`

#### `sentRequestAtMillis`

```norm
Long sentRequestAtMillis()
```

Returns: `Long`

#### `toString`

```norm
String? toString()
```

Returns: `String?`

## `okhttp.client`

Source: `ResponseBody.norm`

### `ResponseBody`

```norm
class ResponseBody implements Closeable
```

#### `ResponseBody`

```norm
ResponseBody(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `byteStream`

```norm
InputStream? byteStream()
```

Returns: `InputStream?`

#### `bytes`

```norm
JavaByteArray? bytes()
```

Returns: `JavaByteArray?`

#### `close`

```norm
Void close()
```

Returns: `Void`

#### `contentLength`

```norm
Long contentLength()
```

Returns: `Long`

#### `contentType`

```norm
MediaType? contentType()
```

Returns: `MediaType?`

#### `string`

```norm
String? string()
```

Returns: `String?`

## `okhttp.client`

Source: `WebSocket_Factory.norm`

### `WebSocket_Factory`

```norm
interface WebSocket_Factory
```

## `okhttp.client.kotlin`

Source: `kotlin/JavaPair.norm`

### `JavaPair`

```norm
class JavaPair<A, B> implements Serializable
```

Type parameters:

- `A`
- `B`

#### `JavaPair`

```norm
JavaPair(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `okhttp.client.kotlin.jvm.internal.markers`

Source: `kotlin/jvm/internal/markers/KMappedMarker.norm`

### `KMappedMarker`

```norm
interface KMappedMarker
```

