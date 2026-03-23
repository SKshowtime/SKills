# AI Skill Forge

A static web tool for creating, editing, previewing and managing CodeBuddy/WorkBuddy SKILL.md files.

## Deploy to GitHub Pages

1. Create a new GitHub repository
2. Push this `skill-hub` folder as the repo root:
   ```bash
   cd skill-hub
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin git@github.com:YOUR_USERNAME/skill-forge.git
   git push -u origin main
   ```
3. Go to **Settings > Pages** in your GitHub repo
4. Set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`
5. Your site will be live at `https://YOUR_USERNAME.github.io/skill-forge/`

## Features

- **Editor**: Visual form for skill metadata (name, description, trigger type, allowed-tools, context, etc.) + Markdown prompt editor
- **Preview**: Rich rendered preview & raw SKILL.md source view
- **Library**: Save skills to browser localStorage, search, edit, delete
- **Import/Export**: Import .md files or JSON backups, export individual .md or bulk .json
- **Zero dependencies**: Pure HTML/CSS/JS, no build step needed
