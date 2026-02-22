# Jeffrey B. Appiagyei - Personal Website

Personal academic and professional portfolio. **Authored by Jeffrey B. Appiagyei.**

## Deploy to GitHub Pages (boakyejeff@gmail.com)

### Step 1: Create a new repo on GitHub

1. Open **Edge** (where you're logged into GitHub with boakyejeff@gmail.com).
2. Go to **https://github.com/new**
3. **Repository name:** `boakyejeff.github.io` (or your GitHub username + `.github.io`)
4. Choose **Public**, add a description if you like.
5. **Do NOT** check "Add a README" — leave it empty.
6. Click **Create repository**.

### Step 2: Push from your PC

Open PowerShell and run:

```powershell
cd "C:\Users\Thinkpad\Downloads\Personal website"
git init
git config user.email "boakyejeff@gmail.com"
git config user.name "Jeffrey Appiagyei"
git add .
git commit -m "Initial personal website - Authored by Jeffrey B. Appiagyei"
git branch -M main
git remote add origin https://github.com/boakyejeff/boakyejeff.github.io.git
git push -u origin main
```

*(Replace `boakyejeff` with your GitHub username if different.)*

### Step 3: Enable GitHub Pages

1. On the repo page: **Settings** → **Pages**
2. Under "Source": choose **Deploy from a branch**
3. Branch: **main**, folder: **/ (root)**
4. Click **Save**

Your site will be live at **https://boakyejeff.github.io** (or your username).

## Local Preview

```powershell
cd "C:\Users\Thinkpad\Downloads\Personal website"
npx serve .
```
