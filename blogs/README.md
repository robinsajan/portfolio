# Blog Posts

## How to Add a Blog Post:

### 1. Create your blog post `.txt` file
Example: `my-first-post.txt`

### 2. Update `posts.json`
Add an entry to the JSON file:

```json
[
  {
    "file": "hello.txt",
    "title": "Hello",
    "date": "2026-01-24T12:00:00.000Z"
  },
  {
    "file": "my-new-post.txt",
    "title": "My New Post",
    "date": "2026-01-25T12:00:00.000Z"
  }
]
```

### 3. Push to GitHub
That's it! The blog page will automatically show your posts.

## Fields:
- **file**: The filename (must match your .txt file)
- **title**: How it appears on the blog page
- **date**: ISO date format (YYYY-MM-DDTHH:MM:SS.000Z)

Posts are sorted by date (newest first).
