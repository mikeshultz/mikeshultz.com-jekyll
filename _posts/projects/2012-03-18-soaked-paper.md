---
layout: project
title: "Soaked Paper"
date: 2012-03-18 13:58:00
update: 2012-06-09 06:45:04
categories: ["Web-Development","Projects"]
tags: ["Web", "html", "javascript"]
status: "Development Stalled"
---

### Summary

A project to build a system for handling online editions of multiple newspapers. This includes their content, advertising, and interactive functions.

### Necessary Features For Release
Features we need to have before presenting to any paper:

- Various stock homepage layouts
- Sections with landing pages
- WYSIWYG editor and full-featured admin
- System for advertising with standard ad sizes
- User auth system with panel for commenting and special features
- Hardcopy subscription system

### Documentation

#### SoakedNews

##### Objects
###### Section
- name
- parent(optional): Parent section
- description(optional): Description of the section

#### SoakedAds

- *incomplete*

#### SoakedPhotos

- *incomplete*

###### Article
- reporter: Associated user that is credited as its author
- section: Section the article is in
- title: Title of the article
- tease(optional): Teaser of the article.  If available, this will be displayed as a summary on pages like sections.
- body: Body of the article
- tags(optional): Tags(news, entertainment, jonbonjovi, etc)

##### Dependencies

- django-tagging