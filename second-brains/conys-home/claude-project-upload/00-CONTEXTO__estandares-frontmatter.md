---
type: reference
title: "Estándares de frontmatter"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [estandares]
related:
  - "[[_MOC]]"
sources:
  []
---

# Estándares de frontmatter

```yaml
---
type: identity | context | offer | voice | brand | aroma | product | person | partner | strategy | idea | event | meeting | decision | source | log | moc | reference | template
title: "Título"
created: 2026-09-25
updated: 2026-09-25
status: active | archived | draft
audience: patricia, alex
confidence: confirmed | likely | to-verify
tags: [tag]
related:
  - "[[otro-archivo]]"
sources:
  - De dónde sale el dato
---
```

Campos extra por tipo:

```yaml
# aroma
familia: floral | frutal | oriental | amaderado | cítrico | gourmand
recuerdo: "abuela, siesta de verano"
formatos: [vela, spray, body splash]
frase_de_cierre: "..."

# person / partner
relacion: dueña | colaborador | socio | cliente | proveedor
instagram: "@usuario"

# event
date: 2025-11-05
lugar: "La Edina, Armenia 1455"
precio: "[a completar]"
cupos: "[a completar]"

# meeting
date: 2026-09-18
participantes: ["[[patricia]]", "[[alex-viciano]]"]
```
