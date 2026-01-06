**Automatically generate animated explainer videos from any topic using AI and Manim**

Transform text topics into professional educational videos with narration, animations, and visual diagrams - fully automated end-to-end pipeline.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_COLAB_LINK_HERE)

---

 
---

## 🎯 Overview

This system implements a **complete AI-driven video production pipeline** that:

1. **📝 Plans Content** - Breaks down any topic into subtopics with optimal word allocation
2. **🎙️ Generates Narration** - Creates natural educational scripts using LLaMA 3.1
3. **🎨 Designs Scenes** - Converts narration into visual scene descriptions
4. **🎬 Creates Animations** - Renders professional Manim animations from blueprints
5. **🔊 Adds Audio** - Synthesizes voice narration using Google TTS
6. **🎞️ Produces Video** - Assembles everything into a polished MP4

---

## ✨ Features

- ✅ **Fully Automated** - Topic → MP4 with zero manual intervention
- ✅ **AI-Powered** - Uses Groq's LLaMA 3.1 for intelligent content generation
- ✅ **Professional Animations** - Manim-based diagrams, arrows, and visual effects
- ✅ **Blueprint-Driven** - Interprets structured visual element descriptions
- ✅ **Flexible** - Handles any educational topic
- ✅ **Customizable** - Modify styles, timing, and visual elements

---

## 🏗️ Architecture
```
Topic Input
    ↓
┌─────────────────────────────────┐
│  1. Content Organizer (AI)      │ → Topic hierarchy + word allocation
└─────────────────────────────────┘
    ↓
┌─────────────────────────────────┐
│  2. Script Generator (AI)       │ → Narration scripts per topic
└─────────────────────────────────┘
    ↓
┌─────────────────────────────────┐
│  3. Scene Planner (AI)          │ → Scene-by-scene visual concepts
└─────────────────────────────────┘
    ↓
┌─────────────────────────────────┐
│  4. Blueprint Generator (AI)    │ → Visual elements + animations
└─────────────────────────────────┘
    ↓
┌─────────────────────────────────┐
│  5. Animation Renderer (Manim)  │ → MP4 scenes
└─────────────────────────────────┘
    ↓
┌─────────────────────────────────┐
│  6. Audio Synthesis (gTTS)      │ → MP3 narrations
└─────────────────────────────────┘
    ↓
┌─────────────────────────────────┐
│  7. Video Assembly (FFmpeg)     │ → Final MP4
└─────────────────────────────────┘