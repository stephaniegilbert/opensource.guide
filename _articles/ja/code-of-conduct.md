---
lang: ja
title: 行動規範
description: 行動規範を採用し遵守してもらうことで、健全で建設的なコミュニティ作りを促進しよう
class: coc
order: 8
image: /assets/images/cards/coc.png
related:
  - building
  - leadership
---

## なぜ行動規範が必要なのか？

行動規範は、あなたのプロジェクトの参加者に期待する振る舞いをまとめたドキュメントです。行動規範を採用し遵守してもらうことで、コミュニティにポジティブな雰囲気をもたらす事ができます。

行動規範は、コミュニティの参加者だけでなく、あなた自身を守ることにも役に立ちます。もしあなたがメンテナーなのであれば、参加者の生産的でない態度に対処することに疲れを感じ、不幸せだと感じることでしょう。

行動規範は、健全で生産的なコミュニティ作りを促進する助けとなります。事前に行動規範を決めておくことで、あなた自身やプロジェクトの参加者が疲れ果ててしまう可能性を下げることができ、あなたが好ましいと思わない事が起きたときに、それに対して行動を起こす助けとなります。

## 行動規範を制定しよう

できるだけ早い段階で行動規範を制定しましょう： 理想的にはプロジェクトを始めに立ち上げるときに作りましょう。

あなたの期待することを伝えることに加えて、行動規範には下記の内容も記述しましょう:

* 行動規範が有効な範囲はどこまでか _(イシューやプルリクエスト上だけで有効なのか、それともイベントのようなコミュニティ活動でも有効なのか？)_
* 行動規範が適用されるのは誰か _(コミュニティメンバーやメンテナー以外にもスポンサーも適用範囲なのか？)_
* 行動規範に違反したら何が起きるのか
* 違反はどのようにして報告するのか

できる限り、既存の行動規範を使いましょう。 [Contributor Covenant](https://contributor-covenant.org/) は40,000以上のオープンソースプロジェクトで使われている行動規範で、 Kubernetes 、 Rails 、 Swift でも使われています。

[Django Code of Conduct](https://www.djangoproject.com/conduct/) や [Citizen Code of Conduct](http://citizencodeofconduct.org/) の2つもよく使われる行動規範です。

CODE_OF_CONDUCT ファイルをプロジェクトのルートディレクトリに置き、 CONTRIBUTING や README ファイルからリンクを張ってコミュニティの皆がすぐに見れるようにしましょう。

## どのように行動規範を遵守してもらうかを決めよう

<aside markdown="1" class="pquote">
  遵守されていない行動規範は、全く行動指針がない状態よりも悪い状態です： 行動規範が遵守されていない状態は、行動規範に記載されている価値観が実際は重要でないか尊重されていないというメッセージをコミュニティの人々に与えてしまうからです。
  <p markdown="1" class="pquote-credit">
— [Ada Initiative](https://adainitiative.org/2014/02/18/howto-design-a-code-of-conduct-for-your-community/)
  </p>
</aside>

行動規範の違反が発生する **前に** どのように行動規範を遵守してもらうかを説明するべきです。そうするべき理由はいくつかあります：

* 必要な時にはあなたが行動を起こすということに本気であるということを示す事ができる。

* 不平不満に対して実際にレビューが入ることで、コミュニティのメンバーを安心させることができる。

* コミュニティのメンバーたちに対して違反について調査をするときに、レビュープロセスが公正で透明性の高いものであると安心させることができる。

メンバーに対しては、行動規範の違反を報告するための（メールアドレスのような）プライベートな方法を与え、それを受け取るのが誰なのかを説明するべきです。それは一人のメンテナーかもしれないし、メンテナー達のグループかもしれないし、行動規範チームかもしれません。

行動規範違反の報告を受けている人自身の違反行為を、誰かが報告するかもしれないことを忘れてはいけません。この場合は、他の人に違反を報告できるような選択肢を設けましょう。例えば、 @ctb と @mr-c は、彼らの [khmer](https://github.com/dib-lab/khmer) というプロジェクトで[このように説明しています](https://github.com/dib-lab/khmer/blob/master/CODE_OF_CONDUCT.rst):

> 不正行為やハラスメント、受け入れられない行為は、 **khmer-project@idyll.org** にメールを送ることによって報告することが出来ます。このメールは、 C. Titus Brown と Michael R. Crusoe のみが受け取ります。彼ら二人のどちらかが関係する問題について報告する場合は、 NSF Center for Science and Technology の BEACON Center for the Study of Evolution in Action のダイバーシティディレクターの **Judi Brown Clarke, Ph.D.** にメールで報告して下さい。*

他にも Django の [enforcement manual](https://www.djangoproject.com/conduct/enforcement-manual/) も参考になります （ただし、プロジェクトのサイズによってはここまで網羅したものは必要ないかもしれません）。

## 行動規範を遵守してもらおう

どんなに努力したとしても、時には行動規範を違反するような行為をする人も出てきます。こういったネガティブで害のある行為を解決する方法は幾つかあります。

### 状況についての情報を集めよう

コミュニティメンバーの声を、あなた自身の意見と同じくらい大事に扱いましょう。誰かが行動規約に違反していると報告を受けたら、たとえあなた自身の経験と照らし合わせてその人らしくないと感じたとしても、報告を真剣に受け止め調査しましょう。そうすることでコミュニティに対して、コミュニティメンバーのものの見方に価値を見出しており、またコミュニティメンバーの判断を信頼しているという事を示すことが出来ます。

疑いのあるメンバーは、何度も人を不愉快にさせている人かもしれないし、一度だけやってしまった人かもしれません。状況によってはどちらも行動が必要な理由になります。

行動を起こす前に、時間を取って何が起きたのか理解しましょう。その人の過去のコメントや会話に目を通して、彼らがどういった人物でなぜそういった行動に出たのかを良く理解しましょう。その人自体やその人の行動に関して、あなたの観点よりも他の人の観点をより集めましょう。

<aside markdown="1" class="pquote">
  論争に巻き込まれないようにしましょう。眼前の問題を解決し終える前に他の人の振る舞いを対処することに意識が逸れないようにしましょう。必要なことに集中するのです。
  <p markdown="1" class="pquote-credit">
— Stephanie Zvan, ["So You've Got Yourself a Policy. Now What?"](https://the-orbit.net/almostdiamonds/2014/04/10/so-youve-got-yourself-a-policy-now-what/)
  </p>
</aside>

### 適切な行動を取ろう

十分な情報を集めて処理したら、何をするか決める必要があります。次のステップを考える際に覚えておく必要があるのは、調整役としてのあなたのゴールは、安全でお互いを尊重しあえる協力的な環境を推進する事であるということです。問題となっている状況にどのように対処するかだけでなく、あなたの対応が今後どのようにコミュニティの残りのメンバーの行動や期待に影響するかを考える必要があります。

行動規約に対する違反が報告されたら、それに対処するのは報告した人ではなくあなたの仕事です。報告者は彼ら自身のキャリアや名声、物理的な安全性をリスクにさらしてまで報告をしていることもあるのです。そんな彼らを違反者に直面させてしまえば、報告者は妥協せざるを得なくなります。そのため、報告者が明確に望まない限りは、あなたが問題の人物と直接やり取りをするべきです。

行動規約を違反した人に対しての対処法はいくつかあります:

* **公の場で問題の人物に警告を与え**、彼らの行動がどのように他の人に対して悪い影響を与えているかを、できるだけ問題が起きたチャネル上で説明しましょう。公の場でのやり取りは、コミュニティの残りのメンバーに対して、あなたが行動規約を重要なものだと捉えている事を示すことが出来ます。丁寧に、しかしはっきりとした態度でコミュニケーションしましょう。

* **問題の人物に個別に連絡を取り**、彼らの行動がどのように他の人に対して悪い影響を与えているかを説明しましょう。取扱に注意が必要な個人情報を含んでいる場合には、個別のコミュニケーションチャネルを使いたいと思うでしょう。もし個別でやり取りをするのであれば、最初に問題を報告した人を CC に入れるのは良い考えです。そうすることで、報告者に対して行動を取っているということを知らせることができるためです。ただし、報告者を CC に入れる前に彼らに同意を取りましょう。

時には解決に至らないこともあります。問題の人物が攻撃的になったり、対面したときに悪意をむき出しにしたり、振る舞いを改めなかったりするかもしれません。そういった場合には、より強い行動に出る必要があるかもしれません。例えば：

* プロジェクトにおける問題の**人物の活動を一時停止させる**。そのために、一時的にプロジェクトのあらゆる活動に参加するのを拒否しましょう。

* 問題の人物をプロジェクトから**永久に追放する**。

メンバーをプロジェクトから追放するのは軽々しく行うべきではありません。それは、考え方の違いが今後もずっと続くということを意味するからです。こういった措置は、明らかに問題が解決できない場合にのみ取るようにしましょう。

## メンテナーとしての責任

行動規約は、勝手に施行される法規とは異なります。あなたが行動規範の施行者であり、行動規範が定めているルールに従ってもらうようにするのはあなたの責任なのです。

メンテナーとして、あなたはコミュニティのガイドラインを定め、そのルールを行動規範の中で定めることによってガイドラインを遵守させるのです。こうすることで、行動規範に対する違反を報告することが重要であると示すことが出来るのです。報告者は、彼らの苦情を徹底的かつ公正にレビューをするべきです。報告された行動が行動規範に違反していないと判断するのであれば、報告者に対してはっきりとそれを伝え、なぜそれに対して対処を取るつもりがないのかを説明しましょう。それに対して報告者がどうするかは彼ら次第です： 問題だと思っている行動を我慢するか、それともそのコミュニティに参加するのを辞めるかです。

_厳密には_ 行動規範を違反していない行動に対して報告があった場合、コミュニティに問題があるということを示しているかもしれません。そのため、この潜在的な問題を調査し、相応の対処をするべきです。相応の対処とは、受け入れられる行動をより明確にするために行動規範を書き換える事かもしれないし、報告された人物に対して、彼らが行動規範を違反しているわけではないが、期待される行動のぎりぎりの行動をとっており、ある人を不愉快にさせているということを伝えることかもしれません。

以上のように、あなたはメンテナーとして、受け入れられる振る舞いについての基準を定め、それを遵守させているのです。あなたにはプロジェクトの価値観を定める資格があり、プロジェクトの参加者はそれらの価値観を公明正大なやり方で遵守することを期待しているのです。

## あなたが世界中で見たいと望む行動を推奨しましょう 🌎

プロジェクトが有効的でなく歓迎的でもない場合、皆が我慢している人物がたった一人しかいなかったとしても、コントリビューターの多くを失うリスクを抱えているのです。そのうちの何人かは一度も会ったことがないかもしれません。行動規範を採用して遵守させるのは必ずしも簡単なことではありません。しかし、歓迎的な環境を育てていくことはコミュニティを成長させる役に立つでしょう。