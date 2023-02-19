# My-Portfolio-Website
Creating your website
In the upper-right corner of any page, use the  drop-down menu, and select New repository.
Drop-down with option to create a new repository

Enter username.github.io as the repository name. Replace username with your GitHub username. For example, if your username is octocat, the repository name should be octocat.github.io.
Repository name field

Under your repository name, click  Settings.
Repository settings button

In the "Code and automation" section of the sidebar, click  Pages.

Under "Build and deployment", under "Source", select Deploy from a branch.

Under "Build and deployment", under "Branch", use the None or Branch drop-down menu and select a publishing source.

Drop-down menu to select a publishing source

Optionally, open the README.md file of your repository. The README.md file is where you will write the content for your site. You can edit the file or keep the default content for now.

Visit username.github.io to view your new website. Note: It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub.

Changing the title and description
By default, the title of your site is username.github.io. You can change the title by editing the _config.yml file in your repository. You can also add a description for your site.

Click the Code tab of your repository.

In the file list, click _config.yml to open the file.

Click  to edit the file.

The _config.yml file already contains a line that specifies the theme for your site. Add a new line with title: followed by the title you want. Add a new line with description: followed by the description you want. For example:

theme: jekyll-theme-minimal
title: Octocat's homepage
description: Bookmark this to keep an eye on my project updates!
When you are done editing the file, click Commit changes.
