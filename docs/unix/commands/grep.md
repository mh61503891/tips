---
tags:
  - grep
  - fgrep
  - CLI
  - 正規表現
description: grepコマンドに関するメモです。
---

# grep

## Tips

### 正規表現ではなく文字列で検索する。

正規表現では `.` に特別な意味があるため、IPアドレスなどで検索しようとするとエスケープが必要になり記述が面倒です。そのような場合は `-F` オプションや `fgrep` コマンドが便利です。

実行例:

```shell title="shell"
grep -F "192.0.2.1" file.log
```

```shell title="shell"
fgrep "192.0.2.1" file.log
```
