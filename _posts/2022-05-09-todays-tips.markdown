---
layout: post
title:  "Today's tips"
date:   2022-05-09 19:52:00 +0900
categories: security
---

The following commits were recently merged into the main rails branch
<https://github.com/rails/rails/pull/44985>

This is a fix to a spell checker that runs in Github Actions.
The spell checker to be installed has been changed from a specific branch to a specific commit hash.

In its unmodified state, if a malicious person injected code into the target branch, arbitrary code would be executed during Github Actions execution.

This is an excellent fix.
I would like to follow up on this for projects I am involved in.
