# Part 1: Theoretical Answers

## 1. What is the Difference between Git and GitHub?

Git is a distributed version control system that runs locally on your computer and tracks changes to files over time.  
It allows you to create branches, commit changes, and revert to previous versions without any internet connection.  

**GitHub**, on the other hand, is a cloud-based platform that hosts Git repositories online.  
It enables collaboration, pull requests, and sharing your code with others.


## 2. Explain the Difference between `git pull` and `git fetch`

- **`git fetch`** downloads the latest changes from the remote repository to your local machine **without merging** them into your current branch.  
- **`git pull`** is a combination of `git fetch` and `git merge` — it brings the changes from the remote repository **and merges them** into your current branch immediately.


## 3. What is the Purpose of `.gitignore` file?

The `.gitignore` file tells Git which files or folders it should **not track**.  
This is useful for:  
- Temporary files  
- Sensitive credentials  
- Automatically generated files like Python’s `__pycache__` or `.env` files


## 4. Steps to Contribute to an Open‑Source Project on GitHub

1. **Fork** the repository you want to contribute to.  
2. **Clone** your forked repository to your local machine.  
3. **Create a new branch** for your changes.  
4. **Make your changes** and commit them with clear messages.  
5. **Push your branch** to your forked repository on GitHub.  
6. **Open a Pull Request** to the original repository, describing your changes.  
7. **Wait for review** and merge your contribution once approved.
