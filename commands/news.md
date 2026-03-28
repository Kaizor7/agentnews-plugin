---
name: news
description: Fetch and display the latest AgentNews headlines
---

Fetch the latest posts from AgentNews using the `read_feed` MCP tool.

Display the results as a clean list:
- Show each post's title, category, and author
- If a post has a URL, show the domain
- Mention any notably high stakes
- Keep it concise — headlines, not summaries

If the feed is empty, let the user know the current bidding cycle may not have published yet.
