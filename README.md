# GitHub Fundamentals

Repository for the `GitHub Fundamentals` training.

## 👉 Objectives

- Learning to __navigate GitHub__ and know the most important features (including shortcuts and search)
- Use __GitHub Mobile__, emails, and web to efficiently manage your __notifications__
- Use GitHub-flavored __Markdown__ to create rich content and collaborate
- Use __Discussions__ and __Wikis__ with Markdown to collaborate and create content
- Learn about your __User Profile__, __Contributions__, __Achievements__, and __For You__  
- Create __nested issues__ and __labels__ to track work and requirements
- Manage and track your work and requirements using __GitHub Projects__ (including visualization)
- Effective collaboration using __pull requests__ and __code reviews__ (draft pull requests, suggestions, auto-merge)

## Getting ready

Please check the [prerequisites](#-prerequisites) so that you have everything prepared.

## 👥 Audience

This training is for all other roles involved in product development besides developers - like `product owners`, `designers`, or any other type of `stakeholder`. The audience can also contain people completely new to engineering. That's why we try not to use the command-line and do everything in visual tools. The focus of this training are the collaboration features and how to use them effectively.

## ⚡ Prerequisites

For this workshop you need the following:

- A laptop (Windows, Mac, or Linux)
- A free account for [https://github.com](https://github.com/signup)
- It is recommended to have a second screen for the hand-on labs

## 📆 Agenda

### Part 1.1: 🚀 GitHub Fundamentals

- [ ] [Navigating GitHub](#-navigating-github)
- [ ] [Mobile and Profile](#-mobile-and--profile)
- [ ] GitHub-flavored [markdown](#-markdown)

### Part 1.2: 🗒️ Collaborate on ideas

- [ ] [GitHub Discussions](#-discussions)
- [ ] [Wikis and Pages](#%EF%B8%8F-wikis-and--pages)
- [ ] [GitHub Issues](#%EF%B8%8F-github-issues)
- [ ] [GitHub Projects](#-github-projects)

## 🧭 Navigating GitHub

### 🏠 GitHub

Navigate to github.com and inspect the menus and the feed. Note the the `For You` feed can be customized by clicking `show less activity like that` in the menu of the items.

<!-- markdownlint-disable MD001 MD033 -->

<img width="655" alt="image" src="https://user-images.githubusercontent.com/5276337/199487145-4dce52c9-5a33-4f5a-8bb3-b2ff9c91bb58.png">

### ⌨️ Keyboard shortcusts

Press <kbd>?</kbd> everywhere in GitHub to get context-sensitive list of [keyboard shortcuts](https://docs.github.com/en/get-started/using-github/keyboard-shortcuts).

<img width="310" alt="image" src="https://user-images.githubusercontent.com/5276337/199472442-3f4d0f40-60fd-40fe-88f3-35040833b00f.png">

Try some. Here is a list you should at least try out:

- [ ] Press <kbd>.</kbd> to open the current repository in [github.dev](https://github.dev/) (Visual Studio Code in the browser) or <kbd>></kbd> to open it in a new tab.
- [ ] Press <kbd>s</kbd> or <kbd>/</kbd> to start a search.
- [ ] Press <kbd>g</kbd>+<kbd>n</kbd> to go to the notifications

### 🔍 Command palette

Press the following keyboard shortcuts to [open the command palette](https://docs.github.com/en/get-started/using-github/github-command-palette):

- Mac: <kbd>Command</kbd>+<kbd>K</kbd> or <kbd>Command</kbd>+<kbd>Option</kbd>+<kbd>K</kbd>
- Windows and Linux: <kbd>Ctrl</kbd>+<kbd>K</kbd> or <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>K</kbd>
  
<img width="310" alt="image" src="https://user-images.githubusercontent.com/5276337/199483344-9a832d0a-4741-4277-8135-108b7f8fabbe.png">

- [ ] Press <kbd>#</kbd> to search for issues, pull requests, discussions, and projects
- [ ] Use filters like `# author:@me` or `# is:pr` in your search
- [ ] Press <kbd>!</kbd> to search for projects
- [ ] Press <kbd>/</kbd> to search for files
- [ ] Press <kbd>?</kbd> to get help
- [ ] Use <kbd>Tab</kbd> and <kbd>Backspace</kbd> or <kbd>Delete</kbd> to navigate in GitHub
- [ ] Use <kbd>Enter</kbd> to select the item / navigate to it
- [ ] Use <kbd>Ctrl</kbd>+<kbd>Backspace</kbd> (Windows / Linux) or <kbd>Command</kbd>+<kbd>Delete</kbd> (Mac) to clear the scope and textbox
- [ ] Use <kbd>Esc</kbd> to close the command palette (or the same keyboard shortcut you used to open it).

### ⚡ Running commands

Press the following keyboard shortcuts to [open the command palette in command mode](https://docs.github.com/en/get-started/using-github/github-command-palette#running-commands-from-the-github-command-palette):

- Mac: <kbd>Command</kbd>+<kbd>Shift</kbd>+<kbd>K</kbd>
- Windows and Linux: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>K</kbd> or <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>K</kbd>

<img width="310" alt="image" src="https://user-images.githubusercontent.com/5276337/199553436-9bc15185-ffd1-4a5c-bdd6-aac63980f516.png">

Try commands like:

- [ ]  `Switch theme`
- [ ]  `New gist`
- [ ]  `New repository`

## 📱 Mobile and 👤 Profile

### 👤 User profile

The user profile is the starting point for all personal owned repositories, projects, and packages.
It can be customized:

- [ ] Profile pic, name, and bio
- [ ] Metadata (location, twitter handle, url, company)
- [ ] You can add a readme by creating a repositoriy with the same name as your user name and adding a `Readme.md` there
- [ ] You can pin repositories to the user profile

<img width="635" alt="image" src="https://user-images.githubusercontent.com/5276337/199670576-81ec4c53-6be9-447a-aaf5-f22d1deb3f4f.png">

### 🌟 Stars

Starring a repository is not only an endorsement. You can use stars in star lists to organize repositories that are important. Like favorites in your browser.

<img width="546" alt="image" src="https://user-images.githubusercontent.com/5276337/199671174-a304637b-1fb5-46ef-b987-8b8af3d45ff1.png">

### 🏆 Contributions

You can also see all your contributions that happend on GitHub.

<img width="464" alt="image" src="https://user-images.githubusercontent.com/5276337/199671371-81930feb-3f2b-441a-bd9f-47d4f9617efe.png">

### 📣 Notifications

Manage your notifications in [:bell:](https://github.com/notifications):

<img width="500" alt="image" src="https://user-images.githubusercontent.com/5276337/204130941-20e8725b-a158-4c3d-938a-d18599926d2d.png">

- Configure notifications settings and routing in [settings/notifications](https://github.com/settings/notifications)
- Manage [watched repositories](https://github.com/watching)
- Manage [your subscriptions](https://github.com/notifications/subscriptions)

### 📱 GitHub Mobile

[GitHub Mobile](https://github.com/mobile) is a mobile app for iOS and Android. It can help you to manage your notifications when you are not at your on the go. You can also use it to collaborate and even to review pull requests.  

<img width="501" alt="image" src="https://user-images.githubusercontent.com/5276337/204131228-2a4ba5d0-d5ca-49ee-a9aa-487ab5bbe5a5.png">

## 📖 Markdown

Explore the posibilities of [GitHub-flavored markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax). You can find many examples [here](https://github.com/wulfland/AccelerateDevOps/blob/main/docs/about-markdown.md?plain=1) and [how they get rendered](https://github.com/wulfland/AccelerateDevOps/blob/main/docs/about-markdown.md)

## 💬 Discussions

### 🔨 Hands-on: Using with GitHub Discussions

Create [new discussions](/../../discussions/new):
- [ ] Ask the others something (about their hobbies, favorit food, favorit GitHub features so far, and so on) 
- [ ] Look for other questions and provide an answer
- [ ] Mark your question as answered with the answer you like the most
- [ ] Create a poll and ask people to vote for one of your favorite movies
- [ ] Look for other polls and respond to them

> **Note**  
> Use markdown to express yourself. Use as many markdown features as possible.

## 🗒️ Wikis and 🌐 Pages

GitHub contains a wiki in each repository (see [this example](https://github.com/wulfland/AccelerateDevOps/wiki)). The wiki has a custom header and footer.

<img width="500" alt="image" src="https://user-images.githubusercontent.com/5276337/204132297-8fea2ca1-53e9-43a1-8aff-267fb30d12fc.png">

The wiki supports many different renderers - not only markdown.

<img width="400" alt="image" src="https://user-images.githubusercontent.com/5276337/204132252-40a5f7b8-cb3a-4b28-b858-7b7cd8426ecd.png">

GitHub pages is a static webpage that can diplay files from the repository as a rendered web page. 

<img width="396" alt="image" src="https://user-images.githubusercontent.com/5276337/204132589-72544d3e-b291-4cef-a03e-502058bc750c.png">

It can use [Jekyll](https://jekyllrb.com/) to render markdown files as web pages. See [this example](https://github.com/wulfland/AccelerateDevOps/tree/main/docs) that gets rendered as [this web site](https://wulfland.github.io/AccelerateDevOps/).

## ✍️ GitHub Issues

- [ ] Pinnes Issues, sort, filter and lables

<img width="636" alt="image" src="https://user-images.githubusercontent.com/5276337/204133374-7b3e0ef4-24a1-4002-8a9b-f613d33ddd95.png">

See [this issue](https://github.com/wulfland/AccelerateDevOps/issues/436) for more details.

- [ ] Issue templates
- [ ] Nesting Issues
- [ ] Lables and Milestones

### 🔨 Hands-on: working with Issues

- [ ] Create a [new issue](../../issues/new) called `🏆 Awesome and epic initiative from [username]` (replace [username] with your GitHub user name).
- [ ] Assign the issue to yourself
- [ ] Apply a label `Epic` to the issue (create the label if it does not exist yet)
- [ ] Add a task list with three tasks to the description of the epic
  - [ ] `🎸 A feature from [username] that rocks`
  - [ ] `⚡ Another epic feature from [username]`
  - [ ] `🔥 Hot feature from [username]`
- [ ] Convert the tasks to issues

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204148043-9e269c5c-16fd-46dd-9b3e-387652261338.png">

- [ ] Open the issues, assign them to yourself, and apply the label `Feature` (create the label if it does not exist yet)
- [ ] Select one of the issues and open it. Add again three tasks and convert them to new issues:
  - [ ] `👥 User Story from [username]`
  - [ ] `❤️ Things users ❤️ from [username]`
  - [ ] `💯 Crazy feature from [username]`

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204149026-7e3ae375-fab2-4ef8-a950-1b497258e58b.png">

 - [ ] Open the created issues, assign them to yourself, and apply the label `User Story` (create the label if it does not exist yet)
 - [ ] Close one of the issues and note the indicators that allwo you to navigate between the issues. 

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204149146-6f76cbef-df1d-4d89-8f75-8dc49dc3d9a6.png">

- [ ] Create [a new milestone](../../milestones/new) `Backlog [username]` without due date and add all your user stories 

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204149627-5d22f3aa-b164-445e-b35f-9d6d0884abe4.png">

- [ ] Use drag and drop to sort the user stories fir the milestone and use <kbd>shift</kbd>+<kbd>j</kbd> or <kbd>shift</kbd>+<kbd>k</kbd> to move items with the keyboard. Note the progression through the closed user story.

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204149689-61a7a265-8334-4deb-b821-71e96d73ae37.png">

- [ ] Create [a new issue template](../../issues/templates/edit) and choose bug report or just create a [new file](../../new/main) `.github/ISSUE_TEMPLATE/bug_report_[username].md` (replace [username] with your GitHub user name)
- [ ] Open the file or `preview and edit`and make sure the filename contains your user name.

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204149991-f2f0d8ea-0d2c-4fc1-838b-34e3cbaa787e.png">

- [ ] Adjust the meta data to contain your name, a title, a label, and an assignee:

```yaml
---
name: 🐞 Bug report wulfland
about: Create a report to help us improve
title: '[Bug]:'
labels: 'bug'
assignees: 'wulfland'

---

**Describe the bug**
A clear and concise description of what the bug is.

...
```

- [ ] Create [a new issue](../../issues/new/choose) and chose your template:

<img width="500" alt="image" src="https://user-images.githubusercontent.com/5276337/204150390-cc792022-5723-4af6-800d-826290269f5d.png">

- [ ] Note the pre-filled data:

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204150422-9c0d0aaf-f1aa-4b5a-ba66-6876f1636495.png">

- __Optional:__ Only if time permits: create a custom issue template. See [this template](https://github.com/wulfland/AccelerateDevOps/blob/main/.github/ISSUE_TEMPLATE/custom.yml) as an example. Also configure that blank issues are not allowed and add an additional URL to the `New issue` dialog ([this example](https://github.com/wulfland/AccelerateDevOps/blob/main/.github/ISSUE_TEMPLATE/config.yml) should help you getting started).

## 📆 GitHub Projects
