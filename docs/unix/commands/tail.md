---
tags:
  - tail
  - CLI
description: tailコマンドに関するメモです。
---

# tail

## Tips

### ファイルへの追記をリアルタイムに確認する。

実験データなどをファイルに記録する場合、実験中に新しい行をすぐに確認したい場合があります。その場合は、`tail` コマンドの `-f` オプションが便利です。

実行例:

```shell title="shell"
tail -f file.log
```
