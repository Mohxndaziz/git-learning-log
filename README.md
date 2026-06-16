<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Learn Git Fundamentals

**Project Link:** [View Project](https://learn.nextwork.org/projects/8bf3bcb5-a70d-418a-9c76-251365f69028)


---

![Image](https://learn.nextwork.org/charmed_brown_innocent_seal/uploads/8bf3bcb5-a70d-418a-9c76-251365f69028_l5jsusg6)

## Project Overview: Learning Git Version Control

### Goals and objectives

In this project, I'm building a Git repository tracking a markdown file with a real edit history, branches, and a resolved merge conflict, all visible on a public GitHub repository.

## Setting Up the Development Environment

### Installing Git and Cursor



![Image](https://learn.nextwork.org/charmed_brown_innocent_seal/uploads/8bf3bcb5-a70d-418a-9c76-251365f69028_ryyzlsf8)

## Configuring Git and Creating the Learning Log

### Setting up Git identity and project file

In this step, I'm setting up my Git Identity so that I can commit any changes to a Markdown file.

![Image](https://learn.nextwork.org/charmed_brown_innocent_seal/uploads/8bf3bcb5-a70d-418a-9c76-251365f69028_d6lm2bxt)

### Understanding global Git configuration

The --global flag means sets your identity for all Git repositories on your computer. I used a specific email because it will link my local commits to my GitHub profile.

## Initializing a Repository and Making Commits

### Creating the first commits

In this step, I'm setting up Github repository so that I can my commits.

![Image](https://learn.nextwork.org/charmed_brown_innocent_seal/uploads/8bf3bcb5-a70d-418a-9c76-251365f69028_blkivqea)

### Understanding git add vs git commit

git add converts the current file into a repository, while git commit does adding of the changes to the curret file.

## Branching and Working in Parallel

### Creating and switching branches

In this step, I'm creating a separate branch so that I can setup merge confict. 

![Image](https://learn.nextwork.org/charmed_brown_innocent_seal/uploads/8bf3bcb5-a70d-418a-9c76-251365f69028_drz4zcda)

### Why merge conflicts occur

A merge conflict happens because version control systems like Git use a three-way merge strategy, comparing both branches to their common starting point (ancestor). When the same line is modified differently on both branches, Git cannot mathematically decide which version is "correct," and must halt to ask a human

## Merging Branches and Resolving Conflicts

### Merging feature branches into main

In this step, I'm merging two branches containing the same edited section so that I can resolve merge conflit.

![Image](https://learn.nextwork.org/charmed_brown_innocent_seal/uploads/8bf3bcb5-a70d-418a-9c76-251365f69028_0e34g9cu)

### Interpreting Git conflict markers

The section between <<<<<<< HEAD and ======= is what is on your current branch (main).

The section between ======= and >>>>>>> add-resources is what is on the branch you are merging in.

Your job is to delete all the marker lines and keep the content you want.

## Publishing to GitHub

### Creating a remote repository

In this step, I'm setting up Github repository so that I can push my local reposirory into github.

![Image](https://learn.nextwork.org/charmed_brown_innocent_seal/uploads/8bf3bcb5-a70d-418a-9c76-251365f69028_l5jsusg6)

### Pushing local commits to GitHub

I ran git push to upload my local repository commits to remoter Github repository. I needed a remote because git does not know the location where the repo lives. Setting up a "remote" acts as a map, linking your offline project folder to an online destination URL



### Commands used to publish the Profile README

## Reflections and Key Takeaways

### Tools and concepts mastered

### Time and challenges

### Looking ahead

---

## Part 2
<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Git Branching and Rebasing

**Project Link:** [View Project](https://learn.nextwork.org/projects/91663bbf-e290-4b23-a79a-b5ecb09d033a)

**Author:** Mohand Mohamed  
**Email:** mohandaziz2005@gmail.com

---

![Image](https://learn.nextwork.org/charmed_brown_innocent_seal/uploads/91663bbf-e290-4b23-a79a-b5ecb09d033a_prbtm81h)

## Mastering Git for Professional Collaboration

### Project goals and motivation

In this project, I'm learning how to resolve merging coflicts, rebasing feature branches and cleaning up commit history so that I can be a profissional team player with my skills.

## Setting Up the Conflict Practice Environment

### Step overview

In this step, I'm setting up Cursor with git repositroy so that I can pull the latest changes and confirm a cleasn working tree.

![Image](https://learn.nextwork.org/charmed_brown_innocent_seal/uploads/91663bbf-e290-4b23-a79a-b5ecb09d033a_41zr0tj6)

### Why create the file on main first

I created this file on main to set up a safe, isolated environment so you can deliberately edit the same lines of code later to trigger and practice resolving merge conflicts

## Resolving a Merge Conflict

### Step overview

In this step, I'm setting up two branches that edit the same line in conflict-practice.md, then merge them both into main to trigger the conflict.


### Understanding conflict markers

The markers show me where the merge conflict occured.  <<<<<<< marks the start of the conflict. The content immediately following this marker up to the ======= represents your current local changes (usually your active branch or HEAD)

![Image](https://learn.nextwork.org/charmed_brown_innocent_seal/uploads/91663bbf-e290-4b23-a79a-b5ecb09d033a_n45dts6x)

## Rebasing a Feature Branch for Clean Linear History

### Step overview

In this step, I'm setting up a new feature branch  with new commits and simulate a teammate pushing into main .That way I can rebase my feature branch onton main's latest  commit and understand how to get clean linear history.

![Image](https://learn.nextwork.org/charmed_brown_innocent_seal/uploads/91663bbf-e290-4b23-a79a-b5ecb09d033a_wycjar4n)

### Rebase vs. merge explained

Merging preserves history exactly as it happened by creating a new "merge" commit. Rebasing rewrites history by moving your branch to the latest point and making your changes appear linear.

## Polishing Commits with Interactive Rebase

### Step overview

In this step, I'm cleaning up my missy commit history and cobmining four messy commits into a single commit so that my history looks polished and clean.

### reword vs. squash commands

Reword allows you to change the commit message in the commit history while squash combines the commits into one.

### Why --force-with-lease is required after rebase

I needed --force-with-lease because you rewrote the history, GitHub notices that the histories do not align, thinks you might be making a mistake, and rejects the push to protect you from accidentally erasing anything. --force-with-lease tells github ti overwrite the remote branch anyway. It blindly forces GitHub to overwrite the remote branch with your local version stackoverflow.com. If one of your team members pushed their own commits to your branch while you were rebasing, a plain force-push will wipe out their work permanently without warning

## Saving Work-in-Progress with Git Stash

![Image](https://learn.nextwork.org/charmed_brown_innocent_seal/uploads/91663bbf-e290-4b23-a79a-b5ecb09d033a_otnu1qbf)

### The value of git stash in team workflows

In this project extension, I learned that git stash allows you to temporarily shelf uncommitted changes so you can immediately switch context without losing work or creating messy commit histories.

## Reflections and Takeaways

### Key tools and concepts

The key tools I used include Cursor, Git and Github. Key concepts I learnt include resolving merge conflicts, rebase , interactive rebase and stash.

### Time and challenges

This project took me approximately 2 hours. The challenge I faced in this project id visualizing what was happening in the differenct branches, most of it is mental as you can not see it.

### Looking ahead

I did this project to solidify my git fundamentals and looking forward to use git in seamless team collaborations with impactful projects.

---

*Built with [NextWork](https://learn.nextwork.org) - [View this project](https://learn.nextwork.org/projects/8bf3bcb5-a70d-418a-9c76-251365f69028)*
