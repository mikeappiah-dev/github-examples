## Cloning

- There are three ways to clone a repository : HTTPS, SSH, Github CLI.

1. HTTPS Cloning:

```sh
! Note : you will need credentials for cloning private repos.
git clone https://github.com/mikeappiah-dev/github-examples.git

> On an isolated editor environment from github, like codespaces, you need to have the credentials of the github account, or a personal access token to push to it.
```

2. SSH Cloning:

```sh  
! Note : you need an ssh key pair to for this type of cloning

ssh-keygen -t ed25519 -C 'this is my githup cloning ssh key public key'

git clone git@github.com:mikeappiah-dev/github-examples.git
```

## Commits

## Branches

## Stashing

## Merging

## Git Reset

- Used to undo changes within the local repository

## Git config file

- Store global configurations for your local git installation, such as email, username, editor and more.

## Git log

- shows the local repository tree.
