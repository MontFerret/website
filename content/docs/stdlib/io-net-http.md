

---
title: "io/net/http"
weight: 1
draft: false
menu: [DELETE,DO,GET,POST,PUT,]
---



{{< header >}}
DELETE
{{</ header >}}
[Source](https://github.com/MontFerret/ferret/tree/master/pkg/stdlib/io/net/http/delete.go#L15)

DELETE makes a HTTP DELETE request.

|          |          |                |
---------- | -------- | -------------- | ----------
Argument   | Type     | Default value  | Description
`params` | `Object`  |  | Request parameters.
`params.url` | `String`  |  | Target url
`params.body` | `Binary`  |  | Request data
`params` | `Object`  | `.headers` | Http headers


**Returns** `Binary` Response in binary format
- - - -


{{< header >}}
DO
{{</ header >}}
[Source](https://github.com/MontFerret/ferret/tree/master/pkg/stdlib/io/net/http/request.go#L27)

REQUEST makes a HTTP request.

|          |          |                |
---------- | -------- | -------------- | ----------
Argument   | Type     | Default value  | Description
`params` | `Object`  |  | Request parameters.
`params.method` | `String`  |  | Http method
`params.url` | `String`  |  | Target url
`params.body` | `Binary`  |  | Request data
`params` | `Object`  | `.headers` | Http headers


**Returns** `Binary` Response in binary format
- - - -


{{< header >}}
GET
{{</ header >}}
[Source](https://github.com/MontFerret/ferret/tree/master/pkg/stdlib/io/net/http/get.go#L16)

GET makes a HTTP GET request.

|          |          |                |
---------- | -------- | -------------- | ----------
Argument   | Type     | Default value  | Description
`urlOrParam` | `Object` `String`  |  | Target url or parameters.
`param` | `String`  | `.url` | Target url or parameters.
`param` | `Object`  | `.headers` | Http headers


**Returns** `Binary` Response in binary format
- - - -


{{< header >}}
POST
{{</ header >}}
[Source](https://github.com/MontFerret/ferret/tree/master/pkg/stdlib/io/net/http/post.go#L15)

POST makes a POST request.

|          |          |                |
---------- | -------- | -------------- | ----------
Argument   | Type     | Default value  | Description
`params` | `Object`  |  | Request parameters.
`params.url` | `String`  |  | Target url
`params.body` | `Binary`  |  | Request data
`params` | `Object`  | `.headers` | Http headers


**Returns** `Binary` Response in binary format
- - - -


{{< header >}}
PUT
{{</ header >}}
[Source](https://github.com/MontFerret/ferret/tree/master/pkg/stdlib/io/net/http/put.go#L15)

PUT makes a PUT HTTP request.

|          |          |                |
---------- | -------- | -------------- | ----------
Argument   | Type     | Default value  | Description
`params` | `Object`  |  | Request parameters.
`params.url` | `String`  |  | Target url
`params.body` | `Binary`  |  | Request data
`params` | `Object`  | `.headers` | Http headers


**Returns** `Binary` Response in binary format
- - - -