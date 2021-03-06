# Instructions

1. Fork this repo
2. Add a markdown file for your author profile in the Authors folder. 
3. Create an article in this month's folder in markdown.

## How to fork a repo 
I can't explain all the things - if someone feels like updating this part - feel free to!

## How to add an authors profile

1. Fork this repository
2. Navigate to `Authors` and then to the letter that corresponds to your **First** name.
3. Create a file `YourFirstName.MD`
4. Paste the below and replace the relevant info with your own.
```
tiaan:
    name: tiaan
    display_name: Tiaan Wolmarans
    gravatar: 1d4073f730790f1b0da3577939c2e02f
    email: your@email.com
    web: www.yoursite.com
    twitter: https://twitter.com/yourtwitter
    description: "a short Bio about yourself."
```
5. Write your article 👇.

## How to add an article

1. You already forked this repository.
2. Navigate to `Articles` and to the relevant calendar month.
3. In the relevant month folder create a new markdown (.MD) file. 
    1. The naming convention is super important.
    2. First add the date like this: YYYY-MM-DD
    3. Then add a dash -
    4. Then add the name-of-the-article separated by dashes.
    5. Then add the file extension .MD
    6. e.g. So if I was writing an article on 03 Jan 2009 and the title was "Chancellor on brink of bailout for banks" the file should be 2009-01-03-Chancellor-on-brink-of-bailout-for-banks.MD
4. Start your article with the following header text: 
```
---
layout: post <- Never change this>
title:  "Your title here" <- only capitalise the first word and proper nouns>
author: tiaan <- the name you used when you added yourself as an author>
categories: [Bitcoin, Cryptocurrency, UTXO, Scaling]
tags: [Bitcoin, Cryptocurrency, UTXO, Scaling]
image: assets/images/utxo.png <- Never change this>
description: "What are UTXO's and how do they affect scaling?" <- A description for socials etc>
featured: false <- Never change this>
hidden: false <- Never change this>
rating: <- Never change this>
---
```
## How to submit

1. Once you have completed all of the above, create a PR for your author file and article. 
2. If you ever need to update the author file, feel free to do so and submit a PR.
3. If you want to add additional articles, please feel free to do so and create a PR. 
    
Thanks!
Tiaan