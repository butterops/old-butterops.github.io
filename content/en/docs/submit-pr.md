---
title: "Creating and submit a pull request"
date: 2019-12-18T10:33:41+09:00
description: Less IT even Lesser Ops
draft: false
hideToc: false
enableToc: false
enableTocContent: false
author: measdot
authorEmoji: 🎅
pinned: false
tags:
- tools
- work-culture
series:
-
categories:
- Community
# image: logo.png
---

You should usually open a pull request in the following situations:

- Submit trivial fixes (for example, a typo, a broken link or an obvious error)
- Start work on a contribution that was already asked for, or that you’ve already discussed, in an issue

A pull request doesn’t have to represent finished work. It’s usually better to open a pull request early on, so others can watch or give feedback on your progress. Just mark it as a “WIP” (Work in Progress) in the subject line. You can always add more commits later.

If the project is on GitHub, here’s how to submit a pull request:

- **Fork the repository and clone it locally.** Connect your local to the original “upstream” repository by adding it as a remote. Pull in changes from “upstream” often so that you stay up to date so that when you submit your pull request, merge conflicts will be less likely. (See more detailed instructions here.)
- **Create a branch** for your edits.
- **Reference any relevant issues** or supporting documentation in your PR (for example, “Closes #37.”)
- **Include screenshots of the before and after** if your changes include differences in HTML/CSS. Drag and drop the images into the body of your pull request.
- **Test your changes!** Run your changes against any existing tests if they exist and create new ones when needed. Whether tests exist or not, make sure your changes don’t break the existing project.
- **Contribute in the style of the project** to the best of your abilities. This may mean using indents, semi-colons or comments differently than you would in your own repository, but makes it easier for the maintainer to merge, others to understand and maintain in the future.
