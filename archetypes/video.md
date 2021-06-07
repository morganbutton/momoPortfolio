
---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
tags: ['posts', 'video']
---

## Youtube Video Heading
{{< youtube 4VX6Nh6YLYk >}}



## MP4 Video Heading
 {{< video  src="/videos/placeholdvid.mp4/" type="video/mp4" preload="auto" >}}
