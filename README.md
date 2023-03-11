# docs.gaiann.com

## Chat bot discord

+ [Open-Assistant/discord-bot at main · LAION-AI/Open-Assistant](https://github.com/LAION-AI/Open-Assistant/tree/main/discord-bot)


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


## IoT

+ [15 kilometre LoRa SSH link with RNode | unsigned.io](https://unsigned.io/15-kilometre-ssh-link-with-rnode/)
+ [SDRangel Now Available on Android: Mobile ADS-B, AIS, APT, Digital Voice, POCSAG, APRS, RS41 Radiosonde Decoders](https://www.rtl-sdr.com/sdrangel-now-available-on-android-mobile-ads-b-ais-apt-digital-voice-pocsag-aprs-rs41-radiosonde-decoders/)
+ [SparkFun LoRa Gateway 868/915MHz - 1 - kanałowa bramka sieciowa ESP32, RFM95W - SparkFun WRL-18074 Sklep Botland](https://botland.com.pl/moduly-radiowe/19510-sparkfun-lora-gateway-868915mhz-1-kanalowa-bramka-sieciowa-esp32-rfm95w-sparkfun-wrl-18074-5904422370299.html)


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

---
+ [edit](https://github.com/gaiann/docs/edit/main/README.md)
