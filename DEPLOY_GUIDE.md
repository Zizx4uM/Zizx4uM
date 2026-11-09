# GitHub Profile README Deployment Guide

This directory contains your special **GitHub Profile README** that displays directly on your GitHub profile page (`https://github.com/Zizx4uM`).

## 🚀 How to Publish

1. **Create a special repository on GitHub**:
   - Repository name must exactly match your username: **`Zizx4uM`**
   - Set to **Public**
   - Check **"Add a README file"** (or leave it unchecked since we're pushing our own)

2. **Push this README from terminal**:
   ```bash
   cd /home/zaax/Projects/github-profile
   git init -b main
   git add README.md
   git commit -m "feat: design modern GitHub profile README"
   git remote add origin git@github.com:Zizx4uM/Zizx4uM.git
   git push -u origin main --force
   ```

3. Visit your profile at:
   👉 **https://github.com/Zizx4uM**
