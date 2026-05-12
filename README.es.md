# Cómo Anthropic hace videos que consiguen 78M de vistas

Análisis sistemático de 77 videos oficiales de producto de Claude (oct 2025 – may 2026). Metodología extraída, sistema de diseño, marcos narrativos y patrones de engagement.

[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Français](README.fr.md) | [Português](README.pt.md) | [Documento completo de metodología →](analysis/METHODOLOGY.es.md)

---

## 5 grandes insights

### 1. Nunca graban pantallas reales — reconstruyen UIs perfectas

Cada "captura de pantalla" en un video de Claude es fabricada. Mockups de UI pixel-perfect compuestos sobre marcos de dispositivo renderizados en 3D (MacBooks, iPhones, monitores), flotando sobre fondos cálidos. Sin chrome del navegador, sin barra de marcadores, sin badges de notificación.

**Por qué funciona:** Elimina el ruido visual. Cada frame es brand-safe. Sin pestañas accidentales, sin marcadores embarazosos, sin elementos UI obsoletos cuando el producto lance una actualización la próxima semana.

### 2. El hook "menos es más" es el patrón de mayor rendimiento

Los dos videos más vistos (77.9M y 63.5M) abren de la misma forma: un ícono diminuto sobre un vasto fondo cálido. Sin texto. Sin animación. Solo espacio negativo y un punto focal.

Esto crea una **brecha cognitiva** — el cerebro no puede parsear el frame instantáneamente, así que invierte atención para descifrarlo. Cuando el nombre del producto aparece a los 0.8–1.2s, el espectador ya está enganchado.

El video de 10 segundos que consiguió 10M de vistas? Mismo principio. Minimalismo extremo. Un elemento. Listo.

### 3. Sin intro de logo, sin CTA final — nunca

En 77 videos:
- **0** empiezan con animación de logo
- **0** terminan con "¡Regístrate ahora!" o cualquier call-to-action

Es posicionamiento de marca deliberado. Un intro de logo dice "necesitamos presentarnos". Un CTA dice "te necesitamos". Claude no hace ninguno — el producto aparece en el frame 1, y el video se desvanece a un logo silencioso sobre fondo cálido.

El mensaje: *nuestro producto no necesita venderse a sí mismo.*

### 4. "Mostrar el pensamiento, no solo el resultado" impulsa el engagement

Los videos que visualizan el proceso de la IA — listas de taches marcándose en verde, comandos de terminal desplazándose, grafos de nodos expandiéndose — consistentemente superan a los videos que solo muestran el output final.

No es solo un truco de producción. Es **arquitectura de confianza.** Mostrar el proceso hace que la IA se sienta menos como una caja negra. El espectador puede verificar: "sí, realmente hizo estos pasos".

El ejemplo más extremo: Computer Use (77.9M) muestra a Claude haciendo click a través de un SO real, app por app. No simulado. No acelerado demasiado. Cursor real, clicks reales, vacilación real.

### 5. Solo hard cuts — cero transiciones elaboradas

En 77 videos:
- ~60% hard cuts entre escenas
- ~15% fade a fondo cálido
- ~10% slide-ins
- ~0% disoluciones, morphs, flips 3D, efectos de partículas

Cada transición dura menos de 2 segundos. Sin disoluciones cinematográficas. Sin transiciones de motion graphics llamativas. La filosofía: si cada frame vale la pena verlo, no necesitas disculparte por cortar a él.

---

## Insights basados en datos

### "Introducing" vale 5x más que "now available"

Los videos que anuncian algo nuevo ("Introducing Claude Cowork") promedian **23.6M de vistas**. Los videos que extienden algo existente ("Claude is now available in Excel") promedian **4.6M**. La palabra "Introducing" no es solo copy — es señal de "nueva especie" vs "actualización de versión".

### 60–90 segundos es el sweet spot — luego cae en picada

| Duración | Vistas promedio |
|----------|----------------|
| <15s | 3.0M |
| 30–60s | 7.3M |
| **60–90s** | **15.6M** |
| >90s | 2.9M |

60–90s da suficiente espacio para un arco narrativo completo (hook → demo → magia → resultado). Menos de 30s se siente incompleto. Más de 90s pierde atención. El sweet spot es estrecho pero real.

### Lanzamiento en pulso, no goteo constante

77 videos en 222 días = 1 cada 2.9 días en promedio. Pero el 77% de los días tienen cero lanzamientos. Anthropic usa **campañas de ráfaga** — ventanas de 3–5 días con 2–3 videos por día, luego períodos de silencio.

Lo más extremo: febrero 2026 vio 23 videos en un mes (30% de todo el contenido), agrupados alrededor de los lanzamientos de Opus 4.6 y Cowork. El día más productivo: 20 de febrero — 7 videos en 24 horas.

**Por qué funciona el pulso:** los algoritmos de plataforma recompensan la concentración temática. Una ráfaga de videos relacionados crea una percepción de "Claude está en todas partes" que un goteo constante no puede igualar.

### Amplitud vs profundidad: dos juegos distintos

- **Juego de amplitud** (exposición de marca): Computer Use — 77.9M vistas, 14,467 retweets. Millones lo vieron, pocos lo guardaron.
- **Juego de profundidad** (lealtad de desarrolladores): Agent View — 2.3M vistas, pero 0.32% de tasa de bookmark y 686 replies. Menos espectadores, pero cada uno profundamente involucrado.

Ambos importan. La amplitud construye la marca. La profundidad construye la comunidad. Anthropic ejecuta ambos tracks simultáneamente.

### Lunes es el día de lanzamiento

| Día | Vistas promedio |
|-----|----------------|
| **Lunes** | **12.6M** |
| Viernes | 9.4M |
| Mar–Jue | 4.7–5.5M |

Los posts del lunes cabalgan la ola de atención del fin de semana al día laboral. Los posts del viernes obtienen amplificación del fin de semana.

---

## Fórmula de producción (versión TL;DR)

```
Lienzo cálido (#FBFAF6) + UI oscura (#1A1A2E) + Acento terracota (#D67C64)
+ UI perfecta reconstruida sobre mockups de dispositivo 3D
+ Títulos serif en sentence case con punto.
+ Hard cuts. Sin intro de logo. Sin CTA.
+ Task sequence para "magic moments"
+ Hook en 0–3s. Magic moment antes de 15s.
= Video de Claude.
```

---

## Posicionamiento competitivo

| | Claude | ChatGPT | Gemini | Apple Intelligence |
|---|--------|---------|--------|-------------------|
| Color | Blanco cálido + terracota | Azul frío + gradiente negro | Blanco + multicolor | Negro puro + blanco puro |
| Tono | Académico, cálido, reflexivo | Tech, cool, vanguardia | Amigable, consumo | Minimal, premium |
| Tipografía | Títulos serif (editorial) | Sans-serif (tech) | Google Sans (marca) | SF Pro (sistema) |
| Humanos en pantalla | 1 de 77 | A veces | Frecuente | Nunca |
| CTA final | Nunca | A veces | Siempre | Tarjeta de marca |

---

## Adáptalo a tu producto

**Presta directamente:** hard cuts, sin intro de logo, sin CTA, títulos en sentence case con puntos, pesos de fuente 500/600/700, task sequences, escenas de 3–8s, lista de anti-patrones, cadencia de lanzamiento en pulso, sweet spot de 60–90s.

**Adapta a tu marca:** sistema de colores (usa tus colores de marca pero mantén la jerarquía lienzo cálido + UI oscura), tipografía (usa tu fuente de marca pero mantén la jerarquía de tamaños), mockups de dispositivo (usa capturas con sombras si no puedes hacer renders 3D).

**El principio subyacente:** cada decisión de producción debe tener una razón. Las elecciones de Claude no son estética arbitraria — son estrategia de marca expresada a través de movimiento. Copia el razonamiento, no los píxeles.
