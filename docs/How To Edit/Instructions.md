# Editing This Website
You need to clone the repo and make changes to it in markdown.
These changes will automatically be applied to the website when you push your code.

I generally suggest editing the website in VSCode, however any text editor should work. 

To compile and view the website locally you need to install python, then run the following commands:
```bash
pip install mkdocs-material
cd path/to/repo/.
mkdocs serve
```
This will open up the website in your web browser and automatically update it whenever you save a file.

## Editing In VSCode
Install YAML extension by following [the reccomendatio here](https://squidfunk.github.io/mkdocs-material/creating-your-site/?h=vscode#minimal-configuration).
I don't reccoment using the built-in markdown viewer in VSCode to edit the code.

## Using GIT

### Clone Repo to make edits
This puts a local copy of the repository onto your computer.
```bash
git clone <website of repo>
```

### Pushing Your Changes
After you edit files and want to save them, follow the following process:
```bash
git status
```
This will show files that you added. Select the files that you want to save to your commit by running:
```bash
git add <filepath1> <filepath2> <filepath3> ...
```
You may repeat the above two commands as much as you want until the `Changes to be committed` section lists all of the files that you want to save the changes to.

Once you are satisfied with the list, you need to create a commit that saves your changes locally on your computer (not the centeral server). Replace the text `Description` with a description of what you changed and why. (i.e. "Fixed A Spelling Error") (You can also use the `-a` flag to automatically add all edited files to the commit without having to run the `git add` command, but it won't add entirely new files.)
```bash
git commit -m "Description"
```

Now, you have a commit saved locally on your computer, to put it on the centeral server and have your changes reflected on the website, run the following command:
```bash
git push
```