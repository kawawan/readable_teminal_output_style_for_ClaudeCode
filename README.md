# tidy-terminal.md

Claude Code の custom output style です。
ターミナル出力の際、リスト表記の行間隔が狭すぎる問題を解消します。「・」と空行と全角空白で無理やりレイアウトを整えてターミナルに出力するよう指示します。

## 導入方法
tidy-terminal.md をダウンロードし、あとは公式ドキュメントの通りに設定お願いします（https://code.claude.com/docs/ja/output-styles#create-a-custom-output-style）
もしくは、お手元のClaude Codeにこのoutput styleを使えるようにして！と頼めばよいと思います。

## 使い方
導入した後は、
1. /config コマンドを実行
2. 検索窓で output と打つと output style が選択肢に出るのでそれを選択
3. 見やすい端末出力 が候補に出てくるのでそれを選択

## 主な内容は次の通り

- markdownのリスト記法を使用せず、「・」と全角スペースで段落を調整する
- 箇条書きを書きたい場合は、項目と項目の間に空行を一つあける
- これをすべてのClaude Codeのターミナル上での回答に適用する（planの内容まで含めて）

## 詳細
ブログ：https://zenn.dev/zekeynn/articles/52ea0be9526e34

Output Styleについては公式ドキュメントをご参照ください：https://code.claude.com/docs/ja/output-styles
