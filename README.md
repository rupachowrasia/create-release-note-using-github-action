# GitHub's Auto-Generated Release Notes

> This flows show how to automatically generate release notes from your GitHub commits when you create a release — without writing them manually every time!

## 🚀 What it will do?

- ✨ Whenever you push a tag like v1.1.0 to GitHub
- ⚡ It will automatically create a Release
- 🔒 It will auto-generate release notes based on commit messages and PR titles


## 🛠 Tech Stack

- Node.js
- Express

## 🎯 How you use it in your project
- Add this workflow under .github/workflows/release.yml
- Push a new Git tag
git tag v1.1.0
git push origin v1.1.0
(You can change v1.1.0 to whatever your new version is.)
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
