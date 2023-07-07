---
title: Group Website
layout: page
nav_order: 3
---
The group [website](https://www.rmmrgroup.org) is hosted via AWS Amplify.

The repository for the website is here:
[https://github.com/RMMR-Group/website](https://github.com/RMMR-Group/website)

To deploy an update, just push a change to the master branch on github. AWS Amplify will automatically pick up these changes and populate the public-facing website with them.

Note that we've used a custom header setting on AWS Amplify so that all images are cached by the browser. This is probably not relevant to you, unless you're trying to do something fancy on the website, in which case you'll be glad to know this detail.
