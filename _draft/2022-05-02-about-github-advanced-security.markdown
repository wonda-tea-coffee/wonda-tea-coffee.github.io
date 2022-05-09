---
layout: post
title:  "About Github Advanced Security"
date:   2022-05-02 20:07:00 +0900
categories: security
---

## Interesting point
- https://docs.github.com/en/enterprise-cloud@latest/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/managing-security-and-analysis-settings-for-your-repository#granting-access-to-security-alerts

> Organization owners and repository administrators can only grant access to view security alerts, such as secret scanning alerts, to people or teams who have write access to the repo.

Security personnel can access any security function without administrative privileges as long as they are granted access privileges.

## Unknown point
- https://docs.github.com/en/enterprise-cloud@latest/billing/managing-billing-for-github-advanced-security/about-billing-for-github-advanced-security

> Users should always create branches from a recent base, or rebase them before pushing. This will ensure that users who have not committed in the last 90 days do not take up GitHub Advanced Security seats.

I don't see why a user who has not authored in the last 90 days would use the GitHub Advanced Security seats.

## Reference
- [x] [About GitHub Advanced Security](https://docs.github.com/en/enterprise-cloud@latest/get-started/learning-about-github/about-github-advanced-security)

- [x] [Managing security and analysis settings for your repository](https://docs.github.com/en/enterprise-cloud@latest/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/managing-security-and-analysis-settings-for-your-repository)

- [x] [Managing billing for GitHub Advanced Security](https://docs.github.com/en/enterprise-cloud@latest/billing/managing-billing-for-github-advanced-security)

- [x] [Using starter workflows](https://docs.github.com/en/enterprise-cloud@latest/actions/using-workflows/using-starter-workflows)

- [x] [GitHub Actions / Security guides](https://docs.github.com/en/actions/security-guides)

- [x] [About GitHub's use of your data](https://docs.github.com/en/enterprise-cloud@latest/get-started/privacy-on-github/about-githubs-use-of-your-data)

- [ ] [Keeping your organization secure](https://docs.github.com/en/enterprise-cloud@latest/organizations/keeping-your-organization-secure)

- [ ] [Managing security managers in your organization](https://docs.github.com/en/enterprise-cloud@latest/organizations/managing-peoples-access-to-your-organization-with-roles/managing-security-managers-in-your-organization)

- [ ] [Code security](https://docs.github.com/en/enterprise-cloud@latest/code-security)

- [ ] [github/roadmap](https://github.com/github/roadmap/issues?q=is%3Aissue+is%3Aopen+label%3A%22github+advanced+security%22)
