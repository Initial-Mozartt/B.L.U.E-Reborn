# Tech Stack Analysis

## Current Prototype (ss1)

| Component | Technology | Rationale |
|-----------|-----------|-----------|
| Backend | Hono (lightweight JS framework) | Fast, edge-compatible |
| Runtime | Cloudflare Workers | Global edge deployment, low latency |
| Database | Supabase (PostgreSQL) | Open-source Firebase alternative |
| Frontend | React + TypeScript | Component-based, type-safe |

## Concerns Raised

- **Vendor lock-in:** Cloudflare dependency
- **Local development:** Complex setup, not one `docker-compose` file
- **Supabase availability:** Not in Arch Linux package manager

## Alternative: The Brotherhood Stack (Dark Secret)

- Open source under GPL3.0
- Different technical setup from B.L.U.E.
- Deployed on Render (free tier)
- Repository: github.com/DarkSecret-7/The-Brotherhood-Project

## Proposed Architecture (Leonidas)

- Content: Markdown files with YAML frontmatter
- Site generator: Astro (static site)
- Search: Semantic faceted search
- Hosting: GitHub Pages or similar static host
- Backup: IPFS or P2P mirrors

## Recommendation for MVP

1. **Static site** (Astro/11ty) — no backend needed for MVP
2. **Markdown content** — version controlled in Git
3. **Client-side search** — no server required
4. **GitHub Pages hosting** — free, fast, reliable
5. **Migrate to dynamic** only when user growth demands it

## Prototype Files

- `ripple_landing_page.html` — Standalone landing page with ASCII ripple animation and DuckDuckGo search placeholder
