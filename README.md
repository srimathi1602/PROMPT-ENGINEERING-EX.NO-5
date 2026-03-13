

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: CHATGPT 

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.

# OUTPUT:
### 1. BASIC PROMPT:
**PROMPT:** Who is the prime minister of india?<BR>
**Output:**<BR>
The Prime Minister of India is Narendra Modi.<BR>

### 2. ZERO SHOT PROMPT:
**PROMPT:** Give me the prime minister of india?<BR>
**Output:**<BR>
The Prime Minister of India is Narendra Modi. He has been serving in this role since 26 May 2014 and is currently in his third consecutive term after the 2024 general elections.

### 3. FEW SHOT PROMPT: 
**PROMPT:** 
1. United States - Donald Trump<BR>
2. France - Emmanuel Macron<BR>
Now generate: India<BR>
**OUTPUT:**<BR>
3. **India – Narendra Modi**

### 4. CHAIN OF THOUGHT PROMPTS:
**PROMPT:** Who is the prime minister of india? From what time he is seving as the prime minister of india ? which party does he belong to ? Is he a good prime minister<BR>
**OUTPUT:**<BR>
Here are the answers to your questions about the **Prime Minister of India**:

### 🇮🇳 **Who is the Prime Minister of India?**

The **Prime Minister of India** is **Narendra Modi**. ([Encyclopedia Britannica][1])

### 📅 **Since when has he been serving as Prime Minister?**

Narendra Modi has been serving as the Prime Minister of India **since 26 May 2014**. He was first sworn in after the **2014 general elections** and then re-elected in **2019** and again in **2024** for a third consecutive term. ([Encyclopedia Britannica][1])

### 🏛️ **Which party does he belong to?**

He is a member of the **Bharatiya Janata Party (BJP)**, which is a major national political party in India. ([Wikipedia][2])

### 🤔 **Is he a good Prime Minister?**

Whether Narendra Modi is a *“good”* Prime Minister depends on perspective and what you consider important:

**Supporters say:**

* He has focused on **economic development**, infrastructure projects, and national security.
* Many people credit his leadership with raising India’s global profile and initiating large welfare programs. ([Prime Minister of India][3])

**Critics say:**

* Some argue his policies have been **divisive** or have weakened certain democratic institutions.
* Different groups have different views on his governance style and priorities, so opinions vary widely.
# ANALYSIS OF PROMPTS:
| Prompt No. | Prompt                                                                                                         | Accuracy                                         | Clarity                                   | Depth                                    | Quality of Response                 | Suitability for Academic Use                | Overall Effectiveness                          |
| ---------- | -------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ | ----------------------------------------- | ---------------------------------------- | ----------------------------------- | ------------------------------------------- | ---------------------------------------------- |
| 1          | *“who is the prime minister of india”*                                                                         | Produces a factually correct and reliable answer | Very clear and unambiguous                | Very limited; asks for only one fact     | Basic factual information           | Suitable for short answers and quizzes      | Effective for quick information retrieval      |
| 2          | *“give me the prime minister of india”*                                                                        | Correct information is provided                  | Slightly vague but understandable         | Very shallow; no additional context      | Minimal but accurate                | Suitable for basic learning                 | Works well for simple fact lookup              |
| 3          | *“1. United States - Donald Trump 2. France - Emmanuel Macron Now generate: India”*                            | Correctly identifies India’s leader              | Context is clear through pattern matching | No depth; relies on list completion      | Concise and accurate                | Useful for lists and tables                 | Effective for structured data completion       |
| 4          | *“who is the prime minister of india? From what time he is serving… which party… Is he a good prime minister”* | Factually accurate with balanced opinions        | Mostly clear, though informal             | High depth due to multiple sub-questions | Detailed, informative, and balanced | Suitable for assignments and discussions    | Very effective for comprehensive understanding |

## RESULT: 
The prompt for the above said problem executed successfully
