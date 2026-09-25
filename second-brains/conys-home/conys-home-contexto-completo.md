# Cony's Home: Segundo cerebro (contexto completo en un solo archivo)

Este archivo reúne todas las notas del segundo cerebro. Cada sección empieza con `=== ARCHIVO: carpeta/archivo.md ===`. Cuando respondas, nombrá el archivo de donde sacaste el dato.


=== ARCHIVO: 00-CONTEXTO/_MOC.md ===

---
type: moc
title: "00 Contexto"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [moc]
related:
  - "[[_MOC]]"
sources:
  []
---

# 00 Contexto

Los archivos base. Leelos primero en cada sesión nueva.

## Contenido
- [[como-usar-este-cerebro]]: guía rápida para Patricia y Alex
- [[identidad]]: quién es Cony's Home y quién es Patricia
- [[foco-actual]]: prioridades de la marca y del trabajo digital
- [[productos-y-precios]]: catálogo y precios
- [[voz-de-marca]]: cómo escribe la marca (tono, palabras, emojis, CTA)
- [[voz-de-patricia]]: cómo habla y piensa Patricia
- [[glosario]]: términos propios
- [[estandares-frontmatter]]: plantillas de frontmatter
- [[checklist-de-materiales]]: qué falta reunir y dónde va


=== ARCHIVO: 00-CONTEXTO/checklist-de-materiales.md ===

---
type: reference
title: "Checklist de materiales"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [checklist]
related:
  - "[[10-FUENTES/_MOC]]"
sources:
  []
---

# Checklist de materiales

Todo entra **a través de Claude** ("procesá esto y guardalo en el segundo cerebro").

## Fase 1: Base (hoy)
- [x] Export de Instagram (40 posteos)
- [x] Apuntes de la reunión con Patricia
- [x] Presentación de estrategia de Alex
- [x] Notas de voz de WhatsApp transcritas → `07-REUNIONES/notas-de-voz-2026-09`
- [ ] Guion de la experiencia (Patricia lo está escribiendo)
- [x] Paleta de colores (HEX) de la presentación → `03-MARKETING/identidad-visual`
- [ ] Lista de precios actual → `productos-y-precios`
- [ ] Lista completa de aromas, con nombre, descripción y recuerdo → `01-MARCA/catalogo-de-aromas`

## Fase 2: Esta semana
- [ ] Historia de Patricia contada por ella (audio o entrevista grabada): abuela, madre, campo, formación científica
- [ ] Datos de ventas: qué se vende más, ticket promedio, canales
- [ ] Métricas de Instagram (seguidores, alcance, perfil de la audiencia)
- [ ] Fotos y descripción del atelier; horarios de atención

## Fase 3: Este mes
- [ ] Referentes y competencia que admira (sin copiar)
- [ ] Proveedores de materias primas
- [ ] Prensa, colaboraciones y eventos pasados completos


=== ARCHIVO: 00-CONTEXTO/como-usar-este-cerebro.md ===

---
type: reference
title: "Cómo usar este segundo cerebro"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [guia]
related:
  - "[[_MOC]]"
  - "[[voz-de-marca]]"
sources:
  []
---

# Cómo usar este segundo cerebro

**Qué es:** una carpeta con notas cortas sobre Cony's Home: quién es Patricia, los aromas, los productos, la voz de la marca y la estrategia. Claude la lee, así que no hace falta volver a explicar la marca cada vez.

**Dónde preguntar:** en el Proyecto de Claude **"Cony's Home: Segundo cerebro"**. Abrí un chat nuevo por tarea. Cuando la precisión importe, terminá con: *"¿Qué archivo usaste?"*

**Qué pedir:**
- "Escribí 3 posteos sobre el aroma Susurro Oriental con la voz de la marca."
- "Armá la descripción del body splash para la tienda online."
- "Contá la historia de la abuela en un reel de 30 segundos (guion)."
- "¿Qué productos tenemos en cera de coco?"

**Cómo sumar información:** nunca arrastres archivos a las carpetas. Dáselos a Claude y decile: **"guardalo en el segundo cerebro"**. Por ejemplo: un audio transcrito, una lista de precios, una foto descrita, una reunión.


=== ARCHIVO: 00-CONTEXTO/estandares-frontmatter.md ===

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


=== ARCHIVO: 00-CONTEXTO/foco-actual.md ===

---
type: context
title: "Foco actual"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [foco, estrategia]
related:
  - "[[estrategia-digital]]"
  - "[[experiencias]]"
  - "[[tienda-online]]"
sources:
  - Presentación de Alex para Cony's Home
  - Apuntes reunión con Patricia (Alex)
---

# Foco actual

**En una frase:** llevar al mundo digital la historia, el conocimiento y el proceso artesanal de Cony's Home, para que Instagram lleve gente al atelier y a una tienda online.

## Prioridades (según la propuesta de Alex)
1. **Identidad reconocible en redes:** menos "publicar por publicar", más historia, proceso y conocimiento. Ver [[estrategia-digital]].
2. **Fotografía y video más cuidados:** texturas, packaging, encendido, formas de uso.
3. **Tienda online simple:** catálogo con aromas, compra, envío o retiro en el atelier. Ver [[tienda-online]].
4. **Definir la experiencia en el atelier:** qué formato representa mejor la filosofía de la marca. Ver [[experiencias]].
5. **Nuevas líneas:** packs para regalo, y una frase de cierre para cada aroma con nombre. Ver [[catalogo-de-aromas]].

## Qué vive en la cabeza de Patricia
Los aromas, sus recuerdos y cómo explicarlos. Por eso el trabajo es sacarlo de su cabeza y llevarlo a contenido.


=== ARCHIVO: 00-CONTEXTO/glosario.md ===

---
type: reference
title: "Glosario"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [glosario]
related:
  - "[[identidad]]"
  - "[[catalogo-de-aromas]]"
sources:
  - Instagram @conys.home (40 posts, export 2026-09)
  - Apuntes reunión con Patricia (Alex)
---

# Glosario

| Término | Significado |
|---|---|
| Laboratorio de aromas | Cómo se define la marca y cómo llama a su espacio |
| Atelier / la casita | El local en La Edina, Armenia 1455, atelier 6 |
| La Edina | Espacio colectivo de marcas de autor en Palermo donde está el atelier. Ver [[atelier-la-edina]] |
| Cata / experiencia olfativa | Actividad de oler y descubrir a dónde te lleva cada aroma |
| Talquito de rosas | El aroma de la abuela, un símbolo de la marca |
| Ratoncito | Apodo de Patricia de chica, porque lo olía todo |
| Frase de cierre | La frase que termina la descripción de cada aroma |
| Armá tu kit | Kit armado por el cliente, con packaging de regalo |
| MD | Mensaje directo en Instagram |


=== ARCHIVO: 00-CONTEXTO/identidad.md ===

---
type: identity
title: "Identidad: Cony's Home y Patricia"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [identidad, marca]
related:
  - "[[patricia]]"
  - "[[historia-de-la-marca]]"
  - "[[atelier-la-edina]]"
  - "[[productos-y-precios]]"
  - "[[voz-de-marca]]"
sources:
  - Instagram @conys.home (40 posts, export 2026-09)
  - Apuntes reunión con Patricia (Alex)
  - Presentación de Alex para Cony's Home
---

# Identidad: Cony's Home y Patricia

## La marca en una frase
**Cony's Home es un laboratorio de aromas artesanal en Palermo.** Patricia crea velas, jabones, sprays y fragancias 100 % naturales a partir de la ciencia (biología, química) y de los recuerdos que despiertan los olores.

| Campo | Dato | Fuente |
|---|---|---|
| Nombre | Cony's Home ("Cony´s home • Aromas") | Instagram |
| Instagram | [@conys.home](https://www.instagram.com/conys.home/) | Instagram |
| Bajada | Laboratorio de aromas | Presentación |
| Creadora / dueña | [[patricia|Patricia]], argentina (apellido [a completar]) | Alex; comentario "HOLA PATRI!" |
| Atelier | [[atelier-la-edina|La Edina]], Armenia 1455, atelier 6, Palermo Soho, CABA | Instagram |
| En el atelier desde | Agosto 2025 | Instagram 2025-08-09 |
| Diferencial | Base científica + artesanía + 100 % natural + aromas con historia | Presentación, apuntes |
| Web / tienda online | [a completar] (hoy la venta es por mensaje privado) | Instagram |

## Qué la hace única
- **Conocimiento:** la marca nace de la biología, la química y el conocimiento de los aromas.
- **Artesanía:** todo es hecho a mano, con ingredientes 100 % naturales. Lo prueban hasta dar con el equilibrio ("prueba y error constante").
- **Memoria:** cada aroma se piensa como un recuerdo. "Los olores nos llevan a recuerdos: llegan muy rápido, de la nariz directo al centro del cerebro."
- **Una casa, no una tienda:** "La casita" viene de que Patricia vivía en el campo. En el atelier la gente huele, comparte anécdotas y a veces trae aromas propios para crear algo juntos.
- **Tres generaciones:** su abuela (el "talquito de rosas"), su madre (autodidacta, luchadora) y ella. Mujeres empoderadas. Patricia quiere que su abuela esté presente en la marca.

## Pendiente de confirmar
- Origen del nombre "Cony" [a completar] · Año de fundación [a completar].
- En redes: Patricia **no quiere mostrar su cara todo el tiempo**. Puede aparecer en momentos puntuales, y el resto del contenido va con su voz, sus manos y el proceso (ver [[voz-de-patricia]]).


=== ARCHIVO: 00-CONTEXTO/productos-y-precios.md ===

---
type: offer
title: "Productos y precios"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [productos, precios, catalogo]
related:
  - "[[catalogo-de-aromas]]"
  - "[[experiencias]]"
  - "[[tienda-online]]"
sources:
  - Instagram @conys.home (40 posts, export 2026-09)
---

# Productos y precios

**Los precios no aparecen en ningún material.** Hay seguidores que los preguntan en los comentarios ("Qué precio tienen las distintas velas?", "Precio x favor") y hoy se responden por privado. Cargarlos es prioridad: [a completar].

| Línea | Productos | Precio |
|---|---|---|
| Velas | de soja, de molde, de **cera de abeja** (pueden traer "pelitos": es propio del proceso), de **cera de coco** (ecológica, biodegradable, combustión limpia, más duración), cera en perlas | [a completar] |
| Cuerpo y manos | jabones naturales de coco; jabones artesanales saponificados con almendras, oliva y aceites esenciales; jabón líquido / de manos; **body splash** (no pegajoso, uso diario) | [a completar] |
| Casa y textil | **spray textil** (dura en las telas), difusor, aromatizante de cajones y placard, bolitas de cerámica bizcocho para aromatizar, flores aromáticas de cerámica (con [[sol-gales]]) | [a completar] |
| Auto | aromatizador de auto (lanzado en feb 2025) | [a completar] |
| Accesorios | apagavelas | [a completar] |
| Regalo | **"Armá tu kit"** (con un packaging "que vas a AMAR"), cajas / box navideños, kits especiales para eventos (a pedido, por MD) | [a completar] |
| Experiencias | [[taller-de-velas-2025-11|taller de velas]] (cupos limitados), experiencia olfativa, creación de aromas a medida | [a completar] |
| B2B / marcas | aromas a medida para otras marcas (p. ej. "Higo Dulce" para [[lab-essence|Lab Essence]]) | [a completar] |

**Cómo se compra hoy:** mensaje privado en Instagram o en el atelier. Envíos: [a completar].


=== ARCHIVO: 00-CONTEXTO/voz-de-marca.md ===

---
type: voice
title: "Voz de marca: Cony's Home"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [voz, copy, redes]
related:
  - "[[voz-de-patricia]]"
  - "[[estrategia-digital]]"
  - "[[auditoria-instagram]]"
sources:
  - Instagram @conys.home (40 posts, export 2026-09)
  - Presentación de Alex para Cony's Home
---

# Voz de marca: Cony's Home

> Usá este archivo cada vez que escribas un posteo, una historia, una descripción de producto o una respuesta a un cliente.

## En tres palabras
**Cálida · sensorial · artesanal.** Con un toque de conocimiento científico explicado simple.

## Cómo suena hoy (análisis de 40 posteos)
- **Plural y cercana:** "nosotras", "les compartimos", "los esperamos", "nuestra casa".
- **Voseo rioplatense:** "podés", "armá tu kit", "escribinos", "¿te lo vas a perder?", "aromatizá tu casa".
- **Afectiva:** "que vas AMAR", "tan felices", "GRACIAS POR RECIBIRNOS CON TANTO CARIÑO", "una persona hermosa".
- **La casa como metáfora:** "nuestra casa", "nuestra nueva casita", "que llegue a sus casas", "vengan a nuestra casa y siéntanlos ustedes mismos".
- **Recuerdo y emoción:** los aromas "evocan", "traen recuerdos", "un momento pasado".
- **Transparencia de proceso:** "mostrar nuestros procesos es tan importante para que vean la transparencia que hay detrás".
- **Formato:** título del producto en MAYÚSCULAS, frases cortas, puntos suspensivos ("..."), emojis ✨❤️🙌🏼🕯️💫🤩. CTA al final ("Escribinos por privado", "Info al MD", "Te esperamos en Armenia 1455").
- **Hashtags de siempre:** #laboratoriodearomas #velaspalermo #conyshome #palermoaromas #aromasnaturales.

## Hacia dónde llevarla (estrategia de Alex)
- Mantener la calidez, y sumar **historia** (la abuela, el campo, el "ratoncito") y **conocimiento** ("¿por qué un aroma dura más que otro?").
- **Cada aroma con nombre lleva una descripción y una frase de cierre** (pedido de Patricia).
- Menos venta directa y más "descubrir → entender → desear".
- Cuidar la ortografía y la consistencia del nombre: siempre **Cony's Home**. En el feed aparecieron "Conny's", "Cony´s" y "conys".

## Sí / No
| Sí | No |
|---|---|
| Hablar de recuerdos, lugares, sensaciones | Frases genéricas de venta ("¡Compralo ya!") |
| Explicar el porqué (química, cerebro, materias primas) | Tecnicismos sin traducir |
| Invitar a oler en persona | Prometer lo que no se puede crear "en el momento" |
| Nombrar a la abuela y el origen | Copiar a otras marcas ("Busco trabajo y no copio") |

## Ejemplos reales que funcionan
- *"Crear estos aromas es un proceso de prueba y error constante... Cada combinación nace de experimentar, ajustar y volver a intentar."*
- *"Más que una vela: un ritual que ilumina tu espacio, calma tu mente y convierte cada momento en uno que vale la pena sentir ✨"* (835 reproducciones)
- *"Estas velas están realizadas con cera de abeja, por eso su color, puede que presente 'pelitos' o impurezas, es propio de su procedimiento!"*


=== ARCHIVO: 00-CONTEXTO/voz-de-patricia.md ===

---
type: voice
title: "Voz de Patricia"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [voz, patricia]
related:
  - "[[patricia]]"
  - "[[voz-de-marca]]"
  - "[[reunion-patricia-apuntes]]"
sources:
  - Apuntes reunión con Patricia (Alex)
  - Instagram @conys.home (40 posts, export 2026-09)
  - Notas de voz de Patricia (transcritas, sep 2026)
---

# Voz de Patricia

> Sale de las notas de la reunión, los posteos y **sus notas de voz transcritas** (sep 2026). Patricia es **argentina** y habla en español rioplatense.

## En cámara (confirmado)
**No se siente cómoda mostrando su cara todo el tiempo.** Puede aparecer de vez en cuando, en momentos especiales (historia, lanzamientos, eventos), pero no como algo fijo. Para el día a día:
- **Voz en off** de Patricia sobre imágenes del proceso (su voz es cálida y funciona muy bien)
- **Manos** trabajando: mezclas, pesaje, vertido de cera, etiquetado
- Planos de espalda o de perfil en el laboratorio, y detalles de materias primas
- La **abuela** y los recuerdos, a través de objetos (el talquito de rosas, fotos antiguas si ella quiere)

## Cómo piensa
- **Neurociencia del olfato:** le interesa explicar cómo el cerebro capta un aroma y por qué lo asocia a recuerdos (el olfato va directo al centro del cerebro).
- **Mezcla ciencia y emoción:** explica cómo el cerebro capta un aroma y, en la misma frase, a qué recuerdo te lleva.
- **Memoria olfativa:** "¿Cómo huelo y me transporto?" Puede no haber ido nunca a un lugar, pero lo lee y le encuentra su aroma (p. ej. **"Noches de palacio"**: Versalles, el Prado, la iglesia de San Jerónimo, el Louvre).
- **Aromas con nombre de recuerdo:** cada nombre lleva una descripción del aroma, y ahora también una frase de cierre.
- **No a todos el mismo aroma les provoca lo mismo:** la experiencia es personal.
- **Originalidad:** "Busco trabajo y no copio."
- **Sin apuro:** un aroma no se puede crear en el momento. Lleva tiempo.

## Su historia (para contar en primera persona)
- Tres generaciones: la **abuela** (el talquito de rosas), la **madre** (autodidacta, luchadora) y ella. "Mujeres empoderadas."
- Su madre le decía **"ratoncito"**, porque lo olía todo.
- "La casita" es porque viene de vivir en el campo.

## Cómo habla (de sus notas de voz)
- **Rioplatense y coloquial:** voseo ("lo que vos me presentaste", "vos consideres"), "tranqui", "dale", "buenísimo, buenísimo", "recontra sincera".
- **Muletillas:** "este...", "digamos", "bueno", "o sea", "es como que". Frases largas que se van hilando, con correcciones sobre la marcha.
- **Cálida y afectuosa:** "te mando un beso grande", "me enamoré de lo que me presentaste", "ya veo que vamos a hacer algo juntas".
- **Honesta y sin vueltas:** "te voy a ser recontra sincera".
- **Abierta a opiniones:** "acepto opiniones de lo que vos consideres que podríamos cambiar".
- **Sin presión:** "tranqui, es un trabajo así, tranquilo".
- **Valora el trabajo cuidado:** describe a la fotógrafa recomendada como "muy consciente, muy cuidado, súper prolijo, y muy a lo que ellas querían".

## Cómo escribe la marca cuando habla ella
- Cálida y agradecida ("GRACIAS", "tan significativo para nosotras").
- Usa "nosotras" aunque hable de sí misma.
- Cierres emotivos y puntos suspensivos.

## Para escribir como Patricia
- **Textos para redes o la web:** la versión cuidada de su voz. Cálida, con recuerdos y "vos", sin las muletillas.
- **Mensajes informales (WhatsApp, respuestas a clientes):** se pueden incluir sus giros ("dale", "tranqui", "un beso grande").
- **Evitar:** el español neutro o de España ("vosotros", "tú"), un tono corporativo o frío.

## Dudas abiertas
- ¿"Pato" (quien desarrolló "Higo Dulce" para Lab Essence) es Patricia? Muy probable: [a confirmar].


=== ARCHIVO: 01-MARCA/_MOC.md ===

---
type: moc
title: "01 Marca"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [moc]
related:
  - "[[_MOC]]"
sources:
  []
---

# 01 Marca

Todo sobre la marca, los aromas y los productos.

## Contenido
- [[historia-de-la-marca]]: la historia completa (documento largo)
- [[catalogo-de-aromas]]: aromas con nombre, recuerdo y frase de cierre
- [[atelier-la-edina]]: el espacio físico en Palermo
- [[experiencias]]: talleres, catas y la experiencia que se quiere diseñar
- [[tienda-online]]: plan de e-commerce


=== ARCHIVO: 01-MARCA/atelier-la-edina.md ===

---
type: brand
title: "Atelier en La Edina"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [atelier, palermo, la-edina]
related:
  - "[[la-edina]]"
  - "[[experiencias]]"
  - "[[historia-de-la-marca]]"
sources:
  - Instagram @conys.home (40 posts, export 2026-09)
---

# Atelier en La Edina

- **Dirección:** Armenia 1455, atelier 6, Palermo Soho, CABA.
- **Desde:** agosto 2025. La Edina se inauguró el 18/10/2025.
- **Qué pasa ahí:** la gente viene a oler aromas y a compartir anécdotas y recuerdos. A veces traen aromas propios para crear algo juntos. También hay talleres ([[taller-de-velas-2025-11]]) y experiencias con los vecinos del espacio ([[punto-vinos-experiencia-2025-09]]).
- **"La cocina de Cony's":** donde "creamos, hacemos, compartimos" (IG 2026-03-31).
- **Vecinos en La Edina:** Casa Tsuji, Emunā de autor (atelier de joyas), [[sol-gales|Sol Gales]], Abrapampa, Punto Vinos, Wine Experts. Ver [[la-edina]].
- **Horarios:** [a completar] · Pet friendly (según el reel de Punto Vinos).


=== ARCHIVO: 01-MARCA/catalogo-de-aromas.md ===

---
type: aroma
title: "Catálogo de aromas"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: likely
tags: [aromas, catalogo]
related:
  - "[[productos-y-precios]]"
  - "[[voz-de-patricia]]"
sources:
  - Instagram @conys.home (40 posts, export 2026-09)
  - Apuntes reunión con Patricia (Alex)
---

# Catálogo de aromas

**Regla de Patricia:** cada aroma lleva nombre (ligado a un recuerdo o un lugar), una descripción y **una frase de cierre**.

| Aroma | Recuerdo / inspiración | Descripción | Frase de cierre | Formatos | Fuente |
|---|---|---|---|---|---|
| **Susurro Oriental** | [a completar] | [a completar] | [a completar] | velas | IG 2026-05-11 |
| **Higo Dulce** (para Lab Essence) | Siestas de verano, la máquina de coser de la abuela, el dulce de higo | Dulce, suave y refinado | [a completar] | aroma textil para prendas | IG 2026-03-11 |
| **Noches de palacio** (concepto) | Versalles, el Prado, la iglesia de San Jerónimo, el Louvre | [a completar] | [a completar] | [a completar] | Apuntes |
| Talquito de rosas (la abuela) | La abuela | [a completar] | [a completar] | ¿aroma de marca? [a confirmar] | Apuntes |
| Pomelo / melón | [a completar] | [a completar] | [a completar] | (consulta de un cliente) | IG 2025-02-20 |

> Pedirle a Patricia la lista completa. Cada aroma después puede tener su propia nota en `01-MARCA/aromas/`.


=== ARCHIVO: 01-MARCA/experiencias.md ===

---
type: brand
title: "Experiencias"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [experiencias, eventos, taller]
related:
  - "[[atelier-la-edina]]"
  - "[[taller-de-velas-2025-11]]"
  - "[[punto-vinos-experiencia-2025-09]]"
sources:
  - Apuntes reunión con Patricia (Alex)
  - Presentación de Alex para Cony's Home
  - Instagram @conys.home (40 posts, export 2026-09)
---

# Experiencias

**Pregunta abierta (presentación):** ¿qué experiencia representa de verdad la filosofía de Cony's Home? ¿Talleres, creación de fragancias, encuentros, experiencias personalizadas?

## Lo que Patricia quiere (apuntes de la reunión)
- **Eventos esporádicos**, para que la gente conozca la marca en persona.
- **Nada de "vino y queso":** algo para tomar y charlar.
- Cada persona viene de un lugar distinto, y eso es parte de la experiencia.
- **Actividades con aromas:** ¿a dónde te lleva este aroma? ¿Cómo capta el cerebro un aroma?
- **No se puede hacer rápido:** no se puede crear un aroma en el momento.
- **Pequeños regalos** para quienes vienen.

## Estado (sep 2026)
Patricia está reescribiendo el **guion (libreto) de su experiencia** y se lo va a mandar a Alex para revisar la comunicación. Ver [[notas-de-voz-2026-09]].

## Lo que ya se hizo
- [[punto-vinos-experiencia-2025-09|Experiencia con Punto Vinos + Wine Experts]]: crear tu propio perfume inspirado en el vino.
- [[taller-de-velas-2025-11|Primer taller de velas]] (nov 2025).

## Propuesta en borrador (para validar)
**"Cata de recuerdos":** un grupo chico. Se huelen 5 aromas a ciegas, cada persona anota a dónde la lleva y después se comparte. Patricia explica la ciencia detrás. Se cierra con un regalo pequeño. [a validar con Patricia]


=== ARCHIVO: 01-MARCA/historia-de-la-marca.md ===

---
type: brand
title: "Historia de Cony's Home"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [historia, long-form]
related:
  - "[[patricia]]"
  - "[[atelier-la-edina]]"
  - "[[voz-de-patricia]]"
  - "[[experiencias]]"
sources:
  - Apuntes reunión con Patricia (Alex)
  - Instagram @conys.home (40 posts, export 2026-09)
  - Presentación de Alex para Cony's Home
---

# Historia de Cony's Home

*Historia armada con los apuntes de la reunión con Patricia, 40 posteos de @conys.home (feb 2025 a jun 2026) y la presentación de estrategia. Nada es inventado; los huecos están marcados.*

## 1. Un ratoncito en el campo
Patricia creció oliéndolo todo. Tanto, que su madre le decía **"ratoncito"**. Viene del campo, y de ahí sale la idea de **"la casita"**: una marca que se siente como un hogar. Detrás hay tres generaciones de mujeres. Su **abuela**, a la que asocia con el **talquito de rosas**. Su **madre**, autodidacta y luchadora. Y ella. Patricia quiere que su abuela esté presente en la marca.

## 2. Ciencia y memoria
Cony's Home nace de la **biología, la química y el conocimiento de los aromas**. Patricia explica por qué un olor nos lleva a un recuerdo: llega muy rápido, de la nariz directo al centro del cerebro. Y sabe que a cada persona el mismo aroma le provoca algo distinto. Sus aromas llevan **nombres de recuerdos o de lugares**, aunque sean lugares donde nunca estuvo: los lee y les encuentra su aroma, como en *"Noches de palacio"* (Versalles, el Prado, San Jerónimo, el Louvre). Su regla: **"Busco trabajo y no copio."**

## 3. Antes del atelier (2025)
En 2025 la marca ya vendía por Instagram. Ese año lanzó el **aromatizador de auto** (febrero), sumó nuevos ingresos y armó propuestas de regalo ("Regalá Cony's Home"). Los pedidos se hacían por mensaje privado.

## 4. La nueva casita: La Edina (ago–oct 2025)
En **agosto de 2025** Cony's Home "aterrizó" con su atelier en **La Edina** (Armenia 1455, atelier 6, Palermo Soho), un espacio colectivo de marcas de autor: "Bienvenidos a nuestra nueva casita ✨". El espacio se inauguró el **18 de octubre de 2025**, junto a Casa Tsuji, Emunā de autor, Sol Gales y Abrapampa. Fueron los reels con más alcance de la historia de la cuenta: 9.400 y 3.500 reproducciones. Ver [[atelier-la-edina]].

## 5. Experiencias y colaboraciones
- **Sep 2025:** una experiencia sensorial con [[punto-vinos|Punto Vinos]] y Wine Experts: degustación de vinos más una experiencia olfativa para **crear tu propio perfume inspirado en el vino**. Llegó a 5.900 reproducciones.
- **Nov 2025:** el primer **taller de velas**, con cupos limitados.
- **Dic 2025:** flores aromáticas de cerámica con [[sol-gales|Sol Gales]], y cajas navideñas.
- **Mar 2026:** el aroma **"Higo Dulce"** para las prendas de [[lab-essence|Lab Essence]], desarrollado por "Pato" (muy probablemente Patricia). Nace del recuerdo de la dueña de Lab Essence: las siestas de verano con la máquina de coser de su abuela y el olor a dulce de higo.

## 6. Cierre de 2025, en palabras de la marca
> "Le dimos comienzo a una nueva etapa, ya que nos mudamos a nuestro Atelier actual, un lugar donde ustedes vienen a sentir aromas y a compartir anécdotas donde se habla de recuerdos... también sucede que vienen con aromas específicos para que trabajemos juntos... y eso es tan significativo para nosotras."

## 7. 2026: de publicar a construir una identidad
Este año la marca abrió una sección de posteos dedicados a cada aroma (marzo) y lanzó "Susurro Oriental" (mayo), "Armá tu kit" y los kits para eventos. Alex propone el paso siguiente: pasar de publicar a construir una **identidad reconocible**, contar la historia, el conocimiento y el proceso, y llevar a la gente a una **tienda online** y a **experiencias** en el atelier. Ver [[estrategia-digital]].

## Preguntas abiertas para Patricia
- ¿De dónde viene el nombre "Cony"? ¿En qué año empezó la marca?
- ¿Cuál es su formación exacta (biología, química, otra)?


=== ARCHIVO: 01-MARCA/tienda-online.md ===

---
type: strategy
title: "Tienda online"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [ecommerce, web]
related:
  - "[[estrategia-digital]]"
  - "[[productos-y-precios]]"
sources:
  - Presentación de Alex para Cony's Home
---

# Tienda online (plan)

Una tienda **sencilla y visual** donde se pueda:
- conocer los productos y sus aromas;
- comprar online;
- elegir envío o retiro en el atelier;
- descubrir la historia de la marca;
- entrar fácil desde Instagram.

**Embudo:** Instagram / contenido → descubrir la marca → tienda online → comprar productos / reservar experiencias.

**Por definir:** plataforma (Tiendanube, Shopify, otra) [a completar] · medios de pago · zona de envíos · fotos de producto · precios.


=== ARCHIVO: 02-PERSONAS/_MOC.md ===

---
type: moc
title: "02 Personas y aliados"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [moc]
related:
  - "[[_MOC]]"
sources:
  []
---

# 02 Personas y aliados

Una nota por persona o marca aliada.

## Contenido
- [[patricia]]: creadora y dueña de Cony's Home
- [[alex-viciano]]: estrategia digital, redes y web
- [[la-edina]]: el espacio colectivo donde está el atelier
- [[sol-gales]]: ceramista, flores aromáticas
- [[punto-vinos]]: vinos, experiencia conjunta (con Wine Experts)
- [[lab-essence]]: marca de ropa, aroma Higo Dulce
- [[fotografa-recomendada]]: fotógrafa recomendada por las chicas de las joyas (pendiente)
- [[_plantilla]]: plantilla para una persona nueva


=== ARCHIVO: 02-PERSONAS/_plantilla.md ===

---
type: template
title: "Plantilla de persona"
created: 2026-09-25
updated: 2026-09-25
status: draft
audience: patricia, alex
confidence: confirmed
tags: [plantilla]
related:
  []
sources:
  []
---

# Nombre Apellido

**En una línea:** quién es para Cony's Home.

| Campo | Dato |
|---|---|
| Relación | cliente / socio / proveedor / colaborador |
| Instagram / contacto | |
| Cómo nos conocimos | |

## Interacciones (la más reciente primero)
- AAAA-MM-DD: resumen

## Pendientes
-


=== ARCHIVO: 02-PERSONAS/alex-viciano.md ===

---
type: person
title: "Alex Viciano"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
relacion: equipo-digital
instagram: ""
tags: [persona, colaborador]
related:
  - "[[identidad]]"
sources:
  - Instagram @conys.home (40 posts, export 2026-09)
  - Apuntes reunión con Patricia (Alex)
---

# Alex Viciano

Lleva la estrategia digital, las redes sociales, la web / e-commerce y la creación de contenido de Cony's Home. Autor de [[estrategia-digital]].

## Interacciones
- [a completar]

## Pendientes / promesas
- [a completar]


=== ARCHIVO: 02-PERSONAS/fotografa-recomendada.md ===

---
type: person
title: "Fotógrafa recomendada"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: likely
relacion: proveedor
instagram: "[a completar]"
tags: [persona, proveedor, fotografia]
related:
  - "[[notas-de-voz-2026-09]]"
  - "[[identidad-visual]]"
  - "[[la-edina]]"
sources:
  - Notas de voz de Patricia (transcritas, sep 2026)
---

# Fotógrafa recomendada (nombre [a completar])

- Se la recomendaron a Patricia "las chicas de las joyas", muy probablemente **Emunā de autor**, atelier de joyas en La Edina.
- Según ellas, su trabajo fue "muy consciente, muy cuidado, súper prolijo, y muy a lo que ellas querían".
- **Estado (sep 2026):** Patricia tiene su teléfono y está esperando respuesta.
- Contacto / presupuesto / fecha de la sesión: [a completar]


=== ARCHIVO: 02-PERSONAS/la-edina.md ===

---
type: partner
title: "La Edina"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
relacion: socio
instagram: "@laedina_palermo"
tags: [persona, socio]
related:
  - "[[identidad]]"
sources:
  - Instagram @conys.home (40 posts, export 2026-09)
  - Apuntes reunión con Patricia (Alex)
---

# La Edina

Espacio colectivo de marcas de autor en Armenia 1455, Palermo Soho. Se inauguró el 18/10/2025 "después de años de trabajo". Recibió a Cony's Home en agosto de 2025. Otros miembros: Casa Tsuji, Emunā de autor, Sol Gales, Abrapampa.

## Interacciones
- [a completar]

## Pendientes / promesas
- [a completar]


=== ARCHIVO: 02-PERSONAS/lab-essence.md ===

---
type: partner
title: "Lab Essence"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: likely
relacion: cliente
instagram: "[a completar]"
tags: [persona, cliente]
related:
  - "[[identidad]]"
sources:
  - Instagram @conys.home (40 posts, export 2026-09)
  - Apuntes reunión con Patricia (Alex)
---

# Lab Essence

Marca de prendas de diseño de autor. Su aroma de marca, **Higo Dulce**, lo desarrolló "Pato" en Cony's Home (mar 2026). Es un ejemplo de aroma a medida para otras marcas (B2B).

## Interacciones
- [a completar]

## Pendientes / promesas
- [a completar]


=== ARCHIVO: 02-PERSONAS/patricia.md ===

---
type: person
title: "Patricia"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
relacion: dueña
instagram: ""
tags: [persona, dueña]
related:
  - "[[identidad]]"
sources:
  - Instagram @conys.home (40 posts, export 2026-09)
  - Apuntes reunión con Patricia (Alex)
---

# Patricia

Creadora y dueña de Cony's Home ("Patri"). Formación científica: biología / química, a confirmar. Ver [[identidad]], [[voz-de-patricia]], [[historia-de-la-marca]]. Probablemente es la "Pato" que desarrolló Higo Dulce para Lab Essence.

## Interacciones
- [a completar]

## Pendientes / promesas
- [a completar]


=== ARCHIVO: 02-PERSONAS/punto-vinos.md ===

---
type: partner
title: "Punto Vinos + Wine Experts"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
relacion: socio
instagram: "@somospuntovinos · @winexpertsarg"
tags: [persona, socio]
related:
  - "[[identidad]]"
sources:
  - Instagram @conys.home (40 posts, export 2026-09)
  - Apuntes reunión con Patricia (Alex)
---

# Punto Vinos + Wine Experts

Vecinos en Armenia 1455. Hicieron con Cony's Home una experiencia de vino, gastronomía y aromas en la que se crea un perfume inspirado en el vino (sep 2025, reel de 5.900 reproducciones). Wine Experts da cursos de sommelier.

## Interacciones
- [a completar]

## Pendientes / promesas
- [a completar]


=== ARCHIVO: 02-PERSONAS/sol-gales.md ===

---
type: person
title: "Sol Gales"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
relacion: colaborador
instagram: "@sol_gales"
tags: [persona, colaborador]
related:
  - "[[identidad]]"
sources:
  - Instagram @conys.home (40 posts, export 2026-09)
  - Apuntes reunión con Patricia (Alex)
---

# Sol Gales

Ceramista de La Edina. Con Cony's Home hizo las flores aromáticas de cerámica (dic 2025): "Es increíble el aroma y la duración que logramos".

## Interacciones
- [a completar]

## Pendientes / promesas
- [a completar]


=== ARCHIVO: 03-MARKETING/_MOC.md ===

---
type: moc
title: "03 Marketing"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [moc]
related:
  - "[[_MOC]]"
sources:
  []
---

# 03 Marketing

Estrategia digital, auditoría y contenido.

## Contenido
- [[estrategia-digital]]: la propuesta de Alex: pilares, embudo, qué aporta
- [[auditoria-instagram]]: qué funciona y qué no en @conys.home (40 posteos)
- [[identidad-visual]]: colores y hojas aprobados; sesión de fotos
- [[competencia]]: Pol French Gallery y otros (sin copiar)
- [[banco-de-ideas]]: ideas de reels y posteos listas para producir


=== ARCHIVO: 03-MARKETING/auditoria-instagram.md ===

---
type: strategy
title: "Auditoría de Instagram (@conys.home)"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [instagram, metricas, auditoria]
related:
  - "[[estrategia-digital]]"
  - "[[voz-de-marca]]"
  - "[[banco-de-ideas]]"
sources:
  - Instagram @conys.home (40 posts, export 2026-09)
---

# Auditoría de Instagram: @conys.home

**Muestra:** 40 posteos, de feb 2025 a jun 2026 (15 reels, 25 fotos o carruseles).

## Top por alcance
| Fecha | Posteo | Resultado | Por qué funcionó |
|---|---|---|---|
| 2025-10-21 | Inauguración de La Edina (colab) | **9.419 reproducciones**, 28 comentarios | Colaboración: el alcance de varias cuentas juntas |
| 2025-09-08 | Experiencia Punto Vinos + Wine Experts | **5.902 reproducciones**, 171 likes, 28 comentarios | Experiencia + gancho ("¿Sabías que en Palermo…?") + CTA de guardar y compartir |
| 2025-10-23 | Inauguración de La Edina desde Emunā | 3.511 reproducciones, 76 likes | Colaboración |
| 2025-08-10 | Bienvenida de La Edina | 76 likes, 18 comentarios | Comunidad; felicitaciones a Patri |
| 2025-09-05 | El espacio del atelier | 1.126 reproducciones | Mostrar el lugar |
| 2025-11-26 | "Más que una vela: un ritual…" | 835 reproducciones | Copy emocional |

## Promedio de los posteos propios
Entre 6 y 38 likes, y entre 260 y 835 reproducciones por reel. **El contenido en colaboración multiplica el alcance 5 a 10 veces.**

## Hallazgos
1. **Hay preguntas de precio sin resolver en público:** "Qué precio tienen las distintas velas?", "Precio x favor", "Dónde puedo [comprar]" (alguien de 25 de Mayo, provincia de Bs As). **Hay demanda de una tienda online y de envíos al interior.**
2. **Lo que mejor funciona:** experiencias, el espacio y las colaboraciones. **Lo que menos:** un producto solo con un copy corto (6 a 15 likes).
3. **La historia de Patricia casi no aparece.** Solo "Así es como nace Cony's…" (ene 2026, 334 reproducciones).
4. **El nombre no es consistente:** Cony's, Cony´s, Conny's, conys.
5. **Música:** se repiten tracks genéricos. Probar con audio original (voz de Patricia).
6. **Hashtags:** hay errores, como #laboratoriodesromas.

## Recomendaciones inmediatas
- Grabar 1 reel por semana con la voz de Patricia, sobre proceso o conocimiento.
- Hacer 1 colaboración por mes con los vecinos de La Edina.
- Poner un link en la bio a una lista de precios o a un catálogo, hasta que exista la tienda.
- Dedicar un posteo a cada aroma, con recuerdo y frase de cierre.


=== ARCHIVO: 03-MARKETING/banco-de-ideas.md ===

---
type: idea
title: "Banco de ideas de contenido"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [ideas, reels, contenido]
related:
  - "[[estrategia-digital]]"
  - "[[auditoria-instagram]]"
  - "[[catalogo-de-aromas]]"
sources:
  - Presentación de Alex para Cony's Home
  - Apuntes reunión con Patricia (Alex)
  - Instagram @conys.home (40 posts, export 2026-09)
---

# Banco de ideas de contenido

| # | Idea | Pilar | Fuente |
|---|---|---|---|
| 1 | "Así creamos una fragancia desde cero" | Proceso | Presentación |
| 2 | "3 cosas que probablemente no sabías sobre las velas naturales" | Conocimiento | Presentación |
| 3 | "Entrá conmigo al laboratorio de aromas de Cony's Home" | Historia / Atelier | Presentación |
| 4 | "¿Por qué un olor te lleva a un recuerdo?" (de la nariz al centro del cerebro) | Conocimiento | Apuntes |
| 5 | "El talquito de rosas de mi abuela": 3 generaciones de mujeres | Historia | Apuntes |
| 6 | "Mi mamá me decía ratoncito" | Historia | Apuntes |
| 7 | "Noches de palacio": cómo creo el aroma de un lugar donde nunca estuve | Historia / Conocimiento | Apuntes |
| 8 | "¿Qué es la cera de coco?" (ya funcionó como carrusel; pasarlo a reel) | Conocimiento | IG 2026-02-04 |
| 9 | "Por qué nuestras velas de cera de abeja tienen 'pelitos'" | Conocimiento | IG 2026-02-13 |
| 10 | "¿Cómo influye la temperatura en cómo percibimos un aroma?" | Conocimiento | Presentación |
| 11 | Serie "Un aroma, un recuerdo": cada aroma con su frase de cierre | Producto | Apuntes |
| 12 | "Armá tu kit" en video, con el packaging de regalo | Producto | IG 2026-04-28 |
| 13 | Colaboración mensual con un vecino de La Edina | Atelier | Auditoría |
| 14 | "Neurociencia del olfato en 30 segundos" (voz en off de Patricia + manos en el laboratorio) | Conocimiento | Apuntes |
| 15 | Serie "Manos de laboratorio": el proceso sin mostrar la cara, con la voz de Patricia | Proceso | Aclaración |


=== ARCHIVO: 03-MARKETING/competencia.md ===

---
type: reference
title: "Competencia"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: likely
tags: [competencia, mercado, palermo]
related:
  - "[[estrategia-digital]]"
  - "[[identidad]]"
  - "[[reunion-patricia-apuntes]]"
sources:
  - Apuntes reunión con Patricia (Alex)
  - Aclaración de Alex (2026-09-25)
---

# Competencia

**Postura de Patricia:** "Busco trabajo y no copio." Mirar a la competencia es para diferenciarse, no para imitar.

| Marca | Dónde | Qué es | Diferencia de Cony's Home | Fuente |
|---|---|---|---|---|
| **Pol French Gallery** (nombre exacto a verificar) | Local en Palermo Soho, CABA | Competidor de aromas / velas [a completar] | [a completar tras visitarlo: precios, productos, experiencia, redes] | Apuntes de la reunión |

## Diferenciales de Cony's Home (para comparar)
- Base científica (química, biología, neurociencia del olfato)
- Aromas con nombre de recuerdo, descripción y frase de cierre
- 100 % natural y artesanal (ceras de soja, abeja y coco)
- Atelier-casa en La Edina: oler, charlar, crear aromas a medida
- La historia de tres generaciones de mujeres

## Pendiente
- [ ] Relevar Pol French Gallery: Instagram, web, rango de precios, productos, tipo de experiencia en el local
- [ ] Sumar otros 2 o 3 competidores de Palermo / CABA


=== ARCHIVO: 03-MARKETING/estrategia-digital.md ===

---
type: strategy
title: "Estrategia digital (propuesta de Alex)"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [estrategia, redes, contenido]
related:
  - "[[auditoria-instagram]]"
  - "[[banco-de-ideas]]"
  - "[[tienda-online]]"
  - "[[voz-de-marca]]"
sources:
  - Presentación de Alex para Cony's Home
---

# Estrategia digital: propuesta de Alex

> "No vender solamente una vela o una fragancia, sino contar todo lo que existe detrás de ese aroma."

## Qué llevar al mundo digital
- **Historia:** quién crea los aromas, cómo y por qué.
- **Conocimiento:** una marca creada desde la biología, la química y el saber de los aromas.
- **Proceso artesanal:** ingredientes 100 % naturales, hecho a mano.
- **Atelier:** el espacio en Palermo donde conocer, oler y experimentar.

## Lógica
**Dejar de publicar por publicar → construir una identidad reconocible → generar contenido → que la gente descubra el producto → lo entienda → lo desee.**

## Pilares de contenido
| Pilar | Qué mostrar | Ejemplos |
|---|---|---|
| Proceso | Cómo nace un aroma: laboratorio, materias primas, pruebas, mezclas, velas | "Así creamos una fragancia desde cero" |
| Conocimiento | Ciencia simple y atractiva | "¿Qué hace que un aroma dure más que otro?", "¿Cómo influye la temperatura en cómo percibimos un aroma?" |
| Producto | Mejor fotografía y videos cortos: texturas, packaging, encendido, usos | "3 cosas que probablemente no sabías sobre las velas naturales" |
| Historia | La creadora y el origen de Cony's Home; que la marca tenga una persona y una voz | "Entrá conmigo al laboratorio de aromas de Cony's Home" |
| Atelier / Experiencias | Qué pasa en Armenia 1455; que Instagram lleve gente al local | Talleres, catas |

## Regla de formato
Patricia **no quiere mostrar su cara todo el tiempo**. El contenido de historia y proceso se hace con su **voz en off, sus manos y el laboratorio**, y ella aparece en cámara solo en momentos puntuales.

## Qué aporta Alex
Estrategia digital · redes sociales · creación de contenido · identidad y comunicación · e-commerce · campañas digitales · análisis y crecimiento. El enfoque es una estrategia **sencilla, realista y acorde al tamaño de la marca**.


=== ARCHIVO: 03-MARKETING/identidad-visual.md ===

---
type: decision
title: "Identidad visual"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [identidad-visual, diseño, fotografia]
related:
  - "[[estrategia-digital]]"
  - "[[notas-de-voz-2026-09]]"
  - "[[fotografa-recomendada]]"
sources:
  - Notas de voz de Patricia (transcritas, sep 2026)
  - Presentación de Alex para Cony's Home
  - Canva: presentación de Alex (colores confirmados 2026-09-25)
---

# Identidad visual

## Paleta de colores (de la presentación en Canva, confirmada por Alex el 2026-09-25)

| Color | HEX | Nombre | Uso |
|---|---|---|---|
| 🟫 | `#544541` | Marrón principal | Texto de cuerpo y formas. **El más usado** |
| ⬜ | `#F4F4F4` | Blanco roto | Paneles superpuestos, texto claro sobre fondos oscuros |
| 🟫 | `#745E59` | Marrón claro | Formas y algunos textos |
| 🟫 | `#51413E` | Marrón oscuro | Texto |
| 🟫 | `#49301E` | Marrón profundo | Texto y títulos con más peso |
| 🟨 | `#C3AE93` | Beige / tostado | Fondos de las slides |

**Paleta:** `#544541` `#F4F4F4` `#745E59` `#51413E` `#49301E` `#C3AE93`

**Carácter:** tierra, cálida y natural, con marrones y beige. Conecta con lo artesanal, la cera, la madera y el campo.

### Contraste (legibilidad, WCAG)
| Combinación | Contraste | Uso |
|---|---|---|
| #544541 sobre #F4F4F4 | 8.3:1 | ✅ texto normal |
| #49301E sobre #F4F4F4 | 11.1:1 | ✅ texto normal |
| #544541 sobre #C3AE93 | 4.3:1 | ⚠️ solo títulos grandes |
| #49301E sobre #C3AE93 | 5.7:1 | ✅ texto normal |
| #745E59 sobre #F4F4F4 | 5.5:1 | ✅ texto normal |
| #745E59 sobre #C3AE93 | 2.8:1 | ❌ no usar para texto |
| #F4F4F4 sobre #544541 | 8.3:1 | ✅ texto normal |
| #F4F4F4 sobre #745E59 | 5.5:1 | ✅ texto normal |

**Regla práctica:** sobre `#F4F4F4` se pueden usar todos los marrones. Sobre el beige `#C3AE93`, el texto normal va solo en `#49301E`, `#544541` solo sirve para títulos grandes y `#745E59` no se usa para texto. `#51413E` y `#544541` son casi iguales, así que alcanza con elegir uno para el cuerpo del texto.

### Recursos visuales (revisados en Canva, solo lectura, 2026-09-25)
- **"Las hojas":** no son un color plano. Son **fotos recortadas de flores y hojas secas** (tallos, pétalos marchitos, hojas curvadas) en tonos marrón, malva y sepia. Se usan en las esquinas de las slides, sobre el fondo beige. Aparecen en las slides 3 y 8.
- **Fotografía:** frascos de vidrio ámbar; sombras de una mano sosteniendo el frasco sobre lino; flat lays de materias primas (cítricos, especias, algodón, madera); texturas de seda, piedra y corteza. Luz cálida y natural.
- **Tipografías (3 estilos; los nombres exactos están por confirmar en Canva):**
  1. **Script manuscrita** para el logo "Cony's Home" (portada)
  2. **Sans serif geométrica en mayúsculas con mucho espaciado** para títulos y texto (parecida a Montserrat)
  3. **Serif tipo máquina de escribir** para frases destacadas ("NO VENDER SOLAMENTE UNA VELA…")
- **Ícono:** una casita con ramas (esquina de la portada).

### Pendiente
- Confirmar los nombres de las 3 tipografías (en Canva: hacer clic en el texto y leer el nombre en la barra de arriba)
- Ojo: la slide 2 dice "CONTRUYEDO"; debería decir "CONSTRUYENDO".

## Aprobado por Patricia (sep 2026)
Patricia se "enamoró" de la estética de la presentación de Alex:
- **La paleta de colores** de la presentación (ver arriba)
- **Las hojas en el fondo** (un recurso botánico, que conecta con lo natural y con el campo)

**Decisión:** usar la estética de la presentación como base de la identidad visual en redes, la web y el material del atelier.

## Pendiente
- [x] Documentar la paleta (HEX)
- [ ] Documentar las tipografías y el recurso de las hojas → este archivo
- [ ] Sesión de fotos con [[fotografa-recomendada]]
- [ ] Unificar el nombre en todas las piezas: **Cony's Home**


=== ARCHIVO: 04-EVENTOS/_MOC.md ===

---
type: moc
title: "04 Eventos"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [moc]
related:
  - "[[_MOC]]"
sources:
  []
---

# 04 Eventos

Eventos con fecha.

## Contenido
- [[punto-vinos-experiencia-2025-09]]: sep 2025: vino + aromas
- [[la-edina-inauguracion-2025-10-18]]: 18/10/2025: inauguración de La Edina
- [[taller-de-velas-2025-11]]: nov 2025: primer taller de velas


=== ARCHIVO: 04-EVENTOS/la-edina-inauguracion-2025-10-18.md ===

---
type: event
title: "Inauguración de La Edina (18/10/2025)"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
date: 2025-10-18
lugar: "Armenia 1455, Palermo Soho"
tags: [evento, la-edina]
related:
  - "[[la-edina]]"
  - "[[atelier-la-edina]]"
sources:
  - Instagram @conys.home (40 posts, export 2026-09)
---

# Inauguración de La Edina: 18/10/2025

"Después de años de trabajo en donde hubieron mil idas y vueltas, por fin se inauguró La Edina ✨". Marcas presentes: Casa Tsuji, Cony's Home, Emunā de autor, Sol Gales, Abrapampa. Los reels de la inauguración sumaron más de 12.900 reproducciones.


=== ARCHIVO: 04-EVENTOS/punto-vinos-experiencia-2025-09.md ===

---
type: event
title: "Experiencia vino + aromas (sep 2025)"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
date: 2025-09-08
lugar: "Armenia 1455, Palermo"
tags: [evento, colaboracion]
related:
  - "[[punto-vinos]]"
  - "[[experiencias]]"
sources:
  - Instagram @conys.home (40 posts, export 2026-09)
---

# Experiencia vino + aromas: Punto Vinos + Cony's Home + Wine Experts

Degustación de blancos, rosados y tintos maridados con platos, más coctelería. La parte de Cony's Home era una **experiencia olfativa para descubrir aromas y crear tu propio perfume inspirado en el vino**. Pet friendly. El reel llegó a 5.902 reproducciones y 171 likes. **Es el mejor contenido propio de la cuenta.**


=== ARCHIVO: 04-EVENTOS/taller-de-velas-2025-11.md ===

---
type: event
title: "Primer taller de velas (nov 2025)"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
date: 2025-11-05
lugar: "La Edina, Armenia 1455"
precio: "[a completar]"
cupos: "limitados"
tags: [evento, taller]
related:
  - "[[experiencias]]"
  - "[[atelier-la-edina]]"
sources:
  - Instagram @conys.home (40 posts, export 2026-09)
---

# Primer taller de velas: noviembre 2025

"Nos alegramos de compartir con ustedes nuestro primer taller de velas 🕯️". Cupos limitados, información por MD. El posteo tuvo 22 likes y 6 comentarios. Precio, asistentes y aprendizajes: [a completar].


=== ARCHIVO: 07-REUNIONES/_MOC.md ===

---
type: moc
title: "07 Reuniones"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [moc]
related:
  - "[[_MOC]]"
sources:
  []
---

# 07 Reuniones

Reuniones y notas de voz procesadas.

## Contenido
- [[reunion-patricia-apuntes]]: reunión con Patricia: aromas, historia, experiencias
- [[notas-de-voz-2026-09]]: notas de voz de Patricia (fotógrafa, guion de la experiencia, identidad visual)


=== ARCHIVO: 07-REUNIONES/notas-de-voz-2026-09.md ===

---
type: meeting
title: "Notas de voz de Patricia (sep 2026)"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
date: 2026-09-24
participantes: ["[[patricia]]", "[[alex-viciano]]"]
tags: [audio, patricia, pendientes]
related:
  - "[[voz-de-patricia]]"
  - "[[experiencias]]"
  - "[[fotografa-recomendada]]"
  - "[[identidad-visual]]"
sources:
  - Notas de voz de Patricia (transcritas, sep 2026)
---

# Notas de voz de Patricia (WhatsApp, 18 y 24 de sep 2026)

## Lo importante
1. **Fotógrafa:** Patricia consiguió el teléfono de una fotógrafa que le recomendaron "las chicas de las joyas" (muy probablemente Emunā de autor, en La Edina). Dicen que el trabajo que hizo con ellas fue "muy consciente, muy cuidado, súper prolijo, y muy a lo que ellas querían". Todavía no le contestó. **Cuando hablen, le avisa a Alex.** Ver [[fotografa-recomendada]].
2. **Guion de la experiencia:** Patricia le está dando "una vuelta más" al libreto de su experiencia. Lo va a escribir "sobre blanco" y se lo manda a Alex, y acepta opiniones para la comunicación. Ver [[experiencias]].
3. **Le encantó la propuesta de Alex:** "Me enamoré de lo que vos me presentaste", en especial **los colores** y **las hojas en el fondo**. Ver [[identidad-visual]].
4. **La relación:** entusiasmo por trabajar juntas ("ya veo que vamos a hacer algo juntas"). Tono relajado: "tranqui, es un trabajo así, tranquilo".
5. Logística: "Estoy acá en la esquina, te espero afuera" (un encuentro en persona).

## Pendientes
- [ ] **Patricia:** mandar el guion de la experiencia (escrito sobre blanco).
- [ ] **Patricia:** avisar cuando conteste la fotógrafa.
- [ ] **Alex:** revisar el guion y proponer ajustes de comunicación.
- [ ] **Alex:** preparar un brief para la sesión de fotos (producto, proceso, atelier, retrato si Patricia quiere).

## Transcripción (limpia)
> Hola Álex, mirá, ya estuve a punto también de hablarte porque, bueno, conseguí el teléfono de la fotógrafa, todavía no me contestó. Me recomendaron, me dijeron las chicas de las joyas que el trabajo que había hecho con ellas era bueno: muy consciente, muy cuidado, súper prolijo y muy a lo que ellas querían. Pero estoy esperando que me conteste, así que en cuanto me conteste y hablemos te aviso. Y yo quise darle una vuelta más, digamos, al libreto que tenía de mi experiencia, la que había hecho, y me quedé en el aire, porque la verdad, te voy a ser recontra sincera, me enamoré de lo que vos me presentaste: en cuanto a los colores, en cuanto a ese primer… y más a esas hojas en el fondo. Entonces yo lo hago sobre blanco… lo voy a hacer así en blanco, te lo mando y después vamos viendo, porque también acepto opiniones de lo que vos consideres que podríamos cambiar para la comunicación. Pero tranqui, es un trabajo así, tranquilo. Algo vamos a hacer. Te mando un beso grande.

> Buenísimo, buenísimo. Sí, sí… aparte me encanta eso que decimos, cuando trabajemos juntas, y yo ya es como que veo que vamos a hacer algo juntas. Pero bueno, dale, sí, sí, nos mantenemos en contacto. Cuando la fotógrafa me conteste te mando… *(se corta)*


=== ARCHIVO: 07-REUNIONES/reunion-patricia-apuntes.md ===

---
type: meeting
title: "Reunión con Patricia: apuntes"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
date: "[a completar]"
participantes: ["[[patricia]]", "[[alex-viciano]]"]
tags: [reunion, patricia]
related:
  - "[[patricia]]"
  - "[[voz-de-patricia]]"
  - "[[experiencias]]"
  - "[[catalogo-de-aromas]]"
sources:
  - Apuntes reunión con Patricia (Alex)
---

# Reunión con Patricia: apuntes de Alex

## Lo más importante
- **Cata / experiencia olfativa:** los recuerdos que traen los olores. Le gusta mezclar aromas.
- **Nombres de aromas ligados a recuerdos**, con una descripción del aroma. Puede no haber ido a un lugar, pero lo lee y le encuentra su aroma ("Noches de palacio").
- **No a todos el mismo aroma les provoca lo mismo.**
- **Historia:** tres generaciones (la abuela del talquito de rosas, la madre autodidacta y ella). Luchadoras, empoderadas. La madre la llamaba "ratoncito". "La casita" es porque viene del campo.
- **Quiere que su abuela esté presente** en la marca.
- "Busco trabajo y no copio."
- **Eventos esporádicos** para que conozcan la marca en persona. Ver [[experiencias]].
- Productos mencionados: body splash.
- **Nuevo:** cada aroma con nombre y descripción lleva una **frase de cierre**. Hay que armar una **línea de packs para regalo**.

## Aclaraciones (confirmadas por Alex)
- "No quiere he de Mar su imagen": **no se siente cómoda mostrando su cara todo el tiempo.** Aparece de forma ocasional. Ver [[voz-de-patricia]].
- "Nuriciencua": **neurociencia**, es decir, cómo el cerebro capta y recuerda un aroma. Es un eje del contenido de conocimiento.
- "Pol French gallery": **competidor** con local en Palermo Soho, CABA. Ver [[competencia]]. Se relaciona con "Busco trabajo y no copio".


=== ARCHIVO: 08-INBOX/_MOC.md ===

---
type: moc
title: "08 Inbox"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [moc]
related:
  - "[[_MOC]]"
sources:
  []
---

# 08 Inbox

Material que todavía no se procesó.

## Contenido
- (vacío por ahora)


=== ARCHIVO: 09-DECISIONES/2026-09-identidad-visual-aprobada.md ===

---
type: decision
title: "Se aprueba la estética de la presentación de Alex"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
date: 2026-09-24
tags: [decision, identidad-visual]
related:
  - "[[identidad-visual]]"
sources:
  - Notas de voz de Patricia (transcritas, sep 2026)
---

# Se aprueba la estética de la presentación de Alex (sep 2026)

- **Decisión:** los colores y las hojas de fondo de la presentación de Alex son la base visual de la marca.
- **Quién:** [[patricia|Patricia]] ("me enamoré de lo que vos me presentaste").
- **Por qué:** conecta con lo natural y lo artesanal, y a Patricia le gustó más que su propio borrador.
- **Reversible:** sí.


=== ARCHIVO: 09-DECISIONES/_MOC.md ===

---
type: moc
title: "09 Decisiones"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [moc]
related:
  - "[[_MOC]]"
sources:
  []
---

# 09 Decisiones

Decisiones con fecha y motivo.

## Contenido
- [[2026-09-identidad-visual-aprobada]]: se aprueba la estética de la presentación de Alex


=== ARCHIVO: 10-FUENTES/_MOC.md ===

---
type: moc
title: "10 Fuentes"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [moc]
related:
  - "[[_MOC]]"
sources:
  []
---

# 10 Fuentes

De dónde sale la información.

## Contenido
- [[registro-de-fuentes]]: lista de fuentes


=== ARCHIVO: 10-FUENTES/registro-de-fuentes.md ===

---
type: source
title: "Registro de fuentes"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [fuentes]
related:
  []
sources:
  []
---

# Registro de fuentes

| Fuente | Qué alimentó |
|---|---|
| Instagram @conys.home (40 posts, export 2026-09) | productos, eventos, aliados, voz de marca, auditoría |
| Apuntes reunión con Patricia (Alex) | historia, voz de Patricia, experiencias, aromas |
| Presentación de Alex para Cony's Home | foco, estrategia digital, tienda online, ideas |
| Notas de voz de Patricia (transcritas, sep 2026) | voz de Patricia, pendientes, identidad visual |


=== ARCHIVO: 99-LOGS/_MOC.md ===

---
type: moc
title: "99 Logs"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [moc]
related:
  - "[[_MOC]]"
sources:
  []
---

# 99 Logs

Registro de cambios.

## Contenido
- [[changelog]]: cambios


=== ARCHIVO: 99-LOGS/changelog.md ===

---
type: log
title: "Changelog"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [log]
related:
  []
sources:
  []
---

# Changelog
- 2026-09-25: Cerebro creado a partir del export de Instagram, los apuntes de la reunión y la presentación de Alex. Las notas de voz quedan pendientes.
- 2026-09-25: Notas de voz procesadas. Voz de Patricia completada (argentina, rioplatense). Nuevas notas: identidad visual, fotógrafa recomendada y la decisión de estética aprobada.
- 2026-09-25: Dudas resueltas: cámara (ocasional), neurociencia (confirmado), Pol French Gallery = competidor en Palermo Soho. Nueva nota: competencia.
- 2026-09-25: Paleta de colores (6 HEX) agregada a identidad-visual, con tabla de contraste.


=== ARCHIVO: _MOC.md ===

---
type: moc
title: "Cony's Home: Mapa principal"
created: 2026-09-25
updated: 2026-09-25
status: active
audience: patricia, alex
confidence: confirmed
tags: [moc]
related:
  []
sources:
  []
---

# Cony's Home: Mapa principal

Empezá acá. ¿Primera vez? Leé [[como-usar-este-cerebro]].

## Contenido
- [[00-CONTEXTO/_MOC]]: identidad, foco actual, productos y precios, voz, estándares
- [[01-MARCA/_MOC]]: historia, aromas, productos, atelier, experiencias
- [[02-PERSONAS/_MOC]]: Patricia, Alex, socios y aliados
- [[03-MARKETING/_MOC]]: estrategia digital, auditoría de Instagram, pilares y banco de ideas
- [[04-EVENTOS/_MOC]]: talleres, inauguraciones y experiencias con fecha
- [[07-REUNIONES/_MOC]]: reuniones y notas de voz procesadas
- [[08-INBOX/_MOC]]: material pendiente de procesar
- [[09-DECISIONES/_MOC]]: decisiones tomadas y por qué
- [[10-FUENTES/_MOC]]: de dónde sale cada dato
- [[99-LOGS/_MOC]]: registro de cambios
