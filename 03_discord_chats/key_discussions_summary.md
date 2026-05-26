# Key Discord Discussions Summary

## 1. Content Strategy: Create vs. Curate vs. Search

**cuitin** proposed: "Instead of creating content, build an education-only search engine."

**Team response:**
- benzo: Content should be learnable entirely through B.L.U.E., not just links
- Elias: Hybrid approach — start with curated search, evolve to original content
- **Consensus:** Start as specialized search/curated links, build original guides over time

## 2. Architecture: DAG Knowledge Graph

**Leonidas Zervas** proposed:
- Directed Acyclic Graph (DAG) for prerequisites
- YAML frontmatter in Markdown files for machine-readable metadata
- Astro static site generator
- Semantic faceted search: [WHAT/HOW] [BUILD/LEARN] [TOPIC]

**Team concerns:**
- LaEspada: 60 prerequisite articles for advanced topics is overwhelming
- Leonidas: Use progressive disclosure — show only immediate prerequisites (Level N-1)

## 3. The Brotherhood Collaboration

**Dark Secret** offered The Brotherhood Project (GPL3.0) as infrastructure base:
- Skill graph / curriculum mapping
- Work-based assessment (not test-based certification)
- Already deployed at the-brotherhood-project.onrender.com

**Position:** Collaboration > integration. B.L.U.E. creates content, Brotherhood maps curricula.

## 4. Certification Philosophy Debate

**Dark Secret:** Traditional certifications are gatekeeping. Track actual work/portfolios.

**Tim:** Transparent test-based credentials are fine. "Can multiply fast" is a clear credential.

**Status:** Unresolved philosophical disagreement.

## 5. Tech Stack Debate

**Current prototype:** Hono + Cloudflare Workers + Supabase + TypeScript/React

**argator's concerns:** Dependency on Cloudflare, inconvenient local setup

**ss1's response:** Prototype stack, open to migration for production

**Dark Secret's alternative:** Brotherhood codebase (different stack, GPL3.0)

## 6. The Ripple / MVP Movement

A community member (not an admin) posted:
- "We should NOT focus on making the whole site from the start"
- Proposed The Ripple as visual identity
- Advocated for true MVP: landing page + search + user submissions
- Received significant positive reaction from community

## 7. Business Model Questions (benzo)

- Importing copyrighted content: requires legal partnerships
- Advertising/affiliate links: needs consistency across topics
- Donor benefits: educational software bundles proposed
- **Status:** All open questions, no decisions made

## 8. Governance & Legal

From the roadmap document:
- 501(c)(3) non-profit proposed
- "Constitution" with termination clauses for leadership
- Voting mechanism must be architecturally separate from website
- No share sales, no rebranding beyond aesthetic changes
- **Status:** Documented but not implemented
