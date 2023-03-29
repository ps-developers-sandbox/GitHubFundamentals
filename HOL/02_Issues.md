# 🔨 Hands-on: working with Issues

In this hands-on lab, you will practice working with nested Issues, Labels, Milestones, and Issue Templates. 

The lab contains the following sections:
- [Creating and nesting issues](#creating-issues)
- Working with [Milestones](#milestones)
- Working with [Issue Templates](#issue-templates)

## Creating Issues

- [ ] Create a [new issue](../../../issues/new) called `🏆 Awesome and epic initiative from [username]` (replace [username] with your GitHub user name).
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

> **Note**  
> Note that the task list of nested issues has to be in the description - not a comment. Edit the first entry in the Issue instead of adding a new comment.

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204149026-7e3ae375-fab2-4ef8-a950-1b497258e58b.png">

 - [ ] Open the created issues, assign them to yourself, and apply the label `User Story` (create the label if it does not exist yet)
 - [ ] Close one of the issues and note the indicators that allwo you to navigate between the issues. 

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204149146-6f76cbef-df1d-4d89-8f75-8dc49dc3d9a6.png">

## Milestones

- [ ] Create [a new milestone](../../../milestones/new) `Backlog [username]` without due date and add all your user stories 

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204149627-5d22f3aa-b164-445e-b35f-9d6d0884abe4.png">

- [ ] Use drag and drop to sort the user stories for the milestone and use <kbd>shift</kbd>+<kbd>j</kbd> or <kbd>shift</kbd>+<kbd>k</kbd> to move items with the keyboard. Note the progression through the closed user story.

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204149689-61a7a265-8334-4deb-b821-71e96d73ae37.png">

## Issue templates

- [ ] Create [a new issue template](../../../issues/templates/edit) and choose bug report or just create a [new file](../../new/main) `.github/ISSUE_TEMPLATE/bug_report_[username].md` (replace [username] with your GitHub user name)
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

- [ ] Create [a new issue](../../../issues/new/choose) and chose your template:

<img width="500" alt="image" src="https://user-images.githubusercontent.com/5276337/204150390-cc792022-5723-4af6-800d-826290269f5d.png">

- [ ] Note the pre-filled data:

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204150422-9c0d0aaf-f1aa-4b5a-ba66-6876f1636495.png">

- __Optional:__ Only if time permits: create a custom issue template. See [this template](https://github.com/wulfland/AccelerateDevOps/blob/main/.github/ISSUE_TEMPLATE/custom.yml) as an example. Also configure that blank issues are not allowed and add an additional URL to the `New issue` dialog ([this example](https://github.com/wulfland/AccelerateDevOps/blob/main/.github/ISSUE_TEMPLATE/config.yml) should help you getting started).

## Summary

In this hands-on lab you've practiced to work with nested Issues, Labels, Milestones, and Issue Templates. 

You can now continue with [GitHub Projects](../01_02_Collaborate-on-ideas.md#-github-projects)
