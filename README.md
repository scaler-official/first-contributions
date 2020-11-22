[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/scaler-official/first-contributions/)
## What and Why is this Project?
This project exists to give all open source beginners a taste of contributor without dwelling much
into complexities. On a high level, every open source project follow the similar pattern we follow
in this project.

## Prerequisites

1. Comfortable with the command line. *If you are not comfortable with the command line, try this 
beginner friendly guide: [https://ubuntu.com/tutorials/command-line-for-beginners](https://ubuntu.com/tutorials/command-line-for-beginners)*
2. Git is installed in your machine. If not installed, install it using this guide: [https://help.github.com/articles/set-up-git/](https://help.github.com/articles/set-up-git/)

## Steps

### Fork Repo
Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

<img align="right" width="300" src="https://raw.githubusercontent.com/scaler-official/first-contributions/master/assets/fork.png" alt="clone this repository" />

### Clone Repo
Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

<img align="right" width="300" src="https://raw.githubusercontent.com/scaler-official/first-contributions/master/assets/clone.png" alt="clone this repository" />

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

For example:

```
git clone https://github.com/your-username/first-contributions.git
```

where `your-username` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

### Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd first-contributions
```

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name
```

For example:

```
git checkout -b add-alonzo-church
```

(The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

### Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-name> to Contributors list"
```

replacing `<your-name>` with your name.

### Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

### Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://raw.githubusercontent.com/scaler-official/first-contributions/master/assets/create-pull-request.png" alt="create a pull request" />

Now submit the pull request using `Create pull request` button. Make sure there is `scaler-official/first-contributions` written in top-left corner.

<img style="float: right;" src="https://raw.githubusercontent.com/scaler-official/first-contributions/master/assets/open-pull-request.png" alt="submit pull request" />

Soon We'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

### And that's it. You have done your first contribution
Congrats! You have just completed very first crucial step in starting contributions in open source.
Feel free to submit play around and try this once more.  
All Open Source Projects follow the same loop: `fork => clone => edit => pull request` workflow.

## Next Steps
TODO: Add links to other helpful repo & resources
