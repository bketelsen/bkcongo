---
title: Azure VM List
description: List all available VM base images in Azure.
date: 2020-08-25T00:27:29.004Z
link: https://cda.ms/1yM
tags:
  - azure
categories:
  - Cloud
type: byte
lastmod: 2022-06-03T08:47:37.549Z
---

I needed this today. To get a list of the different Virtual Machine base images (Azure calls them SKUs) use this command:

```bash
az vm image list --all --output table
```
