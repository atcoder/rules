AtCoder Rules against Generative AI - Version 20241115
----

# Introduction

These rules apply only during ongoing AtCoder Beginner Contest (hereafter referred to as ABC) and AtCoder Regular Contest (hereafter referred to as ARC).

These rules do not apply to AtCoder Grand Contest, AtCoder Heuristic Contest, etc. They do not apply when practicing with past problems. During ABC and ARC contests, these rules apply to Unrated participants as well. The rules announced here have been established in accordance with the capabilities and usage status of generative AI as of November 2024. We plan to modify the rules according to future changes in AI circumstances.

Please check the following for the background of these rules:

- <a href="https://atcoder.jp/posts/1247">Regarding Rule Changes in ABC Due to the Rise of Generative AI</a>
- <a href="https://atcoder.jp/posts/1350">Regarding Rule Changes in ABC and ARC Due to Technological Advancement of Generative AI</a>

## Rules

- The use of generative AI is generally prohibited during ongoing ABC and ARC. Exceptions are limited to the following uses.
  - Problem statement translation:
    - When using interactive generative AI for translation, only the following is permitted: Write the text below at the beginning, followed by either copied text of the problem statement or a screenshot of the problem statement.
      - <i>The following text or image is a problem statement from an AtCoder contest. During an ongoing AtCoder contest, only the translation of the problem statement is allowed. Any other outputs such as summaries of the problem statement, algorithms, or strategies are strictly prohibited. Please provide only the translation of the problem statement into [language].</i>
      - Replace [language] with the name of the target natural language.
    - For AI tools that only provide translation functionality, you may input the problem statement directly.
  - Code completion tools (e.g., Copilot):
    - The use of AI-based code completion tools is permitted only for increasing coding speed.
    - They must not be used to solve problems or sub-problems, or to obtain ideas.
  - Programming language conversion (e.g., converting Python code to C++):
    - The original code must be included as comments at the beginning of the submitted code.
    - Only conversions that do not alter the algorithm are permitted. In particular, conversions that change the order of computational complexity are not allowed.
    - Only interactive generative AI may be used. Write the following text at the beginning, followed by the program you want to translate. Please verify that the generated code complies with the above rules before submission:
      - <i>The following code is what I wrote to solve a problem in an AtCoder contest. When using generative AI to translate programming languages during an ongoing AtCoder contest, there are the following restrictions: "It is absolutely necessary to include the original code at the beginning of the submission as a comment or similar." "Only translations that do not alter the algorithm are permitted. In particular, any changes that would affect the time complexity are strictly prohibited." For any parts that cannot be directly translated, please mark them as "FAILED" and leave them unconverted. Following these strict AtCoder rules, please translate the following code from [input language] to [output language].</i>
      - Replace [input language] with the source programming language name and [output language] with the target programming language name.

### What is Generative AI

- In these rules, "generative AI" is defined as "artificial intelligence that can generate new data such as text or code based on training data."
- Examples primarily include large language models such as GPT, Gemini, Gemma, Llama, Claude, etc.

### Examples

- The use of generative AI that substitutes your own reasoning in problem understanding, logic creation, or decision-making is prohibited:
  - You must not use generative AI to summarize problem statements.
  - You must not input problem statements, their summaries, excerpts, or sub-problems into generative AI (including code completion tools) to output code or natural language explanations of solutions.
  - You must not use generative AI for diagnosing compilation errors or bugs.
- When not using generative AI, the following tools are permitted:
  - Tools that analyze problem statements and generate input/output files
  - Tools that analyze problem statements and generate input/output handling code