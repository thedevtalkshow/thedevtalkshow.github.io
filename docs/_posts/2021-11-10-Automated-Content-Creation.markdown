---
layout: post
category: video
title: Live Coding - Automated Content Creation
author: Rich Ross
description: In an ongoing collection of ideas of how we can automate some of the routine tasks we need to do as a weekly live stream, we want to create a blog post as a follow-up to each show here on The Dev Talk Show.  the blog post contains the title, description, and link to the video on our YouTube archive.<br><br>There are a number of different ways to do this and our current plan focuses on GitHub actions to do the heavy lifting.  Our data for the post is stored with the YouTube video so we will need to reach out to that service.  The custom GitHub Action will then pull this all together in a file and check this into the GitHub pages repo, which is where we host our blog.<br><br>This will be a Live Coding session, so join us on Wed at 8:30 and see if we can pull this off or watch it go back into the backlog.  Either way, this will be fun to see.

youtubeurl: xLPyxKDmL00

medImage: "https://i.ytimg.com/vi/xLPyxKDmL00/mqdefault.jpg"
---

{{ page.description }}

{% include youTubeEmbed.html id=page.youtubeurl %}