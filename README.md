# ✦ WebForge AI

### Turn an idea into a website — with a single prompt.

WebForge AI is a generative-AI web development tool that transforms plain-English ideas into ready-to-preview websites.

Instead of starting with a blank HTML file, describe what you want:

> **“Build a modern portfolio website for an AI engineer with a dark theme, project section, skills, and contact form.”**

WebForge AI uses the **Gemini API** to turn that description into structured **HTML, CSS, and JavaScript**, then brings the result to life through an interactive preview.

---

## ⚡ What It Does

```text
        YOUR IDEA
           │
           ▼
   ┌─────────────────┐
   │   WebForge AI   │
   │  Prompt Engine  │
   └────────┬────────┘
            │
            ▼
      Gemini API
            │
            ▼
   ┌─────────────────┐
   │ HTML + CSS + JS │
   └────────┬────────┘
            │
            ▼
     Live Preview
            │
            ▼
      Export Website
```

### Core capabilities

* 🧠 **Natural-language website generation**
* ✨ **AI-generated HTML, CSS & JavaScript**
* 👀 **Live website preview**
* 📦 **Download generated source files**
* 🗜️ **Export the complete website as a ZIP**
* 🔐 **Environment-based API key configuration**
* 🖥️ **Simple browser-based interface**
* ⚙️ **Structured handling of AI-generated output**

---

## 🎯 Why WebForge AI?

Traditional website development usually starts with:

```text
Idea → Design → HTML → CSS → JavaScript → Debug → Preview
```

WebForge AI experiments with a different workflow:

```text
Idea → Prompt → AI → Website
```

The goal isn't to replace developers.

It's to **reduce the distance between an idea and a working prototype**.

---

## 🛠️ Tech Stack

| Technology       | Purpose                   |
| ---------------- | ------------------------- |
| 🐍 Python        | Application logic         |
| 🎈 Streamlit     | Interactive web interface |
| ✦ Gemini API     | Generative AI             |
| 🌐 HTML5         | Website structure         |
| 🎨 CSS3          | Styling & layout          |
| ⚡ JavaScript     | Website interactions      |
| 🔑 python-dotenv | Environment configuration |

---

## 📂 Project Structure

```text
WebForge-AI/
│
├── app.py                 # Streamlit application
├── generator.py           # Website generation logic
├── gemini_utils.py        # Gemini API utilities
├── requirements.txt       # Python dependencies
├── .env.example           # Environment variable template
│
├── generated_sites/       # Generated website output
├── templates/             # Website-related templates
│
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/WebForge-AI.git
cd WebForge-AI
```

### 2. Create a virtual environment

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### macOS / Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure the Gemini API

Create a `.env` file in the project root:

```env
GEMINI_API_KEY=your_api_key_here
```

**Never commit your real `.env` file or API key to GitHub.**

### 5. Launch WebForge AI

```bash
python -m streamlit run app.py
```

Open the local URL shown in your terminal, usually:

```text
http://localhost:8501
```

---

## 💡 Try These Prompts

### Portfolio

```text
Create a professional portfolio website for a
computer science student specializing in artificial intelligence.
Include a hero section, skills, projects, education,
and a contact section.
```

### Restaurant

```text
Create a modern restaurant website for an Italian
restaurant. Include a hero section, menu, about section,
gallery, customer reviews, and reservation button.
```

### Startup

```text
Create a SaaS landing page for an AI productivity platform.
Include pricing, features, testimonials, navigation,
and a strong call-to-action.
```

### Personal Website

```text
Build a minimal personal website for a software developer
with a clean layout, project showcase, skills section,
and contact form.
```

---

## 🧩 How the Application Works

### 01 — Describe

The user explains the website they want using natural language.

### 02 — Generate

The application sends the prompt to Gemini and requests structured website code.

### 03 — Assemble

The generated HTML, CSS, and JavaScript are separated and prepared for rendering.

### 04 — Preview

The website is displayed directly inside the application.

### 05 — Export

The generated files can be downloaded individually or packaged into a ZIP archive.

---

## 🔒 Security Note

API credentials should always remain outside version control.

Use:

```text
.env
```

for your local secret and:

```text
.env.example
```

for the repository template.

Example:

```env
GEMINI_API_KEY=your_gemini_api_key_here
```

Do not expose real API keys in source code, screenshots, commits, or README files.

---

## 🧪 Example Workflow

```text
"I need a portfolio for an AI student"
                 ↓
        WebForge AI processes prompt
                 ↓
             Gemini API
                 ↓
       ┌─────────┼─────────┐
       ↓         ↓         ↓
     HTML       CSS       JS
       └─────────┼─────────┘
                 ↓
          Website Preview
                 ↓
        Download / Export
```

---

## 🌱 Future Improvements

Some directions for extending the project:

* [ ] Multiple website design templates
* [ ] AI-powered prompt enhancement
* [ ] Regenerate individual website sections
* [ ] Editable generated code
* [ ] Website accessibility checks
* [ ] Responsive-design validation
* [ ] Image generation integration
* [ ] Component-level regeneration
* [ ] One-click deployment
* [ ] Website version history

---

## 👩‍💻 Built With

Built as a hands-on exploration of **Generative AI, prompt engineering, API integration, and AI-assisted web development**.

The project focuses on one simple question:

> **What if building the first version of a website started with describing it instead of coding it?**

---

## ⭐ Support

If you find the project interesting, consider giving the repository a ⭐.

Every star helps the project get noticed and motivates further development.

---

### 📜 License

This project is available under the license included in this repository.
