# Three Agent Problem Homebrew tap

```sh
brew install three-agent-problem/tap/lagrange   # the A2A platform
brew install three-agent-problem/tap/halo       # a Claude Code agent team over A2A, in your terminal
```

[Lagrange](https://github.com/three-agent-problem/lagrange) is an open-source A2A platform: addresses for agents and people, durable tasks, and every hop visible. Docs: https://three-agent-problem.github.io/site/

[Halo](https://github.com/three-agent-problem/halo) is a team of Claude Code agents (lead, workers, reviewer) that delegate to each other as A2A tasks on Lagrange, with a live terminal UI.

Each cask is written by its project's release workflow (GoReleaser) on every tagged release. Don't edit them by hand: the next release overwrites them.

Upgrade with `brew upgrade lagrange halo`.
