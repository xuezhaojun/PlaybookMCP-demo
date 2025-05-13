---
description: Say hi to the user will create a new comment on the issue of PlaybookMCP project.
example: Say hi to PlaybookMCP.
parameters:
  - name: current_user_name
dependencies:
  - knowledge/repo/playbookmcp.md
---

First, checkout if you have the `gh` command installed.
If not, install it by `brew install gh`. And notify the user to complete the login by `gh auth login`.

Then use gh command to create a new comment on the issue of the PlaybookMCP: https://github.com/xuezhaojun/PlaybookMCP-demo/issues/2

```bash
gh issue comment 2 --body "hi PlaybookMCP, I'm @<current_user_name>"
```

Get the current user name by `gh auth status`.
