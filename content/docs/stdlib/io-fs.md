---
title: "io/fs"
weight: 1
draft: false
menuTitle: IO::FS
menu: [READ,WRITE,]
---



{{< header href="read" >}}

IO::FS::READ

{{</ header >}}
[Source](https://github.com/MontFerret/ferret/tree/master/pkg/stdlib/io/fs/read.go#L14)

READ reads from a given file.

|          |          |                |
---------- | -------- | -------------- | ----------
Argument   | Type     | Default value  | Description
`path` | `String`  |  | Path to file to read from.


**Returns** `Binary` File content in binary format.
- - - -


{{< header href="write" >}}

IO::FS::WRITE

{{</ header >}}
[Source](https://github.com/MontFerret/ferret/tree/master/pkg/stdlib/io/fs/write.go#L20)

WRITE writes the given data into the file.

|          |          |                |
---------- | -------- | -------------- | ----------
Argument   | Type     | Default value  | Description
`path` | `String`  |  | File path to write into.
`data` | `Binary`  |  | Data to write.
`params` | `Object`  |  | Additional parameters:
`params.mode` | `String`  |  | Write (default): will create a file if the specified file does not exist


**Returns** `None`
- - - -
