# Cómo Anthropic hace videos que consiguen 78M de vistas

Análisis sistemático de 77 videos oficiales de producto de Claude (oct 2025 – may 2026). Metodología extraída, sistema de diseño, marcos narrativos y patrones de engagement.

 **Languages:** [English](README.md) · [中文](README.zh.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [**Español**](README.es.md) · [Français](README.fr.md) · [Português](README.pt.md)

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

---

# Metodología de Producción de Videos de Producto Anthropic Claude

Análisis sistemático basado en 77 videos oficiales de @claudeai (2025-10 a 2026-05).
Cubre pipeline de producción, sistema de diseño, marco narrativo, gramática de animación, motor de ritmo y fórmulas de interacción.

---

## 1. Pipeline de Producción

### 1.1 Las 6 etapas del concepto al lanzamiento

```
Brief → Storyboard → UI Fabrication → Animation → Audio → Delivery
```

**Etapa 1: Brief**
- Determinar el tipo de video (ver Capítulo 3: Marco Narrativo)
- Fijar el presupuesto de duración: 30s / 60s / 90s / 10s tarjetas cortas
- Confirmar el canal: X/Twitter (16:9 o 1:1), YouTube (16:9), Instagram (4:5)
- Seleccionar la estrategia de apertura (ver Capítulo 5: Arquitectura de Hook)

**Etapa 2: Storyboard**
- No se hace storyboard dibujado a mano — se organizan escenas directamente en herramientas de UI mockup
- Cada escena se anota con: timecode, descripción del contenido, tipo de animación, método de transición
- El enfoque de Claude: granularidad fina (3-8s/escena), cada escena hace solo una cosa

**Etapa 3: UI Fabrication**
- **Principio central: no grabar pantallas reales, reconstruir UI perfecta**
- Reconstruir la interfaz del producto a nivel de píxel con Figma/Sketch/After Effects
- Eliminar todo el ruido: tabs irrelevantes, marcos de debug, barras innecesarias, datos sucios en datos reales
- Los marcos de dispositivos usan mockups 3D renderizados (iPhone, MacBook, monitores) con sombras sutiles
- Este es el mayor punto diferencial de los videos de Anthropic frente a la competencia: cada frame es perfecto

**Etapa 4: Animation**
- Todo el movimiento proviene de la animación del contenido, no del movimiento de cámara
- Las transiciones entre escenas son predominantemente hard cuts; transiciones complejas (<2s) se usan ocasionalmente
- Simulación de movimiento del cursor: establecer punto de inicio, opacidad 0→1 en 0.46s, vuelo hacia el objetivo, pulso de clic
- Task Sequence entra línea por línea, cambio de estado, check

**Etapa 5: Audio**
- Videos de animación de ritmo rápido: música electrónica/percusión sincronizada con el beat
- Demostraciones de producto: música ambiental ligera
- Videos de terminal/developers: mínimo o sin música
- Declaraciones de marca: silencio o un solo tono
- Conservar la versión original sin audio, luego exportar por separado la versión con música

**Etapa 6: Delivery**
- Exportar en múltiples resoluciones: 4K (3840x2160) para insignia, 1080p para uso regular
- Múltiples formatos de aspecto: 16:9 horizontal como principal, 4:5 vertical / 1:1 cuadrado para redes sociales
- Convención de nombres: `YYYY-MM-DD-slug-keyword.mp4`

### 1.2 Dos pistas de producción

| Pista | Inversión | Características | Uso típico |
|------|-----------|----------------|------------|
| **Oficial premium** | Alta | 4K, UI simulada, mockups de dispositivos compuestos, gráficos en movimiento | Lanzamientos de producto, funciones principales |
| **Comunidad/En vivo** | Baja | Grabación de pantalla cruda, persona en cámara, postproducción mínima | Hackathons, eventos de comunidad, demos reales |

Ambas pistas corren en paralelo. El contenido en vivo ocasionalmente obtiene la mayor interacción (demo en vivo de Cowork 14.6M), porque la "autenticidad" es un recurso escaso en sí mismo.

---

## 2. Sistema de Diseño

### 2.1 Sistema de color: "Inteligencia Cálida"

```
Fondo del lienzo:  #FBFAF6 ~ #F5F0E8  Blanco cálido/crema (no blanco puro)
Superficie del producto:  #1A1A2E ~ #2D2D3D  Carbón en modo oscuro
Color de acento principal:  #D67C64  Terracota/naranja quemado
Color de acento secundario:  #4ECDC4  Azul verdoso/cyan
Texto oscuro:  #0F172A / #1A1A1A
Texto claro:  #FFFFFF / #E0E0E0
```

**Intención de diseño:**
- Blanco cálido no es blanco puro. El blanco cálido crea una textura de "papel", más premium y suave que el blanco puro
- El color terracota es el elemento visual más reconocible al instante — se identifica como Claude en un segundo
- UI en modo oscuro = insinúa "premium", "tecnológico", "enfocado"
- En conjunto se aleja de los degradados fríos azul/negro de la competencia (OpenAI/Google) y del blanco/negro puro (Apple)
- Cálido + inteligente = sensación académica, no corporativa

**Diferenciación de posicionamiento con la competencia:**
- OpenAI: azul frío + degradado negro → sensación tecnológica/fria
- Google: blanco + multicolor → vibrante/consumo masivo
- Apple: negro puro + blanco puro → minimalista/consumo premium
- Claude: blanco cálido + terracota + UI oscura → académico/reflexivo/cálido

### 2.2 Sistema de tipografía

| Uso | Estilo de fuente | Peso | Características |
|-----|-----------------|------|-----------------|
| Tarjetas de título/marca | Serif de alto contraste (estilo Editorial New) | 700 | Sentence case con punto final |
| Etiquetas de UI/cuerpo | Sans-serif geométrica (Inter/SF Pro) | 500-600 | Limpia y legible |
| Código/terminal | Monoespaciada (JetBrains Mono) | 400-500 | Resaltado de sintaxis |
| Etiquetas en mayúsculas | Sans-serif | 600 | "PROGRESS", "CONTEXT" |

**Detalles clave:**
- Los títulos usan sentence case, no Title Case
- Los títulos terminan con punto — crean sensación de conversación y confianza: "Claude now integrates."
- Solo se usan pesos 500 / 600 / 700, se prohíbe la negrita sintética (`font-synthesis: none`)

### 2.3 Lenguaje de Mockups de Dispositivos

Los mockups de dispositivos son el dispositivo visual más central, no decoración:

```
┌─────────────────────────┐
│                         │
│   ┌─────────────────┐   │
│   │  [UI del producto]│   │  ← Marco de dispositivo 3D renderizado
│   │  Interfaz en modo │   │     con sombra sutil
│   │  oscuro           │   │     box-shadow: 0 8px 32px rgba(0,0,0,0.12)
│   └─────────────────┘   │
│                         │  ← Lienzo blanco cálido/crema
└─────────────────────────┘
```

**Tres composiciones para mostrar múltiples pantallas simultáneamente:**

**A. Dispositivo centrado** — Un solo foco, ideal para anuncios de funciones
**B. Layout de pantalla dividida** — Agente a la izquierda + aplicación objetivo a la derecha, ideal para mostrar integraciones
**C. Narrativa espacial** — Móvil → garabato conector → escritorio, ideal para flujos multi-dispositivo

---

## 3. Marco Narrativo

### 3.1 Cuatro modos narrativos principales

#### Modo A: Anuncio estándar de función (30-60s) — El más usado

```
Hook    (0-3s)   Nombre/icono de función revelado sobre fondo cálido
Context (3-8s)   Mostrar el problema o necesidad del usuario
Action  (8-15s)  El usuario dispara la acción (clic/entrada)
Demo    (15-45s) Demo animada del producto (contenido central)
Magic   (30-50s) El sistema completa automáticamente (Task Sequence/visualización de progreso)
Result  (45-55s) Mostrar el estado completado
Close   (55-60s) Logo + cierre con fondo cálido
```

Aplicable: La mayoría de lanzamientos de funciones. Representa ~60% de los 77 videos.

#### Modo B: Escaneo de ecosistema (30-50s)

```
Hook  (0-3s)   "[Producto] se conecta a [herramienta/workflow]"
Setup (3-8s)   Mostrar la aplicación objetivo (Slack/Excel/Figma)
Flow  (8-35s)  Cambios entre múltiples apps, mostrar flujo de datos
Proof (35-45s) Estado final del resultado
Close (45-50s) Logo
```

Aplicable: Anuncios de integraciones, showcases de partners. El dispositivo visual clave es la pantalla dividida + disparador @mention.

#### Modo C: Tarjeta social ultra-corta (8-15s)

```
Escena única: fondo de marca + texto animado/revelación de icono
Sin demo de producto, pura información de marca/anuncio
```

Aplicable: Promoción de eventos, anuncios breves, declaraciones de marca. "Thank You" (8.2s, 12.7M vistas) es este modo.

#### Modo D: Demo profunda para desarrolladores (60-90s)

```
Hook        → La terminal ya está corriendo (narrativa in medias res)
Setup       → El usuario introduce comandos avanzados
Execution   → Salida de terminal + vista previa en pantalla dividida
Magic       → El árbol de tareas se expande, múltiples subtareas en paralelo
Result      → Estado completado + interfaz de auditoría/seguimiento
Close       → Tarjeta de marca
```

Aplicable: Funciones técnicas orientadas a desarrolladores. Estética de terminal, fuentes monoespaciadas, resaltado de diff de código.

### 3.2 Cinco variantes narrativas especiales

| Variante | Video representativo | Vistas | Técnica central |
|----------|---------------------|--------|-----------------|
| Comando y ejecución | Computer Use | 77.9M | Izquierda a derecha: móvil → flujo de procesamiento → escritorio |
| Revelación de galería | Claude Design | 63.5M | Revelación progresiva de lo abstracto a lo complejo |
| Narrativa de terminal | Managed Agents | 21.6M | Contar historia a través de comandos CLI y su salida |
| Momento de gratitud | Thank You | 12.7M | Resonancia emocional minimalista en 8.2s |
| Escaneo de ecosistema | Office GA | 27.7M | Mostrar secuencialmente Excel → PowerPoint → Word |

### 3.3 Leyes de hierro de apertura y cierre

**Apertura:**
- Sin intro de logo — el producto se muestra directamente en los primeros 2 segundos
- Los primeros 2 segundos deben tener atracción visual
- 50% fondo de marca + fade-in de texto, 30% materialización de ventana de UI

**Cierre:**
- Sin hard cut a pantalla negra
- No usar tarjeta de CTA final tradicional (la gran mayoría)
- Terminar con el contenido o con fondo cálido + logo en fade-out
- Refuerza el posicionamiento de marca "premium, confiada"

---

## 4. Transiciones y Gramática de Animación

### 4.1 Reglas de transición

**Ley de hierro: hard cuts como protagonistas, cero transiciones llamativas.**

| Tipo de transición | Frecuencia de uso | Escenario |
|--------------------|--------------------|-----------|
| Hard cut | ~60% | Método principal de cambio entre escenas |
| Fade a fondo cálido | ~15% | Cierre de marca, cambio de ritmo |
| Deslizamiento (horizontal/vertical) | ~10% | Expansión de panel, barra lateral |
| Animación de dibujo | ~5% | Revelación de icono, conexión de trazos |
| Zoom a UI | ~5% | De vista general a detalle |
| Disolución/fade lento | ~0% | **Nunca se usa** |

Todas las transiciones se mantienen dentro de 2 segundos. Sin giros 3D, morph, ni efectos de partículas.

### 4.2 Vocabulario central de animación

**Simulación de Cursor (Cursor Simulation)**
```
Línea de tiempo:
  -0.46s: Establecer punto de inicio, opacity: 0→1
  -0.38s: Vuelo hacia el objetivo, ease: power3.out
   0.00s: Llegada, animación clickPulse
  +0.12s: Escala sutil (yoyo)
  +0.82s: El cursor se desvanece
```
Clave: el cursor debe "llegar adelantado", sin arrastrarse.

**Task Sequence — El núcleo del Magic Moment**
```
Entrada  → El elemento desliza desde abajo, opacity: 0→1, 0.28s
Cambio de color  → El círculo de estado pasa de gris a verde, 0.16s
Check  → Aparece la marca de verificación, 0.10s
```
Cada línea de tarea tiene su propio tiempo, pueden intercalarse (stagger 0.05s).

**Entrada de Modal (Modal Entrance)**
```
Inicio: y:34, scale:0.965, opacity:0
Animación: y→0, scale→1, opacity→1, 0.42s, ease: back.out(1.35)
```

**Revelación escalonada (Staggered Reveal)**
```
y:16 → y:0, opacity: 0→1, 0.28s, stagger: 0.05s
```
Usado para listas de integraciones, listas de archivos, tarjetas de herramientas.

**Animación de dibujo (Draw-on)**
```
SVG stroke-dasharray:
  strokeDashoffset: 200 → 0, 0.8s, ease: power2.inOut
```
Uso: garabatos dibujados a mano conectando dos áreas de UI, iconos de boceto a relleno.

### 4.3 Reglas de movimiento de cámara

**Por defecto: imagen estable, sin deriva continua.**

El movimiento de cámara se usa solo con un propósito narrativo claro:
- Pan/zoom global para enfocar un área del producto, duración 0.3-0.6s
- Zoom a toda la pantalla o área del producto, no solo ampliar un botón individual
- Una vez la cámara llega a posición, se mantiene estable para que el texto de UI y los estados sean legibles
- Entre escenas predominan hard cuts, cambio de capas y animación de entrada de contenido

---

## 5. Arquitectura de Hook (los primeros 3 segundos lo deciden todo)

### 5.1 Cinco estrategias de apertura

| Estrategia | Técnica | Efecto | Video representativo |
|------------|---------|--------|---------------------|
| **Minimalismo extremo** | Espacio negativo enorme + icono diminuto | Mayor curiosidad, mayor tasa de permanencia | Computer Use (77.9M), Design (63.5M) |
| **Revelación de marca** | Fondo cálido + fade-in de elementos | Contenido, premium, consistente | Mayoría de videos de funciones estándar |
| **Producto directo** | Captura de UI o mockup de dispositivo directo | Sin rodeos, orientado a eficiencia | Cowork Windows, Chrome |
| **Pregunta sobre dolor** | Texto que plantea la pregunta del usuario | Impulsado por empatía | "Tired of tedious work?" |
| **Declaración audaz** | Declaración de marca o posicionamiento | Propagación por controversia | "Keep Thinking" (5.2M) |

### 5.2 Hook "menos es más" — El modo más fuerte

Los dos videos con mayor visualización (77.9M y 63.5M) usaron la misma estrategia:

1. Primer frame: un elemento diminuto (icono de cursor/icono de boceto) sobre fondo cálido
2. Sin texto — obliga al espectador a detenerse a "decodificar" qué es esto
3. Segundo beat (0.8-1.2s después): revelación del texto con el nombre de la función

**Principio:** Minimalismo extremo → Brecha cognitiva → Curiosidad → Permanencia → Finalización.

---

## 6. Motor de Ritmo

### 6.1 Reglas de duración de escena

| Tipo de video | Duración por escena | Sensación de ritmo |
|---------------|--------------------|--------------------|
| Demo larga de función (60-96s) | 4-8s/escena | Medido, estilo tutorial |
| Demo media de función (40-60s) | 3-5s/escena | Ritmo medio, estilo narrativo |
| Anuncio corto (<20s) | 2-3s/escena | Rápido, contundente |
| Tarjeta social (<12s) | Escena única | Mínimo |

### 6.2 Relación entre duración e interacción

**Hallazgo contraintuitivo: la duración por sí sola no determina la interacción.**

- Los videos con mayor interacción son de 73s (Computer Use) y 81.5s (Design)
- Un video de 10 segundos obtuvo 10M de vistas (Remote Control)
- Un video de 96 segundos solo obtuvo 12.5M (Excel/PowerPoint)

**Lo que realmente determina la interacción es:**
1. Calidad del hook de apertura (primeros 3 segundos)
2. Universalidad de la función (atracción interdisciplinaria)
3. Ritmo narrativo (sin arrastrarse, cada escena tiene densidad de información)
4. Refinamiento visual (4K vs 1080p tiene correlación pero no causalidad)

### 6.3 Ubicación del Magic Moment

**El Magic Moment debe aparecer dentro de los primeros 15 segundos.**

El Magic Moment es el instante visualizado de "qué está haciendo el sistema por el usuario" — no es un spinner de carga, sino:
- Tareas completándose línea por línea (checks verdes)
- Archivos generándose automáticamente
- Comandos de terminal ejecutándose autónomamente
- Datos fluyendo entre múltiples aplicaciones

Si en 15 segundos no le das al espectador un momento "wow", se va deslizando.

---

## 7. Fórmulas de Interacción

### 7.1 Cinco características comunes de videos de alta interacción

Extraídos de los datos de 77 videos:

1. **Resolución 4K** — 3840x2160 está fuertemente correlacionado con vistas altas
2. **Apertura minimalista extrema** — Curiosidad que impulsa la permanencia
3. **Función universal** — Atracción interdisciplinaria, no solo para desarrolladores
4. **Narrativa rítmica de 70-80 segundos** — El espectador está dispuesto a ver la demo completa
5. **Composición narrativa espacial/horizontal** — Flujo visual de izquierda a derecha

### 7.2 Factores que NO determinan la interacción

- La duración en sí (no es que más corto sea mejor)
- La relación de aspecto (horizontal y vertical tienen altos y bajos)
- El enfoque en desarrolladores (Code Review 23.5M)
- El costo de producción (video en vivo 14.6M vs video premium 2M)

### 7.3 Niveles de interacción

| Nivel | Vistas | Proporción | Características comunes |
|-------|--------|------------|------------------------|
| Super | 50M+ | ~3% | 4K, apertura minimalista extrema, función universal, narrativa espacial |
| Alto | 10-30M | ~15% | Producción refinada, demo clara de función, narrativa fuerte |
| Medio | 2-10M | ~40% | Producción estándar, narrativa media |
| Bajo | <2M | ~42% | Baja densidad de información o audiencia estrecha |

---

## 8. Guía de Niveles de Producción

### Tier 1: Lanzamiento insignia (4K, 60-90s)

- **Escenario:** Lanzamientos de funciones principales, introducción de nuevos productos
- **Características:** 3840x2160, composición de mockups de dispositivos, animación compleja multi-escena, música sincronizada con beat
- **Ciclo de producción:** 1-2 semanas
- **Equipo:** Diseñador de motion + Diseñador de UI + Audio

### Tier 2: Demo de función (1080p, 30-60s)

- **Escenario:** Showcase de una sola función, anuncio de integración
- **Características:** 1920x1080, layout de pantalla dividida, 3-5 escenas, música ligera
- **Ciclo de producción:** 3-5 días
- **Equipo:** Diseñador de motion

### Tier 3: Tarjeta social (1080p o cuadrado, 8-15s)

- **Escenario:** Anuncios, promoción de eventos, mensajes de marca
- **Características:** Escena única, animación de texto como protagonista, sin demo de producto
- **Ciclo de producción:** 1 día
- **Equipo:** Diseñador de motion (puede acumular funciones)

### Tier 4: Comunidad en vivo (calidad original, sin límite)

- **Escenario:** Hackathons, eventos de comunidad, demos reales de producto
- **Características:** Postproducción mínima, persona en cámara, grabación de pantalla cruda
- **Ciclo de producción:** Mismo día
- **Equipo:** Personal de producto/ingeniería grabando por sí mismo

---

## 9. Lista de Anti-patrones

Extraídos del análisis de 78 videos — estas son cosas que Claude NO hizo, y tú NO deberías hacer:

1. **No hacer entrada solo con logo** — El producto o la promesa de función debe aparecer en los primeros 2 segundos
2. **No usar tarjeta de CTA final** — Terminar con el contenido/estado del producto o una marca de brand simple
3. **No usar transiciones llamativas** — Priorizar hard cuts, cambio de capas, animación de entrada de contenido
4. **No usar fondos de degradado decorativos** — El lienzo se mantiene contenido, el producto es el protagonista
5. **No poner personas en cámara salvo que sea necesario** — Solo 1 de 78 videos tiene un rostro humano
6. **No grabar pantallas reales** — Reconstruir UI perfecta, eliminar todo el ruido
7. **No dejar en blanco el proceso de generación de IA** — Se debe visualizar task / progress / preview
8. **No usar copy de marketing genérico** — Usar nombres reales de funciones y etiquetas de producto
9. **No hacer deriva continua de cámara** — Solo pan / zoom cortos y precisos
10. **No ampliar solo un botón** — Hacer zoom a toda la pantalla o área del producto

---

## 10. Análisis de Evolución Temporal: 18x las vistas en 8 meses

### 10.1 Panorama de datos

| Período | Videos | Promedio de vistas | Máximo de vistas | Total de vistas |
|---------|--------|-------------------|-----------------|----------------|
| 2025 Q4 | 21 | **0.7M** | 2.7M | 14M |
| 2026 Q1 | 41 | **9.1M** | 77.9M | 373M |
| 2026 Q2 | 15 | **12.6M** | 63.5M | 190M |

En 8 meses, el promedio de vistas se multiplicó por 18. No es que se tuvo la suerte de un viral — es la metodología iterando.

### 10.2 Cambios cualitativos en tres etapas

#### 2025 Q4 — "Ya podemos hacer videos"

Etapa de inicio. Producción tosca pero se establece el lenguaje base:
- Ventanas de aplicaciones flotantes sobre fondos de marca (como animaciones de PPT)
- Terracota + modo oscuro se establecen como estándar
- Títulos serif + sentence case con punto final
- Solo 1 video con persona en cámara (ingeniero de Opus 4.5)
- Máximo de vistas: 2.7M (Claude Code on Web)

**Característica: seguro — todos los videos se parecen, como si salieran de una plantilla.**

#### 2026 Q1 — "Se encontró la fórmula viral"

Etapa de cambio cualitativo:
- De ventanas flotantes a **mockups de dispositivos 3D** (móvil/laptops/monitores compuestos sobre fondo cálido)
- Aparece la filosofía de marca "Keep Thinking" — de vender funciones a vender actitud
- La serie Cowork define la narrativa de "flujos de trabajo de IA para no técnicos"
- **Dos virales a nivel de evento:** Lanzamiento de Cowork (49.7M), Computer Use (77.9M)
- Video de seguridad 26.2M — la palabra "seguridad" tiene poder de propagación inherente
- Videos en vivo (demo de Cowork, 14.6M) demuestran que la "autenticidad" pega más que el "refinamiento"

**Hallazgo clave: no es que cuanto más refinada sea la producción, mejor — es que cuanto más fuerte sea la narrativa, mejor.**

#### 2026 Q2 — "Menos es más" se valida

La evolución de la etapa final es sustractiva:
- La apertura minimalista extrema se convierte en el Hook más fuerte (Computer Use solo tiene un icono de cursor + gran espacio vacío)
- Claude Design (63.5M) abre con un icono de paleta de boceto, sin decirte qué es al principio
- La narrativa espacial madura: flujo visual de izquierda a derecha (móvil → procesamiento → escritorio)
- Los conectores de garabato dibujados a mano se convierten en elemento icónico
- Office GA (27.7M) muestra la narrativa de "escaneo de ecosistema"

**Comprensión central: cuanto menos información den los primeros 2 segundos, más tiempo permanece el espectador.**

### 10.3 Evolución de la postura narrativa

```
Q4 2025: "Mira, Claude puede hacer X"           → Explicativa
Q1 2026: "Imagina, solo necesitas decir una frase"   → Demostrativa
Q2 2026: "(Mostrar en silencio, sin hablar)"        → Sugerente
```

De "explicativa" a "demostrativa" a "sugerente" — la energía de marca cada vez más alta, los videos cada vez más silenciosos.

### 10.4 Análisis del ritmo de publicación: estrategia de publicación por pulsos

**Datos globales: 77 videos, 222 días, promedio de 1 cada 2.9 días.**

Pero el "promedio" es engañoso — las publicaciones de Anthropic no están distribuidas uniformemente, sino que siguen un ritmo de pulsos intensos + largos intervalos.

#### Distribución mensual

| Mes | Videos | Característica |
|-----|--------|----------------|
| 2025-10 | 5 | Inicio, 1 por semana |
| 2025-11 | 5 | Estable, 1 por semana |
| 2025-12 | 11 | Aceleración, sprint de fin de año |
| 2026-01 | 9 | Estable-alto |
| 2026-02 | **23** | **Mes de explosión — 30% del total** |
| 2026-03 | 9 | Retroceso pero mantiene nivel alto |
| 2026-04 | 10 | Estable |
| 2026-05 | 5 | Desde inicio de mes (datos hasta el 10 de mayo) |

**Febrero de 2026 es el punto de inflexión clave** — 23 videos en un mes, 30% de los 77 totales. No es coincidencia: lanzamiento de Opus 4.6, salida de Sonnet 4.6, promoción intensiva de la serie Cowork, y actividad de hackathon todo concentrado en este mes.

#### Solo 51 de 222 días tuvieron publicaciones de video

Esto significa que **el 77% de los días son "días vacíos"** — sin publicar ningún video. La densidad de publicación no es lineal, sino por pulsos.

#### Tres campañas de publicación intensiva

| Campaña | Fechas | Días | Videos | Contenido clave |
|---------|--------|------|--------|-----------------|
| Semana de lanzamiento de Opus 4.6 | 2-6 de febrero | 5 días | 9 | Opus 4.6, Sonnet 4.6, matriz de funciones |
| Semana de promoción de Cowork | 17-20 de febrero | 3 días | 10 | Serie de funciones Cowork, demos en vivo, 7 en un solo día el 2/20 |
| Semana insignia de Q1 | 23-25 de marzo | 3 días | 3 | Computer Use (77.9M), Design (63.5M), total 93.1M |

**La tercera campaña es la más extrema** — 3 videos en 3 días, pero vistas totales de 93.1M. Validación perfecta de calidad > cantidad.

#### Intervalos más largos

| Intervalo | Duración | Período |
|-----------|----------|---------|
| Más largo | 28 días | 2025-10-28 → 2025-11-25 |
| Segundo | 19 días | 2025-12-29 → 2026-01-17 |
| Tercero | 14 días | 2025-11-11 → 2025-11-25 |

Estos largos intervalos aparecen al principio (Q4 2025), indicando que el equipo todavía estaba explorando el ritmo. Para 2026 Q1-Q2, el intervalo más largo se acorta a 7-10 días.

#### Lógica subyacente de la estrategia de pulsos

```
Período normal: 1-2 videos por semana, mantener presencia de marca
     ↓
Lanzamiento de producto: 3-5 días intensos, 2-3 videos por día, crear densidad de información
     ↓
Período de enfriamiento: volver al ritmo normal
```

**¿Por qué usar pulsos en vez de publicación uniforme?**

1. **Efecto algoritmo** — Los algoritmos de redes sociales premian la "concentración temática", múltiples videos en poco tiempo = empujado a más feeds
2. **Densidad narrativa** — Una función grande mostrada desde diferentes ángulos en 3-5 videos cubre más que un solo video
3. **Ritmo del equipo** — La producción de video es un trabajo por lotes, hacer un lote completo de una vez es más eficiente que hacer poco cada día
4. **Percepción del usuario** — "Claude está por todos lados últimamente" tiene más impacto que "uno estable por semana"

**Práctica:** No busques publicar un video cada día. Acumula un lote, publícalo concentrado en 3-5 días, luego vuelve al ritmo silencioso. Pulso > Uniforme.

#### Análisis de puntos de publicación (precisión por hora, zona horaria PST)

Tiempo de publicación extraído de los snowflake IDs de 77 tweets, estadísticas en hora estándar del Pacífico (PST):

**Distribución por franja horaria:**

| Franja (PST) | Videos | Vistas promedio | Significado |
|---------------|--------|-----------------|-------------|
| 0-6 AM | 10 | **13.1M** | Publicación programada con anticipación |
| 6-9 AM | 33 | 6.3M | **Ventana principal de publicación** (43% de los videos) |
| 9-12 AM | 24 | 8.4M | Ventana secundaria |
| 12-15 PM | 10 | 3.8M | Publicaciones de cola |

**Los 77 videos se concentran completamente dentro de las 10 horas PST 04:00-14:00.** Después de las 3 PM, cero publicaciones.

**Distribución exacta por hora:**

| Hora (PST) | Videos | Vistas promedio | Videos representativos |
|------------|--------|-----------------|----------------------|
| **05:00** | **9** | **12.9M** | Design 63.5M, Financial Services 13.5M |
| **08:00** | **18** | 7.2M | Office GA 27.7M, Cowork GA |
| 07:00 | 9 | 6.0M | Managed Agents 21.6M |
| 09:00 | 11 | 3.0M | Code Review 23.5M |
| 10:00 | 8 | 10.3M | Thank You 12.7M |
| **11:00** | **5** | **17.1M** | Computer Use 77.9M, Hackathon |
| 13:00 | 8 | 3.4M | Excel 23.4M |
| Otros | 9 | 5.1M | Distribuidos en 04/06/12 |

**Tres picos de publicación:**

| Pico | Hora PST | Videos | Vistas promedio | Característica |
|------|----------|--------|-----------------|----------------|
| **Primera ola matutina** | 05:00-06:00 | 15 | 10.0M | Mayor promedio de vistas, videos insignia publicados aquí |
| **Pico de inicio laboral** | 08:00-09:00 | 29 | 5.4M | Mayor densidad de cantidad, actualizaciones de funciones diarias concentradas aquí |
| **Onda pre-mediodía** | 10:00-11:00 | 13 | 12.9M | Aún tiene videos de alta vista, posiblemente la "segunda ventana" |

**Interpretación:**

1. **05:00 PST = hora de inicio en Europa** — Publicar a esta hora cubre ambos lados del Atlántico: la costa oeste de EE.UU. todavía está en la madrugada, pero Europa (CET 14:00) está en plena hora activa de la tarde. Los 9 videos publicados a las 05:00 promedian 12.9M vistas, **incluyendo dos videos de nivel 50M+**, indicando que la programación anticipada permite que el contenido fermente primero en Europa y luego refluya a EE.UU.

2. **08:00 PST = hora de inicio laboral en EE.UU.** — La ventana de publicación más densa (18 videos), justo en el inicio laboral de la costa este (11:00) y la costa oeste (8:00) de EE.UU. Esta es la ventana "estándar" de publicación.

3. **11:00 PST = antes del almuerzo** — El promedio de vistas más alto (17.1M) pero solo 5 videos. Esta franja posiblemente se usa como "segunda ventana" para lanzamientos importantes — si se perdió la publicación matutina, la pre-mediodía sigue siendo efectiva.

4. **Casi no se publica por la tarde** — Después de las 13:00 solo hay unos pocos videos dispersos, y después de las 14:00 completamente cero. Esto indica que el equipo de video de Anthropic concentra su trabajo en la mañana.

**Práctica:**
- **Lanzamiento insignia:** Programar a PST 05:00 (cubre ambos mercados, europeo y estadounidense)
- **Actualizaciones diarias:** PST 08:00-09:00 (hora de inicio laboral en EE.UU.)
- **Evitar publicar por la tarde:** Después de las 14:00 casi nadie mira
- **Si el objetivo es el mercado asiático:** 05:00 PST = 21:00 en Pekín, 22:00 en Tokio, justo en horario prime de la noche

---

## 11. Análisis de Popularidad: Por qué Explotan los Top 10

### 11.1 Resumen de los Top 10

| # | Video | Vistas | Duración | En una frase |
|---|-------|--------|----------|--------------|
| 1 | Computer Use | 77.9M | 73s | "La IA puede usar tu computadora" |
| 2 | Claude Design | 63.5M | 82s | "Hablar es suficiente para diseñar" |
| 3 | Cowork Launch | 49.7M | 69s | "Los no programadores también pueden usar IA para trabajar" |
| 4 | Office GA | 27.7M | 87s | "IA en Excel/Word/PPT" |
| 5 | Code Security | 26.2M | 50s | "IA que encuentra vulnerabilidades de seguridad" |
| 6 | Code Review | 23.5M | 45s | "Review automático de PR" |
| 7 | Excel Launch | 23.4M | 44s | "Preguntar a IA directamente en Excel" |
| 8 | Managed Agents | 21.6M | 59s | "IA gestionando IA" |
| 9 | Computer Use (Code) | 16.1M | 45s | "IA operando autónomamente en CLI" |
| 10 | Cowork Update | 14.6M | 120s | "Colaboración de equipos de IA empresarial" |

### 11.2 Cinco patrones virales

#### Punto viral uno: Contenido > Producción

**La palabra clave de lo viral es "nuevas posibilidades", no "actualización de función".**

- Los Top 10 son todos "Introducing..." o "You can now..." — **primer anuncio**
- Los Bottom 10 son todos "now available on...", "is now in beta" — **extensión de funciones existentes**

| Tipo de contenido | Vistas promedio | Ejemplo |
|-------------------|-----------------|---------|
| Nuevo producto/capacidad por primera vez | **30M+** | Computer Use, Design, Cowork |
| Actualización de función principal | **5-15M** | Code Review, Security |
| Expansión de plataforma/partnership | **1-5M** | Excel on Pro, Chrome |
| Actualización incremental/función menor | **<1M** | Skills Dir, /stats, guest passes |

**La gente paga por "nuevas especies", no por "actualizaciones de versión".**

#### Punto viral dos: El alcance de la audiencia determina el techo

Las funciones del Top 10 son todas universales e interdisciplinarias:
- Computer Use (77.9M) — Todos pueden entender "IA operando tu computadora"
- Cowork (49.7M) — El alcance de audiencia es diez veces el de Claude Code
- Office GA (27.7M) — Todos los usuarios de Office en el mundo

Las funciones del Bottom 10 son todas de nicho:
- Skills Directory (77K) — Solo los usuarios existentes les importa
- Guest Passes (62K) — Solo los usuarios Max les importa
- Comando /stats (70K) — Solo los usuarios de CLI les importa

**Un tema que solo es relevante para 1 millón de personas, por más refinada que sea su producción, no puede competir con un tema relevante para 100 millones de personas.**

#### Punto viral tres: 60-80 segundos es el punto dulce

| Rango de duración | Proporción en Top 10 | Característica |
|-------------------|---------------------|----------------|
| 40-50s | 3/10 | Enfoque en función, demo rápida |
| 60-80s | 4/10 | Narrativa completa, con Demo y Magic |
| 80-90s | 2/10 | Showcase de ecosistema, múltiples productos en cadena |

**No es que más corto sea mejor.** El promedio del Bottom 10 es 35 segundos, el del Top 10 es 67 segundos. El problema de los videos cortos no es "demasiado cortos", sino "densidad de información demasiado baja" — 35 segundos solo dicen "now available on Android", sin demo que valga la pena ver.

#### Punto viral cuatro: Emoción > Función (ocasionalmente)

**La tasa de likes más alta (likes/vistas) no la tienen los Top videos, sino los Bottom videos.**
- Tasa de likes promedio del Top 10: 0.22%
- Tasa de likes promedio del Bottom 10: 0.60%

Porque los Bottom videos llegan a los usuarios centrales — ellos ya siguen a @claudeai, naturalmente dan like. Los Top videos llegan a audiencias masivas — la mayoría son transeúntes.

Pero hay una excepción: **"Thank You" (8.2s, 12.7M, tasa de likes 0.38%)**. El contenido es solo una frase: "la capacidad se duplicará en horas pico las próximas dos semanas". Sin funciones nuevas, solo un gracias.

**"Ser agradecido" es una experiencia escasa.** La mayoría de empresas publican videos diciendo "mira la nueva función", Anthropic dijo "gracias".

#### Punto viral cinco: En vivo > Refinado (ocasionalmente)

La demo en vivo de Cowork (14.6M) es el video con producción más tosca — una persona real grabando pantalla en un dormitorio. Pero supera en vistas a muchos videos 4K refinados.

**En un feed lleno de mockups perfectos, lo "real" es escaso.** No significa que no debas hacer videos refinados — sino que intercalar contenido en vivo ocasionalmente puede generar una reacción química.

### 11.3 Prioridad de los puntos virales

Ordenados por impacto:
1. **Contenido de "nueva especie"** — Primer anuncio de una capacidad completamente nueva
2. **Alcance de audiencia** — Cuantas más personas lo entiendan, mejor
3. **Apertura minimalista extrema** — Cuanta menos información en los primeros 2 segundos, mejor
4. **Ritmo de 60-80 segundos** — Suficiente para desarrollar, sin arrastrarse
5. **Disparador emocional** — Ocasionalmente decir "gracias" es más poderoso que decir "mira la función"
6. **Intercalación de autenticidad** — Poner un video en vivo en un flujo de videos refinados


## 12. Análisis Multidimensional Basado en Datos

Usando datos estructurados de 77 videos, análisis cruzado desde 7 dimensiones: tasa de interacción, resolución, duración, día de publicación, palabras clave de contenido, viralidad y utilidad — para extraer los patrones de marketing de video de Anthropic.

### 12.1 Dimensión de tasa de interacción: quién realmente participa

Tasa de interacción = número de interacciones / vistas. Refleja mejor la calidad del contenido que los valores absolutos — porque filtra el ruido de "el algoritmo lo empujó a transeúntes que no les importa".

| Métrica | Fórmula | Significado |
|---------|---------|-------------|
| Tasa de likes | likes / views | Reconocimiento instantáneo |
| Tasa de guardados | bookmarks / views | "Esto es útil, lo necesito después" |
| Tasa de retweets | retweets / views | "Quiero que otros lo vean" |
| Tasa de respuestas | replies / views | "Quiero discutir esto" |

**Hallazgo clave: vistas altas no significa tasa de interacción alta.**

- Los videos con **mayor tasa de guardados** no son los virales, sino contenido de desarrolladores: Built with Opus 4.6 (0.47%), Code with Claude Conference (0.35%), Hackathon (0.34%), Agent View (0.32%)
- Los de **mayor tasa de respuestas** también tienden a nicho: Claude Code runnable (0.045%), Claude for Public (0.041%)
- Los de **mayor tasa de likes** son contenido relacionado con Opus 4.6 (1.46%) y aniversario de Claude Code (1.19%)

**Interpretación:** La comunidad de desarrolladores, aunque menor en número, tiene una profundidad de participación que supera con creces a la audiencia masiva. Tasa de guardados alta = "esto es una herramienta, la voy a usar". Esto indica que los videos de Claude sirven simultáneamente a dos grupos: la audiencia masiva por vistas, los usuarios centrales por profundidad de interacción.

### 12.2 Dimensión de resolución: 4K tiene correlación pero no causalidad

| Resolución | Videos | Vistas promedio | Vistas máximas |
|------------|--------|-----------------|----------------|
| 3840x2160 (4K) | 16 | 9.2M | 77.9M |
| 1920x1080 (1080p) | 40 | 8.5M | 63.5M |
| Otras resoluciones | 21 | 1.7M | 26.2M |

- La diferencia de vistas promedio entre 4K y 1080p no es grande (9.2M vs 8.5M)
- **El segundo video más visto (Design, 63.5M) es 1080p, no 4K**
- "Otras resoluciones" promedian solo 1.7M — pero esto se debe a que la mayoría son videos tempranos o formatos especiales (vertical, cuadrado)

**Práctica:** Prioriza 4K, pero si los recursos son limitados, 1080p no afectará significativamente el rendimiento. Lo que realmente importa es la calidad del contenido y la narrativa, no el número de píxeles.

### 12.3 Dimensión de duración: 60-90 segundos es el punto dulce

| Rango de duración | Videos | Vistas promedio | Tasa de likes | Tasa de guardados |
|-------------------|--------|-----------------|---------------|-------------------|
| <15s | 13 | 3.0M | 0.56% | 0.17% |
| 15-30s | 7 | 1.9M | 0.54% | 0.20% |
| 30-60s | 27 | 7.3M | 0.43% | 0.15% |
| **60-90s** | **19** | **15.6M** | **0.48%** | **0.13%** |
| >90s | 11 | 2.9M | 0.55% | 0.19% |

**Las vistas promedio de 60-90 segundos (15.6M) son 2-8 veces las de todos los demás rangos.**

Pero el rango >90s cae abruptamente a 2.9M. Esto indica:
- Demasiado corto (<30s): densidad de información insuficiente, sin Demo completa → vistas bajas
- 60-90s: suficiente para desarrollar una narrativa completa (Hook → Demo → Magic → Result) → vistas más altas
- Demasiado largo (>90s): decaimiento de atención, salvo que el contenido sea particularmente denso → vistas retroceden

**La tasa de guardados disminuye al alargar**: videos cortos tienen tasa de guardados más alta (<15s tiene 0.17%, 60-90s solo 0.13%). Videos cortos = consumo rápido, videos largos = ver y seguir, sin guardar.

### 12.4 Dimensión del día de publicación: lunes y viernes son los más fuertes

| Día de la semana | Videos | Vistas promedio | Vistas totales |
|------------------|--------|-----------------|----------------|
| **Lunes** | **15** | **12.6M** | **189.5M** |
| Martes | 17 | 5.5M | 93.6M |
| Miércoles | 16 | 4.7M | 74.8M |
| Jueves | 13 | 5.1M | 65.9M |
| **Viernes** | **15** | **9.4M** | **141.0M** |
| Sábado | 1 | 12.7M | 12.7M |

- **El lunes tiene el promedio de vistas más alto (12.6M)** — el primer día laboral después del fin de semana, alta actividad del usuario
- **El viernes le sigue (9.4M)** — posiblemente relacionado con el patrón de "publicar el viernes, fermentar el fin de semana"
- Sábado tiene solo 1 video (Thank You, 12.7M), muestra demasiado pequeña para concluir
- Martes a jueves son relativamente planos

**Práctica:** Lanzamientos importantes el lunes o viernes. Actualizaciones regulares de martes a jueves para mantener presencia.

### 12.5 Dimensión de palabras clave de contenido: qué temas tienen poder de propagación inherente

| Palabra clave | Significado | Videos | Vistas promedio |
|---------------|-------------|--------|-----------------|
| **Introducing** | **Primer anuncio** | **9** | **23.6M** |
| Design | Diseño | 5 | 19.7M |
| Cowork | Cowork/empresa | 10 | 17.7M |
| Excel | Excel/Office | 4 | 16.1M |
| Security | Seguridad | 2 | 15.5M |
| Claude Code | Herramientas de desarrollador | 26 | 9.9M |
| can now | Expansión de capacidades | 16 | 7.9M |
| Agent | Relacionado con Agent | 11 | 7.6M |
| now available | Función en línea | 8 | 4.6M |

**"Introducing" es la garantía absoluta de vistas** — promedio de 23.6M, 5 veces "now available" (4.6M).

Esto valida el hallazgo del capítulo 11: **Primer anuncio >> Expansión de función**. "Introducing" insinúa "nueva especie", "now available" insinúa "cosa vieja en lugar nuevo".

**Orden de atracción por tema:**
1. Diseño (19.7M) — Universal interdisciplinario, usuarios no técnicos también les importa
2. Cowork (17.7M) — "Los no programadores también pueden usar IA", alcance de audiencia enorme
3. Excel (16.1M) — Base global de usuarios de Office
4. Seguridad (15.5M) — "Seguridad" tiene ansiedad y atención inherentes
5. Claude Code (9.9M) — Exclusivo para desarrolladores, audiencia estrecha pero lealtad alta

### 12.6 Viralidad vs Utilidad: dos señales completamente diferentes

**Retweet rate alto = "Quiero que otros lo vean" (viralidad)**

| Ranking | Contenido | Tasa de RT | Vistas |
|---------|-----------|------------|--------|
| 1 | Claude for Public | 0.098% | 0.1M |
| 2 | Code with Claude Conference | 0.094% | 1.1M |
| 3 | Aniversario de Claude Code | 0.078% | 0.8M |
| 4 | Built with Opus 4.6 | 0.077% | 1.0M |
| 5 | Ads are coming to AI | 0.076% | 5.2M |

**Bookmark rate alto = "Esto es útil, lo necesitaré después" (utilidad)**

| Ranking | Contenido | Tasa de guardados | Vistas |
|---------|-----------|-------------------|--------|
| 1 | Built with Opus 4.6 | 0.47% | 1.0M |
| 2 | Code with Claude Conference | 0.35% | 1.1M |
| 3 | Hackathon | 0.34% | 1.6M |
| 4 | Crossbeam Works | 0.32% | 0.5M |
| 5 | Agent View | 0.32% | 2.3M |

**Hallazgo:** Las tasas de retweet y guardados más altas casi siempre son contenido de desarrolladores de nicho, no virales masivos. Esto indica:
- Los virales masivos (77.9M Computer Use) no tienen tasas destacadas de retweet ni guardados — la gente lo vio, se asombró, y se fue
- El contenido de desarrolladores (0.1M-2M) tiene las tasas más altas de retweet y guardados — la gente lo vio, lo guardó, lo compartió con colegas

**Dos estándares de éxito:**
- **Exposición de marca:** Ver vistas y volumen absoluto de retweets → Computer Use (77.9M, 14,467 rt)
- **Impacto profundo:** Ver tasa de guardados y tasa de respuestas → Agent View (0.32% bm, 686 replies)

### 12.7 Puntuación de interacción compuesta: evaluación ponderada

Asignando diferentes pesos a diferentes comportamientos de interacción (guardados = 3x, respuestas = 5x, retweets = 2x, likes = 1x), se calcula la puntuación compuesta:

```
Puntuación = (likes + bookmarks×3 + retweets×2 + replies×5) / views × 100
```

**Top 5 de interacción compuesta:**

| Ranking | Contenido | Puntuación | Vistas | L | B | RT | R |
|---------|-----------|------------|--------|---|---|----|---|
| 1 | Built with Opus 4.6 | 2.70% | 1.0M | 9.9K | 4.9K | 800 | 370 |
| 2 | Code with Claude Conference | 2.39% | 1.1M | 10.8K | 3.9K | 1,057 | 460 |
| 3 | Agent View | 2.13% | 2.3M | 20.3K | 7.3K | 1,571 | 686 |
| 4 | Aniversario de Claude Code | 2.04% | 0.8M | 9.7K | 1.4K | 641 | 310 |
| 5 | Hackathon | 2.01% | 1.6M | 10.7K | 5.5K | 937 | 622 |

**Patrón:** El contenido con mayor puntuación compuesta tiene un rasgo en común — orientado a desarrolladores o eventos de comunidad. Sus vistas no son altas (0.8M-2.3M), pero cada persona que lo ve participa profundamente.

**Esto ofrece dos rutas para la estrategia de marketing:**
1. **Ruta de amplitud:** Hacer videos de funciones universales, buscar vistas y exposición de marca (Computer Use, Design, Cowork)
2. **Ruta de profundidad:** Hacer contenido de desarrolladores/comunidad, buscar tasas de guardados y discusión (Agent View, Hackathon, Built with Opus 4.6)

Ambas rutas deberían coexistir — la amplitud atrae nuevos usuarios, la profundidad retiene.


## 13. Comparación de Estrategias de Video con la Competencia

### 13.1 Diferencias en el lenguaje de video de las cuatro grandes empresas de IA

| Dimensión | Anthropic (Claude) | OpenAI (ChatGPT) | Google (Gemini) | Apple (Apple Intelligence) |
|-----------|-------------------|------------------|----------------|--------------------------|
| **Color principal** | Blanco cálido + terracota | Azul frío + degradado negro | Blanco + multicolor | Negro puro + blanco puro |
| **Emoción** | Académico, cálido, reflexivo | Tecnológico, cool, vanguardista | Vibrante, amigable, masivo | Minimalista, premium, contenido |
| **Estrategia tipográfica** | Títulos serif (sensación editorial) | Sans-serif (sensación tecnológica) | Google Sans (sensación de marca) | SF Pro (sensación de sistema) |
| **Exhibición de UI** | Modo oscuro constante | Mezcla claro/oscuro | Mayormente brillante | Sigue el sistema |
| **Persona en cámara** | Muy rara (1/78) | Ocasional | Frecuente | Nunca |
| **Estilo narrativo** | Contenido, demostrar > contar | Explicativo, sensación de tutorial | Estilo de vida, impulsado por escena | El producto es la narrativa |
| **Estilo de transición** | Hard cuts predominantes | Degradado + hard cuts | Animaciones vibrantes | Hard cuts precisos |
| **Cierre** | Sin CTA, fade-out | A veces con CTA | Con CTA | Tarjeta de marca |

### 13.2 Interpretación de la estrategia diferenciadora de Claude

**¿Por qué colores cálidos?**
El lenguaje visual predeterminado de los productos de IA es frío (azul/negro) — transmite "sensación tecnológica" e "inteligente". Anthropic va en dirección opuesta: lo cálido transmite "pensamiento", "académico", "humanista". No es una preferencia estética, es la expresión visual del posicionamiento de marca: Claude es "IA que piensa", no "máquina que calcula".

**¿Por qué casi no usa personas?**
Solo 1 de 78 videos tiene un rostro humano. Razones:
- Las personas distraen — el espectador empieza a fijarse en "esta persona" en vez de "esta función"
- La UI/texto/animación pueden cargar la personalidad de la marca por sí solos
- Sin personas = escalabilidad infinita — no se ve afectado por cambios de personal
- Excepción: cuando se necesita "transferencia de confianza" (ingeniero hablando de Opus 4.5), se introduce una persona

**¿Por qué no usa CTA al final?**
El marketing de video tradicional usa CTA ("Sign up now!") para crear urgencia. Claude no lo usa:
- CTA es una señal de "necesitamos que vengas" — reduce la energía de marca
- Fade-out a logo = "nuestro producto habla por sí solo" — aumenta la energía de marca
- Es una **señal de escasez**: cuanto menos te pide que vengas, más quieres verlo

### 13.3 "Keep Thinking" como filosofía de marca

"Keep Thinking" no es solo un slogan, es la lógica subyacente de toda la estrategia de video:
- Sin intro de logo → "No necesitamos presentarnos"
- Sin CTA final → "No necesitamos convencerte"
- UI en modo oscuro → "Trabajamos en un entorno serio"
- Apertura minimalista → "Te damos espacio para pensar"
- Animación contenida → "No interferimos con tu juicio"

Cada decisión de producción se rastrea hasta esta filosofía de marca. Este es el nivel más alto de la metodología — no es "cómo hacerlo", sino "por qué hacerlo así".

---

## 14. Psicología de la Interacción: Por Qué Estos Patrones Funcionan

### 14.1 Principio de brecha cognitiva del "menos es más"

Los dos videos con mayor visualización (77.9M y 63.5M) usaron una apertura minimalista extrema. Principio:

```
Imagen minimalista → Información insuficiente → Brecha cognitiva → El cerebro rellena automáticamente → Curiosidad → Permanencia para ver
```

Esto es la aplicación de la **Teoría de la Brecha de Información (Information Gap Theory)**:
- El cerebro odia los patrones incompletos
- Cuando la imagen solo tiene un icono diminuto + gran espacio vacío, el cerebro se ve obligado a trabajar para "entender" la imagen
- Esta inversión cognitiva crea una conexión emocional — el espectador ya "invirtió" atención, no quiere abandonar

**Práctica:** En el primer frame poner solo un elemento, sin texto. Revelar el texto 0.8-1.2s después.

### 14.2 Construcción de confianza mediante "visualización del proceso"

¿Por qué visualizar el proceso (listas de tareas, salida de terminal) genera más interacción que solo mostrar el resultado?

- **Transparencia = confianza:** Mostrar en qué "está pensando" la IA es más persuasivo que solo decir "terminé"
- **Satisfacción diferida:** El espectador ve la barra de progreso avanzar, generando expectativa de "pronto se completará"
- **Verificabilidad:** La salida de terminal, el diff de código hacen que el espectador sienta "esto es real, no es un demo"

**Práctica:** No te saltes el proceso de generación. Usa Task Sequence, indicadores de progreso, scroll de terminal para visualizar.

### 14.3 Instinto de lectura de la "narrativa espacial"

¿Por qué funciona el flujo visual de izquierda a derecha (móvil → procesamiento → escritorio)?

- La dirección de lectura del texto horizontal es de izquierda a derecha (inglés/chino horizontal)
- El cerebro interpreta "izquierda a derecha" como "relación causal" o "paso del tiempo"
- Esta línea temporal implícita reduce la carga cognitiva — no se necesita explicación adicional de "qué hacer primero y qué después"

**Práctica:** Cuando haya múltiples pasos, usa un layout espacial de izquierda a derecha para insinuar el flujo, en vez de numeración o flechas.

### 14.4 Efecto psicológico de los hard cuts

¿Por qué Claude usa casi exclusivamente hard cuts, y nunca disoluciones lentas/transiciones?

- **Hard cut = confianza:** Sin arrastrarse, insinúa "cada imagen vale la pena detenerse"
- **Disolución = incertidumbre:** La disolución insinúa "esta imagen no vale la pena, pasemos rápido"
- **Sentido del ritmo:** Los hard cuts crean sensación de tempo, como el golpe de un tambor en la música
- **Sensación moderna:** La disolución lenta es la estética de los 2000 — usarla hoy parece anticuado

---

## 15. Estrategia de Audio/Banda Sonora

### 15.1 Esquemas de audio para cinco tipos de video

| Tipo de video | Estilo de banda sonora | Voz | Referencia |
|---------------|----------------------|-----|------------|
| Animación de ritmo rápido | Electrónica/percusión sincronizada con beat | Sin voz | Cowork Launch (49.7M) |
| Demostración de producto | Música ambiental ligera | Sin voz o voice-over | Mayoría de videos de funciones |
| Terminal/developers | Mínimo o silencio | Sin voz | Agent View, Managed Agents |
| Declaración de marca | Tono único o silencio | Posiblemente con voz | "Keep Thinking" |
| En vivo/persona real | Narración de voz | Con voz | Demo en vivo de Cowork |

### 15.2 Principios de producción de audio

1. **Conservar la versión sin audio** — Primero completar la versión puramente visual sin banda sonora, luego superponer la música por separado
2. **La música no compite con la imagen** — La banda sonora es para potenciar el ritmo, no para dominar la narrativa
3. **Fade in/out al inicio y final** — Evitar que la música empiece/termine abruptamente
4. **Alineación con el beat** — En videos de ritmo rápido, los cambios de escena deben caer en el beat de la música
5. **Se puede ver en silencio** — La mayoría de reproducciones en redes sociales son en silencio, el video debe transmitir información incluso sin audio

---

## 16. Lista de Verificación Práctica

### 16.1 Verificación pre-producción

- [ ] Determinar el tipo de video (Modo A/B/C/D)
- [ ] Fijar el presupuesto de duración
- [ ] Confirmar el canal objetivo y la relación de aspecto
- [ ] Seleccionar la estrategia de apertura (minimalismo extremo / revelación de marca / producto directo / pregunta sobre dolor)
- [ ] Escribir en una frase "qué debe sentir el espectador con este video"

### 16.2 Verificación durante la producción

- [ ] Toda la UI es una versión perfecta reconstruida, no grabación de pantalla real
- [ ] Se eliminó UI innecesaria: marcos de debug, tabs extras, barras de aviso irrelevantes
- [ ] Los primeros 2 segundos tienen atracción visual
- [ ] Hay un Magic Moment dentro de los primeros 15 segundos
- [ ] Solo se usan pesos de fuente 500/600/700, con `font-synthesis: none`
- [ ] Los títulos usan sentence case con punto final
- [ ] No hay intro de logo
- [ ] El movimiento del cursor es natural (llega adelantado)
- [ ] La cámara no tiene deriva continua
- [ ] No se amplía solo un botón individual

### 16.3 Verificación post-producción

- [ ] Sin tarjeta de CTA final
- [ ] Sin hard cut a pantalla negra
- [ ] El último frame tiene la marca visible
- [ ] Se puede transmitir la información en estado silencioso
- [ ] La versión con música conserva la versión silenciosa original
- [ ] Exportación en múltiples resoluciones (4K + 1080p)
- [ ] Exportación en múltiples formatos de aspecto (16:9 + 4:5 o 1:1)

### 16.4 Estrategia de publicación

- [ ] X/Twitter: 16:9 o 1:1, los primeros 3 segundos deciden si se queda
- [ ] YouTube: 16:9, el título y la miniatura son igualmente importantes
- [ ] Instagram: 4:5 vertical, visual como prioridad
- [ ] Hora de publicación: seguir la franja horaria activa de la audiencia objetivo

---

## 17. Guía de Adaptación: Cómo Aplicarlo a Tu Propio Producto

### 17.1 Lo que puedes reutilizar directamente

| Práctica de Claude | Principio universal | Puedes usar directamente |
|--------------------|--------------------|-----------------------|
| Hard cuts como protagonistas | Contención de transiciones | Directamente |
| Sin intro de logo | Mostrar el producto en los primeros 2 segundos | Directamente |
| Sin CTA final | Terminar con el contenido | Directamente |
| Títulos en sentence case con punto | Copy con sensación conversacional | Directamente |
| Pesos de fuente 500/600/700 | Estabilidad tipográfica | Directamente |
| Task Sequence | Visualización de procesos | Directamente |
| Escenas de 3-8 segundos | Ritmo compacto | Directamente |
| Lista de anti-patrones | Evitar errores comunes | Directamente |

### 17.2 Lo que necesita adaptación

| Práctica de Claude | Por qué no se puede copiar tal cual | Cómo adaptar |
|--------------------|-------------------------------------|-------------|
| Paleta blanco cálido + terracota | Son los colores de marca de Claude | Cambiar a tu color de marca principal, pero mantener la relación jerárquica de "lienzo cálido + UI oscura" |
| Modo oscuro constante | Tu producto puede tener UI clara | Mantener el brillo/oscuro real de tu producto, solo usar cálido en el lienzo exterior |
| Fuente serif para títulos | Tu marca puede no ser adecuada para serif | Usa tu propia fuente de marca, pero mantén la jerarquía de "título grande + cuerpo pequeño" |
| Composición de mockups de dispositivos | Requiere capacidad de renderizado 3D | Degradar a capturas de pantalla + sombras, el resultado es un poco inferior pero la barrera de entrada es mucho menor |
| Apertura minimalista extrema | Requiere reconocimiento de marca como soporte | Si tu marca no es conocida, primero pon el nombre de la función y luego haz el minimalismo |

### 17.3 Filosofía central

No imites la "apariencia" de Claude, imita la "lógica de decisión" de Claude:

- **¿Por qué colores cálidos?** → Porque la competencia usa colores fríos, diferenciación
- **Tu versión:** Encuentra un lenguaje de color que la competencia no use

- **¿Por qué no usar personas?** → Porque la UI misma puede contar la historia
- **Tu versión:** Si tu UI no es lo suficientemente atractiva, primero arréglala y luego haz el video

- **¿Por qué no usar CTA?** → Porque la energía de marca es suficientemente alta
- **Tu versión:** Si la marca no es conocida, un CTA moderado es razonable

- **¿Por qué hard cuts como protagonistas?** → Porque cada imagen tiene valor
- **Tu versión:** Si alguna escena no aguanta 3 segundos, acórtala o elimínala

**La esencia de la metodología no es una lista de reglas, sino "cada decisión debe tener una razón".**

## Apéndice A: Referencia Rápida de Tipos de Video

| Lo que necesitas hacer | Qué marco usar | Duración | Video de referencia |
|------------------------|----------------|----------|---------------------|
| Lanzar una nueva función | Modo A: Anuncio estándar de función | 30-60s | Opus 4.6, Code Review |
| Anunciar una integración | Modo B: Escaneo de ecosistema | 30-50s | Excel/PowerPoint, Work Tools |
| Anuncio breve/evento | Modo C: Tarjeta social ultra-corta | 8-15s | Thank You, Remote Control |
| Función orientada a desarrolladores | Modo D: Demo profunda para developers | 60-90s | Managed Agents, Agent View |
| Declaración de marca/posicionamiento | Variante del Modo C | 10-60s | "Keep Thinking", "Ads" |

## Apéndice B: Plantilla de Video de Función de 30 Segundos

| Tiempo | Contenido | Animación |
|--------|-----------|-----------|
| 0-3s | Icono minimalista + revelación del nombre de función | Icono con scale bounce-in + texto fade-in |
| 3-7s | Problema/contexto | Barra de anotación captionAt() |
| 7-18s | Demo del producto | clickAt() × 2-3, showPreviewAt() |
| 18-25s | Magic Moment | Task Sequence (líneas pasando a verde) |
| 25-28s | Estado del resultado | Panel showRightAt() |
| 28-30s | Cierre con logo | Final Card (versión simplificada) |

## Apéndice C: Plantilla de Video de Función de 60 Segundos

| Tiempo | Contenido | Animación |
|--------|-----------|-----------|
| 0-3s | Apertura minimalista (icono en espacio negativo) | Icono scale bounce-in |
| 3-8s | Nombre de función + contexto | cameraTo() + captionAt() |
| 8-20s | Operación del usuario (2-3 pasos) | clickAt() × 2-3 |
| 20-40s | Procesamiento del sistema (Magic Moment) | Task Sequence + Pulse breathing |
| 40-50s | Exhibición del resultado | showPreviewAt() + Staggered Reveal |
| 50-55s | Verificación/prueba secundaria | Panel showRightAt() |
| 55-60s | Cierre con logo | Final Card

---
