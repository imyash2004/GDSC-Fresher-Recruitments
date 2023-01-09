# GDSC-Fresher-Recruitments

Steps to Follow

- Fork the project:
 Click the gray Fork button at the top right of this page. This creates your copy of the project and saves it as a new repository in your GitHub account

- Click on the green Code button, then either the HTTPS or SSH option, and, click the icon to copy the URL. Now you have a copy of the project. Thus, you can play around with it locally on your computer.

- Run the following commands into a terminal window (Command Prompt, Powershell, Terminal, Bash, ZSH). Do this to download the forked copy of this repository to your computer.

```bash
  git clone https://github.com/YOUR_GITHUB_USERNAME/GDSC-Fresher-Recruitments.git
```

- Switch to the cloned folder. You can paste this command into the same terminal window.

```bash
  cd GDSC-Fresher-Recruitments
```

- Make a new branch. Your username would make a good branch because it's unique.

```bash
  git checkout -b <name-of-new-branch>
```

- Open the `README.md` file

- **Add your name to the section. Then save your changes.**

- Stage your changes.

```bash
  git add README.md
```

or

```bash
  git add .
```

- Commit the changes.

```bash
  git commit -m "Add <your-github-username>"
```

- Check the status of your repository.

```bash
  git status
```

- The response should be like this:

```bash
On branch <name-of-your-branch>
nothing to commit, working tree clean
```

- Pushing your repository to GitHub.

```bash
  git push origin <name-of-your-branch>
```

or

```bash
  git branch -M main
  git push -u origin main
```
Done!

Happy Contributing!🥳
