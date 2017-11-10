# C_textbook
達哉んC言語テキストのレポジトリです。

## Compile方法
以下で公開されているjtygm.styが必要です。
http://www.khotta.org/ghost/psfont.html

以下のコマンドでコンパイルしています。必要なソフト類は随時インストールしてください。
``` sh
platex basic
dvipdfmx basic.dvi -o Theorem_text.pdf
```

目次等を更新する際は必要回数platexを実行してください。

また、索引の更新は
``` sh
mendex -g -s dot.ist basic.idx
```
で行った後、A-Zをまとめています。
