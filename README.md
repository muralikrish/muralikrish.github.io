# 🌐 Muralikrishna Veeramosu - Personal Portfolio

[![Website Status](https://img.shields.io/website?url=https%3A%2F%2Fmuralikrish.github.io%2F&up_message=online&up_color=success)](https://muralikrish.github.io/)

Welcome to the repository for my personal portfolio! 

**👉 [View the live website here](https://muralikrish.github.io/)**

## 👨‍💻 About Me
I am a Principal iOS Engineer, AI/ML Practitioner, and a Top 1% Global Mentor on ADPList. With over 14 years of experience in mobile architecture, I am passionate about building scalable enterprise solutions, evaluating emerging technologies as a hackathon judge, and fostering the next generation of tech talent.

## 🛠 Built With
This portfolio is designed to be intentionally lightweight, fast, and fully responsive. It is built using:
* Semantic **HTML5**
* Custom **CSS3** (featuring CSS Grid and a modern, professional aesthetic)
* Hosted on **GitHub Pages**

## ✅ Checking Changes Before Merging

Every pull request targeting the `main` branch automatically runs a **PR Check** workflow that:

1. **Validates HTML** — Uses the [html5validator](https://github.com/svenkreiss/html5validator) (based on the W3C Nu HTML Checker) to ensure all HTML files are standards-compliant.
2. **Uploads a Preview Artifact** — Packages the site files into a downloadable artifact so reviewers can preview the changes locally.

### How to Preview a PR Locally

1. Open the pull request on GitHub.
2. Navigate to the **Checks** tab (or click *Details* next to the "Build Preview Artifact" check).
3. In the workflow run summary, download the **website-preview** artifact.
4. Unzip the downloaded archive and open `index.html` in your browser to see the changes.

### Local Development

To preview changes on your own machine before pushing:
```bash
# Clone the repo and switch to your branch
git clone https://github.com/muralikrish/muralikrish.github.io.git
cd muralikrish.github.io

# Open directly in your browser
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows

# Or use a local server for a more realistic preview
python3 -m http.server 8000
# Then visit http://localhost:8000 in your browser
```

## 📫 Let's Connect
* **Mentorship:** [Book a session on ADPList](https://adplist.org/mentors/muralikrishna-veeramosu)
* **LinkedIn:** [Connect with me](https://www.linkedin.com/in/muralikrishna-veeramosu-7ba94641/)
