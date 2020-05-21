# Cesta open source Learning Portal:-
This is the open source project for [cesta.me](url) portal

here are some guidlines to help you on how to contribute to this project 
follow the steps below :-

<img align="right" width="300" src="assets/images/fork.png" alt="fork this repository" />

If you don't have git on your machine, [install it]( https://help.github.com/articles/set-up-git/).

And if you get stuck at anywhere just [go here](https://www.google.com/webhp?hl=en&ictx=2&sa=X&ved=0ahUKEwjX4fnS4MPpAhWDhXIEHYbeCncQPQgH) and type in the problem.

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="assets/images/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the clone button and then click the *copy to clipboard* icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```
where "url you just copied" (without the quote marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="assets/images/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:
```
git clone https://github.com/sidx8/Cesta-open-source-project.git
```
where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd Cesta-open-source-project
```
Now create a branch using the `git checkout` command:
```
git checkout -b <add-your-new-branch-name>
```

For example:
```
git checkout -b add-alonzo-church
```
(The name of the branch does not need to have the word *add* in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

Now open the [index.css](index.css) file and change the front-end design according to your likeing and after that open [`Contributors.md`](Contributors.md) file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="assets/images/git-status.png" alt="git status" />


If you go to the project directory and execute the command `git status`, you'll see there are changes.


Add those changes to the branch you just created using the `git add` command:

```
git add index.css
git add Contributors.md
```
Or you can use this command to add all files at once 

```
git add .
```

Now commit those changes using the `git commit` command:
```
git commit -m "Add <your-name> to Contributors list"
```
replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:
```
git push origin <add-your-branch-name>
```
replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button. Click on that button.

<img style="float: right;" src="assets/images/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="assets/images/submit-pull-request.png" alt="submit pull request" />

Soon We'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.
