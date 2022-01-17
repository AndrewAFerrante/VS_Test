---
title: "Andrew A Ferrante"
layout: splash
author_profile: false
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/images/crowded_sidewalk.jpg
  actions:
    - label: "About Me"
      url: "https://andrewaferrante.github.io/about/"
excerpt: "Personal ideas and notes from a financial economist researcher."
intro: 
    - excerpt: "Something that everyone knows isn't worth knowing. - Bernard Baruch."
intro2:
    - excerpt: "Welcome to my webpage! This is a porfolio to showcase my research as a Financial Economist. I am interested in financial regulation, monetary policy, and financial markets. Most of my research now involves banking regulation since I am an Economic Research Assistant at the Federal Deposit Insurance Corporation (FDIC), but I also spend most of my time studying my interests through books, podcasts, the news, and social media. More about me can be found in my [About me](https://andrewaferrante.github.io/about/) page. Otherwise, have fun browing my site!"
feature_row:
  - image_path: assets/images/blog_16x9.jpg
    title: "Blog"
    excerpt: "Read up on my newest hot takes and book reviews!"
    url: "https://andrewaferrante.github.io/blog/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/data_16x9.jpg
    title: "Data"
    excerpt: "Learn more about primary source databases and even some coding!"
    url: "https://andrewaferrante.github.io/data/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/history_16x9.jpg
    title: "History"
    excerpt: "Check out my financial regulation timeline and learn some history!"    
    url: "https://andrewaferrante.github.io/history/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/twitter.jpg
    alt: "Social Media"
    title: "Social Media"
    excerpt: "Follow me on Twitter to keep up with all my updates!"
    url: "https://twitter.com/Big_Red0"
    btn_label: "Follow Me"
    btn_class: "btn--primary"
---

<link rel="shortcut icon" type="image/png" href="favicon.png">

<!---
Django code:
--->

{% include feature_row id="intro" type="center" %}

{% include feature_row id="intro2" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}
