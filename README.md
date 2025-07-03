# PiNucleus
The brain of PiVerse, a large multi project system which aims at revolutionizing home start-up projects of the modern age. With things like storage servers, voice to 3d printers, etc while doing everything offfline maintaining privacy

# Description

The PiNucleus is a planned to be a Raspberry Pi 5 16GB model, with 2 - 4 TB of external hardrive storage, a 256GB SSD with HAT, and an active cooler. This is would be the most powerful computer of the PiVerse, with all the sub-projects sending data to it for any heavy processing that might be needed to be performed. It would be the core, as the name sugggests, which will hear, translate, and relay the human voice commands, processed to any of the respective modules. Mainly a Google Home or Amazon Alexa, but better and more secure.

# Software

LLM: Gemma 2 (2B), or Qwen 2.5 (3B) are some choices i have in mind, based on a balance of speed and Performance. TinyLlama (1.1B) runs best, while Mistral (7B) is the most complex it can go. I might even add different modes, and switch them accordingly. Like TinyLlama for those focused work sessions, Mistral for a deep conversation, and Gemma 2 for the regular.

Text-To-Speech: ChatterBoxTTS by Resemble AI. OpenSource, lightweight, and customizable, what more could you want?

Speech-To-Text: Vosk, a Kaldi-based STT model, with models ranging from 40MB to 1.8 GB, so i will test around. The main thing is the diversity of models, and the support for Indian English and Hindi, which is crucial for an Indian like me.

Storage Management: OpenMediaVault or Samba, I haven't dabbled my hands in this field, so I will check each of them out and then decide.

Might add more software later down the line based on actual performance, but this is the core.

# Core Values

This project aims to build a modern, AI-powered entreprenuer focused office. It does most of the things by itself, leaving the owner free for actual work to do. Some specific modules, such as PiPrint (a 3D+PCB printer), are focused completely towards them. I aim to provide each person with the modules they need, their own subset of PiVerse, with the PiNucleus at the center as their assistant.

# BOM

| Item       | Total Cost                     | Link        |
|--------------|---------------------------------|-----------------|
| **Raspberry Pi 5 16GB**      | ~$150       | [https://www.silverlineelectronics.in/products/raspberry-pi-5-16gb-ram-silverline-raspberry-pi-india?variant=46201981010142&country=IN&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&srsltid=AfmBOopvJGzOQRy6fDcyLoFzoeTpJn_8FkbO2ofecV5iPcxqrfnYpYndjLs]   |
| **Raspberry Pi 5 256GB SSD kit**      | ~$46        | [https://www.silverlineelectronics.in/products/raspberry-pi-official-ssd-kit-iops3-40k-256gb-silverline-electronics-official-distributor?_pos=2&_sid=c2dcb73a1&_ss=r]    |
| **WD Blue 4TB HDD** with shipping      | ~$125      | [https://www.amazon.com/Western-Digital-Blue-Internal-Drive/dp/B0BNGL4BND/ref=sr_1_1?crid=2QP8F1NOCBH6Y&dib=eyJ2IjoiMSJ9.wS52W-qaFHO2Apa1IPqbNPGscxxS1A7nezjBum6-qtAvCfwSXRjrxQPcHHGXHwvGBQYODQ7C7HlyYirKSPYeeO1vpTBXNyL6kc1kLhR13xy0f3PafrmzzjmjnLwye9_tRYfC9e6T8E14JtvJTEDdITBgrKvdl4ih-yHpf4ZH9i_UuZUq6lb0eikFsVT9Qsh04lJaQtUxN9ly2ysH32WmYAymVqJ8TPvTY6DP1kLlll0.kQsVlX0_Kn4vHU8BtogHApi2xlSZjUfbrkMk0bXh6vI&dib_tag=se&keywords=6TB%2BHDD&qid=1751553380&sprefix=tb%2Bhdd%2Caps%2C517&sr=8-1&th=1]  |
