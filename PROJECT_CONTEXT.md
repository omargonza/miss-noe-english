# PROJECT_CONTEXT.md

## Proyecto

Sitio web educativo/comercial para **Miss Noe Online English**.

La implementación actual está resuelta principalmente en un único archivo `index.html`, con HTML, CSS y JavaScript embebidos.

---

## Objetivo del sitio

El objetivo principal del sitio es:

- presentar la marca de Miss Noe con una imagen profesional y premium
- mostrar cursos de inglés online
- facilitar exploración del catálogo
- mejorar confianza y percepción de valor
- incentivar registro y compra
- ofrecer una experiencia clara, simple y atractiva desde celular y desktop

---

## Tipo de producto

No es una app compleja con backend real en esta etapa.
Es una **plataforma/lading educativa frontend-only**, con comportamiento de catálogo y navegación interna simulada/renderizada en cliente.

---

## Stack actual

- HTML
- CSS embebido
- JavaScript vanilla
- Tailwind CSS por CDN
- Font Awesome por CDN
- Google Fonts por CDN
- localStorage para persistencia simple en cliente

---

## Arquitectura actual

La arquitectura actual está basada en:

- un único archivo `index.html`
- render dinámico dentro de `<main id="app"></main>`
- navegación interna controlada por JavaScript
- estado global manejado en variables JS
- carrito y progreso persistidos con `localStorage`

Esto implica que cualquier cambio puede tener impacto cruzado en varias vistas o funciones.

---

## Contexto funcional actual

La web contiene lógica para:

- home
- catálogo de cursos
- detalle de curso
- reproductor / vista de lecciones
- dashboard / mis cursos
- carrito
- modal
- búsqueda
- filtros
- navegación mobile
- almacenamiento local de progreso y compras simuladas

---

## Prioridades del proyecto

Estas prioridades deben mantenerse siempre presentes:

1. experiencia mobile excelente
2. claridad comercial
3. percepción premium y profesional
4. navegación simple
5. buena legibilidad
6. CTA claros
7. mantenimiento sencillo
8. performance razonable
9. accesibilidad básica correcta
10. no romper funcionalidad existente

---

## Perfil de usuario principal

El sitio debe funcionar especialmente bien para:

- mujeres adultas interesadas en aprender inglés online
- madres que evalúan propuestas educativas
- alumnos que buscan cursos claros, confiables y bien presentados
- usuarios no técnicos
- usuarios mobile-first

Por eso la experiencia debe ser:

- simple
- elegante
- intuitiva
- emocionalmente confiable
- libre de fricción

---

## Criterios de UX importantes

Toda mejora debe respetar estos criterios:

- el usuario debe entender rápido qué ofrece el sitio
- los cursos deben verse valiosos y confiables
- los botones importantes deben notarse
- el recorrido hacia explorar, registrarse o comprar debe ser claro
- el sitio no debe sentirse recargado ni confuso
- en celular todo debe verse limpio, cómodo y usable

---

## Criterios técnicos importantes

Al modificar el código, priorizar siempre:

- no romper otras vistas renderizadas
- no introducir complejidad innecesaria
- no duplicar lógica si puede evitarse
- no empeorar performance
- no empeorar accesibilidad
- no hacer cambios globales peligrosos sin revisar impacto
- mantener consistencia visual y estructural

---

## Restricciones

- no migrar a React, Vue, Next u otro framework salvo pedido explícito
- no separar en múltiples archivos salvo pedido explícito
- no agregar backend salvo pedido explícito
- no incorporar librerías nuevas sin necesidad real
- no reescribir toda la arquitectura sin justificación
- no sacrificar claridad por efectos visuales

---

## Enfoque esperado del agente

Ante cada nueva instrucción, el agente debe:

1. entender qué vista o flujo afecta
2. revisar HTML, CSS y JS relacionado
3. detectar errores, riesgos y oportunidades
4. pensar en mobile, UX, accesibilidad y conversión
5. recién después proponer o aplicar cambios

---

## Qué debe vigilar siempre el agente

### En HTML
- semántica
- estructura de headings
- accesibilidad básica
- uso correcto de botones, links e imágenes

### En CSS
- responsive
- consistencia visual
- contraste
- espaciado
- efectos costosos
- escalabilidad

### En JavaScript
- estado global
- funciones compartidas
- render dinámico
- side effects
- errores silenciosos
- mantenibilidad

### En UX/comercial
- claridad de propuesta
- confianza
- CTA
- flujo de compra/registro
- percepción profesional
- facilidad de uso en celular

---

## Resultado esperado

El código debe evolucionar hacia una web que se perciba:

- premium
- clara
- ordenada
- confiable
- fácil de navegar
- fácil de mantener
- apta para vender cursos online con buena experiencia de usuario