---
title: Writing Content - Instruction 
layout: default
parent: Examples
grand_parent: Prompt Design Strategies
nav_order: 2
---
<img src="../Images/7.png" alt="Header Prompt Design Strategies" width="100%">

## **Writing Content - Instruction** ##
***

Let us start with a simple instruction, for which we wrote a prompt in the previous paragraph. Next, we will see what three publicly available tools will generate for us.

### Example ###

```
<GOAL_AND_PERSONA> 
[PERSONA/AUTHOR] You are a technical writer who is writing instructions.
[GOAL]Your main goal is to provide clear instructions to people on how to open a box using direct commands. 
[PERSONA/AUDIENCE] 
Your audience consists of Americans aged 10 to 100 years.
</GOAL_AND_PERSONA> 
<INSTRUCTIONS> 
To complete the task:
1.	Write Introduction for Instruction of Opening the Box.
2.	Provide step-by-step instructions on How to Open a Box.
3.	Show How to Do This.
4.	Provide Information About Utilizing the Box. 
 </INSTRUCTIONS> 
CONSTRAINTS> 
Don’t use more than two sentences in the introduction. 
</CONSTRAINTS> 
<CONTEXT> 
This is small, light, cardboard box. 
</CONTEXT> 
<TONE>
Use professional and understanding tone. 
</TONE>
<COMMAND>
Write clear instructions to people on how to open a box using direct commands.
</COMMAND>
<RESPONSE_FORMAT> 
Format your response in Markdown.
</RESPONSE_FORMAT> 
<EXAMPLES> 
I found six steps instruction of opening the box. 
<EXAMPLES> 
<SPECIFICATIONS>
Write instruction in the direct style using max. one hundred words.
</SPECIFICATIONS>
<RECAP> 
Always format your response in Markdown format.
</RECAP>
```

