# How to Add New Blog Posts

This guide will help you add new blog posts to document your capstone project journey.

## Quick Start

1. Create a new file in the `_posts` directory
2. Name it with the format: `YYYY-MM-DD-title-of-post.md`
3. Add front matter at the top
4. Write your content in Markdown
5. Commit and push to publish

## File Naming Convention

Blog post files must follow this format:
```
YYYY-MM-DD-title-of-post.md
```

Examples:
- `2026-01-21-week-1-progress-update.md`
- `2026-01-28-certification-1-complete.md`
- `2026-02-04-challenges-and-solutions.md`

## Front Matter Template

Add this at the top of every blog post (between the `---` markers):

```yaml
---
layout: post
title: "Your Post Title Here"
date: YYYY-MM-DD
categories: [Category1, Category2]
---
```

### Suggested Categories

- `Week-1`, `Week-2`, etc. - Track which week of the journey
- `Certification-1`, `Certification-2`, etc. - Track which certification
- `Progress`, `Learning`, `Challenges`, `Resources`, `Reflection` - Content type
- Course-specific categories (e.g., `AWS`, `Azure`, `Python`, etc.)

## Writing Content

After the front matter, write your post content in Markdown.

### Example Post Structure

```markdown
---
layout: post
title: "Week 1: Getting Started with My First Certification"
date: 2026-01-21
categories: [Week-1, Progress, Certification-1]
---

Brief introduction paragraph about what you accomplished this week.

## What I Accomplished

- Item 1
- Item 2
- Item 3

## Key Learnings

Share the most important concepts or skills you learned.

## Challenges Faced

Describe any obstacles you encountered.

## Solutions Found

How you overcame those challenges.

## Resources Used

- [Resource Name](URL) - Brief description
- Book/Course/Tool that was helpful

## Next Steps

What you plan to work on next week.

---

*Reflection or closing thought*
```

## Markdown Tips

- Use `#` for headings (the more `#` symbols, the smaller the heading)
- Use `**bold**` for bold text
- Use `*italic*` or `_italic_` for italic text
- Create lists with `-` or `*`
- Add links: `[link text](URL)`
- Add code: `` `inline code` `` or `` ```language `` for code blocks
- Add images: `![alt text](image-url)`
- Use `---` for horizontal separators

## Testing Locally

Before committing, you can preview your post locally:

```bash
bundle exec jekyll serve
```

Then visit `http://localhost:4000` in your browser.

## Publishing

Once you're happy with your post:

```bash
git add _posts/YYYY-MM-DD-your-post.md
git commit -m "Add week X progress update"
git push
```

GitHub Pages will automatically rebuild your site within a few minutes.

## Tips for Good Blog Posts

1. **Be Consistent**: Try to post at the same time each week
2. **Be Honest**: Share both successes and struggles
3. **Be Specific**: Include concrete examples and details
4. **Be Helpful**: Think about what would help someone else on a similar journey
5. **Be Reflective**: Take time to process what you've learned

## Questions or Issues?

If you encounter any issues with the blog setup or have questions about posting, refer to the [Jekyll documentation](https://jekyllrb.com/docs/) or check the README.md file.
