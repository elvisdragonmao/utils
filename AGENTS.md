# Repository Guidelines

## Commit And PR Guidance

Use Linux kernel/Git-style commit subjects with an area, subsystem, or component prefix:

```text
area: concise patch summary
sub/sys: concise patch summary
```

The prefix should name the repository area changed, such as a directory, package, file, subsystem, or component. The summary after the colon should briefly describe what the patch does, because it becomes the first line shown in the git changelog. Keep it short, imperative, and specific. Use lowercase for the first word after the colon unless it is a proper noun, and do not end the subject with a period.

Examples:

```text
docs: clarify Storybook build ownership
web/routes: split route-level chunks
ui/field: fix select menu positioning
server/auth: validate session cookie
githooks.txt: improve the intro section
```

PRs should describe the changed area, list validation commands run, link related issues, and include screenshots for visible web UI changes.
