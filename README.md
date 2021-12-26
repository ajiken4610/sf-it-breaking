# このリポジトリは一体。
　SFIT班の近況報告用れどめリポジトリです。  
　正確にはIT班ではなく網代の活動報告です。  
　気分的に自動翻訳調で書かれています。
# Dashboard
　現在、`AjiMarkupScript`を開発中です。  
　`AjiMarkupScript`に関しては、[こちら](https://github.com/ajiken4610/ams-interpreter)をご覧ください。  
# 方針
　2022年度サレ祭サイトは、去年、サイトへ企画を投稿するのを数人でやったのがあまりにも辛かったため、Youtubeのような自動化システムを組みます。
- FirebaseのSPAとして設計する予定。Reactは使いませんが、Vue.jsは使います。あと自前のwindowlib.ts。
- CSSライブラリは[MDC](https://material-components.github.io/material-components-web-catalog/)を使う予定。
- 企画の説明文などを書くときに、PlaneText、MD、AMSから選べるようにしたい。MDのパースは適当にライブラリを見繕うことにします。
- 適当なAIは、適当なAIです。具体的に説明すると、ユーザーが企画を見た後にどの企画を見る傾向にあるかの統計を取って、傾向に応じてYoutubeの関連動画のような感じで並べて表示します。
# 日記
- 2021年
  - 12月
    - 22日  
    れどめを表示するだけなのに、何を血迷ったかMarkDownをパースするプログラムを書いて、3時間無駄にした。
    - 23日  
    `EJS`を読み込もうとして必死にあがいたけど、結局`EJS`必要なかった。
    - 24日  
    AjiMarkupScriptの仕様が決まってきた
    - 25日  
    AjiMarkupScriptのインタプリタの作成に取り掛かった
    - 26日  
    AjiMarkupScriptの構文解析プログラムの作成がだいぶ進んできた  
    AjiMLの時は異常に書きあげるの早かったなぁ(仕様が決まってから2日)
