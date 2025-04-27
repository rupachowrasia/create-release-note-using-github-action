# GitHub's Auto-Generated Release Notes

> This flows show how to automatically generate release notes from your GitHub commits when you create a release — without writing them manually every time!

## 🚀 What it will do?

- Whenever you push a tag like v1.1.0 to GitHub
- It will automatically create a Release
- It will auto-generate release notes based on commit messages and PR titles


## 🛠 Tech Stack

- Node.js
- Express

## 🎯 How you use it in your project
- Add the workflow under .github/workflows/release.yml (code is in github, can copy that)
- Push a new Git tag
```bash
git tag v1.1.0
git push origin v1.1.0
```
(You can change v1.1.0 to whatever your new version is)
- GitHub will automatically create a new Release with auto-generated notes!

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/rupachowrasia/github-release-note-template.git

# Move into the project directory
cd github-release-note-template

# Install dependencies
npm install

# Run the app
npm run start

# Run the following, it should trigger the workflow
git commit -am "chore: prepare sample release v1.1.0" \
&& git tag v1.1.0 \
&& git push origin main --tags
```

## 🧭 How to view Releases in your GitHub repository
- Go to your GitHub Repository (example: https://github.com/your-username/your-repo-name/releases)

## 📢 Tips
- **Manual/Draft Release:** You can manually create a draft release even without pushing a tag!
- **Auto Release:** If using GitHub Action like we set, it will auto-create a Release when you push a new tag!

