---
id: ssh
title: SSH
sidebar_label: SSH
---

## SSH for Github

Generate key.

```sh
ssh-keygen -t rsa -b 4096 -f ~/.ssh/github
```

Update `~/.ssh/config` to something like:

```sh
Host github.com
  HostName github.com
  User git
  PreferredAuthentications publickey
  IdentityFile ~/.ssh/github
```

Add `.pub` as "New SSH Key" to Github -> Settings

Test by running `ssh -T git@github.com`. All is good if you see something like:
> "Hi username! You've successfully authenticated, but GitHub does not provide shell access.
