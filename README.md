# simple-github-actions-example
simple github actions example

このアクションは"Hello World"もしくは"Hello" + ログに挨拶する人物名を出力します。

# 参考
https://docs.github.com/ja/actions/creating-actions/creating-a-docker-container-action

## 入力

### `who-to-greet`

**必須** 挨拶する相手の名前。 デフォルトは `"World"`。

## 出力

### `time`

挨拶した時間。

## 使用例

uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: 'Mona the Octocat'
