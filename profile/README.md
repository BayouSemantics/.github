# Bayou Semantics

**Built for the companies that build the Gulf South.**

We are a Louisiana AI engineering firm. We build custom AI for industrial companies across Louisiana and Southeast Texas: agents that take a recurring job from start to finish, systems that read the documents your people read by hand, models trained on your own history, and the integrations that connect it all to the software you already run.

Every system is designed around your process, proven against your real work, and monitored after it ships.

[bayousemantics.com](https://bayousemantics.com)

## Open source, free for everyone

The tools we rely on every day are tools anyone can use. We publish them because good practices for working with AI agents should be easy to find, and because we have benefited from others doing the same. No signup, no strings. Everything is MIT licensed.

### [bs-skills](https://github.com/BayouSemantics/bs-skills)

Agent skills we use in our own engineering work. They are plain folders of instructions and scripts, so they work with any agent that reads skills, including Claude Code and Codex.

| Skill | What it does |
| --- | --- |
| [`swarm-mine`](https://github.com/BayouSemantics/bs-skills/tree/master/skills/swarm-mine) | Discovers, classifies, and collects web assets locally. Many agents share one source registry, take turns politely with each website, and never fetch the same document twice. |
| [`graphviz-contract`](https://github.com/BayouSemantics/bs-skills/tree/master/skills/graphviz-contract) | Keeps architecture diagrams tied to the source code they describe, so people can follow a codebase that agents change quickly. |
| [`skills-standard`](https://github.com/BayouSemantics/bs-skills/tree/master/skills/skills-standard) | A short guide to writing skills that agents find and use well. |
| [`git-preferences`](https://github.com/BayouSemantics/bs-skills/tree/master/skills/git-preferences) and [`python-preferences`](https://github.com/BayouSemantics/bs-skills/tree/master/skills/python-preferences) | Our working conventions for git and Python. Fork them and make them yours. |

Install any skill with the [Agent Package Manager](https://github.com/microsoft/apm):

```sh
apm install bayousemantics/bs-skills/skills/swarm-mine
```

Found a bug or have an improvement? Issues and pull requests are welcome.

## Work with us

If your team spends senior hours on repetitive review, or your know how lives in a few key people, we should talk. We start with a free 60 minute AI assessment: we map where the hours go and hand you a short list of what is worth automating, what is not, and what each would return.

[Book an assessment](https://cal.com/bayousemantics)
