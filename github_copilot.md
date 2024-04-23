## Github Copilotの利用状況に関するまとめ(JA)
開発言語別のGitHub Copilotの利用状況に関するデータは、サイバーエージェントが公開した情報に含まれています。サイバーエージェントは、社内でのGitHub Copilotの利用データを公開し、AIが提案したコードの採用率を言語別に明らかにしています。例えば、Typescriptでは提案のうち36.5%が採用され、Goでは39.9%、Pythonでは32.2%の提案が採用されていると報告されています[6]。

また、ZOZO TECH BLOGによると、GitHub Copilotを使用しているプログラミング言語にはBash, C++, Go, Java, JavaScript, Kotlin, Objective-C, PHP, PowerShellなどがあります[1]。これらの言語でGitHub Copilotがどの程度利用されているかについての具体的なデータは記載されていませんが、多様な言語での利用が可能であることが示されています。

調和技研のブログでは、GitHub Copilotが特に得意とする言語としてPython, JavaScript, TypeScript, Ruby, Go, C#, C++が挙げられており、これらの言語でのソースコード生成において高い能力を持っていることが説明されています[7]。

これらの情報は、GitHub Copilotが多様な開発言語に対応しており、言語によって採用率に差があることを示しています。ただし、これらのデータはあくまでサイバーエージェントとZOZOの事例であり、全体的な利用状況を反映しているわけではない点に注意が必要です。

Citations:
[1] https://techblog.zozo.com/entry/introducing_github_copilot
[2] https://sqripts.com/2023/11/02/76103/
[3] https://docs.github.com/ja/copilot/using-github-copilot/getting-started-with-github-copilot
[4] https://xtech.nikkei.com/atcl/nxt/column/18/02670/112900002/
[5] https://www.kagoya.jp/howto/it-glossary/develop/githubcopilot/
[6] https://www.itmedia.co.jp/news/spv/2307/20/news117.html
[7] https://www.chowagiken.co.jp/blog/github_copilot
[8] https://www.sbbit.jp/article/cont1/137432

## GitHub Copilotの開発生産性向上についての情報(EN)
GitHub Copilotは開発者の生産性を向上させることで開発コストを削減する可能性があります。このドキュメントでは、GitHub Copilotが組織の開発努力を加速し、改善する方法についての洞察を得るためのいくつかの方法を提供しています。具体的には、開発者の調査を実施し、プルリクエストの数などの下流指標を測定することが挙げられます。GitHubの研究によると、GitHub Copilotを使用する開発者はタスクを最大55%速く完了できるとされています。また、開発者はGitHub Copilotからの提案の平均30%を受け入れており、これにより効率が向上していることが示されています。GitHub Copilotは、コードの提案数、受け入れられた提案数、書かれたコード行数など、組織内でのGitHub Copilotの使用に関する追加情報を収集するために、GitHub Copilot Metrics APIベータを利用することができます。開発者が効率を上げることで、イノベーション、学習、古いコードのリファクタリング、技術的負債の対処など、他の優先事項に自由に時間を割くことができるようになります。しかし、これらの下流効果をどのように測定するかは重要な課題です。GitHub Copilotは構造的な制限や進捗を妨げる可能性のある制約を取り除くことはできませんが、開発者の生産性と満足度にプラスの影響を与えることができます[1]。

Citations:
[1] https://resources.github.com/learn/pathways/copilot/essentials/measuring-the-impact-of-github-copilot/
[2] https://www.netguru.com/blog/github-copilot
[3] https://github.blog/2022-09-07-research-quantifying-github-copilots-impact-on-developer-productivity-and-happiness/
[4] https://devops.com/measuring-github-copilots-impact-on-engineering-productivity/
[5] https://insidebigdata.com/2023/08/07/the-economic-impact-of-the-ai-powered-developer-lifecycle-and-lessons-from-github-copilot/
[6] https://ar5iv.labs.arxiv.org/html/2302.06590
[7] https://www.harness.io/blog/the-impact-of-github-copilot-on-developer-productivity-a-case-study
[8] https://www.linkedin.com/pulse/evaluating-copilots-impact-productivity-dimitar-bakardzhiev-b4k9f

## 実験の定量的データ
はい、実験の定量的データがいくつかのソースで提供されています。特に、以下のソースが詳細な定量的データを提供しています：

1. **MITの研究**（[3]）では、MicrosoftとAccentureで行われたランダム化実験について説明しています。この実験では、一部の開発者がGitHub Copilotにアクセスできるようになり、他のグループはアクセスできませんでした。実験の結果、成功したビルドの総数において、84%から107%の増加が見られました。これらの効果は統計的に有意であり、経済的にも意味があるとされています。

2. **GitHubのブログ**（[4]）では、GitHub Copilotの使用が開発者の生産性に与える影響を定量的に測定するために複数の研究ラウンドが行われたことが記されています。具体的には、95人のプロフェッショナル開発者をランダムに2つのグループに分け、JavaScriptでHTTPサーバーを書くタスクの完了時間を計測しました。GitHub Copilotを使用したグループはタスクをより迅速に完了することができました。

3. **Uppsala Universityの研究**（[5]）では、GitHub Copilotの効果を評価するために、定量的および定性的な手法を組み合わせた混合方法論が採用されました。この研究では、GitHub Copilotを使用することで開発時間が大幅に短縮され、コードの品質も若干向上することが示されました。

これらのソースは、GitHub Copilotが開発者の生産性に与える影響を定量的に評価するための実験データを提供しており、その結果はGitHub Copilotが開発プロセスを効率化し、生産性を向上させる有効なツールであることを示唆しています。

Citations:
[1] https://devops.com/measuring-github-copilots-impact-on-engineering-productivity/
[2] https://github.blog/2023-06-27-the-economic-impact-of-the-ai-powered-developer-lifecycle-and-lessons-from-github-copilot/
[3] https://mit-genai.pubpub.org/pub/v5iixksv/release/2
[4] https://github.blog/2022-09-07-research-quantifying-github-copilots-impact-on-developer-productivity-and-happiness/
[5] https://uu.diva-portal.org/smash/get/diva2:1775041/FULLTEXT01.pdf
[6] https://cacm.acm.org/research/measuring-github-copilots-impact-on-productivity/
[7] https://www.nngroup.com/articles/ai-tools-productivity-gains/
[8] https://dl.acm.org/doi/10.1145/3633453


## An empirical analysis of GitHub Copilot
ソース[1]によると、GitHub Copilotの効果を評価するための実験が行われました。この研究では、特定のプログラミングタスクを解決する際にGitHub Copilotがどのように役立つかを定量的および定性的に分析しました。具体的な実験結果としては、GitHub Copilotを使用した場合、タスク1の平均完了時間が26分であり、Copilotを使用しない場合は46分でした。しかし、GitHub Copilotを使用した参加者は、使用しない参加者に比べて3%少ないテストをクリアしました。これは、Copilotを使用した参加者が経験が少ないためかもしれません。

また、参加者からのフィードバックによると、GitHub Copilotは特に初心者プログラマーにとって有用であるとされています。初心者はCopilotの提案を通じて新しい問題解決方法を学ぶことができ、新しい言語を学ぶ際の支援や単純なコードスニペットのタイピング時間の短縮に役立つと評価されています。しかし、一部の参加者は、長期的にはプログラマーの学習曲線に悪影響を与える可能性があると懸念しています。

プライバシーに関する懸念も指摘されており、企業環境での使用においては、自社のコードがCopilotによって学習され、外部に共有される可能性が問題となる可能性があるとされています。このようなフィードバックは、GitHub Copilotの導入を検討する際の重要な考慮事項となります。

Citations:
[1] https://uu.diva-portal.org/smash/get/diva2:1775041/FULLTEXT01.pdf
[2] https://www.diva-portal.org/smash/record.jsf?dswid=-9784&pid=diva2%3A1775041
[3] https://juholeinonen.com/assets/pdf/becker2023generative.pdf
[4] https://www.mdpi.com/2071-1050/15/17/12983
[5] https://github.com/TimotheeMickus/codwoe
[6] https://journals.sagepub.com/doi/10.1177/07356331241240460
[7] https://github.com/noumannahmad
[8] https://github.com/nationskollen

## Is GitHub Copilot a Substitute for Human Pair-programming? An Empirical Study

Saki Imaiの研究「Is GitHub Copilot a Substitute for Human Pair-programming? An Empirical Study」は、GitHub Copilotが人間のペアプログラミングの代替としてどの程度有効かを実証的に調査したものです。この研究では、21人の開発者を対象に「マインスイーパー」ゲームのコード実装を行わせ、GitHub Copilotの使用がコードの生産性と品質にどのような影響を与えるかを分析しました[1][5][6][7][8].

研究の結果、GitHub Copilotを使用することでコードの生産性は向上するものの、生成されたコードの品質は低下する傾向があることが観察されました。具体的には、Copilotを使用した場合、コードの行数は増加するものの、コードの品質には問題が生じることが示されています。この研究は、GitHub Copilotが開発者の生産性を向上させる可能性を示しつつも、人間のペアプログラマーに完全に取って代わるものではないと結論付けています。

また、他の研究では、GitHub Copilotが提案するコードにはセキュリティの脆弱性が含まれる可能性があることが指摘されています。例えば、ある研究では、Copilotが提案するコードの40%が脆弱性を含む可能性があるとされています[1]. さらに、Copilotが提案するコードの正確性に関する研究も行われており、LeetCodeの問題を入力としてCopilotの提供する解決策の正確性を評価しています[2].

このように、GitHub Copilotは開発者の生産性を向上させるツールとしての潜在力を持ちながらも、コードの品質やセキュリティに関しては人間のペアプログラマーに比べて劣る可能性があることが、複数の研究によって示されています。

Citations:
[1] https://arxiv.org/pdf/2302.00438.pdf
[2] https://arxiv.org/pdf/2303.08733.pdf
[3] https://uu.diva-portal.org/smash/get/diva2:1775041/FULLTEXT01.pdf
[4] https://dl.acm.org/doi/10.1007/s10664-023-10380-1
[5] https://www.researchgate.net/publication/364417476_Is_GitHub_copilot_a_substitute_for_human_pair-programming_an_empirical_study
[6] https://www.researchgate.net/publication/361291301_Is_GitHub_Copilot_a_Substitute_for_Human_Pair-programming_An_Empirical_Study
[7] https://dl.acm.org/doi/fullHtml/10.1145/3589996
[8] https://www.scribd.com/document/630850244/Saki-Imai-Is-GitHub-Copilot-a-Substitute-for-Human-Pair-programming-An-Empirical-Study