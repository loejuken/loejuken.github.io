# Georgia Tech Electrical Engineering Portfolio — Joseph Luken

Welcome to the personal website repository for **Joseph Luken** (Georgia Institute of Technology, B.S. in Electrical Engineering, Planned Graduation: Spring 2029).

---

## 📁 Repository Structure (How your photo & resume are included)

This export package is pre-configured with everything in one clean folder:

```text
loejuken.github.io/
├── index.html            <-- Your complete website (references ./assets/profile.jpg & ./assets/resume.pdf)
├── .nojekyll             <-- Tells GitHub Pages to serve all files directly
├── README.md             <-- Documentation & instructions
├── portfolio-data.json   <-- Content backup
└── assets/
    ├── profile.jpg       <-- Your photo (already bundled in this repository!)
    └── resume.pdf        <-- Your resume PDF (already bundled in this repository!)
```

Because your photo and resume PDF are placed in the `assets/` folder inside this repository, they are hosted directly by GitHub Pages and will always display on your website without needing third-party hosting!

---

## 🚀 How to Host on GitHub Pages (Free, in 3 Minutes)

### Step 1: Create your GitHub repository
1. Go to [GitHub](https://github.com) and sign in to your account (`loejuken`).
2. Create a new public repository named:
   `loejuken.github.io`

### Step 2: Push these files
Open your terminal in this extracted folder and run:

```bash
git init
git add .
git commit -m "Deploy personal website with photo and resume"
git branch -M main
git remote add origin https://github.com/loejuken/loejuken.github.io.git
git push -u origin main
```

### Step 3: View your website live!
Visit:
👉 **https://loejuken.github.io**

*(Note: GitHub Pages takes about 1–2 minutes to build on your first push).*

---

## 🔄 How to Update Your Photo or Resume in the Future
- **To update your photo**: Simply overwrite `assets/profile.jpg` with your new photo and push to GitHub.
- **To update your resume**: Overwrite `assets/resume.pdf` with your new PDF and push to GitHub.
