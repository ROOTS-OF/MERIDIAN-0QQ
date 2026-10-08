# Roots-Of/MERIDIAN-0QQ

MERIDIAN_Blue's own 2D agentic-system rootfs — a real "flatland" the way
LeagueOS's own WSL containers are MERIDIAN's product-side rootfs, this
monorepo is the agentic-side equivalent, scoped to MERIDIAN-0QQ's own
workspace.

## Shape

This is a monorepo with many packages and sub-projects, but a cohesive
shape: each parent path down the `AS/` chain below is itself a real space
to discuss a more general version of self, not just a container for the
terminus:

```
AS/MERIDIAN-OTTOBOT/AS/PFM___/AS/LeagueOS/_
```

- `AS/MERIDIAN-OTTOBOT/` — the MERIDIAN-OTTOBOT identity level: everything
  true of this agent regardless of which project it's currently doing.
- `AS/MERIDIAN-OTTOBOT/AS/PFM___/` — the PlayFieldMultiplier office level:
  everything true of MERIDIAN's work inside the PFM office specifically.
- `AS/MERIDIAN-OTTOBOT/AS/PFM___/AS/LeagueOS/` — the LeagueOS project
  level: the actual product work.
- `.../LeagueOS/_` — the terminus: real, current, in-progress artifacts.

Built per `roots-of/roots-of`'s own abstract-class convention — see that
repo for the real "why a meta-schema, not a GitHub template" rationale.

## Real planned content (not yet built)

- `LeagueOS_Blue`/`LeagueOS_Red` tracked as real subclasses of the
  LeagueOS rootfs concept — not started, needs the monorepo's package
  structure decided first.

## Branch hygiene

`main` is protected from the first real commit: PR-required,
`enforce_admins` on, no force-push, no deletion — this monorepo
"contains many universes inside" (Victor's own words) and gets the same
ruthless discipline from day one, not after the first mess.
