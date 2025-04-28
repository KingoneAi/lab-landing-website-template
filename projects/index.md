---
title: 项目
nav:
  order: 2
  tooltip: 软件、数据集等 # 或者其他合适的中文描述
---

# {% include icon.html icon="fa-solid fa-wrench" %}项目

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-wrench" %}项目
## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-wrench" %}项目
## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
