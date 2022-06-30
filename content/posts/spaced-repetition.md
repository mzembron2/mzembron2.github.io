---
title: "Flashcard app, using: C++11 + Qt5 \U0001F4DD + SQLite \U0001F4D3 "
summary: "Flashcard app using spaced repetition method"
# date: 2020-09-15T11:30:03+00:00
# weight: 1
# aliases: ["/first"]
# tags: ["first"]
author: "Mateusz Zembroń"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
enableEmoji: true
# description: "Goal of this project was to implement evolutionary algorithm  "
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: true
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: false
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    enabled: false
    URL: "https://github.com/mzembron2/mzembron2.github.io/blob/main/content/"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---

## Intro

This project is a simple flashcard application that helps you learn anything using [spaced repetition method](https://en.wikipedia.org/wiki/Spaced_repetition), which will allow you to do it noticeably faster. Flashcards can contain text, images, or sound (there is an easy way to add new ones through the application). The implemented algorithm calculates new repetition dates according to the [SuperMemo-2 method](https://en.wikipedia.org/wiki/SuperMemo#Description_of_SM-2_algorithm).

## Tools used 

The whole application is written in C++11. Nearly every part is made with the help of the Qt5 framework(from GUI to connecting to the database). All flashcards data is stored in the SQLite database.

## GUI screenshots

![photo](https://github.com/mzembron2/spaced_repetition/blob/main/Docs/images/home.png?raw=true)

![photo](https://github.com/mzembron2/spaced_repetition/blob/main/Docs/images/pine_question.png?raw=true)

## Link to repository
You can find repository of this project under this [link](https://github.com/mzembron2/spaced_repetition).
