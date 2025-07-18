---
cover:
description: 文書化されたポストモーテムを完了した後、インシデントについて議論するためのミーティングを行います。このミーティングの目的は、直接的なコミュニケーションを通じてポストモーテム分析を深め、アクションアイテムへの賛同を得ることです。
---
![The Postmortem Meeting](assets/img/headers/Postmortems-Meeting.png)

## 目的
文書化されたポストモーテムを完了した後、インシデントについて議論するためのミーティングを行います。**このミーティングの目的は、直接的なコミュニケーションを通じてポストモーテム分析を深め、アクションアイテムへの賛同を得ることです。** 文書化されたポストモーテムの非同期的な作成はチームがインシデントから学び始めるのに役立ちますが、会話を持つことでより深い学びにつながります。さらに、文書化されたポストモーテムについて議論するためのミーティングをスケジュールすることで、ポストモーテムをタイムリーに完了するための[説明責任（accountability）](culture/accountability.md)が生まれます。このミーティングでアクションアイテムについて議論することで、それらのタスクが確実に完了するよう支援します。

ポストモーテムミーティングのアンチパターンは、文書化されたポストモーテムに記載された直接的な懸念事項に過度に焦点を当てることです。ドキュメントの各セクションを単に読み上げることにミーティング時間を使うのは避けてください。この時間を最も有効に使う方法は、詳細な分析から一歩引いて、インシデントにつながったシステム的要因をより良く理解することです。

一部のチームは、ミーティングの基調を設定し、目的を定期的に思い起こすために[レトロスペクティブ・プライム・ディレクティブ](http://retrospectivewiki.org/index.php?title=The_Prime_Directive)を活用しています。これは、レトロスペクティブ、ポストモーテム、またはポストインシデントレビューを始めるための白紙の状態を提供し、議論の基盤となる役立つツールとなります。

>
  「私たちが何を発見しようとも、その時点で知っていたこと、スキルと能力、利用可能なリソース、そして直面していた状況を考慮すれば、誰もが最善を尽くしたと理解して信じています。」
  --Norm Kerth著「Project Retrospectives: A Handbook for Team Review」


**ポストモーテムミーティングの最も重要な成果は、アクションプランへの賛同です。** これは提案された[アクションアイテム](how_to_write/writing.md)について議論し、他の選択肢についてブレインストーミングし、チームリーダーシップ間でコンセンサスを得る機会です。ときには、提案されたアクションアイテムの投資対効果が作業を正当化するほど大きくない場合や、他の優先事項をポストモーテムのアクションアイテムに比べて遅らせなければならない場合もあります。ポストモーテムミーティングは、これらの難しい決断について議論し、どの作業を行い、どの作業を行わないのか、そしてそれらの選択によって予想される影響を明確にする時間です。

文書化されたポストモーテムは組織内で広く共有されることを意図していますが、ポストモーテムミーティングの主な対象者はインシデントに直接関わったチームです。このミーティングは、チームが何が起こったのか、それについて何をすべきか、そしてインシデントについて内部および外部のステークホルダーにどのように伝えるかについて認識を合わせる機会を提供します。

!!! tip
    ミーティングの24時間前にポストモーテムドキュメントのリンクを参加者に送信してください。ポストモーテムは参加者に送信される時点で完成している必要はありませんが、ポストモーテムミーティングの開催までに完成させましょう。参加者が文書を読み始められるように、不完全なポストモーテムでも事前に共有しておく価値があります。

    これにより、ミーティングで単に文書を読み上げるために時間を無駄にすることを避けられます。ミーティングの目的は、インシデントの原因と将来それを防ぐ方法について深い会話をすることであり、文書をレビューすることではないことを覚えておいてください。ポストモーテムミーティングは、何が起こったのか、そしてそれが再び起こるのを防ぐためにチームで何をするかに関する疑問点を明らかにする機会でもあります。全員が同じ認識を持てるよう、参加者にあらゆる質問を促し、分析を進める上でチームが新しい視点から考えられるようにしましょう。

## アジェンダ
ミーティングのサンプルアジェンダは以下の通りです：

1. **ポストモーテム担当者**がインシデントの原因とタイムラインを要約します。**ファシリテーター**が議論をリードします：
    - インシデントにつながったより大きな文化的・構造的要因は何でしたか？**どのようにしてここに至ったのでしょうか？**
1. **ポストモーテム担当者**が提案されたフォローアップアクションアイテムを要約します。**ファシリテーター**が議論をリードします：
    - この計画がインシデントの再発の可能性を減らすことに、チームは**自信**を持てますか？
    - **どのような追加または異なる作業が必要な可能性がありますか？**
    - チームリーダーシップ（エンジニアリングマネージャー、プロダクトマネージャー、テックリードなど）はこれらのアクションアイテムを優先することを**約束**しますか？
1. **カスタマーリエゾン**が顧客への影響を要約します。
    - インシデントに対する顧客の反応について、新たなコンテキストを提供します。
    - ポストモーテムで起草された外部コミュニケーション内容をレビューし、承認します。

## 参加者
ポストモーテム担当者は、ポストモーテムミーティングに以下の人々を招待します。以下は、各自が議論で果たす役割についての詳細です。

- 必須参加
    - [インシデントコマンダー](https://response.pagetduty.co.jp/training/incident_commander/)。
        - インシデントコマンダーは対応の調整を担当します。ポストモーテムミーティングでは、インシデントコマンダーはインシデント対応の取り組みとプロセス改善について貴重なフィードバックを提供できます。
    - インシデントコマンダーのシャドーイングをしていた人（いた場合）。
        - この人は[書記官](https://response.pagetduty.co.jp/training/scribe/)または[副指揮官](https://response.pagetduty.co.jp/training/deputy/)を務めた可能性があります。副指揮官は、必要な対応者をコールに追加し、インシデント対応コール外の内部ステークホルダーを更新する責任があります。副指揮官は対応の取り組みと、インシデント対応中に追加された対応者やステークホルダーとのコミュニケーションに関し、やりやすかった面や難しかった面について貴重なフィードバックを提供できます。
    - インシデントに関わった[サービスオーナー](https://response.pagetduty.co.jp/training/subject_matter_expert/)と他の主要なエンジニア。
        - オンコールのサービスオーナーとインシデントに対応した他のエンジニアは、影響を受けたサービスの専門家です。ポストモーテムミーティングでは、システムがどのように構築されたかについての歴史的コンテキスト、インシデントに至るまでのチームで起きていたことについての文化的コンテキスト、そしてこのインシデントの再発の可能性を減らすためにどのような作業が必要かについての提案を提供できます。
        - 生産的なポストモーテムの議論には、チームが所有するシステムの部分について深い知識を持つエンジニアが含まれます。インシデントに対応したエンジニアが新しいチームメンバーである場合は、同じチームのより経験豊富なエンジニアにポストモーテムミーティングへ参加してもらうと効果的です。
    - 影響を受けたシステムのエンジニアリングマネージャー。
        - インシデントに対応したチームを担当するマネージャーは、スタッフ配置と技術投資の決定に情報を提供するためにポストモーテムミーティングに参加します。
    - 影響を受けたシステムのプロダクトマネージャー。
        - プロダクトマネージャーは、インシデントが顧客体験に与える影響を理解するためにポストモーテムミーティングに参加します。ポストモーテムのアクションアイテムを優先し完了するためには、提案されたフォローアップタスクの重要性と範囲についてのこの議論にプロダクトマネージャーを関与させることが重要です。
- 任意参加（Sev-1インシデントのみ）
    - [カスタマーリエゾン](https://response.pagetduty.co.jp/training/customer_liaison/)。
        - カスタマーリエゾンはインシデントに対する顧客の反応について話すことができます。彼らは外部メッセージを最終化して送信できるように、アクションアイテムに関するチームの決定を理解する必要があります。

## ファシリテーション
### ファシリテーションとは
ポストモーテムミーティングにおけるファシリテーターの役割は、他の参加者とは異なります。ファシリテーターはミーティングで自分のアイデアを表明せず、代わりにグループが発言し、議論を軌道に乗せるよう促します。ポストモーテム担当者、インシデントコマンダー、またはインシデント中に積極的な役割を果たした他のミーティング参加者は、議論に貢献する必要があり、ファシリテーションの責任も負うべきではありません。

ファシリテーターが行うこと：

- 人々が発言するよう促し、全員の声に耳が傾けられるようにします。
- 洞察を明確にし、チームに質問を投げかけます。
- チームが異なる視点と異なる選択肢に目を向けられるよう促します。
- 全員が時間通りに議論を進め、軌道に乗るようにします。話の脱線を防ぎ、特定の人々がミーティング全体を支配するのを止めます。
- できるだけ少なく話します。議論を導くことを念頭におきながら、ミーティングを乗っ取らないように注意してください。

ファシリテーターが行わないこと：

- 決定を下すこと。
- 誰かの肩を持つこと。ファシリテーターが特定の側につくと、チームメンバーは攻撃されていると感じ、ミーティングへの貢献をやめるかもしれません。
    - 人々が言うことにコメントするのは、たとえそれが肯定的なフィードバックを与える意図だったとしても避けましょう。話者自身は肯定感を感じるかもしれませんが、他の人からすると自分がこれから言おうとすることについて悪く感じたり、貢献することを思いとどまったりすることにつながるかもしれません。

### 誰がファシリテートすべきか
優れたファシリテーターは通常、高度な感情的知性を持ち、人々がどのように感じているかを理解するために非言語的な手がかりを容易に読み取ることができます。彼らはこの感覚を使って、誰もが話しやすい環境を育みます。アジャイルコーチやプロジェクトマネージャーはしばしば熟練したファシリテーターです。PagerDutyでは、ファシリテーションの学習に興味のある個人をコーチする自信のあるファシリテーターのギルドがあります。組織内でポストモーテムミーティングのファシリテートを手伝う個人を探す際には、これらのコアコンピテンシーを持つ人を探してください：

- 部屋の中で人々がどのように感じているかを見定め、非言語的な手がかりを読み取って言いたいことがある人を見つけることができる。
- 自分自身と他の人のため、発言内容が明確になるように言い換えることができる。
- より深い思考を刺激するために、オープンな質問をすることができる。
- 議論が脱線したとき、または誰かが議論を支配するときに中断することに慣れている。
- 会話が目標に向かっていくように方向転換することができる。
- 時間を追跡し、時間の通知を与えることができる。
- 議論を導き、意思決定とアクションアイテムへ繋げることができる。

ポストモーテムミーティングのファシリテーターは、影響を受けたシステムの専門家である必要はありません。ファシリテーターは議論の内容に精通している必要はありません。ファシリテーターは議論に自分の意見を貢献するのではなく、他の人が話すよう促すことを忘れないでください。インシデント対応に関わったミーティング参加者がインシデントの専門家であり、ファシリテーターはそれらの専門家がグループと情報を共有するよう促す質問をします。

しかし、ファシリテーターはポストモーテムプロセスとポストモーテムミーティングの目標に精通しているべきで、それによりグループ議論をそれらの目標達成に導くことができます。ポストモーテムミーティングのファシリテーターは、[非難のないこと（ブレームレス）](culture/blameless.md)についてしっかりした理解を持っている必要があり、グループがミーティングで非難の言葉を避けられるようにします。

## ファシリテーションのヒント
ポストモーテムミーティングのファシリテーターは、チームが分析をより深く掘り下げ、[非難を避け](culture/blameless.md)ながら、アクションアイテムへの賛同を得られるようにします。ポストモーテムミーティングの一般的な課題は、文書化されたポストモーテムに過度に焦点を当てることと、システム障害の責任を個人に帰する傾向に屈することです。以下は、効果的なポストモーテムミーティングを実施する方法と、発生した場合の厄介な状況の対処方法に関するヒントです。

**準備事項**

- ミーティングの冒頭でルールを設定します。
    - 全員が発言すべきだが、誰も会話を独占すべきではないという期待値を設定します。
    - ブレームレスなポストモーテムを実践していることを、改めてグループに認識してもらいます。
- 会話が脱線した場合のセーフワードを確立します。
    - チームメンバーが会話がトピックから外れていることに気づいた場合、セーフワードを言って、チームに議論の有用性を再評価させることができます。PagerDutyでは、一部のチームは「ELMO」という頭字語を使用しています。これは「Enough, let's move on（十分です、次に進みましょう）」を意味します。これにより、議論がトピックから外れたときに中断するプレッシャーをファシリテーターだけが負う必要がなくなります。
- アジェンダを共有して、チームが何がトピックに含まれ、何が含まれないかを明確にします。
- タイマーを使用して時間を制限します。
    - 各アジェンダ項目の時間を制限できます。タイマーを表示することで、全員が時間制限を認識し、ファシリテーターが時間のために中断する必要性が減ります。
- ポストモーテムドキュメントをあなたのラップトップからTVに表示して、全員が見られるようにします。

[**非難を避ける方法：**](culture/blameless.md)

- ミーティングの開始時、および/またはミーティング中に非難が発生した場合に、ブレームレスなポストモーテムを実践することに同意していること、そして非難が発生した場合にお互いに指摘することをチームに思い出してもらいます。
- 分析の可能性を狭め、非難を暗示するような「誰が」または「なぜ」という質問は避けるよう注意してください。代わりに「何を」や「どのように」という質問をします：
    - 「何が起きていると思いましたか？」
    - 「次に何をしましたか？」
    - 「その行動はその時点でどのように理にかなっていましたか？」
- 人間の行動について尋ねるとき、特定されていない対応者に抽象化します。誰でも同じミスを犯す可能性があることをチームに思い出させます。
    - 「どのような要因によって対応者がその行動を取る可能性が生じましたか？」

**会話がトピックから外れている場合の対処法：**

- ファシリテーターの仕事はチームを軌道に乗せておくことであり、トピックを続けることが価値があるか、またはオフラインで取り上げることができるかを尋ねることで、ミーティングの目標をチームに思い出してもらい、不適切なトピックを中断する必要があります。
    - 「申し訳ありませんが、このトピックはこのミーティングの目標と関係ないようです。元のトピックに戻りますか、それともこの議論を続けますか？」
- アジェンダ項目の時間を制限します。時間が終わったら、さらに数分間話し続けるかどうかの投票を行います。

**一人がミーティングを支配している場合の対処法：**

- 全員の参加が重要であることを最初に言います。ファシリテーターの責任を説明して、話すのをやめるように頼まれたり、発言するように頼まれたりしても気分を害さないようにします。ミーティング全体を通して、人々がどれだけ話しているかに注意を払います。
- 「最初の人が言っていたことが聞こえませんでした。」
- 仲介者として行動し、人々が中断されているときに指摘します：「その考えをいったん保留してください – Shariが話を終える機会を確保したいと思います」

**チームメンバーが何も言っていない場合、どのように貢献させるか：**

- 「部屋を一周してみなさん全員から意見を聞きましょう」
- 「これまでで目立ったことは何ですか？」
- 「他に考慮すべきことは何がありますか？」

**分析を刺激する方法：**

- オープンな質問をします。「はい」または「いいえ」で答えられる質問はしません。
- [分析の質問](resources/analysis.md)を参照してください。もしかするとチームでは既に、文書化されたポストモーテムを準備する際にこれらの質問を自問しているかもしれません。ミーティングで改めてこのうちのいくつかの項目を尋ねることで、協調的で新しい思考を促しましょう。
