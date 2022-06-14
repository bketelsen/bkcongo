---
title: Shortcodes
draft: true
date: 2019-03-05
description: Shortcode Cheatsheet
summary: 📖🏞️🧗🏽🪂🐉🧙🏽‍♂️🧚🏽👸
aliases:
    - /shortcodes
tags:
  - shortcodes
  - sample
lastmod: 2022-03-07T08:54:37.444Z
---

## Alert

{{< alert skull-crossbones >}}
**Warning!** This action is destructive!
{{< /alert >}}

## Youtube

{{< youtube O_qmlv5Ob9w >}}

## badge

{{< badge >}}
New article!
{{< /badge >}}

## button

{{< button href="#button" target="_self" >}}
Call to action
{{< /button >}}

## chart

{{< chart >}}
type: 'bar',
data: {
  labels: ['Tomato', 'Blueberry', 'Banana', 'Lime', 'Orange'],
  datasets: [{
    label: '# of votes',
    data: [12, 19, 3, 5, 2, 3],
  }]
}
{{< /chart >}}

## figure

{{< figure
    src="abstract.jpg"
    alt="Abstract purple artwork"
    caption="Photo by [Jr Korpa](https://unsplash.com/@jrkorpa) on [Unsplash](https://unsplash.com/)"
>}}

## icon

{{< icon "github" >}}

## lead

{{< lead >}}
When life gives you lemons, make lemonade.
{{< /lead >}}

## mermaid

{{< mermaid >}}
graph LR;
A[Lemons]-->B[Lemonade];
B-->C[Profit]
{{< /mermaid >}}
