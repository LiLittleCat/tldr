# df

> ファイルシステムのディスク使用量の概要を表示します。
> もっと詳しく: <https://manned.org/df.1posix>。

- 512バイト単位で全てのファイルシステムとそのディスク使用量を表示する:

`df`

- 指定したファイルまたはディレクトリを含むファイルシステムとそのディスク使用量を表示する:

`df {{path/to/file_or_directory}}`

- 1024バイト単位で表示する:

`df -k`

- 移植性のある方法で情報を表示する:

`df -P`
