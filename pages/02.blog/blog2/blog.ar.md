---
title: blog2
dateformat: 'd-m-Y H:i'
process:
    markdown: true
    twig: false
twig_first: true
child_type: default
visible: true
admin:
    children_display_order: collection
content:
    items: '@self.children'
    limit: 5
    order:
        by: date
        dir: desc
    pagination: true
    url_taxonomy_filters: true
---

BLOG 2
