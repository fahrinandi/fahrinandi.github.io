---
title: "The Author"
permalink: "/about/"
layout: page
---

<style>
    .author-container {
        display: flex;
        align-items: center;
    }

    .author-image {
        flex-shrink: 0;
        margin-right: 20px;
        width: 200px;
        height: 100px;
    }

    .author-info {
        color: #007af6;
    }
</style>

<div class="author-container">
    <img src="assets/images/pict_1.jpg" alt="profile picture" class="author-image">
    <div class="author-info">
        <h2>Fahrin Ramadan Andiwijaya</h2>
        <p>Hi! <span style='font-size:30px;'>&#128075;</span></p>
        <p>I'm Fahrin... 🔭 I'm currently training in Physical Medicine and Rehabilitation Medicine. My side quest is to keep what I've learned about Public Health and Epidemiology intact for the time being. So in that effort, this blog will mostly consist of snippets or stories related to public health, epidemiology, health in general, or just anything random 🔭.</p>
    </div>
</div>


## <span style="color: #fc4804;">Publications</span>
Please visit my [Research Gate](https://www.researchgate.net/profile/Fahrin-Andiwijaya)





### Education
#### Universitas Airlangga/ Soetomo General Hospital Department of Physical Medicine and Rehabilitation Indonesia (2022 – Current) 
Physical Medicine and Rehabilitation Residency programme
#### The London School of Hygiene and Tropical Medicine London, United Kingdom (2020 - 2021)
MSc in Public Health
#### Universitas Airlangga Indonesia (2016 – 2018)
Medical Doctor


### Teamwork
- Former active member at the Indonesian Student Association in the United Kingdom (PPI-UK)
- Former Head of Health Policy Analysis at the Health Unit of the Indonesian Student Association in the UK (PPI-UK)




### Willingness to learn
- Studied translational degenerative neuroscience at the University of Groningen, Summer School, 2018
Undergoing extra online courses:
- Systematic Review and Meta-analysis course from the Johns Hopkins University,
- introduction to R for statistical analysis from the Imperial College London.

## Installation

Just fork this [repository](https://github.com/niklasbuschmann/contrast) and adjust the `_config.yml` to use with [Github Pages](https://pages.github.com/) and your page is done.

## Features

 - supports dark mode on macOS Mojave
 - optional sidebar
 - MathJax support
 - no external ressources
 - included archive page
 - supports pagination
 - feed generation
 - responsive
 - syntax highlighting
 - supports comments via [disqus](https://disqus.com/) or [isso](http://posativ.org/isso/)

## Based on

- [Hyde](https://github.com/poole/hyde)
- [Minima](https://github.com/jekyll/minima)
- [Lagrange](https://github.com/LeNPaul/Lagrange)
- [Font Awesome](http://fontawesome.io/)
- [KaTeX](https://katex.org/)
- [Pygments](https://github.com/richleland/pygments-css)

## Installation (jekyll-remote-theme method)

You can use this theme with the `jekyll-remote-theme` plugin. Just create an empty repo, copy over the `index.html` file and add this to your `_config.yml`:

```yaml
remote_theme: niklasbuschmann/contrast@v2.11

plugins:
  - jekyll-remote-theme
```

Note: to enable icons you also need to copy over the `_data` folder.

## Config

Your `_config.yml` could for example look like this:

```yaml
title: "Blog Title"
author: "Blog Author"
description: "My personal blog about ... something"
permalink: /:title/
lang: "en"
excerpt_separator: "\n\n\n"
date_format: "%B %d, %Y"

# Layout

show_excerpts: true        # show article excerpts on the home page
show_frame: true           # adds a gray frame to the site
show_sidebar: false        # show a sidebar instead of the usual header

# Menu

navigation:                # accepts {file, title, url, icon, sidebaricon}
  - {file: "index.html"}
  - {file: "README.md"}

external:                  # shows a footer with social links - for available icons see fontawesome.com/icons
  - {title: Mail, icon: envelope, url: "mailto:niklasbuschmann@users.noreply.github.com"}
  - {title: Github, icon: github, url: "https://github.com/niklasbuschmann/contrast"}
  - {title: Subscribe, icon: rss, url: "/feed.xml"}

comments:
#  disqus_shortname: ""    # see https://disqus.com/
#  isso_domain: ""         # see https://posativ.org/isso/

plugins:
 - jekyll-feed

```

## MathJax

Contrast comes preinstalled with a leightweight alternative to MathJax called [KaTeX](https://katex.org/). To display equations in a post simply set `mathjax: true` in the article's front matter.

## License

[public domain](http://unlicense.org/)

## Screenshots

![screenshot](https://user-images.githubusercontent.com/4943215/109431850-cd711780-7a08-11eb-8601-2763f2ee6bb4.png)

![screenshot](https://user-images.githubusercontent.com/4943215/109431832-b6cac080-7a08-11eb-9c5e-a058680c23a1.png)

![screenshot](https://user-images.githubusercontent.com/4943215/73125194-5f0b8b80-3fa4-11ea-805c-8387187503ad.png)
