---
title: "Understanding AI for Copywriters"
description: "This is the introductory section and overview of the content that will be covered by part 1. This will very briefly introduce terms that the site will cover."
tags:
  - chatbot
  - ai-tools
  - byui-license
author:
  name: Ander Cullen
  email: cul24002@byui.edu
section: part1
published: false
---
# Copywriting In the Age of AI 
***Key Takeaway:** For copywriters to use AI responsibly, they must know its possibilities, risks, and limitations to use it effectively, efficiently, and ethically.*

Generative Artificial Intelligence tools have become prevalent across many creative, tech, and knowledge sectors, promising to automate repetitive tasks and increase productivity.<a id="ref-1"></a><sup>[1](#cite-1)</sup> 

BYU-Idaho is preparing students for the future workforce by employing GenAI tools in faculty and student workflows<a id="ref-2"></a><sup>[2](#cite-2)</sup>, but it isn't easy because navigating the future of Human-AI collaboration requires both understanding and applying Gen AI tools to serve humanity, not to harm or hinder it.<a id="ref-3"></a><sup>[3](#cite-3)</sup>

The capacity of multimodal AI tools makes it easy for people to replace their own effort with machine-generated content, but current research demonstrates that this approach has an overall net negative impact on quality and performance across many areas.<a id="ref-4"></a><sup>[4](#cite-4),</sup><a id="ref-5"></a><sup>[5](#cite-5),</sup><a id="ref-6"></a><sup>[6](#cite-6)</sup> Yet, there is also evidence that Human-AI collaboration can complement our capabilities, giving to us rather than taking away from us.<a id="ref-7"></a><sup>[7](#cite-7)</sup> 

The conflicting data suggests there is an appropriate middle ground for GenAI, but the current AI models require an apprehensive—*both comprehensive and skeptical*—approach. The apprehensive approach assumes that GenAI tools are going to stay relevant in the future, that humanity will address and resolve the issues with GenAI, but in the meantime individuals and organizations must define specific policies and guardrails to protect against overreliance of AI.

The purpose of *The AI Copywriting Manual* is to provide Copywriters for BYU-Idaho at University Communications the knowledge and strategies they need to responsibly use GenAI tools effectively, efficiently, and ethically. This section provides an introduction to GenAI, exploring its development and training processes, its proposed capabilities weighed against its limitations and risks, and its appropriate potential use cases for Copywriters.

> **Consider This**
>
> **What is Artificial Intelligence?**
>
> - How do we get from AI to Chatbots?
> - What is the process of training a Chatbot?
> - How do Chatbots work?
> 
> **What are the possibilities, limitations, and risks of AI Chatbots?**
>
> - *Possibilities:* Human-AI Collaboration, Accelerated Productivity, Learning, Creativity, Reasoning, Analysis, and Research.
> - *Limitations:* Tokens, Context Window, Limited Reasoning, No True Understanding, and Limited Data Access.
> - *Risks:* Hallucinations, Sycophancy, Bias, Cognitive Overreliance, Data Privacy, Copyright, Academic Integrity, and Plagiarism.
>
> **Where does AI get data and how can I protect mine?**
>
> - How does AI collect data?
> - What data can you share safely?
> - CES Privacy Principles

## What Is Artificial Intelligence? 
Artificial Intelligence (AI) is a popular term that refers to diverse technologies with different functions and purposes. It is generally described as technology that is meant to simulate human-like intelligence. Generative Artificial Intelligence (GenAI) is a modern adaptation of AI technologies meant to generate human-like creations such as text, code, images, math, videos, or any other form of content.<a id="ref-8"></a><sup>[8](#cite-8)</sup> 

GenAI's ability to generate text is the primary concern for roles like that of Copywriters. While much of the information about AI generated text might apply to other forms of content, Copywriters will focus on primarily on the tasks related to Copywriting that can be replicated by AI.<a id="ref-9"></a><sup>[9](#cite-9)</sup> These tasks can be summarized as:

- **Research**
- **Planning and outlining**
- **Brainstorming and drafting**
- **Editing grammar, tone, and style**
- **Logical Analysis**
- **Review and quality control**
- **Citation and reference generation**
- **Content Creation**

GenAI tools now have a capacity to generate large volumes of text almost instantaneously. Copywriters might feel intimidated by these tools and feel that they will have to use them to keep up and stay relevant. However, GenAI isn't the extent of AI, it is a product of a multi-step process that creates high-quantity, not high-quality outputs. Understanding the mechanics of this process undermines the apparent capacity of GenAI, highlighting its limitations, and the risks of overreliance.

GenAI wasn't created by a team of programmers meticulously coding every single prompt and output one-by-one. AI engineers built GenAI through a three-phase process: (1) collecting large amounts of text and training machines to read it, (2) constructing a language processing model and training it to respond, and (3) preparing the model to become an adaptable and helpful assistant.

***Phase 1***

AI models are trained in a process called **Machine Learning**, a branch of AI that performs data analysis tasks, using mathematics and statistics to understand text. By giving using a large amount of data, Machine Learning can start to guess relationships and recognize patterns between things without explicit programming. Machine learning can understand textual data by converting text into individual units called **Tokens**. Each token is assigned a numerical id which the AI can use to start finding patterns.

In essence, Machine Learning treats language as statistics, which essential for building for advanced models later. The idea is that when you type the input the sentence, "I like to pet" Machine Learning tells the model that "there is a 50% chance the next word is dogs."

For Machine Learning models to have enough data to start to recognize the almost uncountable relationships between words, it needs a vast amount of textual data which can be found across the internet in web pages, books, repositories, articles, blogs, academic papers, Wikipedia, news archives, public forums, and more. This textual data is the building block for GenAI systems, but it also starts to introduce some limitations and risks:

- Machine Learning is expensive, requiring data centers which play a role in disrupting the environment
- There are plenty of ethical and legal concerns about the intellectual property AI is training on.
- Statistical relationships represents knowledge


, is collected and processed into individual units called **Tokens**. GenAI models use tokens to calculate the statistical relationships across language and train their models on data in a process called **Machine Learning (ML)**.

https://aws.amazon.com/what-is/machine-learning/
https://help.openai.com/en/articles/7842364-how-chatgpt-and-our-foundation-models-are-developed
https://lakefs.io/blog/data-preprocessing-in-machine-learning/

In ML, rather than programming the computer to understand this data, an algorithm analyzes the patterns within the data to learn automatically. 

***Phase 2***

Through this process, a system of synthesized data emerges called a **Neural Network**. The synthesized data is used to reverse engineer human-like language. Using multiple neural networks, called the **Transformer Architecture**, the data enters the **Natural Language Processing** stage, where it begins to process tokens and track their connections.  

Once the model completes natural language processing, it becomes a **Large Language Model (LLM)**, a model of human-like language. The LLM can read, reason, and generate text that resembles human text. However, despite its capabilities, it still isn't like the chatbots we are using. 

***Phase 3***

Converting an LLM into a **Chatbot** requires an additional training stage. In this final stage, it is trained to become a conversational system that manages the dialogue flow, personalizes responses, and serves as a helpful, adaptable assistant.

***GenAI Step-By-Step***
```mermaid
graph LR
    subgraph Step 1: Phase 1
      A(Data Collection) --> B(Machine Learning)
    end
    
    subgraph AI["GenAI Development"]
        subgraph Phase 2: Training
            B --> C(Neural Network)
            C --> D(Transformer Architecture)
            D --> E(LLM)
        end
        
        subgraph Phase 3: Interface
            E --> F(Chatbot)
        end
    end
```

## What Are the Possibilities, Limitations, and Risks of AI Chatbots?
### What GenAI Promises
GenAI enthusiasts promise that AI will promote political and economic health while also enabling individual growth across personal relationships, career advancement, and creativity. Furthermore, enthusiasts argue that GenAI tools enable individuals to code, design, build products, and produce media effortlessly because they will have 24/7 access to an AI agent with expertise in every subject.

LLMs have enabled chatbots to generate natural language from a dataset of text so vast that a single human couldn't read it in a lifetime. Human-AI collaboration seems more efficient because GenAI's enormous generating capacity outperforms that of a single human every time. 

As Copywriters, we are promised an increase in productivity and a decrease in mental drudgery because GenAI chatbots can augment and automate many of our tasks, such as:



GenAI enthusiasts promise what GenAI might be, but those promises do not describe what GenAI currently is. GenAI models have limitations and risks that prevent them from completely replacing the work and effort of Copywriters. 

GenAI enthusiasts may argue that the limitations and risks of AI do not demonstrate that Copywriters cannot be replaced, only that GenAI requires human oversight to govern and verify outputs. The need for human oversight means that GenAI is not prepared to fulfill the enthusiasts' promises. Potentially, AI could be incorporated into a Copywriter's workflow to increase productivity, but that is not equivalent to the Copywriter role itself.

While human effort may have similar limitations and risks, the difference is that we can take full accountability. Copywriters can explain decisions, accept responsibility, and learn from experience. Copywriters who choose to employ GenAI in their work can overcome its limitations and weaknesses, showcasing its potential use cases in effective, efficient, and ethical ways. You can find effective strategies for copywriters in [part2](../part2/overview.md).

### AI Limitations & Risks
Copywriters should adapt an apprehensive—*both comprehensive and skeptical*—approach to using Chatbots by exploring their underlying mechanics.  

| Chatbot Mechanics ||
|:--|:-----|
| **Tokens** | The basic units of text (roughly ¾ of a word, including punctuation and formatting) that a Chatbot uses to process and calculate language. |
| **Context** | The set of tokens included to generate a response. It represents the information available to a Chatbot during a session, including user prompts, uploaded files, system instructions, and prior chat history. |
| **Context window** | The limit on the total volume of text that a Chatbot can hold in its active working memory at any single moment. |
| **Hallucinations** | The generation of plausible, authoritative-sounding text that is factually incorrect or entirely fabricated. |
| **Sycophancy** | The tendency for Chatbots to align with user expectations. |

#### Tokens & Training

Chatbots such as ChatGPT, Google Gemini, or Microsoft Copilot do not process words the same way that you do. Instead of reading a sentence straightforwardly, they break it down in a process called tokenization. The models are trained to understand the statistical relationships among those words, and that training is stored in their neural networks. Tokens are given a numerical identity, which changes how they read text. For example:

Humans read:

    The quick brown fox jumps over the lazy dog.

AI reads: 

    ["The", " quick", " brown", " fox", " jumps", " over", " the", " lazy", " dog", "."]

AI tokenizes: 

    [976, 4853, 19705, 68347, 65613, 1072, 290, 29082, 6446, 30]

For simple words and characters, it breaks them down into IDs. However, for more complicated words, it has to break them down into different sections. For example: 

Humans read:

    Supercalifragilisticexpialidocious.

AI reads:

    ["Super", " cal", " if", " rag", " il", " istic", " exp", " ial", " id", " ocious", "."]

AI tokenizes:

    [17789, 5842, 366, 17764, 311, 6207, 8067, 563, 315, 170661, 13]

When you input a prompt into a chatbot, it calculates the relationship between each token to predict the most likely next word. Internal mechanics, such as verification and instructions, consume tokens. Since each token incurs computational cost, it is usually better to train the model to generate certain types of responses. This kind of training is done through **Reinforcement Learning from Human Feedback (RLHF)** and **Direct Preference Optimization (DPO)**.

#### Token Limits & Context Window

Each token competes for space within the model's computational limit, called the context window. Every Chatbot has a context window, a maximum number of tokens it can hold at one time. This includes everything: your prompts, the Chatbot's responses, any uploaded documents, and the entire conversation history. No matter how large the context window is, it is still finite. 

This is why usage limits exist in Chatbots. Message limits, document size restrictions, and conversation length caps trace back to the context window. A short, focused prompt consumes fewer input tokens than a long, unfocused one. A request that generates a two-paragraph response costs less than one that produces a ten-page document.

The economics are straightforward: tokens are the currency of GenAI Chatbots. However, there is a catch: context is important because Chatbots are more prone to hallucinations without it. There is a balance for AI chatbots. More context improves responses and reduces the risk of hallucinations, but increasing context also consumes token capacity, creating a trade-off between performance and information retention.

##### *Diminishing Returns*

Context window limitations and GenAI's tendency for hallucinations challenge the promises of greater productivity.

If a Copywriter must spend time tailoring prompts that provide enough guidance and content to ensure helpful responses and avoid hallucinations, then evaluating those outputs to ensure stylistic and factual cohesion, and readjusting for improved output, while also managing the limitations of the context window, then the efficient and effective use of GenAI is diminished because the time required for oversight may be better spent performing the task.

If a Copywriter reduces the time spent reviewing the output to improve productivity, they risk including hallucinations, misinformation, and poor-quality copy. While it may be more efficient to utilize generated content, an increase in output volume and speed will not compensate for the reduction in output quality. Still, it does at least guarantee the appearance of productivity.

#### Hallucinations & Sycophancy

AI chatbots are intentionally designed to always generate useful responses to user requests, rather than guaranteed truth verification. Hallucinations and sycophancy are features of GenAI Chatbots, not bugs. These features are required for GenAI chatbots, because they are supposed to act as highly adaptable assistants for any given scenario. This adaptability creates hallucinations and sycophancy because Chatbots have limited:

- **Accessible Data:** They rely on next-word prediction, not a fact-checking engine. It is extremely difficult for them to verify the accuracy of information.
- **Verification Methods:** They are trained to produce a plausible type of result, not an exact factual result. Whatever facts they get correct are circumstantial and due to statistical frequency.
- **Research Capacity:** They can potentially fabricate fictional resources, events, or facts that appear authoritative.
- **Language Processing:** They may be adept at processing superficial text that appears grammatically accurate, professionally sophisticated, and logically sound at a glance, but deeper inspection reveals the content lacks substantive thought, contextual grounding, or applicability. Functionally, they don't understand language on a semantic level; they aggregate patterns of writing using tokenization algorithms.
- **Content Restraints:** They don't have hard-coded restraints that limit specific types of content, instead they are trained to suppress undesired outputs. However, those restraints can be bypassed. This means they can generate content that is inappropriate, illegal, deceptive, biased, manipulative, dangerous, or completely fabricated.

### AI Possibilities
When the promises of GenAI are tested against the limitations and risks these models currently have, they are only as effective and efficient as the Copywriter using them. A Copywriter who embraces the technology without preparing to handle the limitations may create copy with errors that were easily preventable with human overview. A Copywriter who uses the technology with cation and strategy fight is not as fast as the first copywriter, but they are more likely to create error-free, helpful copy.

GenAI has the ability to write all of your work for you, but human governance is in every sentence and word, not just prompting the machine. Copywriters should use GenAI with skepticism, reserving GenAI to three specific roles: Find, Challenge, and Inspect.

##### *<p align="center">AI Possibilities = Human Governance + AI Promises - Risks & Limitations</p>*

#### ***Find***
GenAI's hallucinations prevent it from becoming a truly effective researching, summarizing, and notetaking tool. There is never a guarantee that it has sufficiently generated an accurate response, even if its reasoning and syntax appear authoritative. Copywriters should not leverage GenAI as a replacement for traditional research methods and tools, but by taking advantage of the integrated LLMs and search systems, they can efficiently augment the search for relevant sources.  

By using GenAI as a search tool for research materials you are able to quickly find sources that relate directly at a greater rate. It will still be up to you to verify appropriateness, accuracy, and authority of each source. Tools like Google's Gemini, which are connected to systems like Google Search and Google Scholar, could easily be introduced into the Copywriter's research strategy.

You can find more effective strategies for Find here:

#### ***Challenge***
Copywriters can assign GenAI tools user personas to test stress points and friction within their copy. It can offer various perspectives to challenge the Copywriter's assumptions, offering a fast-paced review with various audiences. While not a total replacement, during the drafting and revising period, this feature can be used to sharpen thinking, especially when used with skepticism.

The principle behind Challenge is using GenAI to sharpen the Copywriters work rather than replace it, by evaluating underlying assumptions, casual connections, logical thinking, and rhetorical strategy. GenAI shouldn't suggest methods to overcome these gaps, but it may help the Copywriter see an issue they weren't aware of.

The goal with Challenge is to use GenAI as a tool that strengthens Copy through rigorous testing, not automatic rewriting. By assigning testing and analytical personas the Copywriter will be able to better reason through, defend, and explain decisions that they made.

You can find more effective strategies for Challenge here:

#### ***Inspect***
GenAI is able to process large amounts of text almost instantaneously. Through that process, they are able to analyze, evaluate, and critique texts' weaknesses and strengths. The issue is that even with context and prompt engineering, GenAI will still make erroneous mistakes. GenAI should not be used as the only editing tool. Tone, style, and grammar should always be reviewed by humans.

GenAI should be given specific parameters before evaluating text, such as persona, style guidelines, and objectives. When going through the final audit, the Copywriter can evaluate the AI-reviews one at a time and still use their own judgment to determine what is best.

You can find more effective strategies for Inspect here:

- **Research**
- **Planning and Outlining**
- **Brainstorming and Drafting**
- **Editing Grammar, Tone, and Style**
- **Logical Analysis**
- **Review and Quality Control**
- **Citation & Reference Generation**
- **Content Creation**

GenAI multimodal chatbots like ChatGPT, Google Gemini, or Microsoft Copilot are tools that BYU-Idaho Copywriters will have access to through their official `@byui.edu` accounts.

# AI Terminology
> * **Artificial Intelligence (AI):** the computer systems that are trained to perform tasks in ways that resemble human intelligence.
> * **Machine Learning (ML):** the process of training AI, without explicitly programming it, with an algorithm developed from patterns found in data sets.
> * **Deep Learning:** a form of machine learning that uses artificial neural networks to mimic the human brain
> * **Neural Network:** the model created by machine learning that resembles the structure and function of the neural networks found in the brain.
> * **Transformer Architecture:** the collection of neural networks that helps build AI models by converting text into tokens.
> * **Tokens:** the unit of data processed by AI models during training.
> * **Tokenization:** the process of converting text into tokens.
> * **Natural Language Processing:** the processing of human-like language for a computer system. This includes the process of finding relationships between words in neural networks.
> * **Large Language Model (LLM):** the model based on transformer architecture, trained from a large amount of text for natural language processing and language generation.
> * **Chatbots:** software applications built on LLMs called GPTs that are meant to generate text that resembles human-like conversation, reasoning, and creativity.

# Citations

1. <a id="cite-1"></a> https://www.goldmansachs.com/insights/articles/how-will-ai-affect-the-us-labor-market [↩ Back to text](#ref-1)
2. <a id="cite-2"></a> https://www.byui.edu/ai/academics [↩ Back to text](#ref-2)
3. <a id="cite-3"></a> https://www.unesco.org/en/artificial-intelligence/recommendation-ethics [↩ Back to text](#ref-3)
4. <a id="cite-4"></a> https://www.mdpi.com/2075-4698/15/1/6 [↩ Back to text](#ref-4)
5. <a id="cite-5"></a> https://news.harvard.edu/gazette/story/2025/11/is-ai-dulling-our-minds/ [↩ Back to text](#ref-5)
6. <a id="cite-6"></a> https://tulanehullabaloo.com/74464/data/ai-reliance-may-have-detrimental-cognitive-effects-new-study-finds/ [↩ Back to text](#ref-6)
7. <a id="cite-7"></a> https://mitsloan.mit.edu/press/new-mit-sloan-research-suggests-ai-more-likely-to-complement-not-replace-human-workers [↩ Back to text](#ref-7)
8. <a id="cite-8"></a> https://www.ibm.com/think/topics/artificial-intelligence [↩ Back to text](#ref-8)
9. <a id="cite-9"></a> https://sloanreview.mit.edu/article/how-genai-changes-creative-work/ [↩ Back to text](#ref-9)








