# Redbird Robotics: New Member Guide

Welcome to Redbird Robotics! This guide walks you through your **first day with GitHub**, so you can start contributing to projects safely and efficiently. No prior experience is required.

---

## 1. GitHub Account & GitHub Desktop

If you haven’t already:

1. [Create a GitHub account](https://github.com) using your university email.  
2. [Install GitHub Desktop](https://desktop.github.com) and sign in.  
3. Verify your name and email in **File → Options → Git**.  

> GitHub Desktop is recommended for beginners. Only advanced users need Git Bash.

---

## 2. Clone a Repository

1. Your team lead will provide the repo URL (e.g., `https://github.com/redbird-robotics/project.git`).  
2. In GitHub Desktop:  
   - Click **File → Clone Repository → URL**  
   - Paste the URL  
   - Choose a local folder (e.g., `C:\Redbird`)  
   - Click **Clone**  

3. Verify the files are on your computer. You should see folders like `/CAD`, `/code`, `/PCB`.

---

## 3. Set Up Your Software

visit [this site](https://cardmaillouisville.sharepoint.com/sites/SpeedStudentBundle/SitePages/Software.aspx) to access all software provided to students at Speed School.
- **CAD**: Our teams tend to use SolidWorks.
- **PCB**: Likely unneeded for beginners, speak with your team lead about specific software preferred.
- **Code**: Install Arduino IDE if your work involves arduino, or other code editors such as VSCode.

> Make sure the software can open the project files in your cloned repo.

---

## 4. Branching

`Main` should be reserved for working prototypes, demos, finished projects, etc. As such, it is important to do your work on **branches** to ensure safe work (without fear of overwriting progress, missing work, etc). There are two ways to branch:

### If you are joining someone else's work, or joining a ready branch:
1. In GitHub Desktop: hit the **"Current Branch:"** button, and switch to the branch you wish to work on.
2. If you have unsaved changes, you will be prompted to push or discard your current work first.

### If you are creating a new branch to work on a new piece of a project:

1. In GitHub Desktop: **Branch → New Branch**  
2. Name it descriptively (e.g., `claw-assembly`, `motor-driver`)  
3. Click **Create Branch**

---

## 5. Making Your First Change

- **For CAD**:  
  1. Open the part or subassembly you’re assigned (`claw.SLDPRT`, `chassis.SLDPRT`, etc.).  
  2. Make edits (geometry, mates, constraints).  
  3. Save the file — **do not edit the top-level assembly yet** unless instructed.  

- **For Code**:  
  1. Open the `.ino` or other code file in ArduinoIDE or your preferred editor.  
  2. Make a small change (e.g., add a comment or tweak a parameter).  
  3. Save your work.

---

## 6. Committing Your Changes

1. In GitHub Desktop, you should see the files you modified under **Changes**.  
2. Write a **clear, descriptive commit message**, e.g.,:  
   - `Fixed claw joint alignment`  
   - `Updated motor driver parameters`  
3. Click **Commit to branch-name**

> Commits are snapshots of your work — commit often!

---

## 7. Pushing to GitHub

1. Click **Push origin** in GitHub Desktop.  
2. Your branch is now on GitHub and ready for a Pull Request (PR).  

---

## 8. Creating a Pull Request (PR)

1. Go to the GitHub repo in your browser.  
2. GitHub will usually prompt you to create a PR for your recently pushed branch.  
3. Click **Compare & pull request**  
4. Add a description of your changes.  
5. Submit the PR.  

> Team leads will review your PR before merging into `main`.

---

## 9. Pulling Updates

Before starting work each day:

1. Switch to your branch in GitHub Desktop.  
2. Click **Fetch origin**, then **Pull origin** to get the latest updates.  
3. Open your CAD/code files and continue working.

> This avoids conflicts and keeps your work up to date.

---

## 10. Assembly Editing Guidelines

- Only one person should edit the top-level assembly at a time.  
- If you must edit it:  
  1. Pull the latest `main`.  
  2. Rebase your branch on top of `main`.  
  3. Make your assembly changes, then commit and push.  
- If a merge conflict occurs, reapply your changes on top of the updated assembly.

---

## 11. Best Practices

- Commit **frequently** with descriptive messages.  
- Pull updates before starting each session.  
- Work on separate files/subassemblies when possible.  
- Ask questions — don’t guess if you’re unsure about assembly edits.  
- Follow the [Redbird Robotics coding and CAD standards](../README.md).  

---

By following this guide, you’ll be able to safely contribute to Redbird Robotics projects from day one while learning industry-standard workflows for Git, CAD, and electronics.
