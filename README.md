增加视频社交媒体 网红的监测
关键词视频的监测
视频评论的监测

# GitHub Actions Templates
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](.github/CODE_OF_CONDUCT.md)

Automate community integrations for your Orbit workspace with these GitHub Actions template starter files

![First-time setup: create a GitHub account, create a new GitHub repository, add your Orbit details. Each integration: create a new workflow, copy & paste the provided code, follow and integration-specific instructions.](images/main_flow.png)

# Overview

This repository helps you get up and running with third party integrations to Orbit in a matter of minutes.

Inside this repository are template YAML workflow files you can use to automate **third party integrations** with your Orbit workspace.

**What are 3rd party integrations?**

All Orbit users have access to [built-in integrations](https://orbit.love/integrations/), such as GitHub, Twitter, Slack, and Discord. These built-in integrations can be added and set up from within the Orbit app.

Community-built, or 3rd party integrations, are additional integrations offered by the larger Orbit community. While not officially supported, they offer many opportunities to further extend the utility of the platform.

**What is this repository for?**

Within each subfolder of this repository is a GitHub Actions workflow template file, along with instructions on how to use it. GitHub Actions is a runtime environment provided by GitHub to any GitHub user. You can run applications on GitHub Actions for free on any publicly available (*not private*) repository.

# First Time Setup

Before setting up an integration using GitHub Actions, you will need to follow the [First Time Setup Guide](./FIRST_TIME_SETUP.md)

# Available Integrations

The following integration workflows are available to use, and more will be added:

| Platform | Features |
|---|---|
| [Circle](https://github.com/orbit-love/github-actions-templates/blob/main/Circle) | <ul><li>New posts in Circle Spaces</li><li>New comments on Circle Spaces posts</li></ul> |
| [DEV Community](https://github.com/orbit-love/github-actions-templates/blob/main/DEV) | <ul><li>New followers</li><li>New comments</li></ul> |
| [LinkedIn](https://github.com/orbit-love/github-actions-templates/blob/main/LinkedIn) | <ul><li>New comments on posts</li></ul> |
| [Meetup](https://github.com/orbit-love/github-actions-templates/blob/main/Meetup) | <ul><li>New RSVPs for Meetup group events</li></ul> |
| [Notion](https://github.com/orbit-love/github-actions-templates/blob/main/Notion) | <ul><li>New Notes in a Notion database</li></ul> |
| [Planning Center](https://github.com/orbit-love/github-actions-templates/blob/main/PlanningCenter) | <ul><li>New Event Check-ins</li></ul> |
| [Pipedrive](https://github.com/orbit-love/github-actions-templates/blob/main/Pipedrive) | <ul><li>New notes on deals</li><li>New notes on people</li><li>New activities on deals</li></ul> |
| [Product Hunt](https://github.com/orbit-love/github-actions-templates/blob/main/ProductHunt) | <ul><li>New votes on products</li><li>New comments on products</li></ul> |
| [Reddit](https://github.com/orbit-love/github-actions-templates/blob/main/Reddit) | <ul><li>New posts in subreddits</li><li>New comments in subreddits</li><li>Ability to filter to specific term</li></ul> |
| [Stack Overflow](https://github.com/orbit-love/github-actions-templates/blob/main/StackOverflow) | <ul><li>New questions with tag</li></ul> |
| [YouTube](https://github.com/orbit-love/github-actions-templates/blob/main/YouTube) | <ul><li>New comments across all videos on a channel</li></ul> |

To use a workflow, please follow the integration-specific instructions.

# Frequently Asked Questions

* **Does this have anything to do with Orbit's GitHub Integration?** No - setting up community integrations using GitHub Actions is independent of the integration. We are essentially using GitHub Actions as a free host and scheduler of our code. 
* **Are there any requirements of the repository I put my .yml files in?** No - it can be called anything, and contain any other files. As long as your workflows are inside of the `.github/workflows` directory it can go in any repository. 
* **How much does it cost?** GitHub provides a generous but limited allowance for using GitHub Actions in private repositories which should be  plenty for most communities. If you are using a lot of GitHub Actions either from Orbit or elsewhere, consider making your repository public for unlimited free runs. [More info](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions#included-storage-and-minutes).
* **Do I need to do any maintainence?** Once you set up a GitHub Actions workflow you shouldn't need to do much to it to keep it running. If you are ingesting very large amounts of data you may hit rate limits - check the logs of any failed executions if this happens for more information. GitHub also require some repository activity on the main branch every 60 days to keep actions running. You should receive an email 7 days before this with notice. [More info](https://github.community/t/no-notification-workflow-disabled-after-60-days/182169).

# Contributing

We :heart:  contributions! Please read the [Contribution Guidelines](.github/CONTRIBUTING.md) on how to get involved and submit your own 3rd party integration template.

# Code of Conduct

This project has a [Contributor Code of Conduct](.github/CODE_OF_CONDUCT.md). We ask everyone to please adhere by its guidelines.

# License

This project is under the [MIT License](LICENSE).
