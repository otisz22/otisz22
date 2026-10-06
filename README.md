# Ottó Misák · Misak Systems

Software engineer in Hungary. I build automation, agent systems, developer tooling and
physical prototypes that do real work, and I start from the problem, not the tool.

**Website:** [misaksystems.com](https://misaksystems.com) · **Services:** [misaksystems.com/services](https://misaksystems.com/services)

## What I work on

- **Automation and agent systems.** A self-hosted multi-agent setup in daily use:
  agents with shared memory, a task board, a scheduler, approvals and background
  workers, plus a phone control app behind Cloudflare Access.
- **Deadline-driven code repair (API Sunset).** A scanner that finds the deprecated API
  versions, SDK pins and retired AI model IDs a codebase actually uses and matches each
  hit to the vendor's official shutdown date. The rules are public in
  [api-sunset-rules](https://github.com/otisz22/api-sunset-rules).
- **Compliance tooling.** Readiness checks for EU rules that hit small firms (CRA, AI Act
  transparency, EUDAMED UDI, ICS2).
- **Physical prototypes.** Print-in-place mechanisms for 3D printing and laser-cut designs,
  with clearance, overhang and motion checks before anything is printed.

## Open-source impact

Findings reported to public projects: **27 issues** so far, each tied to an official vendor
source and date. Fixed by the maintainers, for example:

| Project | Issue | Outcome |
|---|---|---|
| [apache/beam](https://github.com/apache/beam/issues/40401) | Self-hosted runner image (2.296.2) below GitHub's new minimum runner version (2.329.0) | Fixed |
| [stacksjs/stacks](https://github.com/stacksjs/stacks/issues/2856) | FCM topic subscription on the Firebase Instance ID API, shutting down 2027-09-29 | Fixed |
| [jonwiggins/optio](https://github.com/jonwiggins/optio/issues/638) | New Sign in with Apple relay domain (private.icloud.com) missing from the auto-join block list | Fixed |
| [oomol-lab/open-connector](https://github.com/oomol-lab/open-connector/issues/648) | Google Ads API v22 sunset on 2026-10-07: base URL and campaign date fields | Fixed |

### If you got an issue from me

It names the rule it matched, the official vendor source and date, and what was and was not
checked. If the date or the finding is wrong, reply on the issue and I will correct the rule.

## Stack

Python · TypeScript · Node.js · SQLite · PostgreSQL · GitHub Actions · Cloudflare (Workers,
Tunnel, Access) · LLM agents · Blender / manifold3d · Bambu and Snapmaker slicing · xTool

Before all this: desktop process automation since 2006, and IT supervision of an ATM network.

## Contact

Via [misaksystems.com/contact](https://misaksystems.com/contact)
