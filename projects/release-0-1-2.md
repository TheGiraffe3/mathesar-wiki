---
title: Release v0.1.2
description: 
published: true
date: 2023-04-06T15:04:15.655Z
tags: 
editor: markdown
dateCreated: 2023-04-06T13:47:41.302Z
---

**Name**: Release v0.1.2
**Status**: In review 

## Introduction
* This project is a collection of items needed for v0.1.2 release.
* Primary focus of v0.1.2:
  - [Installation improvements](./installation-improvements.md)
  - Ability to switch user databases
  - Fixes and improvements based on user raised issues/bugs
* The spec for Installation improvements is [tracked separately](./installation-improvements.md) as it is a project of it's own.
* The team should prioritize release items assigned to them until the release is complete.

## Team
| Role | Assignee | Notes |
|-|-|-|
| **Owner** | Pavish | |
| **Approver - Project plan** | Kriti | *Needs to approve project plan* |
| **Contributor - Design** | Ghislaine | *Creates designs for 'switching user databases'* |
| **Contributors - Design review** | Sean, Pavish, Kriti (final approval) | *Reviews UX design* |
| **Contributor - Frontend** | Pavish | *Implements frontend for 'switching user databases' and works on any critical frontend issue that might come up during the release cycle* |
| **Contributor - Frontend review** | Sean | *Reviews frontend code* |
| **Contributor - Backend** | Dominykas | *Ensures 'switching user databases' works as expected and works on any crticial backend issue that might come up during the release cycle* |
| **Contributor - Backend review** | Mukesh | *Reviews backend code* |
| **Contributor - Hiring testing team** | Kriti | *Hires testing team and creates required communication channels* |
| **Contributor - Managing testing team** | Pavish | *Organizes/communicates with team for testing the release* |
| **Contributors - Testing plan** | Pavish, Mukesh (for installation testing plan) | *Comes up with the release testing plan* |
| **Contributors - Testing** | Testing team from Upwork | *Performs testing* |

## Work plan
- Create necessarry issues and clean up milestone v0.1.2.
- Installation improvements and Implementation of switching user databases will happen in parallel.
  - Any critical issue that comes up during this phase will be taken up in the same release based on effort involved and user impact.
  - If an issue requires a hotfix, it will take the hightest priority and v0.1.2 will be a hotfix release, and this plan will shift to the next release.
- Hire testing team, prepare testing plan, and manage testing once required features are complete.
- Handle issues that might come up during testing.
- The release process will remain same as our previous releases.
  - Here is the [release process document for creating a release](https://wiki.mathesar.org/en/engineering/release-process).
  - The release management ongoing responsibility is not yet documented. It will be updated during the course of this release and will contain more detailed information.

The plan is more high level, since individual tasks will be tracked using GH issues.

## Risks
- There are unknowns with testing since we're hiring external people, which might affect the timeline.
- Issues uncovered during testing might affect the timeline.

## Resources
- **Milestone**: [v0.1.2](https://github.com/centerofci/mathesar/milestone/68)

## Timeline
* The timeline will be updated with more details once the [Installation improvements project](https://wiki.mathesar.org/en/projects/installation-improvements.md) is specced out and approved.
* Tentative deadline:
  * The maximum time allocated for the release will be **16 working days**.
  * Based on schedules of everyone involved, the starting date will be **2023-04-10**, which marks the deadline to be **2025-05-01**. This includes a buffer period of 4 working days.