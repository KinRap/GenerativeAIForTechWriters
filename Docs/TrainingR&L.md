---
title:  Training
layout: default
parent: Risks & Limitations
nav_order: 7
---

## **Training** ##
***

We know that for GenAI to deliver high-quality information, it must be properly trained. This requires not only preparing the training data appropriately but also updating and working with it to ensure that the generated content is not discriminatory or offensive. Similarly, while AI training presents enormous opportunities to improve the quality of the information received, it also carries certain limitations and risks

## Risks: ##
AI is trained using **Large Language Model (LLM)**. Their improper use can lead to manipulation and falsification of training data to yield inappropriate results. These include:
1.	**Prompt Injection**: Prompt is not just a user instruction when using GenAI. There is also a training method for **Language Models (LMs)** that relies on prompts. By taking a block of text or context, a **Large Language Model (LLM)** tries to compute the most probable next character, word, or phrase. This type of training allows data manipulation. Prompt Injection involves injecting biased, malicious, or misleading prompts into large language models (LLMs) to manipulate their results or behaviour. Prompt injection attacks aim to elicit unintended responses from LLM-based tools. This can lead to the dissemination of misinformation, reinforcement of biases, or even the generation of harmful content.
2.	**Training Data Poisoning**: This is a type of cyberattack in which manipulation of training data or tuning procedures can influence the responses of GenAI or LLM. This can be done by: 
    - intentionally injecting false or misleading information into the training dataset, 
    - modifying the existing dataset or deleting 
    - portion of the dataset. 

    Data Poisoning attacks come in several types:
    - **Targeted Attacks**:
       - **Label Poisoning**: Inserting mislabelled or harmful data.
       - **Training Data Poisoning**: Contaminating a substantial part of the training dataset.
    - **Non-Targeted Attacks**:
       - **Model Inversion Attacks**: This model exploits the model's outputs to reveal sensitive information about the training data.
       - **Stealth Attacks**: Introducing subtle changes in training data to insert hard-to-detect vulnerabilities.

    Through manipulation of the training dataset, biases, erroneous results, biases, vulnerabilities (e.g., backdoors) can be introduced, always affecting the decision-making or predictive capabilities of the model.
3. **Breach of PII**: This refers to situations where persons other than authorized users have access or potential access to personally identifiable information. GenAI may inadvertently disclose sensitive PII during training, tuning, or inference processes. This breach could result from inadequate data security measures, unauthorized access, or vulnerabilities in the model architecture, potentially leading to privacy violations.

### Downsides ### 
Outdated training data can result in erroneous responses. This is extremely important in the work of a technical writer. In the world of innovative technologies, AI often lags progress. The results can be more limited, less dependable, and less reflective of reality. Flawed training data can provide more limited, less dependable, and less reflective of reality responses. Especially since GenAI is limited in its ability to fact-check and respond. This leads to factual errors and even invented quotations. Such errors can cost even human lives.

Insufficient representation of training data can also provide biased results, thus perpetuating discrimination and inequality. The risk of bias often remains in the limitations of the training data itself. This means that existing biases in the training data can make discriminatory results statistically more likely, and the GenAI tool is more likely to generate them.

As you can see, proper preparation and updating of training data are extremely important. As well as protecting them from attacks. Verification and training of GenAI is an ongoing process that cannot be abandoned.


