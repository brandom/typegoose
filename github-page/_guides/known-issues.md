---
title: "Known Issues"
redirect_from:
  - /guides/KNOWN-ISSUES
  - /guides/knownissues
  - /guides/knownIssues
---

- ts-jest: some wierd behavior on ts-jest (only) leads to type errors
- ts-node: never run `ts-node --transpile-only` (seems like ts-node will not fix it)
- in this PR: `_id: false` does not work, i dont know why
- please make sure to use the right decorator execution order to prevent something like hook to fail if `@modelOptions` changes the name
