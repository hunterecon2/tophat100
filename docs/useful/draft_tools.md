---
title: markdown tools
tags: [mkd]
created: '2020-06-19T20:22:33.503Z'
modified: '2020-06-23T18:21:40.985Z'
layout: default
description: Why markdown is a good way to draft in tophat
---

# TopHat course with markdown

## Markdown advantages

Markdown is a good way to sketch and visualize planned for Eco100 pages in Tophat. 

The editor in TopHat Pages itself is rather clumsy and has no good options for collaboration and version control.  For example they make it hard to cut and paste content (e.g. no drag and drop and you'll lose all your latex formatting on a paste).   A good markdown on the other hand allows one to embed practically all the visual and interactive elements of the final TopHat page (minus the gradebook-linked quations), it gives you a pretty faithful representation of what the final TopHat page will look like and is most like a format that TopHat will be able to easily convert into TopHat pages when we are done.

With a good markdown editor (and MS Word can be used as one) you can type in math, insert images, URL links, and HTML elements including `<iframe>` tags to embed [videos](https://support.google.com/youtube/answer/171780?hl=en) and other interactive content such as geogebra, interactive charts, etc.  Some demos further down this page.

## Markdown tools and examples

A markdown editor such as [Typora](https://typora.io/) gives a nice WYSIWYG rendering of all the elements and allows easy export to HTML or PDF for preview.  Another markdown editor [notable](https://notable.app/)  also doubles up as an organizer (*ala* onenote or evernote) to keep snippets of material that you might use all organized in one place.   

### Embedding videos and interactive content

#### Videos

Go to [youtube](https://www.youtube.com/) or [vimeo](https://vimeo.com/), click on the share option and find content. For example, to embed [this video](https://www.youtube.com/watch?v=Uxqw2Pgm7s8) from JPAL on RCTs click on the share link underneath the video, then choose `embed` and you copy the html provided (see [embed instructions](https://www.youtube.com/watch?v=Uxqw2Pgm7s8); note also option to start at a particular point in the video).  The basic idea is to just type `<iframe>src = 'video_url'</iframe>` and get a result like this:

<iframe width="560" height="315" src="https://www.youtube.com/embed/Uxqw2Pgm7s8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

#### Other embeds: Geogebra, Our World in Data, FRED 

Lots of other types of interactive content can be embedded the same way using the `<iframe>` HTML tag. Just search for instructions. A few examples:

- [geogebra](https://www.geogebra.org/) [(embed instructions)](https://wiki.geogebra.org/en/Reference:Material_Embedding_(Iframe)) ,
-  [FRED](https://fredhelp.stlouisfed.org/fred/graphs/share-my-fred-graph/how-to-embedding-fred-graphs/) and [Our World In Data](https://ourworldindata.org ) economic graphs, 
-  [google docs, spreadsheets, slides, forms](https://support.google.com/docs/answer/183965?co=GENIE.Platform%3DDesktop&hl=en).
-  [storyline](https://play.storylinegame.com/play)
-  [nytimes](https://iframely.com/domains/nytimes) 

Here is a sample from Our World in Data:

<iframe src="https://ourworldindata.org/grapher/daily-new-confirmed-cases-of-covid-19-tests-per-case" loading="lazy" style="width: 100%; height: 600px; border: 0px none;"></iframe>



---

## TopHat Questions

The one thing we obviously can't include in markdown are the gradebook-tied questions, but we can draft these up and highlight them 

**Insert Question** (short answer)

```
What is the most pressing issue that economists today should address?
```

In TopHat, student responses can be then displayed as [word clouds](https://support.tophat.com/s/article/Professor-Viewing-the-Word-Cloud-for-Word-Answer-Questions). Here are sample responses to this question (from Humboldt University in 2017)

<img src="https://core-econ.org/the-economy/book/images/web/figure-19-12.jpg" alt="Inequality is one of the main problems that students think economics should address. " style="zoom:50%;" />

```

```
