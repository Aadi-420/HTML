# My Professional Resume - Adarsh Asodiya

## What is This Project?

Hi! I'm **Adarsh Asodiya**, a Software Engineer-1. This repository contains my professional resume built with clean, semantic HTML5. I created this as part of my Cohort 2026 HTML assignment to showcase my skills, experience, and work in a structured and professional way.

## About the Resume File

- **File Name**: `index.html` (formerly resume.html)
- **Format**: HTML5 with semantic markup and accessibility features
- **What it includes**: My professional experience, technical skills, education, projects, and contact information
- **Live URL**: https://aadi-420.github.io/HTML/

When you visit that URL, you'll see my complete resume with interactive forms where you can contact me or rate my resume.

## My Resume Sections - What I Included

### 1. **Header** - Who Am I?
I started with my name, job title, company, and contact details. This section gives you my basic professional information so you can reach out if needed.

### 2. **About Me** - My Professional Philosophy
I wrote about myself as a **results-driven developer** who cares about:
- Writing clean, well-structured code
- Building applications that work across different platforms
- Using modern technologies like Angular, Node, and Electron
- Making things simple and accessible for users

I believe in hard work and making technology easy to use.

### 3. **Technical Skills** - What I Can Do
I organized my skills into four categories so you can quickly see what I'm good at:
- **Languages I know**: JavaScript, TypeScript, Swift
- **Frameworks & Tools I use**: Angular, Node, Electron
- **DevOps & Version Control**: Git/GitHub, Docker, Jenkins
- **Core Concepts**: Data Structures, Development practices, Problem Solving

### 4. **Work Experience** - My Career at Product Company
I've been with **Product Company** for about 3 years (2023 - Present) and progressed through these roles:
- **Trainee Software Engineer** (June 2023 - June 2024) - Started my career, learned technologies, wrote test cases
- **Associate Software Engineer** (June 2024 - June 2025) - Built features, delivered client requests, improved product stability
- **Software Engineer 1** (June 2025 - Present) - Contributing to desktop application development and DevOps practices and RnD

### 5. **Key Projects** - What I've Built
I've worked on two major projects:
- **aDrive**: A cloud sync engine (similar to OneDrive/Dropbox) for Org's CDE platform
- **Product CDE**: A collaborative platform that helps construction companies manage their projects and data in the cloud

### 6. **Education** - My Background
I graduated with a **B.E. in Information Technology** from **V.V.P. Engineering College** (2019-2023).

### 7. **Contact Section** - Let's Connect
I added an interactive form where visitors can:
- Send me their name, email, and message
- Get instant feedback with validation
- See a character counter for the message field

### 8. **Resume Rating Form** - What Do You Think?
I added a fun section where visitors can:
- Rate my resume from 1-5 stars
- Optionally leave feedback or suggestions
- Help me improve my presentation

## Why I Built This Resume This Way

### HTML Structure I Used
I focused on **semantic HTML5** because it's the right way to build websites:
- Proper heading hierarchy (h1 → h2 → h3) for better SEO and accessibility
- Semantic tags like `<header>`, `<main>`, `<section>`, `<footer>` to organize content
- Tables for actual tabular data (skills and experience)
- Forms with proper labels and fieldsets for user input

### Accessibility - Making It Usable for Everyone
I made sure my resume is accessible to people using screen readers:
- ARIA labels on form fields
- Proper label associations so screen readers understand what each input does
- Error messages that screen readers announce
- Keyboard navigation support

### Browser Compatibility
I ensured it works on all modern browsers:
- UTF-8 encoding for international characters
- Responsive viewport settings for mobile devices
- Table-based layout that's compatible everywhere
- Fixed 800px width for readable content

## How I Set Up This Project with Git

### Step 1: Created the Folder Structure
First, I created my project folders:
```bash
mkdir "Cohort 2026"
cd "Cohort 2026"
mkdir HTML
cd HTML
```
This organized everything in a Cohort 2026 folder with an HTML subfolder for the assignment.

### Step 2: Opened in VS Code
I opened the folder in Visual Studio Code so I could write and edit code:
```bash
code .
```

### Step 3: Initialized Git
I started version control for this project:
```bash
git init
```
This created a local git repository where I could track my changes.

### Step 4: Set Up Master Branch
I pushed the master branch to GitHub (my remote repository):
```bash
git push origin master
```
This created the master branch on GitHub as my main production branch.

### Step 5: Created Development Branch
I created a separate `dev` branch for development work:
```bash
git checkout -b dev
```
This way, I can work on new features in `dev` without affecting the master branch.

### Step 6: Pushed Dev Branch
I pushed the dev branch to GitHub:
```bash
git push origin dev
```
Now both branches exist on GitHub.

### Step 7: Built the Resume
I created `index.html` with my complete resume including:
- Professional information and contact details
- Technical skills and experience
- Interactive forms for contact and feedback

### Step 8: Added Files to Staging
When I was ready to save my work, I staged all changes:
```bash
git add .
```
This prepared my files for commit.

### Step 9: Made My First Commit
I committed my work with a clear message:
```bash
git commit -m "Initail HTML added for resume assignment"
```
This saved my changes to the local repository with a timestamp and message.

### Step 10: Pushed to GitHub
Finally, I pushed everything to GitHub:
```bash
git push
```
Now my code is safely backed up on GitHub and can be deployed.

### What My Repository Looks Like
```
Cohort 2026/
└── HTML/
    ├── .git/              (Git version control folder)
    ├── index.html         (My resume - now the main file)
    └── README.md          (This documentation file)
```

### My Git Branches
- **master**: The main/production branch - what users see
- **dev**: Development branch - where I work on improvements

---

## Deploying to GitHub Pages - Getting My Resume Online

I wanted to share my resume online, so I deployed it to **GitHub Pages** - GitHub's free hosting service. Here's how I did it:

### What is GitHub Pages?
GitHub Pages is a free service that lets you host static websites directly from your GitHub repository. Perfect for portfolios, resumes, and personal websites!

### How I Deployed My Resume

1. **Went to Repository Settings**
   - I opened my repository on GitHub
   - Clicked the **Settings** tab
   - Found the **Pages** option in the left sidebar

2. **Configured GitHub Pages**
   - Selected **Deploy from a branch**
   - Chose the **master** branch
   - Set the source to **/ (root)** folder
   - Clicked **Save**

3. **Waited for Deployment**
   - GitHub automatically built and deployed my site in 1-2 minutes
   - I saw a green checkmark when it was ready

4. **Got My Live URL**
   - My resume is now live at: **https://aadi-420.github.io/HTML/**
   - Anyone can visit this link to see my resume!

### Why I Renamed `resume.html` to `index.html`

When I first deployed, visiting `https://aadi-420.github.io/HTML/` gave a 404 error. Here's why:

- GitHub Pages automatically looks for `index.html` as the default page
- My file was named `resume.html`, so GitHub couldn't find a default file
- That's why it only worked when accessing the full filename

**The fix:** I renamed the file:
```bash
ren resume.html index.html
git add .
git commit -m "Rename resume.html to index.html for GitHub Pages default page"
git push origin dev
```

Now:
- ✅ `https://aadi-420.github.io/HTML/` works perfectly!
- ✅ `https://aadi-420.github.io/HTML/index.html` also works

### What Happens When I Make Updates

Now whenever I:
1. Make changes to `index.html`
2. Push to GitHub
3. GitHub automatically deploys the new version

My resume updates live in seconds!

### How to Access My Live Resume

You can view my complete resume with all sections and forms at:
- **Main URL**: https://aadi-420.github.io/HTML/
- **Direct File**: https://aadi-420.github.io/HTML/index.html

The resume includes:
- My professional experience
- Technical skills
- Education
- Contact form (so you can reach out!)
- Resume rating form (feedback welcome!)
- Links to my GitHub, LinkedIn, and Twitter

### Important Notes About GitHub Pages

- **HTTPS**: GitHub automatically provides secure HTTPS encryption
- **Free Hosting**: No cost at all!
- **Auto Deploy**: Changes push live automatically
- **Build Time**: Usually deploys within 1-2 minutes
- **Caching**: If changes don't show immediately, clear your browser cache

### Troubleshooting

| Problem | Solution |
|---------|----------|
| Still seeing 404 | Wait 2-3 minutes and clear browser cache |
| Old content showing | Hard refresh (Ctrl+Shift+R) your browser |
| Site looks broken | Check that `index.html` exists in the repo |

---

## How to Access This Resume

### Online (Live Version)
Visit my live resume at: **https://aadi-420.github.io/HTML/**

You can:
- Read my complete professional profile
- Fill out the contact form to reach me
- Rate my resume and leave feedback
- Click links to my GitHub, LinkedIn, and Twitter

### Locally (On Your Computer)
You can also:
- Clone this repository: `git clone https://github.com/Aadi-420/HTML.git`
- Open `index.html` in any web browser
- View the source code in VS Code or any text editor

## Social Links - Connect With Me

Want to connect? Here are my social profiles:
- **GitHub**: https://github.com/Aadi-420 (See all my projects)
- **LinkedIn**: https://www.linkedin.com/in/adarsh-a-649622226 (Professional profile)
- **Twitter**: https://x.com/adarshasodiya (Latest updates)

<img width="1919" height="685" alt="image" src="https://github.com/user-attachments/assets/57b10318-66e3-4f5b-bfb8-f26e14ebbe36" />
<img width="1919" height="855" alt="image" src="https://github.com/user-attachments/assets/347f7c3e-26a7-4f5e-93bd-21f529a68141" />
<img width="1919" height="509" alt="image" src="https://github.com/user-attachments/assets/592aa701-4e90-4f49-ac86-883e8ba4c917" />
<img width="1919" height="605" alt="image" src="https://github.com/user-attachments/assets/61e8145b-0764-4be8-9713-84b391816d1d" />





