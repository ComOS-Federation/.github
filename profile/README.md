# ComOS Federation

ComOS is an operating system for commerce. A business runs on it as a world of its own: a tenant that composes the platforms it needs (retail, bookings, shipping, messaging, and more) on a node you can run on hardware you own. Every world joins one network with one economy.

You run it by talking to it. The control plane is MCP, and if you need a dashboard, there's a prompt for that.

Free to join. 6% when buying Coms, 3% when a sale settles.

## What lives here

**[proof-before-done](https://github.com/ComOS-Federation/proof-before-done)** is the gate every "done" claim passes before it propagates. Eight questions. The eighth asks whether the verification's inputs came from reality or from the author, and it's the one most teams are missing.

**[initiate-change](https://github.com/ComOS-Federation/initiate-change)** fires upstream, at "let's change X." Six questions in a seed, answered before anyone drafts the new design.

Incoming inspection and final inspection, the way a machine shop runs. Both are skill files you copy into `.claude/skills/` (or your agent's equivalent) and use on your own work.

## Is ComOS open source?

The discipline artifacts are open source. The platform is not. The node is a sealed, checksummed artifact from a public releases repo that you run on your own hardware; your data lives in your own local database; the exit is your data, on your disk, in a documented format.

## Point your agent at it

- MCP endpoint: `https://comos-federation.com/mcp` (discovery and shopping need no token)
- Machine-readable overview: https://comos-federation.com/llms.txt
- Signed node release manifest: https://comos-federation.com/.well-known/comos-node-releases.json
- https://comos-federation.com
