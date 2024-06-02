---
title: Components of a prompt 
layout: default
parent: Prompt Design Strategies
nav_order: 5
---
<img src="../Images/7.png" alt="Header Prompt Design Strategies" width="100%">

## **Components of a prompt** ##
***

We already know what prompt design is and what benefits it brings. We have learned the best practices and strategies. However, to create effective prompts, we need to understand what they consist of and how to construct them precisely.

A prompt encompasses the following elements:

-	**Instruction**: A clear task or directive intended for the model to execute.
-	**Context**: External information or additional context provided to guide the model towards more accurate responses.
-	**Input Data**: The input or question for which a response is sought.
-	**Output Indicator**: Specification of the desired type or format of the output.

A prompt can contain more elements. Some of them may be crucial for achieving the desired response.
Essential and optional component of a <a href="https://cloud.google.com/vertex-ai/generative-ai/docs/learn/prompts/prompt-design-strategies" target="_blank">prompt</a>:

| Component| Description | Example |
| -------- | ----------- | ------- |
| Goal     | What you aim for the model to accomplish | Your main goal is to provide clear instructions to people on how to open a box using direct commands. |
| Instruction | Step by step on how to perform the task at hand. | Write Introduction for Instruction of Opening the Box. Provide 5-Step Instructions on How to Open a Box. Show How to Do This. Provide Information About Utilizing the Box. |
| System instructions | In many model APIs, system instructions are defined within a dedicated parameter. The inclusion of these instructions ensures optimal responses.    | You are a webmaster specializing in front-end interface development, please provide the HTML and CSS required to render the code for opening the box. Do not include an explanation for this code.   |
| Persona/Author | Who/what the model is acting as. | You are a technical writer who is writing Instruction of Opening the Box.|
| Persona/ Audience | Fictional character or user archetype created to represent a specific target audience or demographic. Personas provide context for the language model by specifying the characteristics, preferences, and needs of the intended user | Your audience consists of Americans aged 10 to 100 years. |
| Constraints | They refer to the limitations placed on the model regarding the generation of a response, outlining both permissible and impermissible actions. | Do not use more than two sentences in the introduction. |
| Tone | The tone of the response. | Use professional and tone.|
| Context | Any information necessary for the model to reference to complete the task. | This is small, light, cardboard box. |
| Command | You can instruct GenAI what to do: summarize, write, classify, translate, etc. | Write clear instructions to people on how to open a box using direct commands. |
| Examples | Examples of how the response should appear for a given prompt. | I found six steps instruction. |
| Reasoning steps | Instruct the model to explain its reasoning. | Explain your reasoning step-by-step why you put these steps in instruction. |
| Response format | The format in which you desire the response to be presented, like bulleted list, html, markdown, JSON, table, etc. | Format your response in Markdown. |
| Recap | A brief recap of the main points of the prompt, particularly emphasizing the constraints and response format, should be provided at the end of the prompt. Providing a recap at the end ensures clarity and reinforces understanding by summarizing the constraints and response format outlined earlier. | Always format your response in Markdown format. |
| Specifications | Additional informational that should be include in response, like number of words/characters, style, etc. | Write instruction in the direct style using max. two hundred words. |

The skeleton of such a prompt could look like this:

```
<GOAL_AND_PERSONA> 
You are a [insert a persona/author]. 
Your task is to... 
Your audience is… [insert a persona/audience]
</GOAL_AND_PERSONA> 
<INSTRUCTIONS> 
To complete the task, you need to follow these steps: 
1. ...
2. ...
 </INSTRUCTIONS> 
CONSTRAINTS> 
Dos and don'ts for the following aspects 
1. Dos 
2. Don'ts 
</CONSTRAINTS> 
<CONTEXT> 
The provided context 
</CONTEXT> 
<TONE>
Use professional and understanding tone. 
</TONE>
<COMMAND>
In conclusion summarize… [insert command]
</COMMAND>
<RESPONSE_FORMAT> 
The output format must be 1. 2. ... 
</RESPONSE_FORMAT> 
<EXAMPLES> 
Here we provide some examples: 
1.	Example #1
2.	Example #2
<EXAMPLES> 
<RECAP> 
Re-emphasize the key aspects of the prompt, especially the constraints, output format, etc.
</RECAP>
```

