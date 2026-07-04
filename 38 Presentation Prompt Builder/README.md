# 📸 Instagram Prompt Generator

A modern, responsive **Instagram Content & Prompt Generator** built with **HTML, CSS, and JavaScript**. The application allows users to create high-quality Instagram content prompts and preview the generated output in a beautiful Instagram-inspired interface.

Designed and developed by **Hamna Munir** and **Mirza Yasir Abdullah Baig**.

---

# ✨ Features

* 🎯 Generate Instagram content from a simple topic
* 📝 Supports multiple content formats:

  * Caption
  * Reel Script
  * Story Ideas
  * Carousel
* 🎨 Multiple writing tones:

  * Friendly
  * Aesthetic
  * Motivational
  * Viral
  * Funny
* 🌍 Multi-language support

  * English
  * Urdu
  * Roman Urdu
  * Hinglish
* 👥 Target audience customization
* 📂 Niche-specific content generation
* 💡 Extra instruction support
* 📋 One-click copy to clipboard
* 🕘 Content history
* 👀 Live Instagram-style preview
* ⚡ Smart offline fallback generator when API is unavailable
* 📄 View the exact AI prompt used for generation

---

# 📸 User Interface

The application consists of two main panels.

## Left Panel

Input all content details:

* Post Topic
* Niche / Theme
* Target Audience
* Language
* Content Type
* Tone
* Extra Instructions

Buttons:

* ✦ Generate Content
* Clear

---

## Right Panel

Contains three tabs:

### Preview

Displays the generated Instagram content including:

* Hook
* Main Content
* Call-to-Action
* Hashtags

in an Instagram-inspired layout.

### Prompt

Shows the exact prompt sent to the AI model.

### History

Stores up to the last **10 generated posts** for quick access.

---

# 🚀 Content Types

The generator supports:

* 📝 Instagram Caption
* 🎬 Reel Script
* 📱 Story Ideas
* 🖼 Carousel Post

Each content type is generated using a different prompt structure.

---

# 🎭 Available Tones

* Friendly
* Aesthetic
* Motivational
* Viral
* Funny

The selected tone affects:

* Hook
* Writing style
* CTA
* Overall personality

---

# 🌐 Language Support

Choose between:

* English
* Urdu
* Roman Urdu
* Hinglish

---

# 🧠 Smart Fallback System

If the Claude API is unavailable, the application automatically switches to its built-in intelligent generator.

The fallback system creates:

* Hooks
* Captions
* Reel scripts
* Story ideas
* Carousel slides
* CTAs
* Hashtags

without requiring any API connection.

---

# 📋 Generated Output

Each generated post includes:

* Attention-grabbing Hook
* Main Content
* Call-to-Action (CTA)
* Relevant Hashtags

The content is also available as plain text for easy copying.

---

# 📂 Project Structure

```text
Instagram-Prompt-Generator/
│
├── index.html
├── README.md
```

The project is fully contained within a single HTML file using:

* HTML
* CSS
* Vanilla JavaScript

No external frameworks are required.

---

# 🎨 Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript
* Google Fonts
* Fetch API
* Anthropic Claude API (optional)

---

# ⚙️ How It Works

1. Enter your post topic.
2. Fill in optional information such as niche and audience.
3. Select the content type.
4. Choose a writing tone.
5. Click **Generate Content**.
6. The application:

   * Builds an AI prompt.
   * Attempts to generate content using Claude.
   * Falls back to the built-in generator if the API is unavailable.
7. View the formatted preview.
8. Copy the content or revisit it from the History tab.

---

# 🔌 Claude API Integration

The application attempts to generate content using the Anthropic Messages API.

If the API request fails or is unavailable, the application seamlessly switches to the built-in smart generator, ensuring uninterrupted functionality.

---

# 📱 Responsive Design

The interface includes:

* Responsive layout
* Scrollable panels
* Modern purple-themed design
* Interactive buttons
* Toast notifications
* Loading skeletons
* Live generation status

---

# 📄 License

This project is intended for educational, demonstration, and personal use.

---

# 👨‍💻 Developers

**Hamna Munir**

**Mirza Yasir Abdullah Baig**

---

# ⭐ Future Improvements

* Image prompt generation
* AI hashtag optimization
* Multiple caption variations
* Emoji customization
* Scheduling support
* Export to PDF
* Dark mode
* Save projects locally
* Instagram API integration
* AI image generation support

---

## 💜 Enjoy Creating Instagram Content!

Create engaging captions, reels, stories, and carousel posts with a clean, modern interface and intelligent content generation.
