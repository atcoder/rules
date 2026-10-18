AtCoder Rules against Generative AI - Version 20261014
----

# Introduction

These rules apply only during ongoing AtCoder Beginner Contest (hereafter referred to as ABC), AtCoder Regular Contest (hereafter referred to as ARC), regardless of division and AtCoder Grand Contest (hereafter referred to as AGC).

These rules do not apply to AtCoder Heuristic Contest; instead, [the rules here](https://info.atcoder.jp/entry/ahc-llm-rules-en) apply. They do not apply when practicing with past problems. During ABC, ARC and AGC contests, these rules apply to Unrated participants as well. The rules announced here have been established in accordance with the capabilities and usage status of generative AI as of October 2026. We plan to modify the rules according to future changes in AI circumstances.

Please check the following for the background of these rules:

- <a href="https://atcoder.jp/posts/1247">Regarding Rule Changes in ABC Due to the Rise of Generative AI</a>
- <a href="https://atcoder.jp/posts/1350">Regarding Rule Changes in ABC and ARC Due to Technological Advancement of Generative AI</a>
- <a href="https://atcoder.jp/posts/1369">Rule Changes Regarding ARC's Division System</a>
- <a href="https://atcoder.jp/posts/1514">Generative AI Rule Changes Regarding ARC Div. 1</a>
- <a href="https://atcoder.jp/posts/1568">Regarding Rule Changes in ABC, ARC and AGC Due to Technological Advancement of Generative AI</a>
- <a href="https://atcoder.jp/posts/algorithm_rules_20261014_en">Rule Changes in ABC,ARC,AGC（2026, October）</a>

## Rules

- The use of generative AI is generally prohibited during ongoing ABC, ARC and AGC. Exceptions are limited to the following use.
  - Problem statement translation:
    - When using interactive generative AI for translation, only the following is permitted: Write the text below at the beginning, followed by either copied text of the problem statement or a screenshot of the problem statement.
      - <i>The following text or image is a problem statement from an AtCoder contest. During an ongoing AtCoder contest, only the translation of the problem statement is allowed. Any other outputs such as summaries of the problem statement, algorithms, or strategies are strictly prohibited. Please provide only the translation of the problem statement into [language].</i>
      - Replace [language] with the name of the target natural language.
    - For AI tools that only provide translation functionality, you may input the problem statement directly.

### What is Generative AI

- In these rules, "generative AI" is defined as "artificial intelligence that can generate new data such as text or code based on training data."
- Examples primarily include large language models such as GPT, Gemini, Gemma, Llama, Claude, etc.

### Code Created Using Generative AI Before the Contest Begins

Using code that was created using generative AI before the contest begins is permitted. However, the following conditions must be met when using such code.

- To demonstrate that the code was generated before the contest begins, it must be made publicly available on the web before the contest begins.
- When copying and using the code, you must include a URL to the source.

These conditions apply both to code you created using generative AI and to code others created using generative AI. If you copy and use code that someone else created using generative AI without citing the source, it is considered a rule violation even if you did not know that the code was created using generative AI.

### Examples

- The use of generative AI that substitutes your own reasoning in problem understanding, logic creation, or decision-making is prohibited:
  - You must not use generative AI to summarize problem statements.
  - You must not input problem statements, their summaries, excerpts, or sub-problems into generative AI (including code completion tools) to output code or natural language explanations of solutions.
  - You must not use generative AI for diagnosing compilation errors or bugs.
- AI-based code completion (e.g., Copilot) is prohibited.
  - Turn off completion features during the contest.
  - Non–AI-based completion features are permitted.
- Programming-language conversion using generative AI (e.g., converting code written in Python to C++) is prohibited.
- If you are not using generative AI, these rules do not apply. For example, the following tools are permitted:
  - Non-AI-based tools that analyze problem statements and write sample input/output data to files
  - Non-AI-based tools that analyze problem statements and generate input/output handling code
- Using code that was created using generative AI before the contest begins is permitted, provided that the above conditions regarding prior publication and inclusion of a URL to the source are met. If these conditions are met, you do not need to check whether generative AI was used to create the code or explicitly disclose its use.
  - There are no specific requirements regarding where you publish the code, but third parties must be able to view its contents and a timestamp showing that it was publicly available before the contest began.
  - For example, if you have made a library publicly available in a GitHub repository before the contest begins, including a link to that repository in the source code you submit is sufficient. In this case, you do not need to provide a separate link for each piece of copied code.
  - When copying a submission made before the contest begins, including the URL of that submission satisfies the requirement to include a URL to the source.
- The following tools are explicitly permitted:
  - WolframAlpha, Mathematica
  - OEIS (The On-Line Encyclopedia of Integer Sequences)
- Internet Search
  - Search results may display AI-generated overviews (e.g., Google Search "AI Overview"). Please take care not to view such content.
  - Do not use conversational AI search modes (e.g., Google Search "AI Mode").

## Supplement: Policies on Copying Code and Related Matters

In connection with the treatment of code created using generative AI, the policies on copying code, obfuscation, and licensing are set out below. The only change to these policies is the explicit prohibition of obfuscation.

### Copying Code Written by Others Without Generative AI

- As before, copying and using code written by others without generative AI before the contest begins is permitted. In this case, citing the source is not mandatory.
  - This is because requiring source citations in every case, including when copying a single line from a programming language's official documentation or using a library jointly maintained with teammates, would cause considerable inconvenience.
  - However, to help avoid bans due to inconsistencies in coding style, we strongly recommend citing the source whenever possible, especially when copying long sections of code.

### Checking Licenses

- Each user is responsible for checking the license when copying source code.
  - For example, when copying another user's past submission, check whether that user has specified a license for the code, granted permission to use it in some form, or imposed any restrictions.
  - License violations may result in a ban.
  - License violations have already been treated as misconduct, and this policy has now been explicitly stated as part of this rule revision. The criteria for imposing bans remain unchanged.

### Code Obfuscation

- Code obfuscation is prohibited. Obfuscation is considered a rule violation even for code you wrote yourself, not just when copying code written by others.
- Whether code is considered obfuscated is determined by whether it has been deliberately modified for the purpose of making human review difficult.
- Variable names or formatting that are difficult to understand do not, on their own, constitute a rule violation.
- Compressing the template portion of your code to reduce the length of the submitted source code is also permitted.

### Submissions Outside Contest Hours

- The rules on copying code and obfuscation do not apply to submissions outside contest hours. However, the rules on licensing still apply outside contest hours.
