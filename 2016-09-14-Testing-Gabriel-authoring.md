---
title: Testing Gabriel authoring
layout: post
author: proschoolhomework
permalink: /testing-gabriel-authoring/
source-id: 13zQxMWYr_Zh03lStIf4RdTOhSJGxsXqkKfbZdzygapY
published: true
---
# **Gabriel**

## **Overview**

Post Google-Docs To GitHub-Pages with Gabriel (The Markdown Angel).

This is a simple Google Apps 'Add-On' which converts a Google Doc to a text based format called [Markdown](http://daringfireball.net/projects/markdown/). It adds a [little metadata](https://jekyllrb.com/docs/frontmatter/) (in YAML format) about the document (e.g. a title, author, categories/tags) and commits it (together with any associated images) to a Github Repository (repo).

It is aimed at users who have a Jekyll blog or static site that is hosted using Github Pages, but who are not especially familiar with the Markdown format, or the technicalities of GitHub 'commits'. Jekyll (see the links below for more information) is a static site generator, transforming Markdown into a fully feature blog or article-driven website. You can host these for free using Github. What Gabriel does is allow you to transform your Google Docs into this Markdown format, and publish in one easy step (and straight from Google Apps).

* [http://jmcglone.com/guides/github-pages/](http://jmcglone.com/guides/github-pages/)

* [https://github.com/barryclark/jekyll-now](https://github.com/barryclark/jekyll-now)

* [http://joshualande.com/jekyll-github-pages-poole/](http://joshualande.com/jekyll-github-pages-poole/)

* [http://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/](http://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/)

* [https://jekyllrb.com/](https://jekyllrb.com/)

Gabriel essentially lets you use Google Docs as a simple content authoring system for your blog. Ordinarily, you would author blog posts (in Markdown) on your local computer (then use the Github Command Line Interface or GUI Application to push them to Github) or on the Github website directly (which won't allow you to save your draft whilst working on it). With Gabriel, you can author each post as a document in Google Docs, including tables, links, headers and images. When you're ready to publish it, simply 'save' it to Github and all the technicalities of conversion and publishing are taken care of. If you need to update the post in the future, you can simply make any content change you wish and re-save it, updating the published versions.

It allows for simple permalinks, tagging and titles. You can also submit arbitary YAML if you're doing custom things in Jekyll. All Gabriel related metadata is stored in the DocumentProperties of the document, making it ideal for collaboration (e.g. the settings for each document follow each document, rather than the user).

You can also publish to simultaneous blogs/repos at the same time, making cross-posting much faster and easier.

## **Usage**

To use this add-on, you'll need to have a Github account already set up, and ideally your Jekyll-based blog already set up and running (although this is a recommendation, not a requirement). To set up an account, just visit 'https://github.com' and sign up. Once you've done this, the first time you run this add-on, you'll need to authorise it to talk to Github on your behalf. This involves clicking on the link that will appear in the side bar and following the on-screen instructions (Github will ask you to grant 'Gabriel - The Markdown Angel' access to your repositories and to author files within them). If you grant this (which you will need to do for the add-on to work) then you will have to close and re-open the sidebar. Once this is done, you'll be ready to go!

You can download the code yourself (download links above, or fork from the [repository](https://github.com/thiscouldbejd/Gabriel)) for modification/testing/usage/debugging or grab it from the [Google Web Store](https://chrome.google.com/webstore/detail/gabriel-the-markdown-ange/okimajjeocnndpifeelaajdebkkbckff). Please note that this code is currently in late-alpha/early-beta. It's functional but a little rough around the edges (especially in handling the OAuth flow to Github).

## **Naming**

[Gabriel](https://en.wikipedia.org/wiki/Gabriel), 'The Markdown Angel' to make generating a publishing Markdown easier for non-technical or non-confident users. Named with a nod to [Jekyll & Hyde](https://en.wikipedia.org/wiki/Strange_Case_of_Dr_Jekyll_and_Mr_Hyde) as it is mainly used in conjunction with a Jekyll / Github-Pages repository on Github.

## **Licensing**

It is licensed under version 2.0 of the Apache License and contains code (thanks!) from the following projects (any alterations or modifications are marked in the code):

<table>
  <tr>
    <td>File</td>
    <td>From</td>
    <td>Copyright</td>
    <td>License</td>
  </tr>
  <tr>
    <td>OAuth2.gs</td>
    <td>Github Repo</td>
    <td>Copyright 2014 Google Inc. All Rights Reserved.</td>
    <td>Apache License, Version 2.0</td>
  </tr>
  <tr>
    <td>Markdown.gs</td>
    <td>Github Repo</td>
    <td>Copyright 2013 Google Inc. All Rights Reserved.</td>
    <td>Apache License, Version 2.0</td>
  </tr>
  <tr>
    <td>Underscore</td>
    <td>Website</td>
    <td>Copyright 2009-2015 Jeremy Ashkenas, DocumentCloud and Investigative Reporters & Editors</td>
    <td>MIT License</td>
  </tr>
  <tr>
    <td>js-yaml.min.gs</td>
    <td>Github Repo</td>
    <td>Copyright (C) 2011-2015 by Vitaly Puzrin</td>
    <td>MIT License</td>
  </tr>
</table>


The **logo** incorporates the [Markdown Mark](https://github.com/dcurtis/markdown-mark) which is licensed under the Creative Commons License (CC0 UNIVERSAL PUBLIC DOMAIN DEDICATION LICENSE).

All else, **Copyright JD, 2015**.

