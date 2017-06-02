# Manifest

Repo Manifest Repository

## 1. Branch Namimg Specification

* **branch namimg format**: (product name)\_(system type)\_(manifest type)
  * **product name**:
    * SBC-7112S;
    * SBC-7112S-Q;
    * SBC-7109S-454;
  * **system type**:
    * Linux3.0.35;
    * Android4.2.2;
    * All;
  * **manifest type**:
    * SRC(Source Code)
    * SPEC(Specification)
    * BSP(Board Support Package)
* **E.g**:  
`SBC-7109S-454`(product name)`_Linux`(system type)`_SPEC`(manifest type) = `SBC-7109S-454_Linux_SPEC`

## 2. Configure git and Get git-repo 

* 2.1 Set Git Configure
  * `git config --global user.name "<Your Account Name>"`
  * `git config --global user.email "<Your Email>"`
* 2.2 Generate SSH Key
  * `ssh-keygen -t rsa -C "<Your Email>"`
* 2.3 Get git-repo Tools
  * `cd ~ && mkdir AplexOS && cd AplexOS && git clone git://git.omapzoom.org/git-repo.git`
* 2.4 Export the `git-repo directory path` to environmental variable **PATH** 

## 3. Branches

* [AplexOS Repositories Manage Specification](https://github.com/AplexOS/Manifest/tree/AplexOS-Repos-Manage_All_SPEC)

