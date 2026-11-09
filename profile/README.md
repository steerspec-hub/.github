<div align="center">

<img src="https://steerspec.dev/assets/logo-transparent.svg" alt="SteerSpec logo" width="96" height="96">

# SteerSpec Hub

**Standards as realms — pin a standard the way you pin core, and measure your rules against every clause.**

[![Website](https://img.shields.io/badge/steerspec--hub.com-visit-1f6feb)](https://steerspec-hub.com)
[![SteerSpec](https://img.shields.io/badge/built%20on-SteerSpec-2ea44f)](https://steerspec.dev)

[Why](#why) · [How it works](#how-it-works) · [Repositories](#repositories) · [Status](#status)

</div>

## Why

*"We cover 80 % of ASVS L2"* needs a denominator. A [SteerSpec](https://steerspec.dev) project sees
only the clauses its own rules map: a clause nobody mapped is invisible, and a typo in a clause
number passes.

SteerSpec Hub publishes standards as versioned **Standard Realms**: every clause, with its own number
and level, as Published rules. SteerSpec itself still holds no clause list. Each realm is published
under the standard's own licence, with attribution to its authors.

## How it works

```mermaid
flowchart LR
    S["<b>Standard</b><br/>machine-readable release"]
    R["<b>Standard Realm</b><br/>one rule per clause, tagged release"]
    P["<b>Your project</b><br/>rules map clauses"]
    C["<b>Coverage</b><br/>mapped, gaps, typos"]

    S -->|generated into| R
    R -->|pinned as a dependency by| P
    P -->|checked in CI| C

    classDef hub fill:#1f6feb,stroke:#1f6feb,color:#ffffff
    class R hub
```

A project depends on a realm the way it depends on core. Coverage, gaps and clause typos then become
checks its CI can run.

## Repositories

| Repo | What it holds | Licence |
| ---- | ------------- | ------- |
| [**strspc-hb-std-owasp-asvs**](https://github.com/steerspec-hub/strspc-hb-std-owasp-asvs) | OWASP ASVS 5.0.0 as the realm `dev.steerspec.std.owasp.asvs.v5`, generated from OWASP's JSON release | CC BY-SA 4.0 |

More standards follow once the pilot realm ships.

## Status

| Realm | Profile | Requirements | State |
| ----- | ------- | ------------ | ----- |
| OWASP ASVS 5.0.0 | L1 | 70 | In progress |
| | L2 | 253 | Planned |
| | L3 | 345 | Planned |

Things will change. Feedback welcome.

<div align="center">

The tooling is [SteerSpec](https://github.com/SteerSpec), Apache 2.0. Each realm carries the licence of its standard.

</div>
