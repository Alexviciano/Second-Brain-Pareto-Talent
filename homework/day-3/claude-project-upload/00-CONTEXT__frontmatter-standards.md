---
type: reference
title: "Frontmatter Standards"
created: 2026-09-24
updated: 2026-09-24
status: active
audience: kasim, ea
confidence: confirmed
tags: [standards, frontmatter]
related:
  - "[[_MOC]]"
sources:
  []
---

# Frontmatter Standards

Every file starts with YAML frontmatter. Shared fields:

```yaml
---
type: identity | context | offer | company | person | idea | event | call | decision | doc | source | log | moc | reference | instructions | template
title: Human readable title
created: 2026-09-24          # ISO date
updated: 2026-09-24
status: active | archived | draft
audience: kasim, ea          # who should read it
confidence: confirmed | likely | to-verify
tags: [tag-one, tag-two]
related:
  - "[[other-file]]"
sources:
  - Where the facts came from
---
```

Extra fields by type:

```yaml
# company
role: co-founder | owner | partner
stage: pre-revenue | sub-1m | 1m-10m | 10m-plus
team_size: 15

# person
first_name: Ivan
last_name: Bunin
relationship: co-founder | client | advisor | mentor | partner | guest | employee | family
company: "[[pareto-talent]]"
last_contact: 2026-09-23

# event
date: 2026-10-15
location: Phoenix, AZ
price_usd: 2000
capacity: 20

# call
date: 2026-09-23
participants: ["[[ivan-bunin]]"]
recording: fathom | zoom | none

# decision
date: 2026-09-24
decided_by: "[[kasim-aslam]]"
reversible: true
```
