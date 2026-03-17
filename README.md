# SkillSprintPlus

## Git reference note

This repository does **not** use a `master` branch by default.

If you see an error like:

`Provided git ref master does not exist`

use one of these instead:

- The current branch: `work`
- The current `HEAD` commit SHA

Examples:

```bash
git checkout work
# or
git rev-parse HEAD
```
