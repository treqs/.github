<p align="center">
  <img src="https://raw.githubusercontent.com/treqs/.github/main/profile/treqs-mark.svg" alt="TReqs" width="96">
</p>

<p align="center">
  <a href="https://treqs.ai">treqs.ai</a>
</p>

## Capture what ran. Store the record. Control what runs next.

TReqs gives you a complete record of how your models are actually
built — and what gets to run next. Use any piece on its own.

[**roar**](https://github.com/treqs/roar) — *If it ran, roar saw it.*
A CLI that captures lineage at runtime — data, code, environment, artifacts.
No code changes. No loggers. No frameworks.

[**GLaaS**](https://glaas.ai) — *Every model has a recipe.*
A content-addressable registry of every artifact and job. Resolve any
artifact's hash back to the code, data, and environment that made it.

[**TReqs**](https://treqs.ai) — *Approve before compute.*
Training requests as pull requests. Nothing runs until someone — or a
policy — says go.

## TReqs Tools

| | |
| --- | --- |
| [**roar**](https://github.com/treqs/roar) | Run Observation & Artifact Registration. Prefix any command with `roar run` and it records what was read, what was written, the commit, and the environment — no pipeline to declare and no code to change. |
| [**treqs-cli**](https://github.com/treqs/treqs-cli) | Drive TReqs from a terminal: create and review training requests, configure compute targets, queue runs, and follow their logs. `--json` on any command makes it scriptable — and agent-friendly. |
