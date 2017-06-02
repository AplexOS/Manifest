# AplexOS Repositories Manage Specification

## 1. Set Git Configure

* `git config --global user.name "ZoroZeng"`
* `git config --global user.email "<Your Email>"`

## 2. Generate SSH Key

* `ssh-keygen -t rsa -C "<Your Email>"`


## 3. Get git-repo Tools

* `cd ~ && mkdir AplexOS && cd AplexOS && git clone git://git.omapzoom.org/git-repo.git`


## 4. Get All Repos SPEC

* `mkdir AplexOS-Repos-Manage_All_SPEC && cd AplexOS-Repos-Manage_All_SPEC`

### 4.1 Init Repo

* `../git-repo/repo init -u https://github.com/AplexOS/Manifest.git -b AplexOS-Repos-Manage_All_SPEC`

### 4.2 Sync Repo

* `../git-repo/repo sync --no-tags`

### 4.2 Create branch

* `../git-repo/repo start master --all`

### 4.3 Checking branch

* `../git-repo/repo branch`

### 4.4 If you has modify repository, check the repsitory status

* `../git-repo/repo status`
* `../git-repo/repo diff`
* `../git-repo/repo diff Manifest`

### 4.5 Modify, push to remote repository

* `cd <your has modified repository>`
* `git add .`
* `git commit -m <message>`
* `git push <github repository url> <branch>`
