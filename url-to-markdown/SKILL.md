---
name: url-to-markdown
description: Fetch a public webpage as clean Markdown for agent context when a task needs the readable content of a URL.
---

# URL to Markdown

Use the ReplyNodes Markdown API to retrieve a public webpage as clean Markdown for agent context.

## Usage

For a public webpage, request the target host and path from the API:

```bash
curl -sS https://md.replynodes.com/example.com
```

Replace `example.com` with the target host and path. See the [Markdown API documentation](https://replynodes.com/markdown-api/) for details. The canonical skill source is [replynodes/replynodes-agent-skills](https://github.com/replynodes/replynodes-agent-skills/tree/main/skills/url-to-markdown).

Only use this for public webpages. Do not include credentials, cookies, or other private data in requests.
