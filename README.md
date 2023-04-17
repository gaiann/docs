# docs.gaiann.com


## Space


## Chat bot discord

+ [Open-Assistant/discord-bot at main · LAION-AI/Open-Assistant](https://github.com/LAION-AI/Open-Assistant/tree/main/discord-bot)

## chatgpt

+ [Zabaware - Intelligent Machines](https://www.zabaware.com/#page=/loebner.html;)




## webscrapping

[Web scraping code templates · Apify](https://apify.com/templates)

> # Web scraping code templates
> 
> Actor templates help you quickly set up your web scraping projects, saving you development time and giving you immediate access to all the features the Apify platform has to offer.


[Web Scraping, Data Extraction and Automation · Apify](https://apify.com/)

> # Build reliable web scrapers. Fast.
> 
> Apify is the platform where developers build, deploy, and monitor  
> web scraping and browser automation tools.




## video education, chat

+ [Understanding AI Chat Bots With Stanford Online](https://hackaday.com/2023/02/08/understanding-ai-chat-bots-with-stanford-online/)

+ [Let's build GPT: from scratch, in code, spelled out](https://www.youtube.com/watch?v=kCc8FmEb1nY)


## open-assistant.io

+ [LAION AI Repositories](https://github.com/orgs/LAION-AI/repositories?type=all)

+ [faq - Open Assistant](https://projects.laion.ai/Open-Assistant/docs/faq)

+ [Open Assistant](https://projects.laion.ai/Open-Assistant/)

+ [LAION-AI/Open-Assistant: OpenAssistant is a chat-based assistant that understands tasks, can interact with third-party systems, and retrieve information dynamically to do so.](https://github.com/LAION-AI/Open-Assistant)

+ [presentation](https://docs.google.com/presentation/d/1n7IrAOVOqwdYgiYrXc8Sj0He8krn5MVZO_iLkCjTtu0/edit#slide=id.g1c27a3078af_0_1369)

+ [Aligning Language Models to Follow Instructions](https://openai.com/blog/instruction-following/)

+ [https://www.youtube.com/watch?v=64Izfm24FKA](https://www.youtube.com/watch?v=64Izfm24FKA)

+ Help us collect data for OpenAssistant, the largest and most open alternative to ChatGPT. https://open-assistant.io
+ Homepage: https://ykilcher.com
+ Merch: https://ykilcher.com/merch

## another platforms

+ [LAION](https://laion.ai/)

## cloud

+ [Cloud Free Tier | Oracle Polska](https://www.oracle.com/pl/cloud/free/)


## chatGPT

[What Is ChatGPT Doing … and Why Does It Work?—Stephen Wolfram Writings](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/)

> That [ChatGPT](https://chat.openai.com/) can automatically generate something that reads even superficially like human-written text is remarkable, and unexpected. But how does it do it? And why does it work? My purpose here is to give a rough outline of what’s going on inside ChatGPT—and then to explore why it is that it can do so well in producing what we might consider to be meaningful text. I should say at the outset that I’m going to focus on the big picture of what’s going on—and while I’ll mention some engineering details, I won’t get deeply into them. (And the essence of what I’ll say applies just as well to other current “large language models” \[LLMs\] as to ChatGPT.)


### ChatGPT API

[Image generation - OpenAI API](https://platform.openai.com/docs/guides/images/introduction)

> The [image generations](https://platform.openai.com/docs/api-reference/images/create) endpoint allows you to create an original image given a text prompt. Generated images can have a size of 256x256, 512x512, or 1024x1024 pixels. Smaller sizes are faster to generate. You can request 1-10 images at a time using the [n](https://platform.openai.com/docs/api-reference/images/create#images/create-n) parameter.

```python
response = openai.Image.create(
  prompt="a white siamese cat",
  n=1,
  size="1024x1024"
)
image_url = response['data'][0]['url']
```


## tutorials


+ [Building a chatbot using OpenAI's GPT-3 engine, Twilio SMS and Python (2023)](https://enster-info.randvatar.com/article/building-a-chatbot-using-openai-s-gpt-3-engine-twilio-sms-and-python)



## opensource
[Python Chatterbot Tutorial Edureka at DuckDuckGo](https://duckduckgo.com/?t=ffab&q=Python+Chatterbot+Tutorial+Edureka+&atb=v333-1&ia=web)

+ [gaiann/ai-alt-text-generator](https://github.com/gaiann/ai-alt-text-generator)
+ [gaiann/test-english-ai](https://github.com/gaiann/test-english-ai)
+ 


## [SingularityNET](https://github.com/singnet)

+ [SingularityNET - Next Generation of Decentralized AI](https://singularitynet.io/)
+ [ebook](https://raw.githubusercontent.com/singnet/ai-dsl/master/doc/technical-reports/2022-Oct/ai-dsl-techrep-2022-oct.pdf)

[Technology - SingularityNET](https://singularitynet.io/technology/)

> # Technology Platform
> 
> SingularityNET Platform is an open and decentralized network of AI services made accessible through the Blockchain. Developers publish their services to the SingularityNET network, where they can be used by anyone with an internet connection. Developers are able to charge for the use of their services using the native AGIX token.
> 
> Services can provide inference or model training across myriad domains such as image, video, speech, text, time-series, bio-AI, and network analysis. The services can be as simple as wrapping a well-known algorithm, a complete end-to-end solution for an industry problem, or a standalone AI application. Developers can also deploy autonomous AI agents that interoperate with other services on the network.


### AI Marketplace

The core platform performs essential functionality such as facilitating trustless and automated transactions based on our multiparty escrow, publishing new AI services and organizations on the blockchain, tracking successful API calls and defining pricing strategies. On top of the platform, the AI Marketplace offers a rich user interface that allows users to easily find, assess, and try out services registered on the platform. Most services offer a limited number of free API-calls so users can get a good impression of what the service has to offer. Beyond that users can pay for additional services directly with our native AGIX token or with fiat currency using our Paypal integration.

Each service hosted on the marketplace is represented by a profile page that offers information about the service including media gallery visuals, pricing, install & run instructions, the reputation rating and free demo options. There is a wide and growing collection of services on our marketplace, ranging from image manipulation to gene sequencing and more!



AI-DSL is a transformative component in the next phase of our platform that will enable separate narrow services to form ad-hoc workflow collaborations to fulfill more complex tasks than any single service would be capable of.

AI-DSL is an AI service that will not require a strict predefined format of inputs and outputs of the services. This will allow it to orchestrate ad-hoc workflows of fitting services to execute a requested task. Due to the growing number of services on the platform the requirements will evolve to include both functional and non-functional variables (like lowest cost, highest speed, best reliability etc.) based on our reputation system for AIs.



[AI-DSL: Toward a General-Purpose Description Language for AI Agents | by Ben Goertzel | SingularityNET](https://blog.singularitynet.io/ai-dsl-toward-a-general-purpose-description-language-for-ai-agents-21459f691b9e)

> # Functions of the AI-DSL
> 
> So let’s plunge into the practicalities. What exactly do we need an AI-DSL for? The language we are creating will allow:
> 
> - AI agents to effectively interoperate with each other without human intervention (including the choice of which AI agents should interoperate together in which contexts)
> - External software systems to know how to interact with AI agents
> - AI agents to know which datasets they should be considering to ingest or produce
> - Systems in charge of running or guiding the execution of AI agents on infrastructures, to know how to do so most effectively



[AI-DSL Phase 2 — Final report. The AI-DSL Project for an AI… | by Matt Iklé | SingularityNET](https://blog.singularitynet.io/ai-dsl-phase-2-final-report-fc09f8b99c90)

> The AI-DSL project is a cornerstone of the expansion and evolution of the SingularityNET Platform/Marketplace into a revolutionary tool for Decentralized AI and will:
> 
> 1. Contribute to the broad usability and interoperability of services on the Platform
> 2. Allow networkable decentralized AI workflows to be easily created
> 3. Provide structural protocols and linkages to allow SingularityNET to evolve as a self-organizing network
> 4. Create a framework for the potential emergence of AGI from this network of AI












---
+ [edit](https://github.com/gaiann/docs/edit/main/README.md)
