AtCoder Rules against Generative AI ver20240607
----

# Introduction

These rules apply exclusively to AtCoder Beginner Contest (hereinafter referred to as ABC) during the contest period.

AtCoder Regular Contest, AtCoder Grand Contest, AtCoder Heuristic Contest, etc. are exempt from these rules. They are also not applicable when practicing past problems. During ABC, these rules apply to Unrated participants as well. These rules are established based on the capabilities and usage of generative AI as of June 2024. We plan to change the rules in response to future changes in AI circumstances.

For the background of the rule establishment, please check the following:

[Announcement on atcoder.jp](https://atcoder.jp/posts/1247)

### Rules

- It is prohibited to directly input all or part of the information issued as problems in ongoing AtCoder contests into software.
    - This includes copies of the problem statement texts and screenshots.
        - Editors used to write the source code for submission are also subject to this restriction. Copying and pasting parts of the problem statement into the source code is also prohibited as it may lead to unintentional use of tools like GitHub Copilot.
    - It is permissible to input into generative AI what a human has output after visually reading the problem statement, such as:
        - Summarized implementation plans of algorithms
        - Summarized problem statements
            - It is allowed under the current rules to input text that has been typed out word for word from the problem statement, once it is processed by a human.
- Exceptionally, the following uses are allowed:
    - Copying specific integers or strings such as proper nouns given in the problem statement is allowed in any case.
        - For example, numbers like 998244353 given in the problem statement and strings like "Takahashi" and "Aoki". Days of the week like "Monday" and sequences given in the problem statement can also be copied.
    - Software for human viewing, such as browsers, is not subject to this restriction.
        - Tools that make certain texts larger or change the color scheme of diagrams to make them easier to read are also allowed.
    - Tools that automatically generate input/output files from AtCoder pages are not subject to this restriction. Tools that automatically execute written programs are also allowed.
        - However, tools that analyze input and generate source code are not allowed. Tools that create empty files or create the same file regardless of the problem statement are allowed.
            - Allowed examples: [https://github.com/tanakh/cargo-atcoder:title] , [AtCoder Easy Test](https://greasyfork.org/ja/scripts/433152-atcoder-easy-test-v2#google_vignette)
            - Not allowed examples: "atcoder-tools gen" command of [https://github.com/kyuridenamida/atcoder-tools:title] (analyzes the problem statement to generate code), some features of [https://github.com/online-judge-tools/oj:title] (analyzes the problem statement to generate random tests)
    - Items with a copy button displayed on the problem page can be copied in any case.
        - Sample input/output values can be copied, but their annotations cannot.
    - When translating natural language to another natural language, follow the procedures below:
        - When using specialized translation software, you may copy the problem statement as is. However, it is prohibited to input the translated text into another program.
        - When using interactive generative AI for translation, write the following text at the beginning, and then provide only the copied text or screenshot of the problem statement. It is prohibited to input the translated text into another program.
            - The following text or image is a problem statement from an AtCoder contest. During an ongoing AtCoder contest, only the translation of the problem statement into [language] is allowed. Any other outputs such as summaries of the problem statement, algorithms, or strategies are strictly prohibited. Please provide only the translation of the problem statement into [language].
                
                (Copy the problem statement here)
                
            - Replace [language] in two places with the natural language you want to translate into.