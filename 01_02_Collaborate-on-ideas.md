# Part 1.2: 🗒️ Collaborate on ideas

In this part you will learn and practice how to collaborate on Ideas. The part contains the following topics:  

- [ ] [GitHub Discussions](#-discussions)
- [ ] [Wikis and Pages](#%EF%B8%8F-wikis-and--pages)
- [ ] [GitHub Issues](#%EF%B8%8F-github-issues)
- [ ] [GitHub Projects](#-github-projects)

## 💬 Discussions

<img width="423" alt="image" src="https://user-images.githubusercontent.com/5276337/204153901-5d22c9af-0fa8-4236-b4d4-6d3185d1ce08.png">

### 🔨 Hands-on: [Using with GitHub Discussions](https://github.com/ps-developers-sandbox/GitHubFundamentals/blob/main/HOL/01_Discussions.md)

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

See this example [Team backlog](https://github.com/users/wulfland/projects/9/views/1) as an example.

### 🔨 Hands-on: Working with GitHub Projects

- [ ] Create a new project:

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204151147-dae0f9e9-3b11-4947-88a8-a931ab7a95d7.png">

- [ ] Select `Table` and click `Create`:

<img width="500" alt="image" src="https://user-images.githubusercontent.com/5276337/204151235-d15fbaa5-bd84-4fb9-957e-d88d57bf4625.png">

- [ ] Rename the project to `🏆  Team backlog`

<img width="500" alt="image" src="https://user-images.githubusercontent.com/5276337/204151296-59f56a27-9126-4551-85e6-1f11bfb15fc0.png">

- [ ] Click the <kbd>#</kbd> key and select the repository. Add all your issues to the board:

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204151419-0f496f97-5814-4cc8-9d67-4f25b392702b.png">

- [ ] Add the default fields `Labels` and `Milestones`:

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204151519-070cad7c-a617-4332-b7b1-62a2c4c90e5d.png">

- [ ] Edit the values for Status and add an icon:
  - [ ] Todo ✍️
  - [ ] In Progress 🚧
  - [ ] Done  ✅

<img width="300" alt="image" src="https://user-images.githubusercontent.com/5276337/204151656-e01a3da6-146b-4fca-85e9-f6daf95fcbff.png">

- [ ] Set all items to `Todo ✍️`
- [ ] Add a new field:

<img width="250" alt="image" src="https://user-images.githubusercontent.com/5276337/204151821-e444b02b-1123-4e8b-9735-073b5766eca1.png">

- [ ] Add a field `Level` with the type `Single Select` and add backlog levels:
  - [ ] Epic 🚀
  - [ ] Feature 🔥
  - [ ] Story 🗣
  - [ ] Task 🔨 

<img width="250" alt="image" src="https://user-images.githubusercontent.com/5276337/204151877-19ed7d69-355c-403c-8f76-00a87818a532.png">

- [ ] Rename the view to `🗒  Backlog`, group it by `Level`, and save changes.

<img width="300" alt="image" src="https://user-images.githubusercontent.com/5276337/204152232-2b980aef-e6b4-484a-bc80-1b94a7ee4d97.png">

- [ ] Switch the view to `Board` and filter by `level:Story 🗣`: 

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204152331-3aa4f249-4a68-443f-bcf6-4b0dfd5c5a37.png">

- [ ] Save changes to a new view `🗣 Story Board` 
- [ ] Add two more fields:
  - [ ] A field `Quater 📆 ` of the type `Iteration`. Set it to 12 weeks starting with the 1st of the current quater.
  - [ ] A field `Effort 🔨` of type `Number`.
- [ ] Create a new view `Planning` with the column field `Quater` and `field sum: Effort`. 
   

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204153014-86f82b1d-711f-47e4-ae96-616b2e6ee50d.png">


- __Optional:__ Only if time permits: Create a new chart and customize lyout, x-axis, group by, and y-axis. 
- __Optional:__ Only if time permits: View the workflows and enable all workflows that you want
- __Optional:__ Add a draft Issue to the backlog and edit the values. Convert it to a real issue.

## Summary

In this part you've learn and practiced how to collaborate on ideas using GitHub Issues, Discussion, Wikis, Pages and Projects.
