---
layout: page
title:  "About"
---

**awesome-manim** is a website where you can discover the most recent content from creators on YouTube that use [Manim](https://manim.community/).

It automatically fetches the videos from the channels listed in the GitHub repo [ManimCommunity/awesome-manim](https://github.com/ManimCommunity/awesome-manim) and displays them in a single feed. It's goal is to **increase the visibility of new channels and encourage more people to produce their videos using Manim**.

[Click here](https://github.com/ManimCommunity/awesome-manim#creators) to see a list of all the creators that are featured.

### Adding your YouTube channel to awesome-manim

1. Fork the the repo [ManimCommunity/awesome-manim](https://github.com/ManimCommunity/awesome-manim).
1. Add yourself to [README.md](https://github.com/ManimCommunity/awesome-manim/blob/main/README.md) in the fork.
1. Create a pull request and wait for it to be merged.

### About Manim

[Manim](https://github.com/ManimCommunity/manim) is an community maintained Python library for creating mathematical animations. It was created in 2015 by Grant Sanderson, a.k.a. 3blue1brown, as a personal project to produce his own videos. As his channel gained popularity, many grew to like the style of his animations and wanted to use Manim for their own projects. However, as Manim was only intended for personal use, it was difficult for other users to install and use it.

Manim has since been adopted by a group of developers, who forked it mid-2020 into what is now known as the [community edition](https://manim.community). Grant on the other hand still continues to produce videos using [his original branch](https://3b1b.github.io/manim/), having added OpenGL support and many other cool features. There are ongoing efforts in the Manim Community to reconcile these changes into the community edition. Check out [this page](https://docs.manim.community/en/stable/installation/versions.html) for more information on the different versions of Manim currently under development.

The videos that you see on this website would not have been made if Grant had not open-sourced Manim. For that, we are forever grateful.

### Technical notes

The website currently uses YouTube's RSS feed to scrape the videos, which limits the output to the last 15 videos by default. Some older videos might be missing because of that---they will be added in the future.

The feed is currently strictly chronological, but we are planning to create a smarter feed that leverages existing information, such as like and view counts.

### Feedback

If you have a cool idea for this website, [create an issue here](https://github.com/ManimCommunity/awesome-manim/issues) and tag it as a feature request.