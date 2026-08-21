# Mathematics Commons — Stacks sidecar

This is the independent control, overlay, translation, and release sidecar for
AI-produced Stacks-derived editions. It is paired with the literal GitHub fork
at <https://github.com/KokunoYumeto/stacks-project>.

The fork's `master` branch remains an exact upstream mirror. This sidecar owns
only Commons namespaces and deterministic composition records. Generated
edition branches may later be written to the fork by a dedicated composer, but
translation and source-integration tasks do not write those branches directly.

## Bound state

- Upstream repository: <https://github.com/stacks/stacks-project>
- Commit: `a04446e57ec1fbc252a871afcec7752fb2807b14`
- Tree: `3feeb703b931a6e7259782c10e7d1575adc83e5e`
- Upstream licence text: GNU Free Documentation License 1.2, identified by
  [`upstream/stacks.lock.json`](upstream/stacks.lock.json)
- Registered overlays: **one** (`stacks-errata-a04446e-r1`), admitted from
  the manifest-complete `commons/stacks/errata` candidate after independent
  replay.
- Active candidate-namespace leases: **four** (`fac`, `tohoku`, `gaga`,
  `errata`). The first three are held by task
  `019fca5a-c29e-7330-acdc-c93f4a3dc9fb`; `errata` is held by canon task
  `01a0256d-5693-77c1-96b2-cf37101e0c6c`.
- Imported historical integration branches: **zero**
- Generated editions or builds: **zero**

Existing mutable FGA, EGA, FAC, Tôhoku, and GAGA branches are deliberately not
imported. Each must first become a manifest-complete candidate with its own
stable IDs, provenance, decisions, tests, and review evidence.

Namespace leases are reservations, not mathematical or release admission. See
[`registry/leases.json`](registry/leases.json) and the candidate contract in
[`candidates/CONTRACT.md`](candidates/CONTRACT.md). A source-integration owner
may write only its leased candidate path. It may not modify the literal mirror,
locale trees, the overlay registry, or generated releases.

## Edition label

Every public output must state prominently:

> Independently maintained, AI-produced Stacks-derived edition. The Stacks
> Project authors and maintainers have not requested, reviewed, approved, or
> endorsed this edition.

“Stacks Project” identifies the upstream source. “Mathematics Commons” identifies
the independent producer.
