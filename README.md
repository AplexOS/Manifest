# AplexOS Repositories Manage Specification

## 1. Set Git Configure

```shell
    git config --global user.name "ZoroZeng"
    git config --global user.email "aplexos@163.com"
```

## 2. Generate SSH Key

```shell
    ssh-keygen -t rsa -C "aplexos@163.com"
```


## 3. Get git-repo Tools

```shell
    cd ~ && mkdir aplexos && cd aplexos && git clone git://git.omapzoom.org/git-repo.git
```


## 4. Get All Repos SPEC

```shell
    mkdir AplexOS-Repos-Manage_All_SPEC && cd AplexOS-Repos-Manage_All_SPEC 
```

### 4.1 init Repo

```shell
    ../git-repo/repo init -u https://github.com/AplexOS/Manifest.git -b AplexOS-Repos-Manage_All_SPEC
```

### 4.2 sync Repo

```shell
    ../git-repo/repo sync --no-tags
```
