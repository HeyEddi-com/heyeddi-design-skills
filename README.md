# HeyEddi Design Skills

[![skills.sh](https://skills.sh/b/HeyEddi-com/heyeddi-design-skills)](https://skills.sh/HeyEddi-com/heyeddi-design-skills)

Badge populates after skills.sh indexes the first installs.

Design skills for HeyEddi. `@taste-penpot` owns the look in one pass. `@heyeddi-design` records personas and tokens, then hands off to Vue or Flutter. Penpot is optional.

**skills.sh:** [skills.sh/heyeddi-com/heyeddi-design-skills](https://www.skills.sh/heyeddi-com/heyeddi-design-skills)

**SSOT:** skills are authored in [`HeyEddi-com/heyeddi-skills`](https://github.com/HeyEddi-com/heyeddi-skills) (pack `heyeddi-design-skills`). This repo is the **published skills.sh package** (mirror), not a second authoring tree.

For the broader open toolkit (design, handoff, human PR review, …), install the hub instead.

## Install

```bash
npx skills add HeyEddi-com/heyeddi-design-skills -a cursor -y --skill '*'
```

Pin a release:

```bash
npx skills add https://github.com/HeyEddi-com/heyeddi-design-skills/tree/v1.2.0 -a cursor -y --skill '*'
```

Full open toolkit (design, handoff, human PR review, …):

```bash
npx skills add HeyEddi-com/heyeddi-skills -a cursor -y --skill '*'
```

## Pack (v1.2.0)

| Skill | Role |
|-------|------|
| `@taste-penpot` | General design skill. Code-to-design, then zcube Penpot MCP. |
| `@vue-design-system` | Vue 3 router: Quasar, PrimeVue Aura, motion, tokens, CLI |
| `@quasar-foundation` | App shell, drawers, mobile and desktop frames |
| `@primevue-aura` | Dense data, forms, overlays |
| `@motion-physics` | Spring motion presets |
| `@layout-morph` | Shared-element morphs with Quasar v-morph |
| `@fancy-ui-craft` | Spotlight, glass, one TresJS accent, local dotLottie |
| `@cli-interface-design` | Terminal UI; run the script and read stdout |
| `@aura-design-tokens` | `--app-*` bridge to PrimeVue and Quasar tokens |
| `@visual-verification` | Live Playwright MCP screenshots |
| `@heyeddi-design` | Product context, design.md, handoff |
| `@heyeddi-handoff` | Handoff into the Vue design system |
| `@design-handoff-flutter` | Flutter implementation |
| `@visual-auditor` | Recorded screenshots and contrast |
| `@design-system-generalizer` | Token and component spread |

## Hub maintainer

```bash
# from HeyEddi-com/heyeddi-skills
./scripts/publish-design-pack-repo.sh --out /path/to/heyeddi-design-skills --push
```
