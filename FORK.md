# What this fork changes

Forked from [mattpocock/skills](https://github.com/mattpocock/skills). `upstream` points there;
update with `git fetch upstream && git merge upstream/main`.

This file does not exist upstream, so it will never conflict. Keep the divergence list here rather
than in `README.md`.

## Changed

- **`skills/productivity/grilling`** — asks via the `AskUserQuestion` tool instead of numbered plain
  text, capped at four questions per round with deferred frontier questions named in prose.
  Everything else about the skill (rounds, frontier, design tree, facts-are-the-agent's-job) is
  unchanged.

## Deleted

- **`skills/engineering/implement`** — superseded by `skills/robert/implement`.
- **`skills/engineering/code-review`** — superseded by `skills/robert/two-axis-code-review`.

Prose references to `/implement` elsewhere in the set resolve to the replacement. Prose references to
`/code-review` resolve to Claude Code's built-in skill of that name.

## Added

`skills/robert/` holds skills that aren't Matt's. Upstream merges never touch that directory.
