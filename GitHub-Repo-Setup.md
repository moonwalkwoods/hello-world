# GitHub Repository Setup Guide

This guide explains how to create a new GitHub repository under your `moonwalkwoods` account and push your local folder (`balconythoughts`) to it.

---

## Step 1: Create the Repository on GitHub

1. **Log In:** Sign in to your GitHub account.
2. **New Repository:** Click the **"+"** icon in the upper-right corner and select **New repository**.
3. **Repository Name:** Enter `balconythoughts` as the repository name.
4. **Repository Settings:** Choose whether to make it Public or Private and add a description if desired. **Do not** initialize the repository with a README since you already have local code.
5. **Create Repository:** Click **Create repository**.

---

## Step 2: Push Your Local Folder to GitHub

1. **Open Terminal:** Navigate to your local project folder.
   ```bash
   cd /path/to/your-folder
   ```

2. **Initialize Git** (if not already done):
   ```bash
   git init
   ```

3. **Add Your Files:**
   ```bash
   git add .
   ```

4. **Commit Your Changes:**
   ```bash
   git commit -m "Initial commit"
   ```

5. **Set the Default Branch** (if needed):
   ```bash
   git branch -M main
   ```

6. **Add the Remote Repository:**
   ```bash
   git remote add origin https://github.com/moonwalkwoods/balconythoughts.git
   ```

7. **Push to GitHub:**
   ```bash
   git push -u origin main
   ```
