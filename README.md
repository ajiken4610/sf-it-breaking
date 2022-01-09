# SFIT班近況報告
　SFIT班の近況報告用れどめリポジトリです。  
　正確にはIT班ではなく網代の活動報告です。  
　気分的に自動翻訳調で書かれています。
# DASHBOARD
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
    - 27日  
    今日は忙しいのでちょっと更新厳しいな。
    - 28日  
    そろそろAMSの構文解析部分はできそうです。  
    あとは、組み込み関数的なものを実装していきます。
    - 29日  
    今日は一日寝てしまって何もできなかった。
    - 30日  
    起きる前のうつらうつらした状態で鼻血が出たり、電車の中で鼻血が出て萎えたせいで進められていない。やばい。
    - 31日  
    そういえば、俺は扱い的には個人事業主だから休みとかなくても法律に抵触したりしないのか。年末年始ぐらい休みほしいんだが...。
- 2022年
  - 1月
    - 1日  
    年賀状作りが忙しかった
    - 2日
    後輩に記事書かなくちゃいけないのを忘れかけてた
    - 3日  
    進んでません。
    - 6日  
    開発再開。構文解析は完了しました。あとは変数のシステムと呼び出しのシステムを書いたら基幹部分は完成。
    - 7日
    AMSの仕様を書き起こしていた。
    - 8日  
    AbsAMSObjectを間違えてAbsAMSObjectでラップしてしまった。そもそもラップする必要なかった。
    - 9日
    AMSの開発がなかなか進まない理由が分かった。`AbsAMSObject`というクラスがあったのだが、そもそもそのクラスは存在してはいけなかった。
