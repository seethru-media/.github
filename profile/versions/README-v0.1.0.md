# seethru.media

> **Version 0.1.0** — Initial Scaffold  
> **Date:** 2025-12-28

**A trust-first news platform.** No outrage optimization. No hidden algorithms. No cookies.

---

## Our Repositories

| Repository | Description | Status |
|---|---|---|
| [core](https://github.com/seethru-media/core) | Platform infrastructure (Engine) | 🚧 Development |
| [science](https://github.com/seethru-media/science) | Science content + Daily Molecule | 🚧 Development |

## What Makes Us Different

| Traditional Media | seethru.media |
|---|---|
| Optimizes for engagement | Optimizes for understanding |
| Hidden algorithms | Open-source ranking |
| Anonymous moderation | Public jury decisions |
| Unclear funding | Public finances |
| Tracks everything | No cookies. No fingerprinting. |

## Core Principles

1. **Geographic Daily Briefs** — News by location, not outrage
2. **Visible Attribution** — Who made it, who funded it, AI involvement
3. **Liberal Moderation** — Only 4 red lines: CSAM, incitement, doxxing, fraud
4. **Forkable Governance** — All docs are CC-BY-SA. Fork us.
5. **Privacy by Default** — No cookies. Server-side sessions only on opt-in.

## Architecture

```
Engine (core/)
├── apps/web      ← Reader (Astro, zero JS)
├── apps/author   ← Content creation (Next.js)
├── apps/admin    ← Moderation (Next.js)
└── packages/     ← Shared code

Fuel (content repos)
├── science/      ← science.seethru.media
└── [future]/     ← politics, environment, etc.
```

## Get Started

```bash
git clone git@github.com:seethru-media/core.git
cd core && yarn install && yarn dev
```

## Status (v0.1.0)

- [x] Monorepo scaffold
- [x] Design system
- [x] Content schemas
- [x] Governance docs
- [x] Science Fuel repo
- [ ] Dynamic content loading
- [ ] User accounts
- [ ] Jury system
- [ ] Live deployment

## License

- **Code:** MIT
- **Governance:** CC-BY-SA 4.0

---

*Built with distrust of easy answers and hope for better ones.*
