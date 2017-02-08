# 概要
このディレクトリには、（ユーザごとの）環境変数 `PATH` を通しておく。
そうすることで、各バッチファイルをコマンドのように扱えるようになる。

# 各コマンド

## exec.bat

```exec {変数} {コマンド}``` で、｛コマンド｝の実行結果を｛変数｝にsetする。

コマンドは、第二引数として渡す。例えば、 `DATE /T` （現在の年月日）を変数した結果を、変数 `today` に代入したい場合は、 `exec today "DATE /T"` とする。