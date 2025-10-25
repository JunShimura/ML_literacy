# 機械学習って何？
機械学習はMachine Learningという単語から訳されたものですが、果たしてこれは、どういう意味でしょうか？何を意味するのかが分かれば、最終的な到達点が見えてきます。
## 言葉の意味を汲んでみる
これから触るのに何を意味するのか、知らないのは目的が分かりにくくなります。ここは語源を辿ってみましょう。

> A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E

出典：[機械学習-Wikipedia](https://ja.wikipedia.org/wiki/%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92#:~:text=%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92%E3%81%A8%E3%81%84%E3%81%86%E5%90%8D%E5%89%8D%E3%81%AF,%E3%82%B5%E3%83%9F%E3%83%A5%E3%82%A8%E3%83%AB%E3%81%AB%E3%82%88%E3%81%A3%E3%81%A6%E9%80%A0%E8%AA%9E%E3%81%95%E3%82%8C%E3%81%9F%E3%80%82)

Googleで翻訳すると、以下になります。
>コンピューター プログラムは、P によって測定される T のタスクでのパフォーマンスが経験 E によって向上する場合、あるクラスのタスク T およびパフォーマンス測定 P に関して経験 E から学習するといわれます。

ここで気付くわけですが、

**どこにもMachine Learningって書いてない？**

というところです。「何を学習してどうなる」という定義になっています。が、Machineが無い。これを日本語に考えるならば、こういう提案をします。

**機械が機械的に学習するさま**

これから取り組む機械学習において、経験から学んで学習する主体は、**機械=コンピュータ**です。その機械は、機械ですから当然ですが、機械的に学習するわけですね。機械的に学習するのに用いるのが、ソフトウエアプログラムです。ここでは言語化したPythonを用います。
