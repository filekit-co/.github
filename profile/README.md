 # Welcome to `Wikitoday` 👋 




# 1. Wikitoday
> Explore trending topics with wikitoday

- Web: https://wikitoday.io
- Frontend: https://github.com/filekit-co/wikitoday-front
- Back: https://github.com/filekit-co/wikitoday


"Wikitoday is an automated service that, leveraging OpenAI for content generation and DeepL for translation, crawls articles based on Google Trends for each country during peak news consumption hours. After regenerating the content, it translates it into languages of countries interested in that nation's news, pushes to GitHub, triggering a CI/CD process that deploys to the Wikitoday front-end server, and subsequently distributes the content across SNS and video platforms."

<center>
<h3> Desktop </h3>

<table>
  <tr>
    <td><img width="1050" alt="w_landing" src="https://github.com/filekit-co/.github/assets/37536298/70fa19a3-3352-4454-91de-5cb95842bc11"></td>   
    <td><img width="900" alt="filekit" src="https://github.com/filekit-co/.github/assets/37536298/7cdf66cc-8e3c-4d8b-b182-40a5266c9299"></td>
   <td><img width="700" alt="youtube" src="https://github.com/filekit-co/.github/assets/37536298/b2a1ad25-a1c2-4fbc-8da1-d955301ee2c7"></td>
  </tr>

</table>

<h3> Mobile </h3>

<table>
<tr>
    <td><img height="300" alt="wm_landing" src="https://github.com/filekit-co/.github/assets/37536298/32b5e98e-ef7e-414f-9fbf-f73b2ab4cfc4"></td>
    <td><img height="300" alt="filekit-mobile" src="https://github.com/filekit-co/.github/assets/37536298/425e3df3-da56-4915-be09-72ffd2ec65fc"></td>
</tr>
</table>

</center>


# 2. Filekit
# `Filekit`
> Welcome to FileKit, the ultimate toolkit for file and media processing. Designed to simplify complex tasks, FileKit provides a suite of tools for file conversion, image processing, media downloads, and more. With a global reach and a commitment to performance, FileKit is the go-to solution for users worldwide.

<p align="center">

<img src="img/landing.png" height="400px" />

</p>

- Websites:
    - https://filekit.co
    - https://youtubetomp3.pages.dev
- Source codes:
    - [Filekit-front](https://github.com/filekit-co/converto)
    - [Youtube-to-mp3-front](https://github.com/filekit-co/youTubetoMP3)
    - [Image Server](https://github.com/filekit-co/api-bg-remove/tree/main)
    - [Text Server](https://github.com/filekit-co/api-text/tree/main)
    - [Video Server](https://github.com/filekit-co/api-video/tree/main)
- Swagger:
    1. [Video API Server](https://api-video-xgnu4lf2ea-uc.a.run.app/docs)
    2. [Image API Server](https://api-bg-remove-xgnu4lf2ea-de.a.run.app/docs)
    3. [Text API Server](https://api-file-xgnu4lf2ea-de.a.run.app/docs)

## Stack

- Design: Tailwind css
- Framework: Svelte / Sveltekit
- Deploy: Vite / Cloudflare pages


## 🌍 Global Engagement

FileKit's commitment to international users is evident in its extensive localization, supporting **36 languages**. Our platform has seen engagement from users spanning continents, from the bustling streets of India to the serene landscapes of Norway.

just a month 23.07 ~ 23.08, we've had:

- Over 1,200 active users from **Türkiye**.
- A remarkable engagement rate of 72% from **Ukraine**.
- An average session time of over 262 minutes from users in **South Korea**.
- Active users from diverse regions like **Uzbekistan**, **Kazakhstan**, **India**, and the **United States**.

These metrics are a testament to FileKit's universal appeal and its ability to cater to diverse user needs.

<center>

<table>
  <tr>
    <td><img src="img/anaylitics.png" alt="analytics"></td>
    <td><img src="img/anaylitics2.png" alt="analytics2"></td>
  </tr>
  <tr>
    <td><img src="img/anaylitics3.png" alt="anaylitics3"></td>
  </tr>
</table>

</center>

## 🚀 Features

### 📄 Document Conversion
Effortlessly convert between popular document formats like PDF, DOC, DOCX, and more.

### 🎥 Media Processing
Download and convert media from platforms like YouTube and TikTok.

### 🎨 Image Manipulation
From background removal to format conversion, FileKit's image tools have you covered.

### 😊 Emoji & Icon Library
Discover and utilize a vast collection of emojis and icons for your projects.

## 🛠️ Technical Highlights

- **SvelteKit**: Experience lightning-fast performance with SvelteKit's server-side rendering (SSR).
- **SEO Optimized**: With meticulously crafted meta data, FileKit ensures optimal search engine visibility.
- **i18n**: Our platform speaks your language, with support for 36 languages ensuring a seamless user experience.

## Pages

#### Mobile pages

<center>

<table>
  <tr>
    <td><img src="img/mobile1.png" alt="mo"></td>
    <td><img src="img/mobile2.png" alt="mo"></td>
        <td><img src="img/mobile3.png" alt="mo"></td>
    <td><img src="img/mobile4.png" alt="mo"></td>
  </tr>
</table>

</center>

#### Desktop pages
<center>

<table>
  <tr>
    <td><img src="img/main.png" alt="main"></td>
    <td><img src="img/menu.png" alt="menu"></td>
  </tr>
  <tr>
    <td><img src="img/pdf_to_word.png" alt="pdf_to_word"></td>
    <td><img src="img/pdf_to_word2.png" alt="pdf_to_word2"></td>
  </tr>
  <tr>
    <td><img src="img/rmbg.png" alt="nav"></td>
    <td><img src="img/youtube.png" alt="youtube"></td>
  </tr>
  <tr>
    <td><img src="img/emoji.png" alt="emoji"></td>
    <td><img src="img/emoji2.png" alt="emoji2"></td>
  </tr>
</table>

</center>



# 3. Jarvis

## Overview
Jarvis is a cutting-edge platform that integrates ChatGPT with domain-specific knowledge. By vectorizing vast amounts of domain knowledge, Jarvis allows users to utilize GPT in context with domain-specific information. Furthermore, with the power of fine-tuning, Jarvis offers a more customized GPT experience tailored to the specific needs of its users.

## Stack
- Domain Knowledge Utilization: `Langchain` / `Openai`
- Vectorestore / Database: `Redis`
- WSS server / API server: `Fastapi` / `Nginx`
- For Report: [Report Jupyter Notebook Repo](https://github.com/minkj1992/jupyter-notebook-docker-compose/tree/main)


## Features
1. **Domain Knowledge Integration**: Jarvis transforms extensive domain knowledge into vectorstore, enabling GPT to operate within a specific domain context.
2. **Customizable GPT**: Through fine-tuning, users can have a GPT experience that is more aligned with their specific requirements.
3. **Chatbot Service**: Designed with use-cases such as onboarding part-time staff for solo entrepreneurs and facilitating conversations with book authors.
4. **Report Generation**: Using the user's chat conversation history as input, Jarvis allows users to select a topic of interest. It then provides an in-depth report, analyzing the topic across 3-4 subtopics.

## Services

1. **Chatbot**: Ideal for scenarios like assisting self-employed individuals in onboarding part-time workers or enabling conversations with book authors.

2. **Report Writing**: Users can input their existing chat conversation history, and upon selecting a desired topic, Jarvis will generate a comprehensive report, breaking down the topic into 3-4 detailed subtopics.
<div align='center'>

<h4>1. Swagger</h4>
<table width="100%" border="0">
  <tr>
    <td><img src="img/swagger.png" alt="Swagger 1" width="300px"></td>
    <td><img src="img/swagger2.png" alt="Swagger 2" width="300px"></td>
  </tr>
</table>

<h4>2. Vectorstore redis</h4>
<table width="100%" border="0">
  <tr>
    <td><img src="img/redis-commander.png" alt="Redis Commander 1" height="200px"></td>
    <td><img src="img/redis-commander2.png" alt="Redis Commander 2" height="200px"></td>
  </tr>
</table>

<h4>3. Use case</h4>
<table width="100%" border="0">
  <tr>
    <td><img src="img/wss1.png" alt="Use Case 1" height="200px"></td>
    <td><img src="img/wss2.png" alt="Use Case 2" height="200px"></td>
    <td><img src="img/kakao.jpeg" alt="Kakao" height="200px"></td>
  </tr>
</table>

</div>
