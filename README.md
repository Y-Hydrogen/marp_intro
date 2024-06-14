# marp_intro

## 前提
- VScodeの拡張機能を使用
- 簡単なイラストやフローはdrawioを用いて作成

## 導入の流れ
1. Marp for VS Codeをインストール
2. drawio for VS Codeをインストール
3. このリポジトリに格納したcssファイルを設定。(準備中)


## 詳細
1. Marp for VS Code をインストール
https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode

2. drawio for VS Codeをインストール
https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio  
:+1: .drawio.pngとかdrawio.svgでファイルを生成すると、importやexportの必要なくそのまま画像として利用できたり、編集することが可能。

4. このリポジトリに格納したcssファイルを設定。(準備中)(代替手段として、参考cssファイルを紹介。https://github.com/eyemono-moe/marp-eyemono-theme/blob/main/theme.css)  
画面左下の歯車マークから Settingsを開く。
検索窓に、"markdown.marp.themes" と入力。
cssファイルの相対パスを入力。

## 使用方法
新規mdファイルを作成し、ファイルの冒頭に以下を挿入。
```
---
marp: true
theme: eyemono
footer: あああ
size: 16:9
paginate: true
math: mathjax
---
```
以降は本文を書きこむことでスライド作成が可能。
