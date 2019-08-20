---
title: Link Info
slug: link
date: '2019-08-20'
hidetitle: true
---

<!--- Demonstrate links that work when this web-site is deployed on github.io -->

# Link Information

## Link from main Github website to the Github Project web-site for the repository *meetings*

On the irsbugs account the github repository *meetings* has a *project* web-site. We may link to this project website in various ways.


1. This is the full [link](https://irsbugs.github.io/meetings). In markdown the link is:

    `[link](https://irsbugs.github.io/meetings)`

    Nikola converts the above to the following html:

    `<a href="https://irsbugs.github.io/meetings">link</a>`

2. This is a shortened [link](meetings/index.html). In markdown the link is:

    `[link](meetings/index.html)`
    
    Nikola converts the above to the following html:
    
    `<a href="meetings/index.html">link</a>`


3. This is a very short [link](meetings). In markdown the link is:
    `[link](meetings)`
    
    Nikola converts the above to the following html:

    `<a href="meetings">link</a>`

When the `$ nikola serve -b` is used to test the web-site on your laptop, then link methods two and three above will fail. Once the Nikola site has been deployed to `https://irsbugs.github.io` then these links work OK.

Try a link to [google](http://www.google.com).

Markdown: `[google](http://www.google.com)`. HTML: `<a href="http://www.google.com">google</a>`
