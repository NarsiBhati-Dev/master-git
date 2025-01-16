# Welcome to the Git Course

![Master Git](./images/master-git.jpeg)

Thank you for choosing to learn Git with me. I hope this course gives you a solid foundation in version control and helps you manage your projects efficiently.

This course is also available on my [website](#welcome-to-the-git-course). If you find it helpful, please leave a ⭐ on the repository as a token of encouragement!

Happy learning, and let’s get started with Git!

<div align="center" style="padding-top: 60px;">
    <h1>Course Content</h1>  
</div>

**Getting Started:**

<!-- - [Welcome to the course](#welcome-to-the-git-course) -->

- [What is Git](#what-is-git)
- [Installation and Setup](#installation-and-setup-github)

**Chapter I :**

<div align="center" style="padding-top: 60px;">
    <h1>Getting Started</h1>  
</div>

![what is git](./images/getting-started/what-is-git/banner.png)

## What is Git

**Git** is a free, open-source distributed version control system designed to handle projects of all sizes quickly and efficiently. It helps developers track changes in their code, collaborate with others, and manage different versions of a project over time.

Key Features of Git:

1. **Version Control:** Tracks changes to files, allowing you to revert to earlier versions if needed.
2. **Distributed System:** Every developer has a complete copy of the repository, enabling offline work and better data security.
3. **Branching and Merging:** Supports parallel development by letting you create separate branches for features or fixes, then merge them back into the main codebase.
4. **Collaboration:** Git enables teams to work together efficiently by managing code contributions and resolving conflicts.
5. **Speed and Efficiency:** Optimized for performance, even with large projects.

## Installation and Setup Github

![installation and setup](https://cdn.hashnode.com/res/hashnode/image/upload/v1737008262029/74707cb3-d533-490c-bb6e-fbad6d477a74.png)

### Windows / Linux (Ubuntu)

```bash
sudo apt install git-all
```

### MacOS

```bash
brew install git
```

After installation, you can check if Git is installed.

```bash
git --version
```

![example](https://cdn.hashnode.com/res/hashnode/image/upload/v1737008367050/eef3cba1-458e-4096-b7cf-bc3b4ac75795.png)

## Official Manual of Git

```bash
 man git
```

**Navigation Shortcuts:**

• `q` : Quit the manual and return to the terminal.

• `j` : Move one line down.

• `k` : Move one line up.

• `d` : Scroll half a page down.

• `u` : Scroll half a page up.

**Search Shortcuts:**

• `/<term>` : Search for a specific term in the manual.

• `n` : Go to the next occurrence of the search term.

• `N` : Go to the previous occurrence of the search term.

![example](https://cdn.hashnode.com/res/hashnode/image/upload/v1737009029745/c5e1d406-3709-42d2-9995-719249d1f817.png)

## **Steps for Quick Git Configuration**

### **1\. Check Current Configurations**

Run these commands to check if your Git identity is already set:

```bash
git config --get user.name
git config --get user.email
```

### **2\. Set Your Identity**

If the values aren’t set, use the following commands to add them globally (replace with your details):

```bash
git config --add --global user.name "github_username_here"

git config --add --global user.email "email@example.com"
```

### **3\. Set a Default Branch**

Configure Git to use &lt;branch&gt; as the default branch for new repositories:

```bash
git config --global init.defaultBranch <branch>
```

### **Verify Your Configuration**

To ensure your settings were saved, check the contents of your global configuration file:

```bash
 cat ~/.gitconfig
```

**Example Output (~/.gitconfig):**

```bash
[user]

    name = github_username_here

    email = email@example.com

[init]

    defaultBranch = master
```
