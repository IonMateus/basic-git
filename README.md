
[<img src="https://git-scm.com/images/logo@2x.png">](https://git-scm.com/)

<img src="https://img.shields.io/badge/GitHub-Git-red">  <img src="https://img.shields.io/badge/2023-Basic-red">  <img src="https://img.shields.io/badge/document-English-red">


### 🤔 What's Git?
  *_Git is a distributed version control system that tracks changes in any set of computer files._*
Git is often used to update GitHub projects from the machine to the server by specific codes.

### 💻 How to write a Git command?

* Write on **Visual Studio Code**.
   
   * Open the VSCode
   * Go to the `toolbar --> Terminal --> New Terminal`  (or just `Ctrl + Shift + '`)
   * Something like `PS C:\Users\you>` will apear on terminal. Use the command `cd [path to project folder]`, like `cd C:\Users\you\Projects`
   * Write the commands!
    <img width="600" src="https://raw.githubusercontent.com/IonMateus/basic-git/main/ReadmeImages/newTerminal.png">
   
* Write on **Command Prompt**.
   
   * Open the Command Prompt. You can open it by `Window Icon + R` and write cmd. Or search 'Command Prompt' on Window search bar.
   * Something like `C:\Users\you>` will apear on terminal. Use the command `cd [path to project folder]`, like `cd C:\Users\you\Projects`
   *  Write the commands!
<p align="center">
<img width="500" src="https://raw.githubusercontent.com/IonMateus/basic-git/main/ReadmeImages/cmd.png">
</p>


### ⌨️ Commands

**Create the repository**
* The repositoty needs to be empty, without any file, even the README.md. Just don't select the checkbox 'Add a README file' when you create the repository. It's possible to do it in a full repository, but we'll not focus on that at the moment.

* When it's created, use these commands on terminal:
```
git init
```
```
git add .
```
```
git commit -m "a message"
```
* `git init` will create a file named as '.git' on your project folder.
* `git add .` add your changes to your next commit.
* `git commit -m 'a message'` Captures a snapshot of your project. Now you can push it to your GitHub repository.


**Then write the three commands that appear on your repository. They look like this:**

* `git remote add origin https://github.com/YourGitHubUsername/repositoryName.git`
* `git branch -M main`
* `git push -u origin main`
This creates a connection with your GitHub project and send the commit to your repository. You just need to use these three commands once.
You already has your repository up to date! 🎉

**To update again:**
```
git add .
```
```
git commit -m "message"
```
```
git push origin main
```
Just this!

**Your repository was changed by a collaborator, how to update your *LOCAL CODE***
```
git fetch
```
```
git pull
```
Creates a connection to the GitHub server and changes your code to match your project.

### 📖 Sources
* [Wikipédia](https://en.wikipedia.org/wiki/Git)
* [Git](https://git-scm.com/)

