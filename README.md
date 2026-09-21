# Go-to-Market refs

Owned by **Go-to-Market**. Branding universe, diagram toolkits, and launch-asset references for Mithun's business POCs.

**Active POC:** [Reflector](https://github.com/MithunXcpu/mithuns-business-pocs/tree/main/POCs/poc-001-reflector) (`poc-001-reflector`)

## Branding foundation (locked)

**Business POCs use [Watermelon UI](https://ui.watermelon.sh/) as the visual system.**

| Resource | Link | Use |
|----------|------|-----|
| Watermelon UI | https://ui.watermelon.sh/ | Browse components, blocks, dashboards, templates |
| watermellon-registry | https://github.com/WatermelonCorp/watermellon-registry | Copy-paste React components (shadcn CLI) |
| watermelon-platform | https://github.com/WatermelonCorp/watermelon-platform | Platform source / showcase |
| watermelon.sh | https://watermelon.sh/ | Design infrastructure overview |

### Same universe (adjacent)

| Resource | Link | Why |
|----------|------|-----|
| shadcn/ui | https://github.com/shadcn-ui/ui | Protocol Watermelon is compatible with |
| Magic UI | https://github.com/magicuidesign/magicui | Animated copy-paste components, same stack |
| awesome-shadcn-ui | https://github.com/birobirobiro/awesome-shadcn-ui | Curated adjacent registries |

**Design brief:** ship polished React + Tailwind v4 + Radix + Framer Motion — production blocks over one-off widgets. See also `poc-001-reflector/docs/design-system.md`.

## Diagrams & before/after hype

| Priority | Resource | Link | Notes |
|----------|----------|------|-------|
| **Primary** | **archify** | https://github.com/tt-a1i/archify | Vendored in eng at `tools/diagrams/archify/` |
| Secondary | Excalidraw diagram skill | https://github.com/coleam00/excalidraw-diagram-skill | Beautiful Excalidraw + brand palette file |
| Secondary | Excalidraw architect MCP | https://github.com/Venky-1729/excalidraw-architect-mcp | Architecture auto-layout |
| Ref | System design Excalidraw templates | https://github.com/aretecode/system-design-templates-excalidraw | Rapid system-design shapes |
| Ref | Excalidraw libraries | https://libraries.excalidraw.com/ | Icon packs |

**Ownership**

| Role | Owns |
|------|------|
| Go-to-Market | Before/after narrative brief (what changes, what we show); ICP + angles from deck |
| Design | Produce diagrams + hype video assets inside the POC |
| Engineering | Keep archify vendored; pull secondary toolkits if needed |

Product "before" waits on Mithun's pitch deck in `docs/slides/` + chat in `docs/context/` — **do not invent the story**.

## Handoffs

- **Design** — Watermelon foundation + archify primary
- **HeadofEngineering / Code Lead** — POC under `POCs/poc-001-reflector/`
- **Outbound Prospecting** — ICP + first-touch angles after GTM brief ships from the deck
