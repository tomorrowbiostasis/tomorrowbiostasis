# Contributing to Biostasis:

Welcome 👋 We are really happy that you're interested in contributing to Biostasis. Below you'll find some guidelines to help you get started.

## Table of content:
  - [Overview](#overview)
  - [Label Meanings](#label-meanings)
  - [How to Contribute](#how-to-contribute)
  - [Code of Conduct](#code-of-conduct)
  - [Observation before Implementation](#observation-before-implementation)
  - [Run Locally](#run-locally)
  - [Final Message](#final-message)

## Overview:
If you started with our main [ReadMe](README.md) file, you may already know that we have 3 different repositories [Biostasis-Backend](https://github.com/tomorrowbiostasis/Biostasis-Backend), [Biostasis-Frontend](https://github.com/tomorrowbiostasis/Biostasis-FrontEnd), and [Biostasis-Cloud-Infrastructure](https://github.com/tomorrowbiostasis/Biostasis-Cloud-infrastructure). The Frontend and Backend can work separately or together. **However, both need cloud and external services to work perfectly.**

So make sure to read the documentation carefully for each repository to have a clear understanding of how the application works 😊.

## Label Meanings:
The labels that get applied to issues and PRs in our repos have specific meanings and are broken into two categories: **status** and **type**. An issue/PR should only ever have one status label, but can have multiple type labels. The following isn't a complete list, but rather a list of the labels that are more universal across all of our repos.
  
  #### 1. Status Labels:
  - **Accepted:** This PR has been accepted and is able to be merged
  - **Discussion:** This issue/PR has an ongoing discussion
  - **Help Wanted:** This issue can be assigned to other contributors
  - **In Progress:** This issue/PR has ongoing work being done
  - **On Hold:** There is a temporary hold on any continued work or review
  - **Under Review:** This issue/PR is being reviewed by at least one maintainer
  
  #### 2. Type Labels:
  - **Bug:** Involves something that isn't working as intended
  - **Documentation:** Involves an update to the documentation
  - **Duplicate:** This issue/PR already exists
  - **Easy Fix:** Involves a minor fix such as grammar, syntax, etc.
  - **Enhancement:** Involves a new feature or enhancement request
- **Epic:** This issue is a larger, unnamed project with several moving parts
- **Good First Issue:** Good for beginner contributors
- **Priority:** This issue/PR should be resolved ASAP

## How to Contribute:

**Discussions**: 

If you are looking to discuss an issue or feature with other maintainers or contributors, Please visit the repo's discussion page. ***we are planning to create a Discord server in the future when our community gets bigger*** 🤞.    


**Issues:** 

If you have an issue or problem, Please visit the repo's issue page. There you will find specific templates for different purposes (Bug template - Feature template - custom template). Pick the one related to your issue and give more details about it. The more you describe, the easier you get help from others :)

- **Small issues or changes:** These don't have an overall significant impact. You can just open an issue or a PR in the appropriate repo rather than needing to bring it up in the discussion page.

- **Big issues or changes**: You can either go to our discussion page connected to the repo to mention an issue or propose a change, or you can simply open an issue and wait to receive a response. 

  Opening a new discussion about your change/issue lets the community and maintainers provide support and help. Furthermore, it lets them get a better understanding of your proposal. 
  
  You should never submit a PR for a significant issue or change without first getting approval from maintainers. we don't want your time and work to go to waste if your proposal isn't accepted.

## Code of Conduct:
We have a code of conduct in place to ensure that our community is welcoming and inclusive. Please review our [code of conduct](CODE_OF_CONDUCT.md) before contributing.

## Observation before Implementation:
Please make sure to do a quick tour on our repository to gain a practical understanding of how everything works. Also, before creating an issue, make sure that no one previously mentioned it before you. This will help (you and us) avoid any duplicates from being made, as well as prevent more than one person working on the same thing at the same time.

If your proposal already exists in an open issue or PR, but you feel there are details missing or more info to add, comment on the issue/PR to let those involved know.

## Run Locally:
You already decided that you want to be part of our community and leave your touch on our application. So, please follow the steps to get your own copy of the repo that you want to work on:
  
  1- Fork the repo to your own GitHub account. If you don't know how to do so, follow the GitHub documentation on how to [fork a repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo).

  2- Clone the repo to your local machine using the command below. You can also read the GitHub documentation on [cloning a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository).

``` 
git clone <SSH or HTTPS url 'your fork repo'> 
```
  3- Navigate to the repo directory on your machine using ``` cd ```, then set the upstream remote so you can keep your local clone synced with the original repo.

``` 
git remote add upstream <SSH or HTTPS url 'main repo'>
```

### I would like to work on an issue 🧐:

  Glad to hear that 🤗
  -

- Once you have the repo forked and cloned, and the upstream remote has been set, you can begin working on your issue.

- Create a new branch, replacing the ```<branch name>``` with an actual branch name that briefly explains the purpose of the branch in some way:
  ```
  git checkout -b <branch name>
  ```

- Add commits as you work on your issue. Make sure that your commits explain your work accurately, it will make it easier for the maintainers and other developers to understand your changes.

- Replacing the ```<commit message>``` text with your actual commit message:

  ```
  git commit -m "<commit message>"
  ```
- Make sure you are sync with the upstream remote every now and then. 

- Push your branch to your forked repo, replacing the ```<branch name>``` with the branch you've been working on locally:

  ```
  git push origin <branch name>
  ```

### Now I want to create a pull request 💪:
Congrats on reaching this step 🥳
  -  

- After you finish pushing all your commit to a specific branch, go to your forked repo on GitHub and click the "Compare & pull request" button. If you have multiples of this button, be sure you click the one for the correct branch.
  ![compare & pull request](https://i.stack.imgur.com/7yscx.png)

- A maintainer will either leave general comments, request changes, or approve and merge your PR. 
  
  It is important to respond to any comments or requested changes in a timely manner, otherwise your PR may be closed without being merged due to inactivity. 

  After pushing any requested changes to the branch you opened the PR with, be sure to re-request a review from the maintainer that requested those changes.

## Final Message:
We appreciate every and each one of you who considered contributing to the biostasis application. 

Any small or big impact is always meaningful to us 🥰.
