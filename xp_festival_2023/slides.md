---
theme: seriph
background: ./images/erik-witsoe-pvoQJym18Jg-unsplash.jpg
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  Slidev Starter Template
drawings:
  persist: false
transition: slide-left
title: だれかの進捗をうまく「把握」できないときのフレーズ集 〜 よい計画づくりのために 〜
mdc: true
fonts:
  sans: 'Meiryo UI'
  serif: 'Roboto Slab'
  mono: 'Fira Code'
---

# だれかの進捗をうまく「把握」できないときのフレーズ集
〜 よい計画づくりのために 〜

2023.09.30 コボリアキラ

<!--
- 14:01
- タイトル読み上げ
- 30分以上の登壇ははじめて
- 盛り上がっている感を出そう！　ぜひたくさんコメントしてください。進捗把握出来てるよ〜できてないよーとか
-->

---

# Who is?

<div class="grid grid-cols-2 gap-8">

  <div class="p-4 bg-red500/20 border-8 border-red100/20 border-rounded">

  ## 💻 編集よりもITを

  <span class="text-sm">2015年にエンジニアにキャリアチェンジ</span>

  </div>

  <div class="p-4 bg-blue500/20 border-8 border-blue100/20 border-rounded">

  ## 👶 ワークよりもライフを

  <span class="text-sm">2020年に第一子が産まれ、1年間の育休を取得</span>

  </div>

  <div class="p-4 bg-green500/20 border-8 border-green100/20 border-rounded">

  ## 📝 インプットよりもアウトプットを

  <span class="text-sm">がんばって記事を書き続けています</span>

  </div>

  <div class="p-4 bg-gray500/20 border-8 border-gray100/20 border-rounded">

  ## 🤼‍♀️ 野球よりもプロレスを

  <span style="font-size: 0.2rem; color: gray">「東京女子プロレス」という沼にハマり中。<br/>坂崎ユカ選手のアクスタが発表を応援してくれてる......！</span>

  </div>

</div>

<br>
<br>

<!--
- 14:02
- アジャイル4原則をまねてみました
- 育休の話とかはMeetyでぜひ
-->

---
transition: fade-out
layout: default
---

# こんな記事を書いています

<div class="mt-16 text-center text-xl">

<span class="text-sm">今日の発表元になったブログ記事</span>

[だれかの進捗をうまく把握できないときのフレーズ集](https://qiita.com/kobori_akira/items/9ab3e81bbf0d1c00e49f)  

</div>


<div class="mt-24 text-sm">

そのほか、次のような記事を書いています

- [「ふつうのエンジニア」になるための、ちょっとした発想の転換](https://qiita.com/kobori_akira/items/02d9808af29a70068d87)
- [非エンジニア向けにもわかるよう「依存」を解説する](https://qiita.com/kobori_akira/items/29a0f6b3350ccb362424)
- [「できる」と「わかる」を区別する](https://qiita.com/kobori_akira/items/7e78d43e40f6b796929d)
- [有野課長のように、あるいはあの頃のボクのように](https://qiita.com/kobori_akira/items/c8129a3a1de9f2b896d4)

</div>

<!--
- 14:03
- 今日の発表の元ネタになったブログ。Qiitaは95000viewと1200いいね、はてブは1500のブックマーク
  - 変な炎上もせず、いろいろな意見や感想がもらえてよかった
- 技術が好きだが、ブログにはエンジニアリング以外のことを書いています。よかったら読んでみてください
-->

---
layout: default
transition: fade-out
---

# 目次

<div class="text-2xl">

0. イントロダクション
1. 「計画づくり」と「進捗」
2. 進捗を把握する難しさ
3. 進捗をうまく把握するために
3. 「進捗」を把握しやすくするフレーズ
4. みんなのフレーズ

</div>

<!--
- 14:06
- 今日の目次は次の通り
- 1: 「計画づくり」と「進捗」という言葉について、共通した認識を持ち、その重要性を理解すること。
- 2: つぎに重要な「進捗」を把握することの難しさ
- 3: そして重要な要素である「進捗」をどのように把握すればよいか
- 4: 最後は「進捗」を把握しやすくするための具体的なフレーズをひとつずつ見ていく
- 5: さらには、興味・関心を持って集まっていただいた皆さんがどんなフレーズを使っているか。あるいは使ってみようと浮かんだか教えていただき、この場で拾えたらと思っています
  - この時間ですぐ出ないようであれば、こうしたことを強く意識したキッカケを語ろうと思います
-->

---
transition: fade-out
layout: cover
background: ./images/erik-witsoe-pvoQJym18Jg-unsplash.jpg
---

# イントロダクション

<!--
- というわけで、早速内容に入ってきましょう。さて......
-->

---
transition: slide-up
layout: image-right
image: ./images/brooke-cagle--uHVRvDr7pg-unsplash.jpg
---

# ある日の開発チームにて

- 朝会やデイリースクラムで、お互いの進捗を確認しあっています
- どんなふうに報告するでしょうか？

<style>

.footnotes-sep {
  @apply mt-20 opacity-10;
}
.footnotes {
  @apply text-sm opacity-75;
}
.footnote-backref {
  display: none;
}

</style>

<!--
- 14:07
- できるかぎり具体的にイメージさせる。Discordへの書き込みも募集
  - 朝8時に起きて支度して、出社もしくはオンラインでデイリーが始まります
  - おそらくは昨日完了したことや今日やることを話すでしょう
  - 実際今週のデイリーはどうでしたか？
  - デイリーやっていない人は、誰かに状況を確認されたときにどう答えるかを考えてみてもよいです
- だいたいは「いま〜の開発を進めてます。今日はその続きをやります」ぐらいでは？
-->

---
transition: fade-out
layout: image-left
image: ./images/brooke-cagle--uHVRvDr7pg-unsplash.jpg
---

# ある日の開発チームにて

- 朝会やデイリースクラムで、お互いの進捗を確認しあっています
- どんなふうに<span class="p-1 bg-red500/20 font-bold">報告してほしい</span>でしょうか？

<!--
- 14:10
- あなたがプロダクト・プロジェクトのマネージャー、あるいはその作業者・チームの進行具合があなたの作業に影響を与える場合を想定してみましょう
- あなたがさきほどした情報共有は、どれくらい嬉しいものですか？
- たとえば「決済機能を開発をひきつづき続けてます」とか「不具合の改修がだいたい終わりました」とか
- あなたがそれを受け取ったあとのリアクションも考えてみたいですね
-->

---
transition: fade-out
layout: cover
background: ./images/erik-witsoe-pvoQJym18Jg-unsplash.jpg
---

# 「計画づくり」と「進捗」

<!--
- 14:10
- 想像してもらったところで、「計画づくり」と「進捗」について語ってみようと思います。
- まず「計画づくり」から考えてみましょう
-->

---
class: px-20
---

# 「アジャイル」と「計画づくり」

<div class="m-4 p-4 text-sm bg-gray500/20">

見積りと計画づくりは、期日やスケジュールを決定するためだけのものではない。計画づくりとは価値の探求なのだ。\[...\]答えをゴールへと少しつづ近づけていくこと(インクリメンタルに)、そしてそれを繰り返すこと(イテレーティブに)。\[...\]  
たとえばあるプロジェクトで、最初のスケジュールでは一連の機能セットのリリース日を8月31日に設定していたとする。しかし7月に入った時点になって、少し機能を増やして、その分だけリリースを遅らせる判断を下すかもしれない。あるいは少し機能を削ってでも早めにリリースすることに決めるかもしれない。  

<div class="text-right">『アジャイルな見積りと計画づくり〜価値あるソフトウェアを育てる概念と技法』、p28。</div>
</div>

<div class="my-8 text-center">自分なりにかみくだくと...</div>

<div class="m-4 p-4 bg-blue500/20">

- 「計画づくり」をすることで、品質・コスト・納期・スコープの調整ができる
- 「計画」ではなく「**計画づくり**」が重要である  <span class="text-sm">（refs: [アジャイル開発は計画しない？](https://qiita.com/kobori_akira/items/6f122372ff114d4ae373)）</span>
</div>

<!--
14:13
- いったん引用をすべて読む。
- 「計画づくり」をすることで、QCD(質、コスト、納期)の調整ができる
- できあがった「計画」も大事だが、アジャイルにおいてはそれ以上に「計画づくり」が重要。
  - 計画を見直しつづけることで、アジャイルな開発が達成できる
  - Qiita書いてるのでよろしければ
-->

---
preload: false
---

# よい「計画づくり」とは

<div class="m-2">

  <div class="my-16 mx-32 p-4 bg-gray500/20">

  よい計画づくりとは、以下のような特徴を持ったプロセスのことだ。  
  いずれも「ソフトウェア開発の問い」に対する答えを見つける手助けとなる。  

  ・**リスクを軽減する**  
  ・**不確実性を減らす**  
  ・**意思決定を支援する**  
  ・信頼を確立する  
  ・情報を伝達する

  <div class="text-right text-sm">
  (同、p29, 太字は引用者。)
  </div>

  </div>

</div>

<!--
14:15
- 引用を読む
- よい計画づくりを続けていれば、自然と不確実性・リスクのコントロールができるようになる。コントロールには意思決定も含む
- このプレゼンではとくに太字の3つを取り上げて展開したい
-->

---
layout: center
---

# 「進捗」とは

<!--14:15
つぎに「進捗」が「計画づくり」とどう関連しているのかをおさえましょう
-->


---

# 「進捗」とは

<div class="my-4 mx-24 p-4 text-sm bg-gray500/20">

進み具合・捗り具合、物事がどの程度うまく（順調に）進んでいるか、という意味で用いられる語。「進捗は芳しくない」という風に単独で用いられることもあるが、「進捗状況」や「進捗率」のように連語表現として用いられることも多い。<div class="text-right">([「進捗(しんちょく)」の意味や使い方 わかりやすく解説 Weblio辞書](https://www.weblio.jp/content/%E9%80%B2%E6%8D%97))</div>
</div>

<div class="mt-8 mb-4 text-center text-baseline">

自分なりに再定義すると......

</div>

<div class="mx-40 p-4 bg-blue500/20 text-baseline">

<div class="my-4 text-center text-2xl">ある時点からある時点までの間の差分</div>

- ざっくり「状況が変わった」みたいなこと
- ポジティブ、ネガティブは関係ないとしている
- タスクが完了しただけでは不十分であることが多い

</div>

<div class="p-4">



</div>


<!--
14:17
- 辞書的な意味は無視して、もっとわかりやすく表現してみた
- 例: 待ち合わせ場所に行くとき(どこまで着いたか？)
- ネガティブであっても状況が変わったのであれば、それは進捗と捉えたほうがいいと思う
  - ただし環境の変化までは含めない。あくまで自身の行動による影響の範囲内で考える
- TODOリストにおける「完了」がそのまま進捗でないことが重要だと考えている
-->

---

# 進捗であるもの、進捗でないもの

<div class="grid grid-cols-2 gap-8 p-8">

  <div class="p-4 bg-green-500/20">

  <div class="mb-4 text-center text-3xl">👍</div>

  - ◯◯機能のリリースをした
  - ◯◯機能のテストが完了した
  - レビューで修正すべき点が明らかになった
  - MTGによって来期の計画が決まった

  </div>

  <div class="p-4 bg-gray-500/10">

  <div class="mb-4 text-center text-3xl">👎</div>

  - 1時間のMTGをした
  - 実装が進んだ
  - いろいろやった

  </div>

</div>

<div class="mt-4 mx-10 p-4 bg-blue-500/20 text-center text-2xl font-bold">「進捗」のない「完了」も存在する</div>

<!--
14:20
- リリースやテスト完了はとくに違和感ないだろう
  - これは「〜が終わったら次は...をする」みたいなイメージができるから、状況が変わった
- 同じくグッドケースは状況が変わっている
- TODOリストであれば「1時間のMTGをした」ことで完了となる。しかし意味のないMTGだったかもしれない。なにも意思決定ができなかったかもしれない
  - 脱線するが、MTGにおいても「MTG前後で差分が出る」ように意識したほうがいい。差分は意思決定にかぎらず、「相手が〜を知っている状況にする」とかもOK
- 「実装が進んだ」も似ている。進んだことは嬉しい。でもそれで結局なんなの？
  - たとえば「〜のストーリーが完成した」とかだと良い。「開発が難しい開発は終わったので、あとは計画した通りに進められる可能性が高くなった」とかだと最高では？
-->

---

# なぜ「進捗」が重要なのか

<div class="grid grid-cols-2 gap-8 p-10">

  <div class="p-8 bg-blue-500/20">

  ## 計画づくりのため

  「進捗」が出ることによって、計画づくりを続けることができる

  </div>

  <div class="p-8 bg-blue-500/20">

  ## モチベーションのため

  「進捗」は自己効力感・モチベーションを高める

  <span class="text-sm">

  refs: [マネジャーの最も大切な仕事――95%の人が見過ごす「小さな進捗」の力](https://www.amazon.co.jp/%E3%83%9E%E3%83%8D%E3%82%B8%E3%83%A3%E3%83%BC%E3%81%AE%E6%9C%80%E3%82%82%E5%A4%A7%E5%88%87%E3%81%AA%E4%BB%95%E4%BA%8B%E2%80%95%E2%80%9595-%E3%81%AE%E4%BA%BA%E3%81%8C%E8%A6%8B%E9%81%8E%E3%81%94%E3%81%99%E3%80%8C%E5%B0%8F%E3%81%95%E3%81%AA%E9%80%B2%E6%8D%97%E3%80%8D%E3%81%AE%E5%8A%9B-%E3%83%86%E3%83%AC%E3%82%B5%E3%83%BB%E3%82%A2%E3%83%9E%E3%83%93%E3%83%BC%E3%83%AB/dp/4862762409)

  </span>
  </div>

</div>

<!--
14:22
- 進捗が出ると計画づくりができる。なぜなら状況が変わるから
  - 乗り物の例ふたたび
- 進捗が出ていることを確認させることも重要
  - 本人は上手に把握していないが、ちゃんと分析すれば大小関係なく「進捗」はあるはず
  - 「昨日と比べて、〜が変わったね！」という勇気づけができる
-->

---
transition: fade-out
---

# ここまでのまとめ

<div class="m-2 pl-4 bg-blue500/20 border-2 border-blue100/20 border-rounded text-xl">

**・「計画づくり」を続けるには「進捗」を出すことが重要**

</div>

<div class="m-2 pl-4 bg-blue500/20 border-2 border-blue100/20 border-rounded text-xl">

**・「進捗」を把握すれば「計画づくり」が続けられる**  

</div>

<div class="m-2 pl-4 bg-blue500/20 border-2 border-blue100/20 border-rounded text-xl">

**・「進捗」とは差分である**  

</div>

<div class="m-2 pl-4 bg-blue500/20 border-2 border-blue100/20 border-rounded text-xl">

**・「進捗」のない「完了」も存在する**  

</div>

<div class="m-2 pl-4 bg-blue500/20 border-2 border-blue100/20 border-rounded text-xl">

**・進捗を把握するのは難しい**

</div>

<div class="m-2 pl-4 bg-blue500/20 border-2 border-blue100/20 border-rounded text-xl">

**・「これまでどこにいて、いまどこにいるのか」<br/>　「辿り着いてわかったことはなにか」を把握しよう**

</div>


<!--
- アジャイル開発において計画づくりが重要であり、そのためには進捗を出すことが重要である
- ここでちょっと水飲みたい
-->

---
transition: fade-out
layout: cover
background: ./images/erik-witsoe-pvoQJym18Jg-unsplash.jpg
---

# 進捗を把握する難しさ

<!--
- 14:23
- 一方で「進捗を把握する」ことは一筋縄ではいかないことを見ていきましょう
- これは自分の進捗だって難しい。他人ならなおさら。
-->

---

# (再掲)進捗であるもの、進捗でないもの

<div class="grid grid-cols-2 gap-8 p-8">

  <div class="p-4 bg-green-500/20">

  <div class="mb-4 text-center text-3xl">👍</div>

  - ◯◯機能のリリースをした
  - ◯◯機能のテストが完了した
  - レビューで修正すべき点が明らかになった
  - MTGによって来期の計画が決まった

  </div>

  <div class="p-4 bg-gray-500/10">

  <div class="mb-4 text-center text-3xl">👎</div>

  - 1時間のMTGをした
  - 実装が進んだ
  - いろいろやった

  </div>

</div>

<!--
- さらっと再確認
-->

---

# (再掲)よい「計画づくり」とは

<div class="m-2">

  <div class="my-16 mx-32 p-4 bg-gray500/20">

  よい計画づくりとは、以下のような特徴を持ったプロセスのことだ。  
  いずれも「ソフトウェア開発の問い」に対する答えを見つける手助けとなる。  

  ・**リスクを軽減する**  
  ・**不確実性を減らす**  
  ・**意思決定を支援する**  
  ・信頼を確立する  
  ・情報を伝達する

  <div class="text-right text-sm">
  (同、p29, 太字は引用者。)
  </div>

  </div>

</div>

<!--
- さらっと再確認
-->

---
transition: fade-out
---

# 「進捗ではない」「計画づくりにひもづかない」報告

<div class="mt-16 px-16">

  <div class="text-left">
  👨「◯◯機能の実装をつづけます！」
  </div>

  <div class="text-right">

  👩「昨日は〜に関するMTGをして、今日は...のMTGをします！」
  </div>

  <div class="text-center">

  💪「昨日はいろんなことをしました。今日もタスクをどんどん片付けます！」
  </div>

  <div class="text-right">

  😎「とくに報告すべきものはありません！」
  </div>
</div>

<div class="m-8 text-center text-4xl color-gray">↓</div>

<div class="p-4 bg-blue500/20 text-2xl text-center">

**進捗の把握しづらい情報共有は、よい計画づくりを難しくしてしまう**

</div>

<!--
14:25
- まず、これらは決して「怠けている」わけではない。仕事はしている
- しかし計画づくりに活かせる情報か？　そうではない
  - リスクは軽減した？　不確実性は減った？　意思決定を支援できそう？
- 進捗のわからない情報を受けても、計画を見直せない
  - だから土壇場になって計画の大きな見直しが発生する
-->

---
transition: fade-out
layout: cover
background: ./images/erik-witsoe-pvoQJym18Jg-unsplash.jpg
---

# 進捗をうまく把握するために

<!--
- ではどのようにして他人の進捗を把握しましょうか？
-->

---

# どんな情報を引き出したいか

<div class="grid grid-cols-2 gap-4">

  <div class="p-4">

  <div class="text-center text-baseline">進捗を把握するために</div>

  <div class="my-2 mx-8 p-4 bg-blue500/20 text-sm">

  <div class="mb-2 text-center text-3xl">これまでどこにいて、いまどこにいるのか?</div>

  </div>

  </div>

  <div class="p-4">

  <div class="text-center text-baseline">よい計画づくりのために</div>

  <div class="my-2 mx-8 p-4 bg-blue500/20 text-sm">

  <div class="mb-2 text-center text-3xl">辿り着いてわかった<br/>ことはなにか？</div>

  </div>


  </div>

</div>

<div class="pt-8 px-4">

  <div class="text-baseline">たとえば...</div>

  <div class="text-baseline">

  👨「昨日予定していたAPIの設計について、OpenAPIのyamlファイルの作成まで完成した。」
  </div>

  <div class="text-baseline">

  👩「開発は順調だけれど、実装するなかで気になる点が出てきた。それは〜」
  </div>

  <div class="text-baseline">

  😎「仕様・実装が複雑になり、後半に予定している結合テストのシナリオが当初の2,3倍ぐらいに膨らみそうだとわかった」
  </div>

</div>

<!--
- 14:27
- あなたはこれまでどこにいて、いまどこにいるのか
  - 差分（状況の変化）のわかる情報
- 辿り着いてわかったことはなにか？
  - リスク・不確実性の増減のわかる情報
  - 意思決定の材料になる情報
- 具体例の説明
-->

---
transition: fade-out
---

# ここまでのまとめ

<div class="m-2 pl-4 bg-blue500/20 border-2 border-blue100/20 border-rounded text-xl">

**・「計画づくり」を続けるには「進捗」を出すことが重要**

</div>

<div class="m-2 pl-4 bg-blue500/20 border-2 border-blue100/20 border-rounded text-xl">

**・「進捗」を把握すれば「計画づくり」が続けられる**  

</div>

<div class="m-2 pl-4 bg-blue500/20 border-2 border-blue100/20 border-rounded text-xl">

**・「進捗」とは差分である**  

</div>

<div class="m-2 pl-4 bg-blue500/20 border-2 border-blue100/20 border-rounded text-xl">

**・「進捗」のない「完了」も存在する**  

</div>

<div class="m-2 pl-4 bg-blue500/20 border-2 border-blue100/20 border-rounded text-xl">

**・進捗を把握するのは難しい**

</div>

<div class="m-2 pl-4 bg-blue500/20 border-2 border-blue100/20 border-rounded text-xl">

**・「これまでどこにいて、いまどこにいるのか」<br/>　「辿り着いてわかったことはなにか」を把握しよう**

</div>


<!--

-->

---
transition: fade-out
layout: cover
background: ./images/erik-witsoe-pvoQJym18Jg-unsplash.jpg
---

# 「進捗」を把握しやすくするフレーズ

<!--
- 14:28
- Discordにたくさん書いてくれると嬉しい！
-->

---
layout: center
---

# 「進捗」を把握しやすくするフレーズ

<div class="m-20 p-8 bg-green500/20">

みなさんなら、どうやって情報を引き出しますか？

「こうしている」とか「こう言ったらいいかも」など教えてほしいです！

</div>

---
layout: cover
background: ./images/pawel-czerwinski-i0h7EEsOwNQ-unsplash.jpg
---

# 次にやることは？

# このあとは何をする？

---

# 次にやることは？ / このあとは何をする？

<div class="m-16 text-xl">

- できるかぎり具体的な「次の行動」を確認する
- 自然と「いまどこまで終わったか」が明らかになることが多い
- 明確でないときは、なにかに困っていることがわかる
- いざ考えてみると課題が言語化される

</div>

<!--
- めっちゃ具体的な回答が出るまで質問することがポイント
-->

---
layout: cover
background: ./images/pramod-tiwari-2JMKvS2qT9c-unsplash.jpg
---

# 〜時点でどんな状態を目指しますか？

---

# 〜時点でどんな状態を目指しますか？

<div class="m-16 text-xl">

- 「〜という状態になっている」「〜が完了している」などを定義してみる
  - 「状態」の達成条件も決めておくと尚良し
- チームとして想像してないケースも意外に多い
  - 時間をかけてでもやっておくと、ふりかえりがやりやすくなる
- 「わからない」も大事な情報。リスクや不確実性を表すから

</div>

<!--
- どちらかというと目標設定の話
- ただ目標を決める＝計画をつくるには、いまの状況を認識しなければいけない
- 「わからない」は貴重な情報
-->

---
layout: cover
background: ./images/eren-yildiz-oQzH8fIfjoM-unsplash.jpg
---

# 「明日〜して」って言われたら大丈夫ですか？

---

# 「明日〜して」って言われたら大丈夫ですか？

<div class="m-16 text-xl">

- 進捗の確かさや、お互いの完了条件が一致しているかを確認できる
- とくに「完成」「リリース」という状態が各役割で一致していないことが多い
  - 「実装が(だいたい)終わった」と伝えているが、テストは終わってないし、リファクタリングも必要だと自覚している
  - 開発者目線ではリリースできるが、リリースに必要なそのほかのステップが進んでいない

</div>
<!--
- 何％ぐらい終わってますか？　より良いと思っている
- 冗談めかして「明日リリースしちゃってもいいですか？」とか聞く
- 「だいたい終わった」みたいな話が出てきたらこれを使うと効果ある
  - だいたい終わったけれど「完成」ではない、みたいなことあるよね？
-->

---
layout: cover
background: ./images/sumaid-pal-singh-bakshi-W9x3K7pD0S8-unsplash.jpg
---

# 大変だったことはありますか？

---

# 大変だったことはありますか？

<div class="m-16 text-xl">

- 「たどりついてわかったこと」の観点
- 「時間がかかった」「面倒くさかった」「できなかったので〜で代用した」などある
- 再現するものであれば、チーム・組織として潰したい

</div>

<!--
- 「たどりついてわかったこと」の観点
- 「時間がかかった」「面倒くさかった」「できなかったので〜で代用した」などある
- 再現するものであれば、チーム・組織として潰したい
-->

---
layout: cover
background: ./images/gor-UqV3Chmk8v4-unsplash.jpg
---

# どうでもいいけど話しておきたいことはありますか？

---

# どうでもいいけど話しておきたいことはありますか？

<div class="m-16 text-xl">

- ときおりとんでもない効果を出す質問
- ふだん発言の少ない人や発言をためらってる人が喋ってくれるように促してみる
- 「どうでもいい」情報＝「自身ではコントロールできない」情報
  - どうでもいいのではなく、解決が難しいから黙っていたことがほとんど

</div>

<!--
- できるかぎり喋りやすい雰囲気にしてから聞く
-->

---
transition: fade-out
layout: cover
background: ./images/erik-witsoe-pvoQJym18Jg-unsplash.jpg
---

# みんなのフレーズ

<!--
- ぜひ皆さんも！
- 時間があまったときのメモ
  - 週報、テクニカルライティングの話
  - これを何人かに伝えて実際に効果がめちゃくちゃあった
-->

---
transition: fade-out
image: ./images/erik-witsoe-pvoQJym18Jg-unsplash.jpg
---

# ご清聴ありがとうございました！

<div>

- 本日の登壇資料は[SlideShare](https://speakerdeck.com/koboriakira)にもアップされています！
  - Slidevをつかって書いてみたので、よろしければ[GitHub](https://github.com/koboriakira/slidev/tree/main/xp_festival_2023)も
- 感想や疑問、質問など好きに書いていただければ嬉しいです！
- ひきつづき[Qiita](https://qiita.com/kobori_akira)などに記事を書き続ける予定です。よろしければフォローください！
- 自社採用の一貫で[Meety](https://meety.net/matches/iygXhCOyFXsS)もオープンにしています

  <div class="grid grid-cols-3 gap-4 mt-8">

  <div>
    <div class="text-center text-sm">Qiita</div>
    <div class="ml-13"><img src="images/qiita_qr.png" class="h-40 rounded shadow" /></div>
  </div>
  <div>
    <div class="text-center text-sm">Meety(アジャイル話)</div>
    <div class="ml-14"><img src="images/meety-agile-qr.png" class="h-40 rounded shadow" /></div>
  </div>
   <div>
    <div class="text-center text-sm">Meety(育休話)</div>
    <div class="ml-13"><img src="images/meety-ikukyu-qr.png" class="h-40 rounded shadow" /></div>
  </div>

  </div>
</div>
<!--
- 時間があまったときのメモ
-->
