*Welcome to Part 2 of your AI Jumpstart. In this edition, we’ll discuss the revolutionary debut of ChatGPT, what it is, and the basics of using it. If you haven't yet subscribed to The Streamline, [hop aboard](https://thestreamline.ai), then find me on [Twitter](https://twitter.com/williamnutt), [YouTube](https://youtube.com/williamnutt), [LinkedIn](https://linkedin.com/in/williamnutt) and [Bluesky](https://bsky.app/profile/wnutt.bsky.social). 🦾

\<!-- youTube(zF8ELog6tog) --\>

The release of ChatGPT in November 2022 ignited a revolution in AI. Not only did it offer unrivaled *capability*; it was also profoundly *accessible* and *usable*. As a free, web-based, conversational chatbot, ChatGDP placed an unimaginably powerful technology in the hands of everyday people. And it was—and remains—a mere preview of the disruptive force it, and the applications it inspires, will become.

\<!-- TOC --\> 
### How we’ll unpack ChatGPT 👇

- OpenAI: The Company

\<!-- /TOC --\> 

## OpenAI: The Company
[OpenAI](https://openai.com) is an “AI research and deployment company” with a mission “to ensure that artificial general intelligence benefits all of humanity.” It engineers advanced deep learning models for processing and generating language and imagery.

The company began as a nonprofit in 2015 with Elon Musk among its co-founders. In order to attract funding, it transitioned to a “capped” for-profit in 2019, with profits limited to 100 times investments and Sam Altman as CEO. Microsoft invested $1 billion, and would add $10 billion in 2023.

Within its new profit model, OpenAI also began commercially licensing its technologies.

### Generative Pre-Trained Transformers (GPTs)
GPT is a family of OpenAI LLMs that debuted in 2018. It’s named for three characteristics that we introduced in [Part 1](https://www.thestreamline.ai/insight/ai-from-a-birds-eye):

- **Generative** — Not only do the models interpret language; they generate it.
- **Pre-Trained** — The LLMs receive unsupervised training with billions of pages from the web and books. (For their final applications, they’re often “fine-tuned” through supervised and reinforcement training with custom data.)
- **Transformer** — Their transformer architecture boosts accuracy and efficiency by removing, rearranging and assigning weights to words.

### GPTs via API
Initially, GPTs were accessible only via OpenAI’s **API**. An API (application programing interface) allows apps to integrate with other apps. Virtually all of your apps use APIs. 

In the case of GPTs, third-party apps can communicate with, and fine-tune, the LLMs. That allows developers to create interfaces for the models, or visual mediums for interacting with them, with specialized knowledge. When you see variations of “powered by GPT technology,” it’s accomplished using the OpenAI API.

One notable example is [Jasper]()(https://www.jasper.ai/), which generates copywriting for brands.

## Enter ChatGPT
The November 2022 release of ChatGPT gave everyday users a more direct connection to GPTs. Rather than accessing concentrated derivatives of the models through third-party apps, they could go straight to a general-purpose chatbot from OpenAI. That vastly expanded access to GPTs while creating a whole new form of pleasure.

### ChatGPT Snapshot

- ChatGPT is a general-purpose conversational AI, or chatbot, that accepts prompts and returns responses in natural language.
- It’s not an LLM; rather, it’s a medium for interacting with OpenAI’s LLMs. In other words, ChatGPT is an app that offers a visual interface for GPT models, much like Outlook is an interface for emails stored on a server. Some observers call ChatGPT “the eyes and ears of language models.” *(Stay mindful of this distinction between GPTs—the models—and ChatGPT—the chatbot.)*
- On top of their expansive pre-training, GPTs (the models) are fine-tuned for ChatGPT (the chatbot) through (1) supervised learning with sample prompts and responses and (2) reinforcement learning with human monitors. Among other benefits, fine-tuning prepares the tool for common prompts and makes its responses more human-like.
- Initially, ChatGPT relied solely on its training data, which contained no information later than September 2021. That was an enormous limitation, but in May 2023, it gained access to the live web via a plugin that integrates with Microsoft’s Bing search engine. *(As of June 1, ChatGPT’s internet access is limited to the web app and rolling out incrementally to users on the free tier.)*
- ChatGPT supports multiple chats. For each each active chat, it recognizes previous prompts and responses, allowing new prompts to build on them.
- The service is free, but for $20/mo., a Plus plan offers guaranteed uptime, faster responses, access to newer GPT models, and early admission to new features.
- ChatGPT remains in the beta phase of development, meaning it’s vulnerable mistakes, from nuanced misinformation to full-fledged “hallucinations.” Abundant disclaimers reminded users of this experimental phase.

### Access ChatGPT

You can access ChatGPT in two ways:

1. The **web app** on OpenAI’s website at [chat.openai.com](https://chat.openai.com)
2. The **mobile app**, which is currently only available for iOS but coming to Android soon (see my [tour ChatGPT for iOS](https://youtu.be/SfjNdm3CEuM))

You’ll need an OpenAI account, which you can create for free with an email address or by linking an existing account with Apple, Google or Microsoft.

You’ll find the chat interface intuitive, with clear options for entering prompts and creating new chats. Try one of my favorite prompts: `Explain [topic] to a high school student in 500 words`.

![](https://assets.thestreamline.ai/insights/the-chatgpt-revolution/the-streamline_chatgpt-demo.gif)

Methodical prompting is essential to AI and will remain a core focus of *The Streamline*.

## Experimental Prompts

### Objectives
We’ll dive much deeper into ChatGPT’s immediate and long-term applications, as well as methodical “prompt engineering.” For your introduction and experimentation, here’s a quick list of ChatGPT’s core competencies:

- Explain a given topic
- Outline or draft:
	- Blog posts or essays
	- Social media posts
	- Presentations, sales pitches, taglines, etc.
- Brainstorm names, ideas or themes from a topic or outline
- Given a word, list synonyms, antonyms, rhyming words, et al.
- Predict the outcome for a hypothetical scenario
- Generate a strategy, or detailed instructions, for accomplishing a given objective
- Analyze an existing strategy, such as a business model
- Plan a meal from given ingredients or dietary requirements
- Translate one language to another
- Compose or correct computer code

### Parameters
With any prompt, you can supply content for ChatGPT to use or reference, such as the content to summarize. You can also specify: 

- **Length**, such as “500 words”
- **Tone**, like “in the style of Hemingway”
- **Target audience**, like “a ten-year-old”
- **Role of the chatbot**, such as an interviewer for a specified role or a specialized therapist
- **Output format**, such as a table or bullet list.

### Example Prompts
Here are some internet-independent prompts I use daily. (Replace `{}` with your own inputs. Use `[]` as they’re written; they’re variables within your prompts that you define afterward.

#### Teach me like I’m in high school.
```
You're an expert on {topic}. I'm in 10th grade. Explain {topic}, 500-word maximum
```

![](https://assets.thestreamline.ai/insights/the-streamline_chatgpt-sample-prompt_teach.jpg)

#### Summarize this content.
```
Sumarize [article] in a bullet list, 100-word maximum

[article]:

{pasted article}
```

#### Draft an article.
```
You're a blogger about {topic}. Your audience is {audience}. Write a 1000-word blog post about {topic}. Include these topics:

- {Subtopic 1}
- {Subtopic 2}
- {Subtopic 3}
- {Subtopic 4}
- {Subtopic 5}
```

#### List synonyms.
```
List 50 synonyms of {word}.
```

## Explosive Growth

Proponents and skeptics alike describe a sense of magic when using ChatGPT for the first time. Its novelty is undeniable. Its natural conversation, grammatical soundness and conviction are uncanny. In one robotic exchange, the shred of captivation still held by Alexa and Siri vanishes into history. It’s not until you hone in on factual inaccuracies does ChatGPT’s mystique begin to fade.

Thanks to its sensational first impression, ChatGPT spread like wildfire across news and social media. In just two months, it reached 100 million active users—a stunning contrast with TikTok (9 months) and Instagram (2.5 years), among other behemoths.