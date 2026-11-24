[![make.fun](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)
[![rank](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/qw123gyj-dev/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/rank.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)
[![reward](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/qw123gyj-dev/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/reward.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)

# Real-Life Patch Notes: The Comedy Changelog

One patch note for the oldest bug in real life: walking into a room and forgetting why you went in. `main.ts` writes the line to `entry.txt`, enforcing the gates — non-empty, at most 160 characters, exactly one line with no leading or trailing space — then reads the file back and verifies the bytes match.

> "v2.7.3: fixed a bug where entering a room deleted the reason you came in for; you must now carry it in your hands, like groceries."

Run it with:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/u-0xb3e689-patch-out node main.ts
```
