---
sidebar_position: 8
---

# Authors

You can add authors for your blog using the `authors` field in the `truegit.yaml` configuration file. This is an object with keys as the author IDs and values as the metadata for the authors. You can reference the authors in your posts by [using their IDs](/docs/post#authors). We create a page on your blog for each author with their list of posts.

```yaml
authors:
  author-1:
    name: Author 1
    title: Short title
    description: Long description
  author-2:
    name: Author 2
    title: Short title
    description: Long descripiton
```
