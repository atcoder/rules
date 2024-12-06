AtCoder生成AI対策ルール - 20241206版
----

# はじめに

このルールは、AtCoder Beginner Contest（以下、ABCとする）および AtCoder Regular Contest (Div. 2) （以下、ARC Div. 2とする）のコンテスト中にのみ適用されるルールです。

AtCoder Grand Contest, AtCoder Regular Contest (Div. 1), AtCoder Heuristic Contestなどは、このルールの対象外です。過去問を練習している際には適用されません。ABCおよびARC Div. 2のコンテスト中においては、Unrated参加者にも適用されます。今回発表するルールは、2024年12月現在の生成AIの能力と利用状況に合わせて制定されたものです。今後のAI事情の変化に応じて、ルールを変更する予定です。

ルールの制定背景などは、以下をご確認ください。

- [生成AIの台頭に伴うABCにおけるルール変更について](https://atcoder.jp/posts/1246)
- [生成AIの技術向上に伴うABCおよびARCにおけるルール変更について](https://atcoder.jp/posts/1347)
- [ARCのDivision制に伴うルール変更について](https://atcoder.jp/posts/1368)

## ルール

- 開催中のABCおよびARC Div. 2において、生成AIの使用を原則禁止とします。例外は以下に挙げる用途に限られます。
  - 問題文の翻訳：
    - 対話型の生成AIを利用して翻訳する場合については、以下の文章を先頭に書き、その後、問題文をコピーしたテキストまたは問題文のスクリーンショットのみを与えることのみを許容します。
      - The following text or image is a problem statement from an AtCoder contest. During an ongoing AtCoder contest, only the translation of the problem statement is allowed. Any other outputs such as summaries of the problem statement, algorithms, or strategies are strictly prohibited. Please provide only the translation of the problem statement into [language].
      - [language] に、翻訳先の自然言語名を入れてください。
    - 翻訳機能のみを有するAIに関しては、問題文をそのまま入力して構いません。
  - コード補完ツール（例：Copilot）：
    - コードを書くスピードを上げる用途に限り、生成AIベースのコード補完ツールの使用を許容します。
    - 問題や部分問題を解かせたり、アイデアを得たりする用途に使用してはいけません。
  - プログラミング言語の変換（例：Python で書いたコードを C++ に変換）：
    - 提出コードの冒頭に変換元のコードをコメント等で記載する必要があります。
    - アルゴリズムが変化しないような変換のみが許容されます。特に計算量のオーダーが変化するような変換は認められません。
    - 生成AIとしては対話型の生成AIのみが利用できます。以下の文章を先頭に書き、その後、翻訳したいプログラムを与えることのみを許容します。生成されたコードが上記のルールを満たしているかも確認した上で提出を行って下さい。
      - The following code is what I wrote to solve a problem in an AtCoder contest. When using generative AI to translate programming languages during an ongoing AtCoder contest, there are the following restrictions: "It is absolutely necessary to include the original code at the beginning of the submission as a comment or similar." "Only translations that do not alter the algorithm are permitted. In particular, any changes that would affect the time complexity are strictly prohibited." For any parts that cannot be directly translated, please mark them as "FAILED" and leave them unconverted. Following these strict AtCoder rules, please translate the following code from [input language] to [output language].
      - [input language] に変換元のプログラミング言語名、[output language] に変換先のプログラミング言語名を入れてください。

### 生成AIとは

- このルールにおいて、「生成AI」とは「学習データをもとに、文章やコード等の新たなデータを生成することが出来る人工知能」であると定義します。
- 例としては主に、GPT, Gemini, Gemma, Llama, Claude 等の大規模言語モデルが挙げられます。

### 具体例

- 問題理解、ロジックの作成、または意思決定において、自身の推論を代替するような生成AIの使用は禁止されます。
  - 問題文を生成AIに要約させてはいけません。
  - 問題文、その要約、抜粋、または部分問題を生成AI（コード補完ツールも含む）に入力して、コードまたは解法の自然言語での説明を出力させてはいけません。
  - コンパイルエラーやバグの診断に生成AIを使用してはいけません。
- 生成AIを使用していない場合はこのルールの対象外です。例えば以下のようなツールの使用は許容されます。
  - 問題文を解析し、入出力データのファイルを生成するツール
  - 問題文を解析し、入出力を行うコードを生成するツール
- コンテスト開始前にあらかじめ生成AIを用いて作成しておいたコード等の使用は許容されます。
- 以下のツールは明示的に許容します。
  - WolframAlpha, Mathematica
  - OEIS (The On-Line Encyclopedia of Integer Sequences)
  - Google検索
    - Google検索を行った際、Search LabsのAIによる概要が表示されることがありますが、閲覧して構いません。