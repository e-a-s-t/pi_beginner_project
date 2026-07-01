# Git and GitHub Setup

This guide prepares your computer for storing projects in GitHub and using SSH keys.

## 1. Install Git

On Windows, install **Git for Windows**. It includes **Git Bash**, which provides a Linux-like terminal and Git.

Official download:

- https://gitforwindows.org/

## 2. Create a GitHub Account

Create a free account at GitHub.

- https://github.com/

### Choose a Username

Choose a short, memorable username that you can use consistently across your computer, Raspberry Pi, GitHub, and other development tools.

A recommended convention is:

- The first **three letters of your surname**
- Followed by the first **three letters of your given name**

Example:

```
<sur><giv>
```

Using the same username everywhere makes it easier to remember login details and work across multiple systems.

## 3. Configure Git

After installing Git, open **Git Bash** and configure your name and email.

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

Official documentation:

- https://docs.github.com/en/get-started/git-basics/set-up-git

## 4. Set Up SSH for GitHub

Follow GitHub's official SSH guide.

This will create an SSH key on your computer. The same SSH key can later also be useful when connecting to your Raspberry Pi.

Official documentation:

- https://docs.github.com/en/authentication/connecting-to-github-with-ssh

## 5. Test GitHub SSH Access

After adding your SSH key to GitHub, test the connection:

```bash
ssh -T git@github.com
```

Official documentation:

- [Creating SSH keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent?platform=windows)
- [Testing if it works](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection)

## 6. Create a Repository

> [!NOTE]
> This can wait for later

Create a new repository on GitHub for your work.

Official documentation:

- https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository

## 7. Clone the Repository

Clone this repository to your computer using the SSH URL from GitHub.

```bash
git clone git@github.com:github-username>/<repository-name>.git
```

Example:

```bash
git clone git@github.com:e-a-s-t/pi_beginner_project.git
```

## 8. Basic Git Workflow

Use this workflow when working on your project:

```bash
git status
git add .
git commit -m "Describe what changed"
git push
```

Useful official documentation:

- https://docs.github.com/en/get-started/using-git/about-git
- https://docs.github.com/en/get-started/using-git/pushing-commits-to-a-remote-repository

## Next Steps

After this setup, you can use GitHub to store your code and track your progress.

Later, when setting up the Raspberry Pi, you can reuse the same SSH key approach to connect securely.
