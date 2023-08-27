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
> Filekit, the ultimate toolkit for file and media processing. Designed to simplify complex tasks, FileKit provides a suite of tools for file conversion, image processing, media downloads, and more. With a global reach and a commitment to performance, FileKit is the go-to solution for users worldwide.

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


<center>


<table>
  <tr>
    <td><img width="393" alt="mobile1" src="https://github.com/filekit-co/.github/assets/37536298/82d0ed66-9772-4cb8-a00e-02019040bcaf"></td>
    <td><img width="385" alt="mobile2" src="https://github.com/filekit-co/.github/assets/37536298/14b0985f-8396-4113-8120-219ce94778dd"></td>
    <td><img width="386" alt="mobile3" src="https://github.com/filekit-co/.github/assets/37536298/8bac32ac-5284-4c5e-8460-a41a8b4cf601"></td>
    <td><img width="381" alt="mobile4" src="https://github.com/filekit-co/.github/assets/37536298/246297bd-2bdb-4ec3-b928-01882e2f53e5"></td>
  </tr>
</table>

</center>

## Stack

- Design: Tailwind css
- Framework: Svelte / Sveltekit
- Deploy: Vite / Cloudflare pages
- Image Process: [U<sup>2</sup>-Net(U square net)](https://github.com/xuebinqin/U-2-Net)
- Pdf Process: [PyMuPDF](https://pymupdf.readthedocs.io/en/latest/)
- Video Process: [ffmpeg](https://ffmpeg.org/)
- API Server: `fastapi`
- Cloud: `Google cloud run` / `Docker`


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
    <td><img width="1725" alt="anaylitics" src="https://github.com/filekit-co/.github/assets/37536298/98bf8921-3112-4922-9b3a-a9b1f9ffd689"></td>
    <td><img width="1723" alt="anaylitics2" src="https://github.com/filekit-co/.github/assets/37536298/f1b603de-5922-4973-ba4c-b9466fd36142">
</td>
  </tr>
  <tr>
    <td><img width="923" alt="anaylitics3" src="https://github.com/filekit-co/.github/assets/37536298/673f74d9-f6a4-42e9-aa07-8585f86fe80d"></td>
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

## 🚀 API Features
> FileKit API Server is a versatile tool designed to handle various file conversion and manipulation tasks. Built on top of the FastAPI framework, it offers a range of endpoints to cater to different file processing needs, from image background removal to PDF manipulations.

### Image Processing:

#### Background Removal:
- `POST /bg/remove`: Remove the background from an image sent within the request.
- `GET /bg/remove`: Remove the background from an image using a provided URL.
- `POST /images/convert`: Convert images to PNG format.

### File Conversion:

#### Document Conversion:
Convert between various formats like EPUB, PDF, DOC, DOCX, and XPS. Specific routes include:
- `/epub-to-doc`
- `/pdf-to-doc`
- `/xps-to-doc`
- `/epub-to-docx`
- `/pdf-to-docx`
- `/xps-to-docx`

#### PDF Conversion:
Convert different formats to PDF, including EPUB, XPS, OXPS, CBZ, and FB2. Specific routes include:
- `/xps-to-pdf`
- `/epub-to-pdf`
- `/oxps-to-pdf`
- `/cbz-to-pdf`
- `/fb2-to-pdf`

### Media Downloads:
- `POST /info`: Download target URL info.
- `POST /download/audio`: Download to audio format.
- `POST /download/video`: Download to video format.

### PDF Utilities:

#### Encryption & Decryption:
- `POST /pdf/encrypt`: Encrypt a PDF file.
- `POST /pdf/decrypt`: Decrypt a PDF file.

#### Watermark & Logo Addition:
- `POST /pdf/add-watermark`: Add a watermark to a PDF file.
- `POST /pdf/add-logo`: Add a logo to a PDF file.

#### PDF Manipulation:
- `POST /pdf/merge`: Merge multiple PDFs into one.
- `POST /pdf/split`: Split a PDF into multiple files.
- `POST /pdf/compress`: Compress a PDF file.


## Pages

<center>

<table>
  <tr>
    <td><img width="1536" alt="menu" src="https://github.com/filekit-co/.github/assets/37536298/53175a77-2336-4565-8d8f-2e0904eb5f6d"></td>
    <td><img width="1531" alt="main" src="https://github.com/filekit-co/.github/assets/37536298/e0e916b9-7f1f-4207-8bcf-34cce36fa33d"></td>
  </tr>
  <tr>
    <td><img width="1511" alt="pdf_to_word" src="https://github.com/filekit-co/.github/assets/37536298/a38a9f11-6f4c-4eb7-8e84-f01976751d21"></td>
    <td><img width="1508" alt="pdf_to_word2" src="https://github.com/filekit-co/.github/assets/37536298/db0f998c-77bf-4e1b-9bad-86ca400f8530"></td>
  </tr>
  <tr>
    <td><img width="756" alt="youtube" src="https://github.com/filekit-co/.github/assets/37536298/ebf73e25-24c9-428d-9609-7f94fe1b02d7"></td>
    <td><img width="856" alt="rmbg" src="https://github.com/filekit-co/.github/assets/37536298/2b11cca0-0442-4a78-ac3e-b1e295eb1763"></td>
  </tr>
  <tr>
    <td><img width="1530" alt="emoji" src="https://github.com/filekit-co/.github/assets/37536298/5ac03c3b-3012-422f-bedc-4effbfa538c5"></td>
    <td><img width="1532" alt="emoji2" src="https://github.com/filekit-co/.github/assets/37536298/7fca9e5f-7715-4de8-9a05-58481d85ede0"></td>
  </tr>
</table>

</center>

# 3. Jarvis

## Overview
Jarvis is a cutting-edge platform that integrates ChatGPT with domain-specific knowledge. By vectorizing vast amounts of domain knowledge, Jarvis allows users to utilize GPT in context with domain-specific information. Furthermore, with the power of fine-tuning, Jarvis offers a more customized GPT experience tailored to the specific needs of its users.


<table width="100%" border="0">
  <tr>
    <td><img src="https://github.com/filekit-co/.github/assets/37536298/3c73a4fe-bb92-4c00-917d-c05674b7c894" width="300px" /></td>
    <td><img src="https://github.com/filekit-co/.github/assets/37536298/53417b16-4623-45a1-a07f-ed49ed6893e9" width="300px" /></td>
  </tr>
</table>

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

## Pages

<h4>Vectorstore redis</h4>
<table width="100%" border="0">
  <tr>
    <td><img alt="redis-commander" src="https://github.com/filekit-co/.github/assets/37536298/f3b53ceb-3ed1-4c74-97fc-a364bb08a9ce"></td>
    <td><img alt="redis-commander2" src="https://github.com/filekit-co/.github/assets/37536298/345a080c-35bd-4b17-ae6e-39d29edd0f9f"></td>
  </tr>
</table>

<h4>Use case</h4>
<table width="100%" border="0">
  <tr>
    <td><img src="https://github.com/filekit-co/.github/assets/37536298/949d4545-01c4-498e-a276-1cfb7b738522" alt="Use Case 1"></td>
    <td><img src="https://github.com/filekit-co/.github/assets/37536298/deaa7fb7-b34f-4513-b7ec-f09b00b7acc2" alt="Use Case 2"></td>
    <td><img src="https://github.com/filekit-co/.github/assets/37536298/892c8e9e-f613-49ea-bfc5-56e152f03b08" alt="Kakao"></td>
  </tr>
</table>

</div>
