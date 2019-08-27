Instead of the content below, here's suggested Learning Lab-based content for the Welcome repo:
https://gist.github.com/femmebot/3327eee5b6408cc660703c4427a67f45


---

# Welcome to GitHub! :tada:

You are looking at the README of your first repository. We’ve included a few resources to help you get started with the basics and beyond.

***

## GitHub basics


### This hands-on tutorial gets you started with the basics of GitHub. Learn to create and manage a branch. Make changes to a file and push them to GitHub as commits. Add style to your text content with Markdown. No coding experience necessary. Let’s get started!


<details>
  <summary>What is GitHub?</summary>

# What is GitHub?

GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

In this tutorial, you will learn about GitHub essentials like repositories, branches, and commits. You’ll create your own Hello World repository, and create and merge branches.  

</details>

<details>
  <summary>Step 1. Create a Repository</summary>

# Step 1. Create a repository

A repository is usually used to organize a single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets — anything your project needs. We recommend including a README, or a file with information about your project. GitHub makes it easy to add one at the same time you create your new repository. It also offers other common options such as a license file.

Your `hello-world` repository can be a place where you store ideas, resources, or even share and discuss things with others.

## To create a new repository

1. In the upper right corner, next to your avatar, click :plus: and then select New repository.
2. Name your repository `hello-world`.
3. Write a short description.
4. Select Initialize this repository with a README.

![create a new repository](https://guides.github.com/activities/hello-world/create-new-repo.png)

</details>

<details>
  <summary>Step 2. Create a Branch</summary>

# Step 2. Create a branch

_Branching_ is the way to work on different versions of a repository at one time.

By default your repository has one branch named master which is considered to be the definitive branch. We use branches to experiment and make edits before committing them to master.  

When you create a branch from the `master` branch, you’re making a copy, or a snapshot, of `master` at that point in time. If someone else made changes to the `master` branch while you were working on your branch, you could pull in those updates.

This diagram shows:

- The `master` branch
- A new branch called `feature` (because we’re doing ‘feature work’ on this branch)
- The journey that feature takes before it’s merged into master
![](https://guides.github.com/activities/hello-world/branching.png)

Have you ever saved different versions of a file? Something like:

`story.txt`
`story-joe-edit.txt`  
`story-joe-edit-reviewed.txt`  

Branches accomplish similar goals in GitHub repositories.

Here at GitHub, our developers, writers, and designers use branches for keeping bug fixes and feature work separate from our master (production) branch. When a change is ready, they merge their branch into master.

## Creating a new branch

1. Go to your new repository hello-world.
2. Click the drop down at the top of the file list that says branch: master.
3. Type a branch name, readme-edits, into the new branch text box.
4. Select the blue Create branch box or hit “Enter” on your keyboard.

![create a new branch](https://guides.github.com/activities/hello-world/readme-edits.gif)

Now you have two branches, `master` and `readme-edits`. They look exactly the same, but not for long! Next we’ll add our changes to the new branch.

</details>

<details>
  <summary>Step 3. Make and commit changes</summary>

# Step 3. Make and commit changes

Bravo! Now, you’re on the code view for your `readme-edits` branch, which is a copy of `master`. Let’s make some edits.

On GitHub, saved changes are called _commits_. Each commit has an associated _commit message_, which is a description explaining why a particular change was made. Commit messages capture the history of your changes, so you and other contributors can understand what changes you've made and why.

## Make and commit changes

1. Click the `README.md` file.
2. Click the  pencil icon in the upper right corner of the file view to edit.
3. In the editor window, write a bit about yourself.
4. Write a commit message that describes your changes.
5. Click the **Commit changes** button.

![commit changes](https://guides.github.com/activities/hello-world/commit.png)

These changes will be made to just the README file on your readme-edits branch, so now this branch contains content that’s different from master.

</details>

<details>
  <summary>Step 4. Make it fancy with Markdown</summary>

# What is Markdown?

Markdown is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. This README is styled using Markdown. (Tip: Click on the pencil icon at the top of this repository to view how this README content uses Markdown to style the text.)

You can use Markdown in other places around GitHub:

* Gists
* Comments in issues and pull requests
* Files with the Markdown .md or .markdown extension


## Syntax guide

Here’s a brief overview of Markdown syntax that you can use anywhere on GitHub.com or on your own text files.


### Headers

```
# This is an h1 heading
## This is an h2 heading
###### This is an h6 heading
```

### Emphasis
```
*This is how to make text italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
```

### Unordered lists
```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```
### Ordered lists
```
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
```

### To-do lists
```
- [] Item with checkbox 1
- [] Item with checkbox 2
- [] Item with checkbox 3
```

### Images
```
![Alt Text](image url)
```
### Links
```
http://github.com - automatic!
[GitHub](http://github.com)
```

### Blockquotes
```
> Lorem ipsum dolor sit amet
> quid nostrud nonummy
```

### Additional Markdown resources
- [Basic writing and formatting syntax](https://help.github.com/en/articles/basic-writing-and-formatting-syntax)
- [Mastering Markdown](https://guides.github.com/features/mastering-markdown)


</details>

<details>
  <summary>Step 5: Make a pull request</summary>

# What is a pull request?  

Pull requests are the heart of collaboration on GitHub. When you open a pull request, you’re proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in green and red.

</details>


<details>
  <summary>Project: Create your own learning repository </summary>

  Project: Create your own learning repository

</details>
