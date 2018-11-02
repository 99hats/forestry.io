---
aliases:
- "/jekyll/"
title: Static CMS for Jekyll
description: Forestry
authors:
- forestryio
blocks:
hero:
  headline: A Jekyll CMS that **commits**
  textline: Forestry takes Git-powered Content Management to Jekyll Sites. Easily update, build and deploy sites in Forestry. [Learn More](#everything-you-need-for-superior-content-management)
  ctas:
  - permalink: https://app.forestry.io/signup
    textline: Start Building Free
    button: true
  - permalink: "https://app.forestry.io/quick-start?repo=forestryio/hydeout-jekyll-starter&provider=github&engine=jekyll"
    textline: Launch Demo
    button: false
  video:
    fallbackVisual: "/video/forestry_factory.jpg"
    sources:
    - permalink: "/video/forestry_factory.webm"
      type: video/webm
    - permalink: "/video/forestry_factory.mp4"
      type: video/mp4
    - permalink: "/video/forestry_factory.ogv"
      type: video/ogg
  logos:
    textline: Built for static site generators
    sources:
    - permalink: /img/logos/hugo.svg
      alt: Hugo
    - permalink: /img/logos/jekyll.svg
      alt: Jekyll
    - permalink: "/uploads/2018/08/vuepress-1.png"
      alt: Vuepress
features:
- headline: "Everything you need for superior content management"
  textline: |
  tabs:
  - headline: Connect
    textline: |
      Import your Jekyll powered site and make edits within minutes. Tell Forestry what parts of your site you want exposed and configure templates to create new content. 
    visual:
      permalink: "/img/connect.gif"
      alt: Dev workflow
    features:
    - name: Custom Sections
    - name: Set Templates
    - name: Exclude Files 
  - headline: Edit
    textline: |
      Make edits right away or create Front Matter Templates to create new content. Our WYSIWYG Editor is based on Markdown and allows for seamless editing in the visual editor.  
    visual:
      permalink: "/img/editing-top-bar.gif"
      alt: Dev workflow
    features:
    - name: WYSIWYG & Markdown
    - name: Snippets & Blocks
    - name: Drafts 
  - headline: Preview
    textline: |
      Previewing allows to take the guessing out of your editing and makes it easy to share your project with your team and clients.
    visual:
      permalink: "/img/preview.gif"
      alt: Dev workflow
    features:
    - name: Shareable Preview
  - headline: Publish
    textline: |
      Forestry can build and deploy your site to your host on every change. Further optimize the content on its way out by running gems or custom scripts.
    visual:
      permalink: "/img/deploy-illustration-02.png"
      alt: Simple deployment
    features:
    - name: Automatic Deployment
    - name: Custom Build Commands
  - headline: Roles
    textline: |
      With Forestry you can provide the access to users that they need for their individual use-case. Give your entire team access to all sites in your Organization.
    features:
    - name: Editing in Teams
    - name: Organizations
    - name: Restrict Access
    visual:
      permalink: "/img/roles.png"
      alt: Dev workflow
  direction: tab
  class: section-roots
- headline: Support for all of your favorite tools
  textline: |
    Forestry is optimized for Jekyll including Liquid, Sass and Coffeescript.
    
    <div style="display: flex; align-items: center; justify-content: space-between; padding: 20px 30px;">
      <div style="flex:auto;">
        <img height="35px" src="/img/logos/jekyll.svg" alt="Jekyll">
      </div>
      <div style="flex:auto;">
        <img height="35px" src="/img/logos/sass.svg" alt="Sass">
      </div>
      <div style="flex:auto;">
        <img height="35px" src="/img/logos/coffeescript.svg" alt="CoffeeScript">
      </div>
    </div>
  
    Choose your own tools and include them into the build process with Custom Build Commands.
    
    Use an existing theme, create your own site or make use of a Starter-Kit. 
    
  visual:
    permalink: "/img/dev-illustration-02.png"
    alt: Dev workflow
  direction: rtl
  class: section-sync
- headline: Choose your Git Integration
  textline: |
    All Forestry powered projects live on Git.  

    Forestry seamlessly integrates with your Git-workflow, keeping your content in-sync without merge conflicts.  
    <br />
    <div style="display: flex; align-items: center; justify-content: space-between; padding: 20px 30px;">
      <div style="flex:auto;text-align:center;">
        <img height="35px;" src="/img/logos/github.svg" alt="Github">
      </div>
      <div style="flex:auto;text-align:center;">
        <img height="35px;" src="/img/logos/gitlab.svg" alt="Gitlab">
      </div>
      <div style="flex:auto;text-align:center;">
        <img height="35px;" src="/img/logos/bitbucket-logo.svg" alt="Bitbucket">
      </div>
    </div>
  visual:
    permalink: "/img/commits-illustration.png"
    alt: Editor workflow
  direction: ltr
  class: section-sync
- headline: Host where you want
  textline: Your static site can live anywhere you want — including on Amazon S3,
    Fastly, Netlify and GitHub Pages. You can even deploy with plain old FTP.
  direction: vertical
  class: section-deploy
cta:
  headline: Build amazing sites
  textline: We have the tools to manage your content. Ready to try Forestry?
  class: section-roots
type: landing-page
layout: landing-page
draft: true
date: 2017-12-31 04:00:00 +0000

---