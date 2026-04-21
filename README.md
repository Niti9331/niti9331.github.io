# niti9331.github.io

# DevOps Git Project – Portfolio Website Deployment

📌 Project Objective  
To build and deploy a personal portfolio website using Git and GitHub Pages while practicing real-world Git workflows, error handling, and repository management.

🛠️ Step-by-Step Workflow  
1. Initialize Repository  
Created project folder locally, created `index.html`, initialized Git using `git init`, and made the first commit.

2. Connect to GitHub  
Created remote repository on GitHub, linked local repo using `git remote add origin <repo-url>`, and attempted to push code to main branch.

3. GitHub Pages Setup  
Pushed code to GitHub repository and enabled GitHub Pages from settings. Final live website deployed at: https://niti9331.github.io

❗ Errors Faced & Fixes  
🔴 Error 1: VS Code command not found (`code`)  
Cause: VS Code CLI not installed in PATH  
Fix: Installed “Shell Command: Install 'code' command in PATH” from VS Code Command Palette  

🔴 Error 2: Not a git repository  
Error: `fatal: not a git repository (or any of the parent directories): .git`  
Cause: Git not initialized  
Fix: `git init`  

🔴 Error 3: Push rejected (fetch first)  
Error: `! [rejected] main -> main (fetch first)`  
Cause: Remote repository already had commits  
Fix: `git pull origin main --rebase` then `git push origin main`  

🔴 Error 4: Divergent branches  
Cause: Local and remote history mismatch  
Fix: `git pull origin main --no-rebase`  

🔴 Error 5: Push rejected after remote update  
Cause: Remote updated after changes  
Fix: `git pull origin main` then `git push origin main`  

🧠 Key Learnings  
Git repository setup, remote linking, resolving push conflicts, handling divergent branches, using pull/rebase strategies, and deploying static websites via GitHub Pages.

🚀 Final Outcome  
Successfully created a portfolio website, managed version control using Git, resolved all Git errors, and deployed a live website using GitHub Pages.
