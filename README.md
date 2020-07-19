## Welcome to Algorithm and Data Structure Notes :clipboard:

Our open source community is focussed on understanding the concepts and while doing so, whenever someone gets trapped, they can see one way to code in any language they want. So, we are developing a repository having implementation in as many languages as we can.

> [Index](INDEX.md)

## Steps to follow :scroll:

### 1. Fork it 

You can get your own fork/copy of [Algo_Ds_Notes](https://github.com/jainaman224/Algo_Ds_Notes) by using the <a href="https://github.com/jainaman224/Algo_Ds_Notes/new/master?readme=1#fork-destination-box"><kbd><b>Fork</b></kbd></a> button or clicking [this](https://github.com/jainaman224/Algo_Ds_Notes/new/master?readme=1#fork-destination-box).

 [![Fork Button](https://help.github.com/assets/images/help/repository/fork_button.jpg)](https://github.com/jainaman224/Algo_Ds_Notes)

### 2. Clone it 
You need to clone (download) it to local machine using

```sh
$ git clone https://github.com/Your_Username/Algo_Ds_Notes.git
```

> This makes a local copy of repository in your machine.

Once you have cloned the `Algo_Ds_Notes` repository in Github, move to that folder first using change directory command on linux and Mac.

```sh
# This will change directory to a folder Algo_Ds_Notes
$ cd Algo_Ds_Notes
```

Move to this folder for all other commands.

### 3. Set it up :arrow_up:

Run the following commands to see that *your local copy* has a reference to *your forked remote repository* in Github :octocat:

```sh
$ git remote -v
origin  https://github.com/Your_Username/Algo_Ds_Notes.git (fetch)
origin  https://github.com/Your_Username/Algo_Ds_Notes.git (push)
```

Now, lets add a reference to the original [Algo_Ds_Notes](https://github.com/jainaman224/Algo_Ds_Notes) repository using

```sh
$ git remote add upstream https://github.com/jainaman224/Algo_Ds_Notes.git
```

> This adds a new remote named ***upstream***.

See the changes using

```sh
$ git remote -v
origin    https://github.com/Your_Username/Algo_Ds_Notes.git (fetch)
origin    https://github.com/Your_Username/Algo_Ds_Notes.git (push)
upstream  https://github.com/jainaman224/Algo_Ds_Notes.git (fetch)
upstream  https://github.com/jainaman224/Algo_Ds_Notes.git (push)
```

### 4. Sync it :recycle:

Always keep your local copy of repository updated with the original repository.
Before making any changes and/or in an appropriate interval, run the following commands *carefully* to update your local repository.

```sh
# Fetch all remote repositories and delete any deleted remote branches
$ git fetch --all --prune

# Switch to `master` branch
$ git checkout master

# Reset local `master` branch to match `upstream` repository's `master` branch
$ git reset --hard upstream/master

# Push changes to your forked `Algo_Ds_Notes` repo
$ git push origin master
```

### 5. Ready Steady Go...:rabbit2:

Once you have completed these steps, you are ready to start contributing by checking our `Help Wanted` Issues and creating [pull requests](https://github.com/jainaman224/Algo_Ds_Notes/pulls).

### 6. Create a new branch :bangbang:

Whenever you are going to make contribution. Please create seperate branch using command and keep your `master` branch clean (i.e. synced with remote branch).

```sh
# It will create a new branch with name Branch_Name and switch to branch Folder_Name
$ git checkout -b Folder_Name
```

Create a seperate branch for contibution and try to use same name of branch as of folder.

To switch to desired branch

```sh
# To switch from one folder to other
$ git checkout Folder_Name
```

To add the changes to the branch. Use

```sh
# To add all files to branch Folder_Name
$ git add .
```

Type in a message relevant for the code reveiwer using

```sh
# This message get associated with all files you have changed
$ git commit -m 'relevant message'
```

Now, Push your awesome work to your remote repository using

```sh
# To push your work to your remote repository
$ git push -u origin Folder_Name
```

Finally, go to your repository in browser and click on `compare and pull requests`.
Then add a title and description to your pull request that explains your precious effort.

## Help Contributing Guides :crown:

We love to have `articles` and `codes` in different languages and `betterment` of existing ones.

Please discuss it with us first by creating new issue.

:tada: :confetti_ball: :smiley: _**Happy Contributing**_ :smiley: :confetti_ball: :tada:


## References :clipboard: :scroll:

- Books :book: :books:
    - Data Structures with C by Schaum Series
    - Data Structures: A Pseudocode Approach with C by Richard F. Gilberg
    - Fundamentals Of Data Structures in C by Horowitz
    - Introduction To Algorithms By Thomas H. Cormen
    - Java: The Complete Reference By Herbert Schildt
    - Object Oriented Programming with C++ by E Balaguruswamy
    - Computer Oriented Numerical Methods By V. Rajaraman 
- Websites :computer:
    - [GeeksforGeeks](http://www.geeksforgeeks.org)
    - [hackerearth](https://www.hackerearth.com/notes)
    - [topcoder](https://www.topcoder.com/community/data-science/data-science-tutorials)
    - [tutorialspoint](http://www.tutorialspoint.com)
    - [Wikipedia](https://en.wikipedia.org)
    
    
 
Please feel free to fork it and raise issues if you think that something could be done better. Happy coding!!

You can connect with me here: 

[![Github Badge](https://img.shields.io/badge/Follow-blue?style=social&logo=Github&link=https://github.com/Vanshikagarg17/?igshid=k8l41dsudxvo)](https://github.com/Vanshikagarg17/?igshid=k8l41dsudxvo) 
[![Twitter Badge](http://img.shields.io/badge/-@vanshika_garg17-1ca0f1?style=social&logo=twitter&logoColor=blue&link=https://twitter.com/vanshika_garg17)](https://twitter.com/vanshika_garg17) 
[![Linkedin Badge](https://img.shields.io/badge/-Vanshika%20Garg-blue?style=social&logo=Linkedin&logoColor=blue&link=https://www.linkedin.com/in/vanshika-garg-9297a3188/)](https://www.linkedin.com/in/vanshika-garg-9297a3188/) 
[![Instagram Badge](https://img.shields.io/badge/vanshikaaaaa_-blue?style=social&logo=Instagram&link=https://instagram.com/vanshikaaaaa_?igshid=k8l41dsudxvo)](https://instagram.com/vanshikaaaaa_?igshid=k8l41dsudxvo) 


