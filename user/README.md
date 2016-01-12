# Bones Vanilla Course Companion Skeleton

![BVCC Screenshot](assets/bvcc-screenshot.png)

# Configuration

```
title: CPT-363
metadata:
    description: 'A short description of your course companion would go here'
menu:
    - text: Grav
      icon: arrow-circle-right
      url: http://getgrav.org/
icon:
    preparations: check-circle
    posts: calendar-o
github:
    enabled: true
    tree: https://github.com/hibbitts-design/grav-skeleton-bootstrap-course-companion-prototype/edit/master/user/
```

| Setting | Child Setting | Description                                                                                                            |
|---------|---------------|------------------------------------------------------------------------------------------------------------------------|
| title   |               | The name of the course, to be displayed at the top of every page.                                                      |
| metadata  |  description | The short description of the course companion site                                       |
| menu  |  text | Text label for external links to be included on navbar                                       |
| menu  |  icon | Font awesome icon code for external link (optional)                                        |
| menu  |  url | URL for external link
|                                       |
| icon  | preparations    | Change the default font awesome icon for the preparation area on the home page.
|
| icon  | posts          | Change the default font awesome icon for the weekly blog posts (i.e. weekly summaries).            |
| github  | enabled       | Can be set to `true` or `false`. When set to `true`, it generates the **Edit this page** link to GitHub for each page. |
| github  | tree          | Sets the tree by which your site's content is based. Generally the repo your site's content is pulled from.            |

---
