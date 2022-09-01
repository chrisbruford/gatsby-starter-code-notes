---
title: Git cheat sheet
tags:
  - git
emoji: 👨🏻‍💻
modified: 2022-31-08
link: chrisbruford.com
---

There are some git commands I always forget because of how infrequently I use them. So here they are as I remember them:

### Creating a pretty list of commits between two versions
```bash
git log v2.2.0..v2.2.3  --format="%C(auto) %h %s"
```
