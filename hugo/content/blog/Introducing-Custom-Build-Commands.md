---
title: Introducing Custom Build Commands, VuePress Previews and Creating Directories
description: ''
date: 2018-09-20 18:11:49 -1100
authors: []
publishdate: 2017-12-07 04:00:00 +0000
expirydate: 2030-01-01 04:00:00 +0000
headline: ''
textline: ''
images: []
categories: []
tags: []
cta:
  headline: ''
  textline: ''
  calls_to_action: []
private: false
weight: ''
aliases: []
menu: []
draft: true

---
You can now decide what command should be run to build your project.

Until now Forestry chose the command that needed to be run for you, which worked fine for many projects. However, this meant that projects that needed to run their own build commands were unable to use Forestry's deployment tools and in some cases unable to use Forestry's previews.

You can now choose _your_ commands for deployments as well as previews. Learn how to set them up in our [build commands documentation](/docs/settings/build-commands/)

***

**Custom Build Commands**

When you add custom build commands to your project, Forestry will run those commands when creating a preview or preparing your site for deployment. Check out our [build commands documentation](/docs/settings/build-commands/).

    build:
      preview_command: hugo -D -F -E
      publish_command: hugo
      output_directory: public
      preview_env:
      - HUGO_ENV=staging
      publish_env: 
      - HUGO_ENV=production

***

**Sites with Frontend Asset Pipelines**

You no longer need to compile your frontend assets (with tools such as Gulp or Webpack). With custom Build Commands, Forestry compiles your assets for your previews and deployments. Effectively, we can now replace you external CI tools. Simply add your custom build commands to your `settings.yml`. Go to the [docs](/docs/settings/build-commands/).

***

**Preview & Deploy for VuePress**

When we first introduced VuePress support, previewing and deployment were not possible for VuePress sites. Now, adding custom build commands for your VuePress site will unlock preview and deployment capabilities in Forestry! 🌲🎉

![](/uploads/2018/09/vuepress-add-preview.gif)

***

**Flexibility for More Workflows**

We want our users to get the most out of Forestry. With **custom build commands**, we aim to support your workflow so you can use everything we have to offer.

_To review all changes, please visit our_ [_changelog_](/docs/changelog/)_, or visit our_ [_sunset notices_](/docs/sunset/) _to see if any features are going to be replaced or removed._