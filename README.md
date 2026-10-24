# Dash

The live dashboard for Those Who Run v2, served as static files and
reading NATS directly over WebSocket.
It needs nothing from the pit wall, so it keeps working when the pit
wall is down.

Issues are off in this repository. Every issue, the roadmap and the decisions
(ADRs) live in [those-who-run/paddock](https://github.com/those-who-run/paddock). A pull request here closes
its paddock issue with `Closes those-who-run/paddock#N.`

## Checks

`make check` runs what CI runs; [`AGENTS.md`](AGENTS.md) says what that is and
what a new clone runs first.
