---
title: Creating This blog
date: 2025-01-11
categories: [Blogging]
tags: [tutorial, walkthrough, guide]
---
To create a blog with this theme, it was extremly simple thanks to the repo provided by @cotes2020, and can be completed by following the steps below:

1. Go to his repo [chirpy-starter (https://github.com/cotes2020/chirpy-starter)](https://github.com/cotes2020/chirpy-starter)
2. Click "Use Template"
3. For the Repository Name, use your GitHub Username, followed by github.io, example <YourGitHubUsername>.github.io.
4. Install Visual Studio Code and Docker Desktop on your local machine. 
5. Open Visual Studio Code, install the [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) Extension.
6. Please F1 and search for _Dev Containers: Clone Repository into Container Volume_.
7. Locate the Github repo you created in Step 1.
8. Let the Docker container spin up. 
9. With the container setup, follow the [Chirpy Configuration Steps](https://chirpy.cotes.page/posts/getting-started/), this will allow the site to be available at <YourGitHubUsername>.github.io.
   -  _Note - There are also instructions in the [Chirpy Configuration Steps](https://chirpy.cotes.page/posts/getting-started/) to allow local hosting of your site._
10.   When you're done configuring your site, push to github to start the github action, which will build, and publish your new site.
11.   11.  Navigate to <YourGitHubUsername>.github.io to view your new site!
