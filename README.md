# Signeo Documentation

This repository contains all the documentation for the Signeo project, including setup guides, API references, and contributor instructions.

## Contents
- **Setup Guides**: Instructions for configuring and running Signeo applications.
- **API References**: Detailed documentation for Signeo’s APIs.
- **Contributor Instructions**: Guidelines for contributing to the project.
- **Research**: Result of research on various subjects linked to the project.

## Project Architecture

The high-level architecture for Signeo's components is shown below:

![Signeo Architecture](assets/diagrams/SigneoArchitectureDiagram.png)



## Research on current solutions

RWS Group: They have developed SignAll, a real-time communication platform that translates spoken language into sign language. However, it's primarily focused on professional settings and may not be directly consumer-oriented.   

https://www.acrolinx.com/acrolinx-and-rws-getting-clear-compliant-localized-content-to-market-faster/

Hand Talk: This Brazilian company offers an app that translates spoken Portuguese into Brazilian Sign Language (Libras). It's a more accessible solution for individuals, but its language support is currently limited.   

https://www.handtalk.me/en/blog/how-to-use-the-hand-talk-app/

Open-Source Projects: There are various open-source projects exploring audio-to-sign language translation, such as the AudioToSignLanguageConverter on GitHub. These projects, while not commercial products, could potentially evolve into competitive solutions.   

https://github.com/sahilkhoslaa/AudioToSignLanguageConverter/issues/5

Sign Studio: This platform specializes in creating sign language videos for websites and other digital content. While not directly translating audio, it provides a valuable tool for making content accessible to the Deaf community.

https://www.signapse.ai/

### Other relevant websites for competition :

https://www.signfordeaf.com/

https://slait.ai/

https://signer.ai/

## AI research:

While there is no specific Open Source AI for translation of text into sign language we could use **HuggingFaceModel Transformers** for natural language processing or **Fairseq** but we need more time to research which one would be the most interesting to use.

There is already AI projects though to recognize sign languages so it could be interesting to try the other way around and to translate sign languages into text for exemple for messaging some existing solutions to recognize would be **MediaPipe** or **OpenPose**

For **recognition of the speech** there is a **WIDE variety of existing solution** with the most famous one being **Whisper by OpenAI** there is also others like **Kaldi**  or **Vosk**. **Vosk is only for offline speech recognition** so it could be relevant **if we go for a solution like a VLC type software** on pc and phones **Kaldi on the other hand is fully open source** so it could be worth it to give it a try.

## Sign Language Datasets:

**There is a lot of datasets** for sign languages **the problem is actually defining which one we want to tackle first** which will be **directly correlated to the communitys we will try to enter in contact with**, here is a nice website where a lot of those datasets are available: http://facundoq.github.io/guides/sign_language_datasets/slr

Here is one for **British sign language**: https://www.robots.ox.ac.uk/~vgg/data/bobsl/

Here is one for the **American** one: https://www.kaggle.com/datasets/ayuraj/asl-dataset

And for **Spanish sign language (static)**: https://www.kaggle.com/datasets/kirlelea/spanish-sign-language-alphabet-static

https://github.com/zparcheta/spanish-sign-language-db

## Communities to possibly enter in contact with:

Here is a website with a lot of **associations and communities in UK for deaf people**: https://gallaudet.edu/international-affairs/international-relations/local-deaf-and-disability-organizations-and-schools/deaf-organizations-in-united-kingdom/deaf-organizations-in-scotland-uk/

For **Scotland**: https://deafaction.org/

More reseach is needed to find relevant associations for America (State Specific) and China (especially in Beijing




