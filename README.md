# BURI_LOOP

無限に BURI と出力する AArch64 アセンブラ

AArch64 以外では動作しません。

![Demo Video](.github/assets/demo.gif)

## 使い方

```shell
# ビルド
docker build -t buri -f main.dockerfile .
```

```shell
# 実行
docker run buri
```
