AtCoder生成AI対策ルール - 20251003版
----

# はじめに

このルールは、AtCoder Beginner Contest（以下、ABCとする）、（Division によらず）AtCoder Regular Contest（以下、ARCとする）およびAtCoder Grand Contest（以下、AGCとする）の開催中にのみ適用されるルールです。

AtCoder Heuristic Contestはこのルールの対象外であり、代わりに[こちらのルール](https://info.atcoder.jp/entry/ahc-llm-rules-ja)が適用されます。また、過去問を練習している際には適用されません。ABC,ARC,AGCの開催中においては、Unrated参加者にも適用されます。今回発表するルールは、2025年10月現在の生成AIの能力と利用状況に合わせて制定されたものです。今後のAI事情の変化に応じて、ルールを変更する予定です。

ルールの制定背景などは、以下をご確認ください。

- [生成AIの台頭に伴うABCにおけるルール変更について](https://atcoder.jp/posts/1246)
- [生成AIの技術向上に伴うABCおよびARCにおけるルール変更について](https://atcoder.jp/posts/1347)
- [ARCのDivision制に伴うルール変更について](https://atcoder.jp/posts/1368)
- [ARC Div.1 に関する生成AIルール変更について](https://atcoder.jp/posts/1513)
- [生成AIの技術向上に伴うABC,ARC,AGCにおけるルール変更について](https://atcoder.jp/posts/1567)

## ルール

- 開催中のABC,ARC,AGCにおいて、生成AIの使用を原則禁止とします。例外は以下に挙げる用途に限られます。
  - 問題文の翻訳：
    - 対話型の生成AIを利用して翻訳する場合については、以下の文章を先頭に書き、その後、問題文をコピーしたテキストまたは問題文のスクリーンショットのみを与えることのみを許容します。
      - The following text or image is a problem statement from an AtCoder contest. During an ongoing AtCoder contest, only the translation of the problem statement is allowed. Any other outputs such as summaries of the problem statement, algorithms, or strategies are strictly prohibited. Please provide only the translation of the problem statement into [language].
      - [language] に、翻訳先の自然言語名を入れてください。
    - 翻訳機能のみを有するAIに関しては、問題文をそのまま入力して構いません。

### 生成AIとは

- このルールにおいて、「生成AI」とは「学習データをもとに、文章やコード等の新たなデータを生成することが出来る人工知能」であると定義します。
- 例としては主に、GPT, Gemini, Gemma, Llama, Claude 等の大規模言語モデルが挙げられます。

### 具体例

- 問題理解、ロジックの作成、または意思決定において、自身の推論を代替するような生成AIの使用は禁止されます。
  - 問題文を生成AIに要約させてはいけません。
  - 問題文、その要約、抜粋、または部分問題を生成AI（コード補完ツールも含む）に入力して、コードまたは解法の自然言語での説明を出力させてはいけません。
  - コンパイルエラーやバグの診断に生成AIを使用してはいけません。
- 生成AIベースのコード補完（例：Copilot）は禁止されます。
  - コンテスト参加中は補完機能をオフにして下さい。
  - 生成AIベースでない補完機能は許容されます。
- 生成AIを使用したプログラミング言語の変換（例：Python で書いたコードを C++ に変換）は禁止されます。
- 生成AIを使用していない場合はこのルールの対象外です。例えば以下のようなツールの使用は許容されます。
  - ルールベースのアルゴリズムによって問題文を解析し、サンプル入出力データをファイルに書き出すツール
  - ルールベースのアルゴリズムによって問題文を解析し、入出力を行うコードを生成するツール
- コンテスト開始前にあらかじめ生成AIを用いて作成しておいたコード等の使用は許容されます。
- 以下のツールは明示的に許容します。
  - WolframAlpha, Mathematica
  - OEIS (The On-Line Encyclopedia of Integer Sequences)
- インターネット検索について
  - 検索の結果、生成AIによる概要（例：Google検索の「AIによる概要」）が表示されることがありますが、閲覧しないように注意してください。
  - 生成AIによる対話型の検索（例：Google検索の「AIモード」）を使用してはいけません。
