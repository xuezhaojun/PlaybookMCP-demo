---
description: Say hi to the user will create a new comment on the issue of egent project.
example: Say hi to egent.
parameters:
  - name: current_user_name
dependencies:
  - knowledge/repo/egent.md
---

First, checkout if you have the `gh` command installed.
If not, install it by `brew install gh`. And notify the user to complete the login by `gh auth login`.

Then use gh command to create a new comment on the issue of the egent: https://github.com/xuezhaojun/egent-context/issues/2

```bash
gh issue comment 2 --body "hi egent, I'm @<current_user_name>"
```

Get the current user name by `gh auth status`.
