# trced.

![apps](https://img.shields.io/badge/apps-4%20shipped-17181a)
![licence](https://img.shields.io/badge/licence-AGPL--3.0--or--later-17181a)
![PWA](https://img.shields.io/badge/PWA-offline-17181a)
![tracking](https://img.shields.io/badge/tracking-none-17181a)

**One thing, done well.**

A family of micro-apps. Each one does a single thing. Free, no account, no ads,
no trackers. They work offline: data stays on the device and can be exported at
any time. Designed and built end to end, from design system to production.

## The apps

| app | what it does | version | source |
| --- | --- | --- | --- |
| [**habit.**](https://habit-eight-blue.vercel.app/) | one week, one grid | `v0.1.1` | [trced/habit](https://github.com/trced/habit) |
| [**journal.**](https://journal-seven-fawn.vercel.app/) | one year, one day at a time | `v0.1.0` | [trced/journal](https://github.com/trced/journal) |
| [**race.**](https://race-ochre.vercel.app/) | all your races, one line each | `v0.1.2` | [trced/race](https://github.com/trced/race) |
| [**urge.**](https://urge-omega.vercel.app/) | one urge, thirty days, one question | `v0.1.0` | [trced/urge](https://github.com/trced/urge) |
| … | more will follow, one at a time | | |

## Principles

1. One thing at a time. What isn't essential isn't built.
2. No account. Open it and use it.
3. No trackers, no ads, no data collection.
4. Offline by default. Local data, exportable and re-importable.
5. One design system across the whole family.

## How they are built

Every app has the same shape: a React and TypeScript progressive web app built
with Vite, installable, and usable with the network switched off.

The logic lives in a `lib/` that knows nothing of React or the DOM — everything
that could be wrong is tested without a browser. French is the reference
language and English a typed mirror, so a missing key fails the build rather
than the page. The interface comes from one shared design system: monospace,
right angles, light and dark following the system.

Storage is the export format. What an app writes is exactly what you get when
you export it, which leaves the two shapes no room to drift apart.

## In every repository

`CHANGELOG.md` · `CONTRIBUTING.md` · `SECURITY.md` · `CODE_OF_CONDUCT.md`, and
the AGPL-3.0-or-later licence. The sources are open because "nothing leaves
your device" is worth exactly what you can check it against.

## Who

trced. is built by one person, Andrea Larboullet Marin — design, code,
shipping. No team, no public roadmap: an app ships as v0.1.0 when it's ready.
From there it evolves — patches, minor and major versions, new features —
always in line with the philosophy, never against it.

[trced.vercel.app](https://trced.vercel.app) ·
[@alarboulletmarin](https://github.com/alarboulletmarin)
