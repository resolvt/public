---
title: It Hurts
---

# Getting started with It Hurts
**It Hurts** is a technical debt manager. It lives right in your IDE so you can share your concerns about the code with your teammates without leaving it. It also adds a great visibility of existing problems when you are working with the code.

Moreover, It Hurts integrates with your code repositories, keeping track of repositories events and automatically updates the debt records, trying to keep everything up-to-date.

This article describes how to start to work with It Hurts in a few steps.

## Connect It Hurts to your codebase
Sign in to It Hurts with one of supported source code hosting services (currently, only Bitbucket is supported), then click "Create workspace" on the dashboard right-top menu. You will be redirected to  Bitbucket where you will see It Hurts for Bitbucket app authorization dialog. Choose workspace/organisation you want It Hurts connected to. As soon as you grant It Hurts access to your repositories, your It Hurts workspace is created.

<img alt="Bitbucket grant access dialog" src="bitbucket-grant-access.png" height="450px" />

> **Note:** Unfortunately, for now It Hurts for Bitbucket is not listed in Atlassian Marketplace, that's why you will need to enable development mode for your Butbucket Cloud workspace to connect It Hurts to it.

## Working with It Hurts from IDE
To start working with It Hurts you need to install plugin for your IDE.

### Intellij IDEA (and other Intellij Platform IDEs)
#### Plugin installation
You can install/download the plugin from JetBrains Makretplace: [here](https://plugins.jetbrains.com/plugin/18380-it-hurts-integration)
- After you have installed the plugin, go to Settings -> Tools -> ItHurts. 
- Click Connect to It Hurts. You will be redirected to It Hurts, where if you are logged in, you will find an authorization code.
- Put the authorization code into "Code" field the settings dialog and click "Ok".
- If everything is fine, you will see "Logged as ..." label in the settings dialog.

#### Reporting technical debt
While working with the code, select the code you do not like (if the code hurts you, it is exactly the place you want to report to It Hurts). Right click on the selected code and choose "Report Tech Debt" in the context menu.

<img alt="Context menu" src="context-menu.png"/>

"Report Techn Debt" tool windows will be opened. Specify the title (what's wrong with the code) and some description (why exactly the code is base? what is the correct way?). 

<img alt="Report dialog" src="report-dialog.png"/>

Click "It Hurts!" button in the . That's it, now your concern is shared with your teammates and available in their IDEs and on workspace's dashboard. 
