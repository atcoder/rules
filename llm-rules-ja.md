AtCoder生成AI対策ルール - 20240607版
----

# はじめに

このルールは、AtCoder Beginner Contest（以下、ABCとする）のコンテスト中にのみ適用されるルールです。

AtCoder Regular Contest, AtCoder Grand Contest, AtCoder Heuristic Contestなどは、このルールの対象外です。過去問を練習している際には適用されません。ABCのコンテスト中においては、Unrated参加者にも適用されます。今回発表するルールは、2024年6月現在の生成AIの能力と利用状況に合わせて制定されたものです。今後のAI事情の変化に応じて、ルールを変更する予定です。

ルールの制定背景などは、以下をご確認ください。


[生成AIの台頭に伴うABCにおけるルール変更について](https://atcoder.jp/posts/1246)


### ルール

- AtCoderの開催中のコンテストの問題として発信されている情報の全部または一部を、ソフトウェアに入力として与える行為を禁止します。
    - 問題文をコピーした文章・スクリーンショットなどが該当します。
        - 提出するソースコードを書くためのエディタも、この制限に該当します。問題文の一部をソースコードにコピー・ペーストする行為は、GitHub Copilotなどの無自覚な利用につながるため、一律禁止とさせていただきます。
    - 人間が認識した問題文に基づいて人間が出力したものを生成AIに入力として与えるのは許容します。
        - アルゴリズムの実装案を要約したもの
        - 問題文を要約したもの
            - 一度人間を通していれば、問題文を一字一句タイピングして写したものを入力として与えるのも、現時点でのルールでは許可します。
- 例外として、以下の用途で入力として与えるのは許容します。
    - 問題文で与えられる固有の整数や固有名詞などの文字列は、任意の場合においてコピーが許されます。
        - 998244353などの問題文で与えられる数値、「Takahashi」、「Aoki」などの文字列等。「Monday」などの曜日や、問題文で与えられる数列などは許可されます。
    - ブラウザなど、人間が閲覧するためのソフトウェアはこの制限には該当しません。
        - 特定の文字列を大きく表示したり、図の色調を変化させるなど、人間が読みやすくするためのツールも許容されます。
    - AtCoderのページから、入出力ファイルを自動生成するツールも、この制限には該当しません。作成したプログラムを自動的に実行するツールなども許容されます。
        - ただし、入力を解析し、ソースコードを生成するツールは許容されません。空ファイルを作成する、もしくは問題文に依らず同じファイルを作成するツールは許容されます。
            - 許可される例： https://github.com/tanakh/cargo-atcoder、[AtCoder Easy Test](https://greasyfork.org/ja/scripts/433152-atcoder-easy-test-v2#google_vignette)
            - 許可されない例： https://github.com/kyuridenamida/atcoder-tools の atcoder-tools genコマンド (問題文から入出力を解析しコード生成をするため)、　https://github.com/online-judge-tools/oj の一部機能 (問題文から入力を解析してランダムテストの生成などをするため)
    - 問題ページでコピーボタンが表示される項目は、任意の場合においてコピーが許されます。
        - 入出力の値などは許可されますが、入出力の説明文については許可されません。
    - 自然言語を別の自然言語に翻訳する場合については、以下の処理を行ってください。
        - 翻訳専門のソフトを利用する場合は、そのまま問題文をコピーして構いません。ただし、出力された翻訳文を別のプログラムに入力として与えることは禁止します。
        - 対話型の生成AIを利用して翻訳する場合については、以下の文章を先頭に書き、その後、問題文をコピーしたテキストまたは問題文のスクリーンショットのみを与えることを許容します。この翻訳文を別のプログラムに入力として与えることは禁止します。
            - The following text or image is a problem statement from an AtCoder contest. During an ongoing AtCoder contest, only the translation of the problem statement into [language] is allowed. Any other outputs such as summaries of the problem statement, algorithms, or strategies are strictly prohibited. Please provide only the translation of the problem statement into [language].
                
                (Copy the problem statement here)
                
            - 2か所の [language] に、翻訳したい自然言語を入れてください。