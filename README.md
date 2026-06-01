# zyzshishui.github.io

Personal blog built with [Hugo](https://gohugo.io/) and [PaperMod](https://github.com/adityatelange/hugo-PaperMod).

## Local Preview

```bash
git submodule update --init --recursive
hugo server -D --renderToMemory --baseURL=http://localhost:1313/
```

## New Posts

Create a Chinese post:

```bash
hugo new content/zh/posts/my-post.md
```

Create the matching English post with the same `translationKey`:

```bash
hugo new content/en/posts/my-post.md
```
