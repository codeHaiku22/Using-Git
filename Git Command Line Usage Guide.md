![Git Logo](/images/logos/git_logo.png)

# Command Line Usage Guide
## Get Git

### Linux
Depending on the disribution of Linux that you are running, there are multiple ways to obtain the ```git``` command.  Some of the most popular Linux distributions have been documented below.

#### ![Debian Logo](/images/logos/debian_logo.png) &nbsp;&nbsp;&nbsp;Debian
```bash
# apt install git
```

#### ![Ubuntu Logo](/images/logos/ubuntu_logo.png) &nbsp;&nbsp;&nbsp;Ubuntu
```bash
# apt install git
```

#### ![Fedora Logo](/images/logos/fedora_logo.png) &nbsp;&nbsp;&nbsp;Fedora
```bash
# dnf install git
```

#### ![Arch Logo](/images/logos/arch_logo.png) &nbsp;&nbsp;&nbsp;Arch
```bash
# pacman -S git
```

#### ![Solus Logo](/images/logos/solus_logo.png) &nbsp;&nbsp;&nbsp;Solus
```bash
# eopkg install git
```

#### ![openSUSE Logo](/images/logos/opensuse_logo.png) &nbsp;&nbsp;&nbsp;openSUSE
```bash
# zypper install git
```

#### ![MacOS Logo](/images/logos/macos_logo.png) &nbsp;&nbsp;&nbsp;MacOS
##### Homebrew
Install [homebrew](https://brew.sh).
```bash
$ brew install git
```
##### XCode
Git is included as a binary package with [XCode](https://developer.apple.com/xcode/).

##### Build from Souce
Tarballs are available on [kernel.org](https:/www.kernel.org/pub/software/scm/git).


### ![Windows Logo](/images/logos/windows_logo.png) &nbsp;&nbsp;&nbsp;Windows
Windows machines can obtain the git GUI and git command line command from the git website directly.

Click [here](https://git-scm.com/download/win) or visit the link below to download the latest version of git.

[https://git-scm.com/download/win](https://git-scm.com/download/win)

## Create a New Repository 
_**NOTE:** For the remainder of this tutorial, GitHub will be used as the default git repository location AND the repository named in this tutorial will be called testrepository._

Log into GitHub and add a new repository.

![Add Repo](/images/add_repo.png)

Provide the needed information for the newly added repository.

![Add Repo](/images/create_repo.png)

You can also issue the following commands to create a new repository:
```bash
# echo "# testrepository" >> README.md
# git init
# git add README.md
# git commit -m "first commit"
# git remote add origin https://github.com/codeHaiku22/testrepository.git
# git push -u origin master
```

## Clone an Existing Repository
Identify the repository connection information by navigating to the Code page of an existing repository and clicking on the "Code" or "Clone" button.  This will expose the repository connection information.  Copy the repository connection information.

![Add Repo](/images/clone_repo.png)

Perform a clone of the existing repository using the repository connection information:
```bash 
# git clone git@github.com:codeHaiku22/testrepository.git
```
## Check Status of Files in the Local Repository
Once a source repository has been cloned locally it is expected that files will be modified, added, and deleted.

Obtain a status of what has has changed when comparing the local repository with the source repository.
```bash
# git status .
```
## Add/Stage Changes in the Local Repository
The changes which have occurred in the local repository should be staged so that they can be synchronized to the source repository.  

Add/stage the changes on the local repository:
```bash
# git add .
```
## Perform Another Status Check of Files in the Local Repository (Optional)
Optionally, perform another stats check to ensure that all changes have been added/staged:
```bash
# git status .
```
## Commit the Changes in the Local Repository
Prior to synchronizing the local repository to the source repository, it is recommended that a note be created during the commit.

Perform a commit and add a useful note:
```bash
# git commit -m "Added additional text file."
```

## Push the Changes in the Local Repository to the Source Repository
The final step is to push the changes made in the local repository to the source reposirotry.  AFter this step is complete, the local and source repositories will once again contain the same content.

Push changes made in the local repository to the source repository:
```bash
# git push
```

## Update the Local Repository
To update the local repository with any changes that may have been made in the source repository, 

Update the local repository:
```bash
# git pull
```
