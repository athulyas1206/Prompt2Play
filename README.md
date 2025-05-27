# 📖 Prompt2Play - From your prompt to playable story video

**Prompt2Play** is an AI-powered Gradio app that turns your text prompts into engaging children's stories, complete with illustrations and narration. It uses the power of Large Language Models (LLMs), Text-to-Speech (TTS), and image generation APIs to create narrated visual storybook videos.

---

## 🚀 Features

- ✍️ Generate original stories from custom prompts
- 🖼️ Create illustrations for each story scene using AI
- 🗣️ Narrate stories using realistic AI voice (Text-to-Speech)
- 🎞️ Combine everything into a video storybook
- 🧑‍🎓 Built for children, educators, and storytellers

---

## 🛠️ Tech Stack

LLM (Groq + Mixtral model): Generates a short story based on user input
LangChain: Orchestrates the AI pipeline and handles story segmentation
Stable Diffusion (Hugging Face): Generates images for each story scene
TTS (Google TTS): Converts story text into narration audio
MoviePy: Merges images and audio into a complete video
Gradio UI: Provides an interactive chatbot-like experience for users

---
## 📌 How to Use

> ⚠️ Run in **Google Colab** for best experience (GPU recommended)

### 📦 Steps

1. Upload the `.ipynb` to Google Colab
2. Run the cells in order
3. Enter your prompt in the Gradio app
4. Watch your custom illustrated story unfold!
