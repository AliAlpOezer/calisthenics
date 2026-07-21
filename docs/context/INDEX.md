# Context index — calisthenics

This is a 2-file static repo (`index.html` + `README.md`). Minimal pack — most tasks
just need `STATUS.md`.

| If the task is… | Load | ~tok |
|---|---|---|
| "what's the state / what's next" | `STATUS.md` | 400 |
| build a feature, change behaviour, "where does X live" | `architecture.md` (stub — read `index.html` directly) | — |
| "why is it like this" | `decisions.md` (stub, empty) | — |
| something is broken or looks wrong | `gotchas.md` (stub, empty) | — |
| anything else, or unclear | `STATUS.md` | 400 |

There is no build, no dependencies, and no architecture worth routing to separately —
`index.html` is short enough to read directly when a task needs it.
