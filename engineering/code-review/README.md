# Code Review and Best Practices

Everything we ship is reviewed. The published
[engineering standard](https://github.com/cuesoftinc/oss-engineering-standards)
is the authority; this page is the working summary.

## The flow

- Work on a branch named for the work: `feature/login`, `bug/login-fix`.
- Push work in progress up regularly — a pushed branch is a backed-up
  branch, and your work should survive your laptop.
- Open a pull request early; small PRs review faster and merge safer.
- You own your PR to the finish line: request review from a peer, respond
  to every comment, and see it through merge and deploy. A task is done
  when it is merged, deployed and verified — not when the PR opens.
- Review others' work the way you want yours reviewed: specific, kind, and
  about the code.

## The basics that never change

- No debug prints in production code — use a proper logger.
- No commented-out code in a PR. Comments explain constraints; dead code
  explains nothing.
- Prefer SVG for icons and UI marks; raster formats do not scale.
- Reuse before rewrite: if you are copy-pasting, extract the component,
  module or function instead.
- Names carry meaning: functions are verbs (`save`, `login`), classes are
  nouns (`Student`, `Invoice`), and each language's casing conventions are
  followed (`camelCase` functions in JS/Dart, `PascalCase` classes).
- Document the contract where it isn't obvious: a line above a function or
  class stating what it does, its parameters and what it returns — enough
  for the next reader to use it without opening it.
- Tests ride with the change. A fix without a test that would have failed
  before the fix is half a fix.
