---
title: "Scrambled Exif: Make your metadata go Poof!"
date: 2022-12-28
# weight: 1
# aliases: ["/first"]
tags: ["Android","exif","privacy","cyber security"]
categories: ["Android","Review"]
author: "Me"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "An unbelievable amount of targetted information can be extracted from your photos even from a simple selfie! From Capture date to Pinpointed Geo Location, you DO NOT want these to be public! So the solution is..."
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
cover:
    image: "https://github.com/Eniamza/enilog-static-thumbs/blob/main/scramexif.png?raw=true" # image path/url
    alt: "scrambled exif thumbnail indicating that it is available on f droid and playstore and Eniamza is pointing out to the Logo" # alt text
    caption: "Scrambled Exif Thumbnail" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/<path_to_repo>/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---

## Metadata Doxxing and You

---

![Exposed Gif](https://media.tenor.com/eihFXlsRhRIAAAAC/point-pointing.gif)

We all love to snap pics and upload them to social media in the blink of an eye. "Hey, see, I look cool in this dude!”. But you can not be certain of when those dudes will start looking beyond your picture!

This is an example of a logo I created and uploaded to my Quora Space:
![](https://i.imgur.com/mpZYVPU.png)

But there's nothing interesting, right? It's impossible to tell who is the creator and where he lives. But is that really the case?

**Metadata** is associated with every file ever created. It contains valuable information like, Creation Date, Modification Date, Name of the Device which was used for creation, the Creator's Name, and even the Software name that was used to edit this logo!

EXIF (Exchangeable Image Format) is such a standard for images. Let's take a look at the EXIF Data extracted from my logo!

![](https://i.imgur.com/lSjizWr.png)

You can see the last modification date, the creator tool named **Canva** and most important my named under the **Author** Section.

If you were a creep (I know you aren't, my readers are cool!) , a simple google search would present you with a whole page of information and social media links directly related to me. It'd take you less than 10 minutes to find out who I actually am!

Sounds like a nightmare, right?

## Shuffle Up Your EXIF Metadata
---
![](https://media.tenor.com/7feFpn2OST4AAAAC/card-spring-playing-cards.gif)

[Scrambled EXIF](https://play.google.com/store/apps/details?id=com.jarsilio.android.scrambledeggsif&hl=en&gl=US&pli=1) is here to rescue as! It acts as an intermediary for sharing files. This app acts as a middleman when you share your files by just adding another step. When sharing your files, you just need to tap the share button as usual and select [Scrambled EXIF](https://play.google.com/store/apps/details?id=com.jarsilio.android.scrambledeggsif&hl=en&gl=US&pli=1) app. Shortly the share popup with apps will appear again after Scrambled EXIF's magic process! To summarize, it's just three steps:

- Tap Share
- Choose Scrambled EXIF
- Choose the preferred app in the 2nd share popup.

## Results?

---

![ANON GIF](https://media.tenor.com/FnqasB7hsq0AAAAd/v-for-vendetta.gif)

[Scrambled EXIF](https://play.google.com/store/apps/details?id=com.jarsilio.android.scrambledeggsif&hl=en&gl=US&pli=1) not only strips metadata from your files but also renames it with random strings. Why?

Because your phone sometimes names files containing dates and category. For example, My phone saves Photos with this naming format: "YYYYMMDD-TIMESTAMP-PXL" that means, you can know the exact time of the capture and also the device model name. 

But when I share the same logo above through Scrambled EXIF, the filename becomes: `394269db-d328-4ea9-8524-3880efb8df87.png` and the metadata becomes: 

![](https://i.imgur.com/PUBLyfe.png)


Nothing Specific! It's that simple.

## Resources
---
- Scrambled EXIF App - [Play Store](https://play.google.com/store/apps/details?id=com.jarsilio.android.scrambledeggsif&hl=en&gl=US&pli=1) [F-Droid](https://f-droid.org/packages/com.jarsilio.android.scrambledeggsif/)
- What is EXIF - [Wikipedia](https://en.wikipedia.org/wiki/Exif)
- Repository - [GitLab](https://gitlab.com/juanitobananas/scrambled-exif) 