# AI-Powered Instagram Content Automation

Build once. Publish every day.

This AI automation workflow creates complete Instagram posts from a simple content idea. It generates AI-powered content, finds a matching image, designs the final post, and publishes it automatically to Instagram without any manual work.

Built with Make.com, Google Gemini, Pexels API, APITemplate, and Instagram for Business.

# Example Post

![Example Post](Screenshots/example-post.png.jpeg)

---

# Workflow

```text
Google Sheets
      │
      ▼
Google Gemini
      │
      ▼
Parse JSON
      │
      ▼
Pexels API
      │
      ▼
APITemplate
      │
      ▼
Instagram
```

---

# Workflow Screenshot

![Workflow](Screenshots/full-workflow.png.png)

---

# Modules Used

## Google Gemini

Generates the complete Instagram content, including the title, caption, hashtags, and image search query.

![Gemini](Screenshots/gemini.png)

---

## APITemplate

Creates the final Instagram post by combining the generated text with the selected background image.

![APITemplate](Screenshots/apitemplate.png)

---

## Instagram for Business

Publishes the generated post directly to Instagram.

![Instagram](Screenshots/instagram.png)

---

# Features

- Automatically reads content ideas from Google Sheets
- Generates AI-powered captions and hashtags
- Searches for matching images using the Pexels API
- Creates branded post images with APITemplate
- Publishes posts automatically to Instagram
- Uses JSON parsing and HTTP API integrations
- Built as a complete Make.com automation workflow

---

# Technologies Used

- Make.com
- Google Gemini
- Google Sheets
- Pexels API
- APITemplate.io
- Instagram for Business
- JSON
- HTTP

---

# Project Structure

```text
ai-instagram-content-automation
│
├── README.md
├── instagram-automation-blueprint.txt
└── Screenshots
    ├── apitemplate.png
    ├── example-post.png.jpeg
    ├── example-post.png - Copy.jpeg
    ├── full-workflow.png.png
    ├── gemini.png
    └── instagram.png
```

---

# What I Learned

While building this project, I practiced:

- Prompt engineering
- AI content generation
- API integration
- HTTP requests
- JSON parsing
- Image automation
- Instagram automation
- Building complete workflows in Make.com

---

# Blueprint

The Make.com blueprint used for this automation is included in this repository.

---

# Author

**Hassan Haider**

Feel free to explore the project or share your feedback.
