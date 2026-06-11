# Hachure

**An open trust format.** Hachures are the short strokes on hand-drawn maps that
show the shape and steepness of terrain. This format does the same for trust:
it shows the contours of what is supported, what is stale, what is disputed,
and what is simply asserted.

Three verbs over one ledger:

- **Assert** — say what you believe, on the record.
- **Observe** — attach what actually happened, append-only.
- **Resolve** — ask anything; every answer comes with receipts or admits it has none.

Statuses are not opinions: `status = f(claim, evidence, events, policy, authority, now)`
is deterministic and versioned. Any implementation can prove agreement by running
the published conformance test vectors — recompute it yourself.

| | |
| --- | --- |
| Website | [hachure.org](https://hachure.org) |
| Specification | [hachure-org/spec](https://github.com/hachure-org/spec) |
| npm | [`hachure`](https://www.npmjs.com/package/hachure) — schemas + conformance test vectors |
| Reference implementation | [`@kontourai/surface`](https://github.com/kontourai/surface) |

Hachure is currently developed by [Kontour AI](https://kontourai.io), which holds
the name to protect it. We intend to move the specification to neutral governance
as adoption warrants.
