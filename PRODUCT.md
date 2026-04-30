# Product

## Register

brand

## Users

Three first-class audiences, all reached through the same outward surface (`choco.tools` and the brand layer of `cho-co-web`):

- **Doc authors** — engineers who write, publish, and maintain technical documentation through the choco CLI, editor, and platform. Terminal-comfortable, opinionated about tools, allergic to ceremony. Their context: a 27" monitor, an open IDE, a half-written PR. They visit the brand surface to evaluate updates, read changelogs, and link teammates.
- **Doc readers** — engineers consuming docs hosted on `choco.tools` itself or on customer sites built on choco. Job to be done: find the exact answer, copy a verified code sample, trust the provenance. Their context: between a stack trace and a deadline. Brand surface earns their trust on first read.
- **Evaluators / decision-makers** — devtools buyers, staff/principal engineers, eng managers landing on `choco.tools` to decide whether choco belongs in their stack. Job to be done: form a confident judgment in under three minutes. Their context: a Slack thread asking "what should we use for docs?". Brand surface must convey weight-of-record without overselling.

## Product Purpose

Choco is a verifiable, CRDT-native, MCP-first documentation platform — the cryptographically-attested archive of what was published, when, and by whom, with every code sample executed and every mutation provable through the TimeChain ledger.

The brand surface (`choco.tools`, the marketing layer of `cho-co-web`) is dog-fooded: it is *served by the same pipeline customers use*. The website is the proof.

Success looks like: a developer reaches `choco.tools`, understands within thirty seconds that this is verifiable docs (not a wiki, not an LLM wrapper), and feels that the page they are reading was itself compiled and attested. Evaluators leave with a one-line summary they can paste into Slack. Authors leave with a `choco init` command they trust.

## Brand Personality

Choco's voice and visual language is a deliberate composite, mapped per audience:

- **For authors** — *confident, technical, dry-witted*. Linear/Raycast register: assured experts who don't oversell. Copy is precise; humor is in the negative space.
- **For readers** — *brutalist-precise, document-as-artifact*. Type and grid do the work. Long-form reading is sacred. The docs body type and the front-page hero share the same ink budget.
- **For evaluators** — *editorial, weight-of-record*. Are.na and Bret Victor adjacency: this is the durable record, not the latest feed. Pages feel like they will still be readable in ten years.
- **For everyone — Cocoa, the bean** — *warm, crafted, indie-tool* moments. The cocoa-bean mascot is a recurring **editorial narrator**, not a flat sticker. When it speaks (CLI welcome, first-run, 404, changelog asides), it is specific and earned.

Three-word personality: **verifiable, considered, durable.**

Emotional goal: the same feeling as opening a well-printed reference book that turns out to also be a working compiler.

## Anti-references

These are not what choco looks like. Match-and-refuse.

- **Generic devtools dark + electric blue/purple gradient.** Stripe-clone dashboards, Vercel-mimic landings, Linear-knockoff palettes. The category-reflex look. If a stranger could guess "developer tool" from the gradient alone, redo it.
- **AI-startup glassmorphic hero with floating orbs.** Blurred gradients, glowing accents, "AI-powered" dot grids, marquee logos, animated mesh backgrounds. Choco is not an LLM wrapper and must not look like one.
- **Crypto / web3 neon-on-black.** Even though the TimeChain ledger is cryptographically attested, the brand must not LOOK cryptographic. No neon green, no holographic chrome, no "$CHOCO" energy.
- **Notion / Confluence wiki softness.** Pastel emoji headers, rounded-everything, friendly-blob illustrations, "✨ welcome to your workspace ✨". Choco is verifiable docs, not a wiki.

Positive references (what we're adjacent to, not copying):
- **Linear + Raycast** for devtool craft, keyboard-first ergonomics, opinionated empty states.
- **Are.na + Bret Victor / Tools for Thought** for document-as-artifact, archival seriousness, ideas worth preserving.

## Design Principles

1. **Practice what you preach.** `choco.tools` is served by `cho-co-web` from the same compiler/verifier pipeline customers use. Every brand surface must be inspectable as proof: view-source reveals attested provenance, code samples render their execution status, the page itself is in the TimeChain. If we cannot dog-food a brand surface, we cannot ship it.
2. **Document-as-artifact, not document-as-stream.** Every surface signals durability and weight-of-record. No infinite-scroll feeds, no "what's new this week" dopamine. Pages have a publication date, an author, and an attestation. Choco is the archive, not the timeline.
3. **Confidence through restraint, not loudness.** No gradient text, no glass orbs, no marquee logo walls, no "trusted by" social proof bars. Typography, grid, and exactness carry the signal. If the page needs decoration to feel finished, the writing is wrong.
4. **The mascot has a voice.** Cocoa (the bean) is a recurring editorial narrator with consistent character, not a generic friendly sticker. When Cocoa speaks — CLI welcome, first-run state, 404, changelog asides — the line is specific, slightly dry, and earns its place. If a generic mascot illustration would be interchangeable with Notion's or Mailchimp's, we have failed.
5. **MCP-first means addressable.** Every primary brand surface has a stable URL, a stable contract, and works under `curl`. SPA-only routing for primary content is forbidden — agentic clients must reach the surface as easily as humans do.

## Accessibility & Inclusion

- **WCAG 2.2 AA** baseline across the entire brand surface. Aspirational AAA for long-form reading on `choco.tools/docs/*`.
- **Reduced motion** honored via `prefers-reduced-motion`. No motion is load-bearing; motion is decoration that explains transitions, never information.
- **Color is never the sole signal.** Verification status, error states, and provenance indicators always pair color with shape, label, or icon — color-blind readers see the same record.
- **Keyboard reachability** for every interactive element. Visible focus rings tinted toward the brand hue, not the browser default. Tab order matches reading order.
- **Long-form reading constraints** on docs surfaces: line length capped at 65–75ch, body type ≥16px, ≥1.5 line-height. Code samples never trap the eye against a low-contrast token.
- **Screen-reader semantics** are first-class: landmark regions, descriptive link text, attestation status announced as text, not just rendered as a badge.
