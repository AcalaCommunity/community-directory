# community-directory

A directory of Acala's community members and ambassadors!

## What is this?

The point of this repository is to help the community get to know each other better as well as learn how to make contributions to a project on GitHub. Although GitHub is most known as a tool to help programmers it's also useful for general project management! 

In this tutorial you will:

1) `Fork` this repository to your GitHub account.
2) `Clone` your fork locally to your computer.
3) Make edits and use GitHub desktop to `commit`, and `push` your changes.
4) Create a `pull request` to have your edits reflected in the original repository.

Let's get started!

## Setup

### 1) Sign up

The first thing you need to do is have a GitHub account. You can create one by clicking `Sign up` in the top right corner of this page.


### 2) Download GitHub Desktop

Next we're going to download and install [GitHub Desktop](https://desktop.github.com/). GitHub desktop is an application developed by GitHub that allows you to do common git commands without having to go through the terminal.

## Making a contribution

### 1) Fork this repository

The first thing we need to do is create a `fork` of this repository.

_What is a fork? A fork is a copy of some repository that is still linked to the original repository. This lets you safely make any changes they want without worrying about affeceting the original repository._

In the top right corner of this web page you should see the following:

![Fork button](https://i.imgur.com/juvSC3e.jpg)

**Note**: The numbers next to these buttons may different by the time you go through this tutorial.

Click on the `Fork` button and for the `Where should we fork` option choose your GitHub account. It should then automatically redirect you to your personal repository of the fork.

### 2) Clone your fork

Now that you've forked this repository let's `clone` it to your computer so you can add your changes.

Open up GitHub Desktop and in the search bar that says `Filter your repositories` enter the name of this repository and then click the `Clone` button on the bottom to choose where you'd like to copy this repository.

![clone a repository](https://i.imgur.com/oWfYGvL.jpg)

### 3) Adding your information

We are now ready to make changes to your repository! For this section you can use any editor you'd like but I will be using [Atom](https://atom.io/). 

Open up the repository folder in your editor and create a new new file in the appropriate folder (ambassadors in `ambassadors`, community members in `community members`). Name the file `<Your Name>.md`.

**Note**: The file format `md` is for Markdown files. You'll see this format a lot within our repositories and documentation. Markdown makes it easy to add very basic styling to your documents. Read more about Markdown syntax [here](https://guides.github.com/features/mastering-markdown/).

Copy the contents of `template.md` into your new file and fill it out with your information.

![Content](https://i.imgur.com/upcGZeH.png)

### 4) Committing and Pushing your changes

Once you've saved your changes, open up GitHub Desktop. Notice on the left hand of the application you now have one new changed file.

Committing your changes records them locally within your repository.

Press the button `Commit to master`.

![Committing](https://i.imgur.com/RMxamAE.jpg)

To have your changes reflected on GitHub press the `Push origin` button on the top of the application.

![Pushing](https://i.imgur.com/irWoBJX.jpg)

You can now head over to your fork's GitHub page and see your changes!

### 5) Making a Pull Request

You have now added content to your fork and are ready to have your new file incorporated into the original repository! 

If everything has gone according to plan you should see a button that says `Create Pull Request` at the top of your repository on GitHub. Click the button to open up the Compare Pull Request page.

![Compare PR](https://i.imgur.com/GGKhh2f.jpg)

On this page you'll see the changes you've made to the repository and how they compare to what is currently in the original repository. Press `Create pull request`.

![Create PR](https://i.imgur.com/6ct4jId.jpg)

Finally you you'll see a space to leave a detailed comment about the code you are trying to merge. For more complex contributions it can be useful to use this space to describe what changes you've made and refer to any [issues](https://guides.github.com/features/issues/) your change fixes. For this you can just leave it blank. 

Press `Create pull request` one last time to open a pull request! Once your request has been reviewed it will be merged into the original repository!

![Open PR](https://i.imgur.com/PeWrYXI.jpg)
