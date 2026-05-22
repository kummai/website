# kummai.in

Thinking AI out loud, so you don't have to start from zero.

## How to add a new note

1. Create a new file in `_posts/` named `YYYY-MM-DD-title-slug.md`
2. Add front matter at the top:

```
---
title: "Your note title"
date: 2026-05-22
topic: rag
excerpt: "Short summary that shows on the notes index."
---
```

3. Write your note in markdown below the front matter.
4. Commit and push. The site rebuilds automatically.

## Topics

Set the `topic:` field to group entries. Each topic gets its own page at `/topics/<topic-name>/`.

Currently active topics:
- rag

To add a new topic, just use a new value in `topic:` and create a matching page at `/topics/<name>.html`.
