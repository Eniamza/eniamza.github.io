---
title: "How Dictionary Attacks can be more optimized with CUPP"
date: 2022-07-14
# weight: 1
# aliases: ["/first"]
tags: ["dictionary","10 million","cupp","python","custom password list","hacking","password crack"]
author: "Eniamza"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "CUPP is an unique password profiling technique where you can generate a dictionary word list curated for your target!"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
cover:
    image: "https://i.imgur.com/oXSG2Ee.png" # image path/url
    alt: "eniamza looking at a mate who's sitting on a pipe referred as tunnel" # alt text
    caption: "top tunneling services and alternatives" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/<path_to_repo>/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---


## What actually is a Dictionary Attack?

---

In all the Sci-Fi movies, generally, we see a hacker wearing a black hoodie typing constantly on the keyboard. While these movies don't exactly portray a proper hacking culture, they also make it seem unbelievably easy to exploit an individual user.

![Hacker Typing](https://c.tenor.com/VrzXhtoSwcsAAAAd/hacker-typing.gif)

But we have to understand that not all website is easily exploitable. Tech Giants such as Google and Facebook implant high-level security and constantly patch new vulnerabilities. So which part is the most vulnerable? You're right it's the user itself!

Once upon a time, users chose passwords such as "Honey123", "Love321", "I'mdumb111", etc. These passwords could be easily brute-forced and cracked using a Dictionary attack where the script tries the passwords from a provided Dictionary. *Imagine Trying Several Keys at the same time from the collection of keys in the world*

CUPP takes this attack one step ahead.

## CUPP, not Mug or Jug?

---

I know it'd be fun to call it Jug. But CUPP stands for **Common User Password Profiling** 

Also, sounds fun, right? 
In this technique, We basically input a little information about our target. For example, a person named Danny Morgan wouldn't use the word "Scott" as his password. Unless he has a favorite actor named "Scott".

CUPP v3 goes through different combinations and algorithms based on the given data to create a wordlist for the target as effectively as possible.

## Let's get the party started!
---
- **Clone the Official CUPP Repository**

```
git clone https://github.com/Mebus/cupp.git
```

- 
