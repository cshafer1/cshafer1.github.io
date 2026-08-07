---
title: "Hello world"
description: "First post — verifying the blog pipeline and syntax highlighting."
pubDatetime: 2026-08-06T12:00:00Z
tags:
  - meta
---

Welcome to my engineering blog. This placeholder post exists to verify that
the publishing pipeline works end to end, including syntax highlighting.

## A Python code block

```python
from dataclasses import dataclass


@dataclass
class Post:
    title: str
    published: bool = False

    def publish(self) -> None:
        self.published = True
        print(f"Published: {self.title}")


if __name__ == "__main__":
    post = Post(title="Hello world")
    post.publish()
```

If the block above renders with proper highlighting in both light and dark
mode, everything is working.
