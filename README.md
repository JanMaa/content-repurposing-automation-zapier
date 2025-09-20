# Content Repurposing Automation - Zapier

This project automates the process of turning audio or video content into social media posts and blogs.

## Workflow Overview

![Content Repurposing Workflow](content-repurposing-workflow.png)

## How It Works

1. **Trigger** – When a new audio/video file is uploaded to Google Drive.
2. **Transcription** – The file is transcribed using OpenAI.
3. **Content Analysis** – The transcribed text is analyzed for key topics and structure.
4. **Image Generation** – A blog cover image is created using AI.
5. **Blog Post Creation** – AI generates a blog post from the content.
6. **Sentiment Analysis** – The text is analyzed to determine if the sentiment is positive or negative.
7. **Conditional Paths**:
   - **Positive Sentiment** → Post the content to LinkedIn, Instagram, and Facebook.
   - **Negative Sentiment** → Do not post.

## Platforms Used

- **Google Drive** – Source of uploaded files.
- **OpenAI** – Transcription, content analysis, image generation, blog writing, and sentiment analysis.
- **LinkedIn, Instagram, Facebook** – Content distribution channels.

---

This automation saves time by transforming raw video/audio into ready-to-publish content and posting it automatically when sentiment is positive.
