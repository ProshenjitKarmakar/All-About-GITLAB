
# All About GitLab  - `GITLAB` 

Gitlab is a service that provides remote access to Git repositories. 
In addition to hosting your code, the services provide additional features 
designed to help manage the software development lifecycle. These additional 
features include managing the sharing of code between different people, bug 
tracking, wiki space and other tools for 'social coding'.

### Git : A version control system.
- Git mainly do to locally track changes in your project/folder and push & pull changes from remote repositories like GitLab, GitHub etc. 

### GitLab : Continuous integration and Continuous Development.
- Gitlab services that allows to host your project on a remote repositories and have additional features to help in SDLC, CI(Continuous integration) & CD(Continuous Development).
## Features - `GitLab` 

- GitLab hosts your (private) software projects for free.
- GitLab is a platform for managing Git repositories.
- GitLab offers free public and private repositories, issue-tracking and wikis.
- GitLab is a user friendly web interface layer on top of Git, which increases the speed of working with Git.
- GitLab provides its own Continuous Integration (CI) system for managing the projects and provides user interface along with other features of GitLab.


## Git Commands - `GitLab`
- The version of the Git can be checked by using the below command −
```bash
$ git --version
```
- Add Git username and email address to identify the author while committing the information. Set the username by using the command as −
```bash
$ git config --global user.name "USERNAME"
$ git config --global user.name     //for show name
$ git config --global user.email "EMIL"
$ git config --global user.email    //for show email
```
- Use the below command to check the entered information −
```bash
$ git config --global --list
```
- You can pull the latest changes made to the master branch by using the below command −
```bash
$ git checkout master
```
- Create a new branch with the below command −
```bash
$ git checkout -b branch-name
```
- You can switch from one branch to other branch by using the command as −
```bash
$ git checkout branch-name
```
- Check the changes made to your files with the below command −
```bash
$ git status
```
- Now send your changes to master branch with the below command −
```bash
$ git push origin branch-name
```
- To merge the different branch with the master branch, use the below command −
```bash
$ git checkout branch-name
$ git merge master
```
- You can also merge the master branch with the created branch, by using the below command −
```bash
$ git checkout master
$ git merge branch-name
```

## Creating SSH(Secured Socket Shell) Key Setup - `GitLab`
The SSH stands for Secure Shell or Secure Socket Shell used for managing the networks, operating systems and configurations and also authenticates to the GitLab server without using username and password each time. You can set the SSH keys to provide a reliable connection between the computer and GitLab. Before generating ssh keygen, you need to have Git installed in your system.
`- Mainly used for authentication  & by setting SSH Key we can connect to gitlab server without GitLab USERNAME or PASSWORD each time.`
- `#Step - 1 :` To create SSH key, open the command prompt and enter the command as shown below −
```bash
$ ssh-keygen            // from desktop repository
```
It will prompt for 'Enter file in which to save the key (//.ssh/id_rsa):', just type file name and press enter. Next a prompt to enter password shows 'Enter passphrase (empty for no passphrase):'. Enter some password and press enter. You will see the generated SSH key

- `#Step - 2 :` Now login to your GitLab account and click on the Settings option.
- `#Step - 3 :` To create SSH key, click on the SSH keys tab at left side of the menu.
- `#Step - 4 :` Now go to respective drive where you run the command. For me it's `C:\Users\WALTON\.ssh`, you will see the file with `.pub` extension which was generated in the first step.
- `#Step - 5 :` Next open the `key.pub` file, copy the `SSH key` and paste it in the highlighted Key box in gitlab.
- `#Step - 6 :` Click on the `Add Key` button, to add SSH key to your GitLab. You will see the fingerprint (it is a short version of SSH key), title and created date.

## Fork a Project - `GitLab`
Fork is a duplicate of your original repository in which you can make the changes without affecting the original project.
- `#Step - 1 :` To fork a project, click on the Fork button as shown below −
- `#Step - 2 :` After forking the project, you need to add the forked project to a fork group `(first create a group)` by clicking on it −
- `#Step - 3 :` Next it will start processing of forking a project for sometime.
- `#Step - 4 :` It will display the success message after completion of forking the project process.


## Advanced usage of CI - `GitLab-CI`
Fork is a duplicate of your original repository in which you can make the changes without affecting the original project.
- `#Step 1 :` .......


## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


# Documented by :  `Proshenjit Karmakar - Full Stack Developer`.
