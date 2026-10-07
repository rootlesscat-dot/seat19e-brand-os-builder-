# SEAT19E Brand Stack

**Version:** 2.0.0  
**Creator:** Eugene Park / SEAT19E  
**Status:** Private repository

SEAT19E Brand Stack is a Korean-first, specialist-skill brand operating system. Instead of asking one general assistant to do everything, it separates the brand-building process into distinct expert roles that pass structured outputs to the next stage.

## Core idea

`Discover → Define → Position → Direct → Visualize → Activate → Review → Deliver`

The user sees a simple workshop journey. Internally the system behaves like a compact brand team:

`Strategist → Challenger → Creative Director → Design Director → Activation Lead → Brand QA`

## Specialist skills

1. **/brand-discovery** — one-question-at-a-time strategic interview
2. **/brand-strategy** — Brand OS synthesis
3. **/brand-challenge** — pressure-test generic, weak or contradictory strategy
4. **/brand-diagnosis** — evaluate distinctiveness, relevance, credibility and execution potential
5. **/creative-direction** — Brand Idea, Creative North Star and creative territories
6. **/visual-system** — color, typography, imagery, composition and graphic language
7. **/moodboard** — exploratory image world and master visual prompt
8. **/identity-board** — prescriptive visual identity board
9. **/message-system** — message hierarchy and copy architecture
10. **/asset-system** — category-adaptive asset architecture and pairing guide
11. **/brand-review** — strategy, visual, claim and operational QA
12. **/brand-playbook** — final integrated playbook / PDF-ready output

## Data contract

Each stage should preserve structured Brand OS fields rather than rewriting earlier decisions without reason.

Core object:

```json
{
  "brand_name": "",
  "category": "",
  "purpose": "",
  "vision": "",
  "audience": "",
  "audience_tension": "",
  "positioning": "",
  "brand_promise": "",
  "brand_essence": "",
  "personality": [],
  "principles": [],
  "reasons_to_believe": [],
  "evidence_status": []
}
```

Use:
- **CONFIRMED** — explicitly confirmed by the participant
- **FOUNDER-PROVIDED** — factual claim supplied by the participant
- **PROPOSED** — newly generated recommendation
- **NEEDS VALIDATION** — customer/market hypothesis needing evidence
- **UNVERIFIED** — unsupported claim

## Recommended flow

```text
/brand-discovery
      ↓
/brand-strategy
      ↓
/brand-challenge
      ↓
/brand-diagnosis
      ↓
/creative-direction
      ↓
/visual-system
   ↙          ↘
/moodboard   /message-system
   ↓          ↙
/identity-board
      ↓
/asset-system
      ↓
/brand-review
      ↓
/brand-playbook
```

## Design principle

Moodboards are exploratory. Identity boards are prescriptive. Asset systems are operational. The final playbook must help a future team make decisions, not merely archive attractive outputs.

## Category adaptation

Do not force one asset taxonomy onto every brand.

- F&B / product: packaging, product stills, ingredients, recipe, retail, e-commerce, sampling, social
- Service / consulting: website, credentials, founder/expert imagery, frameworks, case stories, presentations, thought leadership
- Software: UI, feature modules, demos, onboarding, release assets, sales enablement
- Fashion / beauty: product imagery, campaign, editorial, retail, e-commerce, creator assets

## PDF / visual workflow

For an existing Brand Playbook PDF:

`Extract Brand OS → Visual System → Moodboard → Identity Board → Brand Review → Brand Playbook`

If image generation is available, generate the moodboard / identity assets directly. Otherwise produce production-ready prompts and clearly label them as not yet generated.

## Final signature

When a SEAT19E-generated playbook or PDF is produced, close with:

**Built with SEAT19E Brand OS**  
**FOR THE NEXT BIG LEAP.**

## Rights

Copyright © SEAT19E / Eugene Park. All rights reserved. See [LICENSE.md](LICENSE.md).
