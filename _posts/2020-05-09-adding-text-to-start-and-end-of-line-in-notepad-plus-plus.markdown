---
layout: post
title: Adding Text to the Start and End of Line in Notpad++
date: 2020-05-09 00:00:020 +0530
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: i-rest.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: ["Regular Expressions", "Notepad++"]
---

# Adding "test" to Start of Line

- Press CTRL-H to bring up the Find/Replace Dialog.

- Choose the "Regular expressions" checkbox near the bottom of the dialog.

- To add "test" to the beginning of each line, type "^" in the "Find what" field, and "test" in the "Replace with" field.

-Then hit "Replace All".

# Adding "test" to End of Line

- Press CTRL-H to bring up the Find/Replace Dialog.

- Choose the "Regular expressions" checkbox near the bottom of the dialog.

- To add "test" to the end of each line, type "\$" in the "Find what" field, and "test" in the "Replace with" field.

- Then hit "Replace All".
