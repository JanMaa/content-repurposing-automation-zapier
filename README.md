# 📌 Content Repurposing & Social Media Posting Automation  

This project automates the process of turning uploaded audio or video files into ready-to-publish blog posts and shares them on social media — only when the sentiment is positive. It saves time by handling transcription, content creation, sentiment analysis, and multi-platform posting in one streamlined workflow.  

---

## 🔄 **Workflow**  

### 🎯 Content Repurposing Workflow  
**Description:**  
This workflow transforms raw audio/video content into blog posts and distributes them to multiple social platforms, provided that the sentiment of the content is positive. This helps ensure only valuable and brand-safe content is shared.  

![Content Repurposing Workflow](content-repurposing-workflow.png)  

**Steps:**  
1. **Trigger (Google Drive):**  
   - Workflow starts when a new audio or video file is uploaded to a designated folder.  

2. **Transcription (OpenAI):**  
   - Transcribes the uploaded media into text.  

3. **Content Analysis (OpenAI):**  
   - Analyzes the transcript to identify key ideas, themes, or takeaways.  

4. **Image Generation (OpenAI):**  
   - Creates a relevant blog post image to accompany the content.  

5. **Blog Post Creation (OpenAI):**  
   - Generates a polished blog post draft based on the transcript and analysis.  

6. **Sentiment Analysis (OpenAI):**  
   - Evaluates whether the content is positive or negative.  

7. **Conditional Logic (Paths):**  
   - **If Positive:** Proceeds to social posting.  
   - **If Negative:** Stops the workflow to prevent publishing inappropriate content.  

8. **LinkedIn Post:**  
   - Publishes the generated blog post on LinkedIn.  

9. **Instagram for Business Post:**  
   - Shares the blog post (with generated image) on Instagram.  

10. **Facebook Pages Post:**  
   - Posts the content on connected Facebook Pages.  

---

## 📝 **How It Works Together**  

This automation takes a single piece of media and turns it into a complete multi-platform marketing deliverable — from transcript to publication — without requiring manual intervention. The sentiment check ensures quality control, keeping your brand reputation safe.  

---

## 💡 **Notes & Tips**  
- Ensure the Google Drive folder is exclusively for content meant for publishing to avoid accidental posting.  
- Customize the blog post prompt in OpenAI to match your brand voice.  
- Consider adding a step for human review for extra-sensitive content.  
- Monitor the Zapier Task History to confirm posts are only shared when sentiment is positive.
