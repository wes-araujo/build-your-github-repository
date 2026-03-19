<!-- Language Navigation -->
<p align="right">
  Read in: 
  <a href="README.en.md">🇺🇸 English</a> | 
  <a href="README.es.md">🇪🇸 Español</a> | 
  <a href="README.md">🇧🇷 Portuguese</a>
</p>

# 🚀 build-your-github-repository

<!-- Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/Audience-Beginners-brightgreen?style=for-the-badge" alt="Audience: Beginners">
  <img src="https://img.shields.io/badge/Status-In%20Development-yellow?style=for-the-badge" alt="Status: In Development">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="MIT License">
</p>

## 📖 About the Project
The README file is often the first thing a visitor or recruiter will see in your repository. It acts as the "virtual storefront" or "gateway" to your code.

The build-your-github-repository project is an interactive guide, created with the support of NotebookLM, that aims to teach developers how to set up repositories from scratch and document projects with excellence. A good README should quickly answer what the project does, why it is useful, and how people can use it.

## 🎯 Why this Guide Exists
We know that starting out in the tech field is full of challenges. Creating repositories and writing good READMEs don't have to be one of them.

This guide was created so you don't waste time searching for scattered tutorials or long videos on platforms. The effectiveness of a project is often measured by its ability to communicate its value in the first ten seconds of reading. Therefore, our focus is to provide a direct and interactive tool for you to get your hands dirty immediately.

## ✨ What You Will Learn
* **GitHub Fundamentals:** The core practices for creating, editing, and deleting a repository correctly.
* **README Structuring:** What to include to make your documentation scannable, clear, and professional.
* **Accessibility and SEO:** How to use alternative texts for images (Alt text), correct heading hierarchy, and optimization for GitHub's internal search.
* **Visual Elements:** The importance of integrating badges, demo GIFs, and tables to facilitate understanding.

## 📚 Guide Structure
The content of this repository was structured with the real learning needs of beginners in mind:

* **Initial Tutorials:** Guided steps so you can get your first results quickly on GitHub.
* **"How-To" Guides:** Solutions for specific and punctual problems regarding repository management.
* **Explanations and Best Practices:** The reasons why the open-source community prefers certain approaches.

## 🤖 Prompt Engineering

In this section, I document the actual prompts used to plan and build the documentation for this repository, along with my analysis of the results obtained with NotebookLM. The quality of an Artificial Intelligence's responses depends directly on the context and intent of our instructions.

### 1. Repository Creation and Structuring

*   **Prompt Used:**
    > *"Help me create a GitHub repository for this Notebook!"*

*   **🎯 Result:** 
    The AI's response was excellent right on the first try. It structured the explanation into two clear steps: 
    1. Creating the repository via the website (with best practice tips for naming, visibility, and the importance of the README and `.gitignore` files).
    2. How to upload the file, offering two options: a visual one for beginners (direct upload via browser) and a professional one (via command line / terminal using `git init`, `git add`, `git commit`, etc.).

*   **💡 Analysis and Learning:** 
    The main lesson from this prompt was the power of **context**. Even though it was a short and direct instruction, specifying the base material ("for this Notebook") made the AI personalize the entire response to my scenario. It abandoned generic explanations and delivered a workflow perfectly aligned with what I needed. This proves that, by knowing how to contextualize the tool, there is no need to create complex prompts to obtain high-level results.

---

### 2. README Creation with Purpose and User Focus

*   **Prompt Used:**
    > *"Now I need to create a README for this repository. I created this Notebook because for those starting in the tech field, I know they face many challenges throughout their studies and creating repositories and READMEs is one of them... my intention is to have a more interactive guide so you don't have to spend more time than you should looking for a really good video..."*

*   **🎯 Result:** 
    Instead of returning a generic template, the AI delivered a complete structure based on market best practices. It explained that the README is the "storefront" of the project and acts as your main marketing material. Besides the template itself, the tool taught me crucial concepts, such as the "10-second rule" for visitor retention, the importance of scannability, and left extra tips for the future: adding visual resources (like banners and GIFs to demonstrate the tool) and using emojis in titles to make reading friendlier.

*   **💡 Analysis and Learning:** 
    The great differentiator of this prompt was sharing my real motivation, the user's pain point (difficulty in finding direct tutorials), and the target audience (beginners). By providing this deep level of intent, the AI stopped being just a "text generator" and started acting as a true consultant. The lesson here is that detailing the *why* you are building the project absurdly elevates the quality of the response, generating content that is much more empathetic, strategic, and aligned with the Open Source community culture.

---

## ♻️ Reusable Prompts (Copy and Paste)

Do you want to create your own project, but don't know how to ask Artificial Intelligence for help? 

Below, I provide the Prompt Engineering templates that I created and improved during this guide. You can copy them, fill in the bracketed areas with your project's context, and paste them into [NotebookLM](https://notebooklm.google.com/notebook/ac8eb143-f2b9-41e5-8421-70d1201df31a) to get professional results!

### 1. To structure your Repository from Scratch
Use this prompt to transform loose notes or ideas into a real repository structure:

> "Act as a Senior Software Engineer. Help me create a GitHub repository for this **[INSERT YOUR BASE MATERIAL, e.g., Notes notebook, project script]**! I want the focus to be **[YOUR GOAL, e.g., helping beginners, serving as a portfolio]**. List which essential files I cannot forget to include, such as the `.gitignore` and the License."

---

### 2. To create a README focused on User Experience (UX)
Use this prompt to create empathetic documentation aimed at solving the reader's pain point:

> "Now I need to create a README for this repository. I created this project because I know that **[INSERT YOUR TARGET AUDIENCE, e.g., those starting in the tech field]** face many challenges such as **[INSERT AUDIENCE'S PAIN POINT, e.g., the difficulty in creating professional repositories]**. My intention is to have an interactive guide. Create a professional README structure based on the rule of capturing the reader's attention in the first 10 seconds, using emojis, badges, and clear sections."

### 3. To master Terminal / Git commands
If you have trouble memorizing commands, use this prompt to have the AI give you a guided tutorial without complex jargon:

> "Act as a Programming Teacher with excellent teaching skills. Create a practical step-by-step guide on how to initialize and push my first project to GitHub through the **[INSERT TERMINAL NAME, e.g., Git Bash, Zsh, CMD]** terminal. Instead of just giving me the codes, explain in a simple and friendly way *why* I need to use each command (such as `git init`, `git add .`, and `git commit`), keeping in mind that I am a beginner in the field."

---

### 4. To understand the Recruiters' perspective (Portfolio)
Use this prompt to transform your ordinary project into a magnet for professional opportunities:

> "Act as a Tech Recruiter specialized in hiring junior developers. Explain to me directly why having a well-structured GitHub repository helps me stand out in selection processes. List **[INSERT NUMBER, e.g., 3 to 5]** visual or technical elements (like folder organization, README quality, and good commit messages) that recruiters evaluate first when opening my profile. Give practical tips on how to apply this to my project focused on **[INSERT YOUR PROJECT THEME]**."

---

## 🧪 Difficulties and Learnings (Troubleshooting)

During the construction of this guide and the creation of my first repositories, I faced some real challenges. I document them below to demonstrate my problem-solving process and, perhaps, help other beginners who might go through the same situation:

### 🚨 Problem 1: Difficulty with Prompt clarity with the AI
* **What happened:** At certain moments when using NotebookLM, I had difficulty expressing exactly the idea I wanted for the final result. The tool generated good responses, but they still didn't reach the complete vision I had in mind.
* **How I solved it (Learning):** I realized the error was not with the tool, but with how I sent the instructions. The solution was to open a notepad, write down everything I wanted, and break the idea down much more clearly. After sending this fragmented idea and ensuring the AI understood the actual scope, I asked it to generate a **checklist**. This allowed me to execute it step by step with focus, ensuring no detail was overlooked.

### 🚨 Problem 2: Markdown formatting breaks
* **What happened:** After obtaining the base README structure from the AI, I decided to make my own manual changes and additions. The goal was to customize the document without relying 100% on NotebookLM, so as not to lose focus on our main conversation. However, while making these edits, I ended up breaking the file's formatting, causing visual misalignments.
* **How I solved it (Learning):** Instead of asking the AI to fix it, I decided to do the troubleshooting manually. Since Markdown is very similar to and accepts HTML syntax (like `<br>`, `<div>`, `<p>` tags, etc.), I used my web markup knowledge base to read the code, find the unclosed tags, and fix the line breaks. In the end, I managed to structure the README exactly the way I wanted, gaining much more autonomy with the language.

---

## 📖 Glossary for Beginners

If you are taking your first steps in the programming world, some terms might seem confusing. Here is a quick translation/explanation of the most used words in this guide and in daily life with GitHub:

*   **Repository (Repo):** It is the main folder of your project. It is the place where all your code, files, and the history of changes are stored. It can be local (on your computer) or remote (in the GitHub cloud).
*   **Branch:** It is a parallel version of your code. It allows you to work on a new feature without changing or breaking the project's main code.
*   **Clone:** It is the act of downloading a complete copy of a GitHub repository to your computer, including the entire version history.
*   **Push:** It is the command used to send your local commits (from your computer) to the remote repository (on GitHub).
*   **Pull:** It is the command used to bring the changes that are on GitHub to your local computer, keeping everything updated.
*   **Fork:** It is an exact copy of someone else's repository into your GitHub account. This allows you to freely make changes to third-party projects without affecting the original project.
*   **Pull Request (PR):** After making changes in a *Branch* or *Fork*, you open a PR to request that the project owner review your code and merge it into the main project.
*   **Markdown (.md):** It is a lightweight markup language used to format text on the web. It is what we use to make text bold, create lists, and add images to the README file!

## 🛠 Repository Best Practices

To make your project stand out and catch the attention of recruiters and the community, I applied essential documentation and version control practices.

### 📄 README Best Practices
The README is your primary technical marketing material. To create a high-impact document:

*   **Be Concise and Scannable:** Avoid very long blocks of text ("walls of text"). If a section gets too long, divide it into subheadings to facilitate dynamic reading.
*   **Incorporate Images and GIFs:** The human brain processes images faster than text. Show how your application or guide works using GIFs or screenshots.
*   **Use Badges:** Badges convey immediate trust about the project status, license, and tools used.
*   **Accessibility First:** Add descriptive alternative text (Alt text) to all images and GIFs to support screen readers and promote inclusion.

---

### 💡 Commit Best Practices
A commit acts as a "save point" for your project. To keep the history readable and professional, it is highly recommended to follow the **Conventional Commits** standard, which makes reading easier for both humans and automations.

The ideal structure of a commit message should be short, direct, and preferably in the present or imperative tense (e.g., "Create page" instead of "Created page"). The most used categories are:

*   **`feat:` (Feature):** Used when you add a new feature to the project (e.g., `feat: add login button`).
*   **`fix:`** Used when you fix a bug or error in the application (e.g., `fix: correct cart calculation`).
*   **`docs:`** Used for exclusive changes to the documentation, such as the README file (e.g., `docs: update installation section`).
*   **`chore:`** Maintenance or configuration tasks that do not alter the user code (e.g., `chore: update project dependencies`).

---

### 📂 Repository Structure
The physical structure of your repository directly reflects the project's level of professionalism. In this guide, we use the following common organization in software development:

```text
📁 build-your-github-repository/
├── 📄 README.md              # Main documentation
├── 📄 CONTRIBUTING.md        # Contributing guidelines
├── 📄 LICENSE                # License file
├── 📁 docs/                  # Extended guides, articles, and tutorials
├── 📁 assets/                # Project images, logos, and GIFs
└── 📁 templates/             # Ready-to-use README templates
```

### 💡 How to Use Our Profile Templates

Did you know that GitHub has a "secret" feature? If you create a repository with the exact same name as your username, its `README.md` file will be prominently displayed on your GitHub home page. It's the perfect opportunity to create an amazing portfolio and stand out to recruiters and other developers!

To make your journey easier, we've provided ready-to-use templates for you to copy and use:

*   **Navigate to our `/templates` folder** here in this repository.
*   **Choose your favorite template:** You will find options ranging from a more basic profile (focused on technologies and contacts) to an advanced profile (with animations and GitHub statistics).
*   **Copy all the code** from the chosen `.md` file.
*   **Create your special repository:** In the top menu of GitHub, click on the `+` and then on **New repository**. Give the repository exactly your username, make sure it is set to **Public**, and check the **Add a README file** box.
*   **Paste and edit:** Open the `README.md` file that was created in your new repository by clicking the pencil icon. Delete the original text, paste the code you copied from our templates, and replace the generic information (such as `YOUR_NAME`, `YOUR_USERNAME`, or links) with your actual data.
*   **Save (Commit):** Scroll to the bottom of the page and click **Commit changes** to save. Visit your profile and see the magic happen!

---

## 📚 Sources Used

The construction of this guide didn't come out of nowhere; it was based on a careful curation of official materials, community articles, and practical tutorials. Below are the main sources that grounded the concepts presented in this repository:

### 📝 Documentation and Articles (Text)

*   **About repositories - GitHub Docs**
    *   **Why I used it:** Official documentation is always the source of truth. I used this material to ground the fundamental concepts of what a repository is, visibility (public vs. private), and management best practices.
*   **Creating a remote repository on GitHub - Alura**
    *   **Why I used it:** This article is essential for understanding how to send data from a local repository to a remote one via command line in a practical way.
*   **How to create a good README.md? - DIO (by Nicole Arruda)**
    *   **Why I used it:** This article served as the foundation for structuring our template, detailing the importance of crucial topics such as feature scope, technologies used, and instructions on how to run the project.
 
### 🎥 Tutorials and Classes (Video)

*   **Primeiro repositório git e GitHub - Gustavo Guanabara (Curso em Vídeo)**
    *   **Why I used it:** Professor Guanabara has impeccable teaching skills for beginners. I used this class as a reference on how to explain the creation of local and remote repositories in a friendly and uncomplicated way.
*   **COMO CRIAR SEU PRIMEIRO PROJETO NO GITHUB - Dev em Dobro**
    *   **Why I used it:** This video was chosen because it presents, in practice, two approaches to pushing a project to GitHub: a faster and more visual method (uploading files directly on the website) and the professional method using Git commands in the terminal.
*   **COMO CRIAR SEUS READMEs? GUIA DO README COMPLETO - Fernanda Kipper**
    *   **Why I used it:** Excellent material focused on the "first impression" a portfolio makes. The formatting tips with badges and the visual structure of this repository were highly inspired by the examples provided by Kipper.
*   **Como personalizar o seu perfil no Github (Readme) - Rafaella Ballerini**
    *   **Why I used it:** I chose this material because it teaches step-by-step how to create the "secret" profile repository with the exact same username, besides showing how to enrich the file with dynamic visual elements in Markdown, such as social media icons, GitHub usage statistics, and animated GIFs.

---

## 🔗 Resources
Useful tools to help build your next READMEs:
*   **Shields.io:** To generate custom badges.
*   **Devicon:** Library with icons and logos of technologies and programming languages.
*   **Emoji Cheat Sheet:** Quick codes to insert GitHub emojis into your documentation.

---

## 🤝 Contributing
This is a project built for the community. All help is very welcome! To learn how to contribute by submitting new templates, fixing errors, or translating content, please read our `CONTRIBUTING.md` file. In it, we detail the steps to make a Fork, follow our commit standards, and submit your Pull Request.

---

## 📝 License
The absence of a license is a legal impediment to software adoption. This project is protected and distributed under the MIT license. This means it is free for use, modification, and distribution, whether commercial or not. See the `LICENSE` file for details.

---
<p align="center">
  Made with 💙 to facilitate your journey in technology!
</p>
