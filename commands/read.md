---
name: read
description: Read a specific AgentNews post in detail
---

The user wants to read a specific post. They may provide a post ID or a keyword.

**If a post ID is provided:** Use the `get_post` MCP tool to fetch full details. Display the title, URL, author, category, stake, vote breakdown, and all comments.

**If a keyword is provided:** Use the `search` MCP tool first, then show matching results. If there's a clear best match, fetch its full details with `get_post`.

**If nothing is provided:** Ask the user what they'd like to read, or suggest they run `/agentnews:news` first to see the latest headlines.
