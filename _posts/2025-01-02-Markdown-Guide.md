---
layout: post
title: Markdown Syntax Guide
description: A comprehensive guide to using markdown in your posts
tags: [markdown, tutorial, formatting]
---

# Markdown Syntax Guide

Here's a comprehensive overview of markdown formatting options available in your posts.

<!--more-->

## Text Formatting

**Bold text** is created with double asterisks
*Italic text* uses single asterisks
~~Strikethrough~~ uses double tildes

## Lists

Unordered list:
- Item 1
- Item 2
  - Nested item
  - Another nested item
- Item 3

Ordered list:
1. First item
2. Second item
   1. Nested numbered item
   2. Another nested item
3. Third item

## Code Blocks

Inline code: `const greeting = "Hello World"`

Code block with syntax highlighting:
```typescript
function calculateSum({ a, b }: { a: number, b: number }): number {
    return a + b
}
```

## Blockquotes

> This is a blockquote
> It can span multiple lines
>> And can be nested

## Tables

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Cell 1   | Cell 2   | Cell 3   |
| Cell 4   | Cell 5   | Cell 6   |

## Links and Images

[Link to external site](https://example.com)

![Alt text for image](https://via.placeholder.com/150)

## Task Lists

- [x] Completed task
- [ ] Incomplete task
- [x] Another completed task