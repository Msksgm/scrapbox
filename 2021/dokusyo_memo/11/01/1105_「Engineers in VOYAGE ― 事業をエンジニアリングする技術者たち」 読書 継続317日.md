# 1105\_「Engineers in VOYAGE ― 事業をエンジニアリングする技術者たち」 読書 継続 317 日

## 第４章 Voyage Lighthouse Studio 数十万記事のメディアをゼロから立ち上げる

VOYAGE Lighthouse Studio （VLS） 「神ゲー攻略」を 2015 年から運営

速度を優先して、静的サイトジェネレータを採用

Markdown で執筆するための「神エディタ」を作成

静的サイトジェネレータ->並列にビルド、他のソースコード ->直列ビルド

API サーバーは GAE（Google App Engine）と Go で構築

前もってシステム側で機能を作りすぎない、という方針で作る

「自分たちの意思決定が間違っていること」を常に想定しながら進める

成功確率が高くなった段階では、成功につながる要因にコストをかけることをいとわない
