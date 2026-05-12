# Como a Anthropic faz vídeos que alcançam 78M de visualizações

Análise sistemática de 77 vídeos oficiais de produto da Claude (out 2025 – mai 2026). Metodologia extraída, sistema de design, frameworks narrativos e padrões de engajamento.

 **Languages:** [English](README.md) · [中文](README.zh.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · [Français](README.fr.md) · [**Português**](README.pt.md)

---

<details>
<summary><b>Table of Contents</b></summary>

- [5 grandes insights](#5-grandes-insights)
- [Insights baseados em dados](#insights-baseados-em-dados)
- [Fórmula de produção (versão TL;DR)](#fórmula-de-produção-versão-tldr)
- [Posicionamento competitivo](#posicionamento-competitivo)
- [Adapte ao seu produto](#adapte-ao-seu-produto)

- [1. Pipeline de Produção](#1-pipeline-de-produção)
- [2. Sistema de Design](#2-sistema-de-design)
- [3. Frameworks Narrativos](#3-frameworks-narrativos)
- [4. Transições e Gramática de Animação](#4-transições-e-gramática-de-animação)
- [5. Hook Architecture (Os primeiros 3 segundos decidem tudo)](#5-hook-architecture-os-primeiros-3-segundos-decidem-tudo)
- [6. Motor de Ritmo](#6-motor-de-ritmo)
- [7. Fórmulas de Engajamento](#7-fórmulas-de-engajamento)
- [8. Guia de Níveis de Produção](#8-guia-de-níveis-de-produção)
- [9. Checklist de Anti-Padrões](#9-checklist-de-anti-padrões)
- [10. Análise de Evolução Temporal: 18x mais reproduções em 8 meses](#10-análise-de-evolução-temporal-18x-mais-reproduções-em-8-meses)
- [11. Análise de Popularidade: Por que o Top 10 Explodiu](#11-análise-de-popularidade-por-que-o-top-10-explodiu)
- [12. Análise Multidimensional Orientada por Dados](#12-análise-multidimensional-orientada-por-dados)
- [13. Comparação de Estratégias de Vídeo com Concorrentes](#13-comparação-de-estratégias-de-vídeo-com-concorrentes)
- [14. Psicologia de Engajamento: Por que Esses Padrões Funcionam](#14-psicologia-de-engajamento-por-que-esses-padrões-funcionam)
- [15. Estratégia de Áudio/Trilha Sonora](#15-estratégia-de-áudiotrilha-sonora)
- [16. Checklist Prático](#16-checklist-prático)
- [17. Guia de Adaptação: Como Usar no Seu Próprio Produto](#17-guia-de-adaptação-como-usar-no-seu-próprio-produto)
- [Apêndice A: Referência Rápida de Tipos de Vídeo](#apêndice-a-referência-rápida-de-tipos-de-vídeo)
- [Apêndice B: Template de Vídeo de Funcionalidade 30s](#apêndice-b-template-de-vídeo-de-funcionalidade-30s)
- [Apêndice C: Template de Vídeo de Funcionalidade 60s](#apêndice-c-template-de-vídeo-de-funcionalidade-60s)

</details>


## 5 grandes insights

### 1. Eles nunca gravam telas reais — reconstróem UIs perfeitas

Cada "captura de tela" em um vídeo da Claude é fabricada. Mockups de UI pixel-perfect compostos sobre molduras de dispositivo renderizadas em 3D (MacBooks, iPhones, monitores), flutuando sobre fundos quentes. Sem chrome do navegador, sem barra de favoritos, sem badges de notificação.

**Por que funciona:** Elimina o ruído visual. Cada frame é brand-safe. Sem abas acidentais, sem favoritos constrangedores, sem elementos de UI desatualizados quando o produto lança uma atualização na semana seguinte.

### 2. O hook "menos é mais" é o padrão de melhor desempenho

Os dois vídeos mais assistidos (77.9M e 63.5M) abrem da mesma forma: um ícone minúsculo em um vasto fundo quente. Sem texto. Sem animação. Apenas espaço negativo e um ponto focal único.

Isso cria uma **lacuna cognitiva** — o cérebro não consegue processar o frame instantaneamente, então investe atenção para decifrá-lo. Quando o nome do produto aparece aos 0.8–1.2s, o espectador já está fisgado.

O vídeo de 10 segundos que alcançou 10M de visualizações? Mesmo princípio. Minimalismo extremo. Um elemento. Pronto.

### 3. Sem intro de logo, sem CTA final — nunca

Em 77 vídeos:
- **0** começam com animação de logo
- **0** terminam com "Cadastre-se agora!" ou qualquer call-to-action

É posicionamento de marca deliberado. Um intro de logo diz "precisamos nos apresentar". Um CTA diz "precisamos de você". Claude não faz nenhum dos dois — o produto aparece no frame 1, e o vídeo desaparece para um logo silencioso em fundo quente.

A mensagem: *nosso produto não precisa se vender.*

### 4. "Mostrar o pensamento, não apenas o resultado" impulsiona o engajamento

Vídeos que visualizam o processo da IA — listas de tarefas marcando verde, comandos de terminal rolando, grafos de nós se expandindo — consistentemente superam vídeos que mostram apenas o resultado final.

Não é apenas um truque de produção. É **arquitetura de confiança.** Mostrar o processo faz a IA parecer menos uma caixa preta. O espectador pode verificar: "sim, ela realmente fez esses passos".

O exemplo mais extremo: Computer Use (77.9M) mostra a Claude navegando em um SO real, app por app. Não simulado. Não acelerado demais. Cursor real, cliques reais, hesitação real.

### 5. Apenas hard cuts — zero transições elaboradas

Em 77 vídeos:
- ~60% hard cuts entre cenas
- ~15% fade para fundo quente
- ~10% slide-ins
- ~0% dissolves, morphs, flips 3D, efeitos de partículas

Cada transição dura menos de 2 segundos. Sem dissolves cinematográficas. Sem transições de motion graphics chamativas. A filosofia: se cada frame vale a pena ser visto, você não precisa se desculpar por cortar para ele.

---

## Insights baseados em dados

### "Introducing" vale 5x mais que "now available"

Vídeos que anunciam algo novo ("Introducing Claude Cowork") têm média de **23.6M de visualizações**. Vídeos que estendem algo existente ("Claude is now available in Excel") têm média de **4.6M**. A palavra "Introducing" não é apenas copy — é sinal de "nova espécie" vs "atualização de versão".

### 60–90 segundos é o sweet spot — depois despenca

| Duração | Visualizações médias |
|---------|---------------------|
| <15s | 3.0M |
| 30–60s | 7.3M |
| **60–90s** | **15.6M** |
| >90s | 2.9M |

60–90s dá espaço suficiente para um arco narrativo completo (hook → demo → mágica → resultado). Menos de 30s parece incompleto. Mais de 90s perde atenção. O sweet spot é estreito, mas real.

### Lançamento em pulso, não gotejamento constante

77 vídeos em 222 dias = 1 a cada 2.9 dias em média. Mas 77% dos dias têm zero lançamentos. A Anthropic usa **campanhas de rajada** — janelas de 3–5 dias com 2–3 vídeos por dia, depois períodos de silêncio.

O mais extremo: fevereiro de 2026 teve 23 vídeos em um mês (30% do total), concentrados em torno dos lançamentos de Opus 4.6 e Cowork. O dia mais produtivo: 20 de fevereiro — 7 vídeos em 24 horas.

**Por que o pulso funciona:** algoritmos de plataforma recompensam a concentração temática. Uma rajada de vídeos relacionados cria uma percepção de "Claude está em todo lugar" que um gotejamento constante não consegue igualar.

### Amplitude vs profundidade: dois jogos distintos

- **Jogo de amplitude** (exposição de marca): Computer Use — 77.9M visualizações, 14,467 retweets. Milhões viram, poucos salvaram.
- **Jogo de profundidade** (lealdade de desenvolvedores): Agent View — 2.3M visualizações, mas 0.32% de taxa de bookmark e 686 replies. Menos espectadores, mas cada um profundamente engajado.

Ambos importam. Amplitude constrói a marca. Profundidade constrói a comunidade. A Anthropic executa ambas as trilhas simultaneamente.

### Segunda-feira é o dia de lançamento

| Dia | Visualizações médias |
|-----|---------------------|
| **Segunda** | **12.6M** |
| Sexta | 9.4M |
| Ter–Qui | 4.7–5.5M |

Posts na segunda surfam a onda de atenção do fim de semana para o dia útil. Posts na sexta obtêm amplificação no fim de semana.

---

## Fórmula de produção (versão TL;DR)

```
Lienzo quente (#FBFAF6) + UI escura (#1A1A2E) + Acento terracota (#D67C64)
+ UI perfeita reconstruída sobre mockups de dispositivo 3D
+ Títulos serif em sentence case com ponto.
+ Hard cuts. Sem intro de logo. Sem CTA.
+ Task sequence para "magic moments"
+ Hook em 0–3s. Magic moment antes de 15s.
= Vídeo da Claude.
```

---

## Posicionamento competitivo

| | Claude | ChatGPT | Gemini | Apple Intelligence |
|---|--------|---------|--------|-------------------|
| Cor | Branco quente + terracota | Azul frio + gradiente preto | Branco + multicolorido | Preto puro + branco puro |
| Clima | Acadêmico, quente, reflexivo | Tech, cool, ponta | Amigável, consumidor | Minimal, premium |
| Tipografia | Títulos serif (editorial) | Sans-serif (tech) | Google Sans (marca) | SF Pro (sistema) |
| Humanos na tela | 1 em 77 | Às vezes | Frequentemente | Nunca |
| CTA final | Nunca | Às vezes | Sempre | Cartão de marca |

---

## Adapte ao seu produto

**Empreste diretamente:** hard cuts, sem intro de logo, sem CTA, títulos em sentence case com pontos, pesos de fonte 500/600/700, task sequences, cenas de 3–8s, lista de anti-padrões, cadência de lançamento em pulso, sweet spot de 60–90s.

**Adapte à sua marca:** sistema de cores (use suas cores de marca, mas mantenha a hierarquia lienzo quente + UI escura), tipografia (use sua fonte de marca, mas mantenha a hierarquia de tamanhos), mockups de dispositivo (use capturas com sombras se não puder fazer renders 3D).

**O princípio subjacente:** cada decisão de produção deve ter um motivo. As escolhas da Claude não são estética arbitrária — são estratégia de marca expressa através de movimento. Copie o raciocínio, não os pixels.

---

# Metodologia de Produção de Vídeos do Produto Anthropic Claude

Análise sistemática de 77 vídeos oficiais de @claudeai (2025-10 a 2026-05).
Cobrindo Pipeline de Produção, Sistema de Design, Frameworks Narrativos, Gramática de Animação, Motor de Ritmo e Fórmulas de Engajamento.

---

## 1. Pipeline de Produção

### 1.1 6 Etapas do Conceito ao Lançamento

```
Brief → Storyboard → UI Fabrication → Animation → Audio → Delivery
```

**Etapa 1: Brief (Resumo Criativo)**
- Definir o tipo de vídeo (ver Capítulo 3: Frameworks Narrativos)
- Fixar o orçamento de duração: 30s / 60s / 90s / 10s short card
- Confirmar o canal: X/Twitter (16:9 ou 1:1), YouTube (16:9), Instagram (4:5)
- Escolher a estratégia de abertura (ver Capítulo 5: Hook Architecture)

**Etapa 2: Storyboard**
- Não se faz storyboard desenhado à mão tradicional — as cenas são organizadas diretamente em ferramentas de UI mockup
- Cada cena anota: timecode, descrição de conteúdo, tipo de animação, forma de transição
- Abordagem do Claude: granularidade de cena muito fina (3-8s/cena), cada cena faz apenas uma coisa

**Etapa 3: UI Fabrication (Fabricação de Interface)**
- **Princípio central: não gravar tela real, reconstruir UI perfeita**
- Reconstruir interfaces do produto em nível de pixel com Figma/Sketch/After Effects
- Eliminar todo ruído: tabs irrelevantes, caixas de debug, barras de aviso extras, dados sujos de dados reais
- Mockups de dispositivos em renderização 3D (iPhone, MacBook, monitores), com sombras sutis
- Este é o maior ponto diferencial dos vídeos da Anthropic em relação à concorrência: cada frame é perfeito

**Etapa 4: Animation (Animação)**
- Todo movimento vem de animação de conteúdo, não de movimento de câmera
- Transições entre cenas priorizam hard cut; transições complexas (<2s) são usadas ocasionalmente
- Simulação de movimento do cursor — definir ponto de partida, 0.46s opacity 0→1, voando ao destino, click pulse
- Task Sequence entrando linha por linha, mudança de estado de cor, check

**Etapa 5: Audio (Áudio)**
- Vídeos de animação de ritmo acelerado: trilha eletrônica/percussiva sincronizada ao beat
- Demonstração de produto: música ambiente leve
- Vídeos de terminal/developer: música mínima ou nenhuma
- Declarações de marca: silêncio ou tom único
- Preservar a versão silenciosa original, depois exportar separadamente a versão com música

**Etapa 6: Delivery (Entrega)**
- Exportar em múltiplas resoluções: 4K (3840x2160) para flagship, 1080p para rotina
- Múltiplos aspect ratios: 16:9 horizontal como principal, 4:5 vertical / 1:1 quadrado para social
- Padrão de nome de arquivo: `YYYY-MM-DD-slug-keyword.mp4`

### 1.2 Duas Trilhas de Produção

| Trilha | Investimento | Características | Uso Típico |
|--------|-------------|-----------------|------------|
| **Oficial Premium** | Alto | 4K, UI simulada, mockup de dispositivo composto, motion graphics | Lançamentos de produto, funcionalidades importantes |
| **Comunidade/Ao Vivo** | Baixo | Gravação de tela crua, pessoas reais em cena, pós-produção mínima | Hackathons, eventos comunitários, demonstrações reais |

As duas trilhas operam em paralelo. Conteúdo ao vivo ocasionalmente alcança o maior engajamento (demo ao vivo do Cowork 14.6M), porque o "realismo" em si é um recurso escasso.

---

## 2. Sistema de Design

### 2.1 Sistema de Cores: "Inteligência Quente"

```
Fundo do canvas:    #FBFAF6 ~ #F5F0E8  branco quente/creme (não branco puro)
Superfície do produto: #1A1A2E ~ #2D2D3D  carvão de modo escuro
Cor de destaque primária:  #D67C64  terracota/laranja queimado
Cor de destaque secundária: #4ECDC4  azul-verde/ciano
Texto escuro:  #0F172A / #1A1A1A
Texto claro:   #FFFFFF / #E0E0E0
```

**Intenção do design:**
- Branco quente != branco puro. Branco quente cria textura "papel", mais refinado que o branco puro, mais suave que o branco puro
- A cor terracota é o elemento visual de identificação mais imediata — reconhecer Claude em um segundo
- UI em modo escuro = insinuação de "premium", "técnico", "foco"
- Distanciamento geral do azul frio/preto gradiente dos concorrentes (OpenAI/Google) e do preto e branco puro (Apple)
- Quente + inteligência = sensação acadêmica, não corporativa

**Diferenciação de posicionamento com concorrentes:**
- OpenAI: azul frio + preto gradiente → tech/frio
- Google: branco + multicolorido → vibrante/consumo
- Apple: preto puro + branco puro → minimalista/premium de consumo
- Claude: branco quente + terracota + UI escura → acadêmico/reflexivo/quente

### 2.2 Sistema de Tipografia

| Uso | Estilo de Fonte | Peso | Características |
|-----|----------------|------|-----------------|
| Cards de título/marca | Serifa de alto contraste (estilo Editorial New) | 700 | Sentence case com ponto final |
| Labels de UI/corpo | Sem-serifa geométrica (Inter/SF Pro) | 500-600 | Limpo e legível |
| Código/terminal | Monoespaçada (JetBrains Mono) | 400-500 | Syntax highlighting |
| Labels em caixa alta | Sem-serifa | 600 | "PROGRESS", "CONTEXT" |

**Detalhes-chave:**
- Títulos usam sentence case, não Title Case
- Títulos terminam com ponto final — criam sensação de conversação e confiança: "Claude now integrates."
- Pesos usados apenas 500 / 600 / 700, negrito sintético proibido (`font-synthesis: none`)

### 2.3 Linguagem de Device Mockup

O device mockup é o dispositivo visual mais central, não decoração:

```
┌─────────────────────────┐
│                         │
│   ┌─────────────────┐   │
│   │  [UI do Produto] │   │  ← Moldura de dispositivo renderizada em 3D
│   │  Interface modo  │   │     com sombra sutil
│   │  escuro          │   │     box-shadow: 0 8px 32px rgba(0,0,0,0.12)
│   └─────────────────┘   │
│                         │  ← Canvas branco quente/creme
└─────────────────────────┘
```

**Três composições para exibir múltiplas telas simultaneamente:**

**A. Dispositivo Centralizado** — foco único, ideal para anúncios de funcionalidade
**B. Layout Split-Screen** — Agent à esquerda + aplicativo de destino à direita, ideal para demonstrações de integração
**C. Narrativa Espacial** — celular → conexão doodle → desktop, ideal para fluxos entre dispositivos

---

## 3. Frameworks Narrativos

### 3.1 Quatro Modos Narrativos Centrais

#### Modo A: Anúncio de Funcionalidade Padrão (30-60s) — Mais Utilizado

```
Hook    (0-3s)   Nome da funcionalidade/ícone revelado em fundo quente
Context (3-8s)   Apresentar o problema ou necessidade do usuário
Action  (8-15s)  Usuário dispara ação (clique/input)
Demo    (15-45s) Demonstração animada do produto (conteúdo central)
Magic   (30-50s) Sistema completa automaticamente (Task Sequence/visualização de progresso)
Result  (45-55s) Exibir estado de conclusão
Close   (55-60s) Logo + fundo quente de encerramento
```

Aplicação: maioria dos lançamentos de funcionalidade. Representa ~60% dos 77 vídeos.

#### Modo B: Scan de Ecossistema (30-50s)

```
Hook  (0-3s)   "[Produto] se conecta a [ferramenta/workflow]"
Setup (3-8s)   Exibir aplicativo de destino (Slack/Excel/Figma)
Flow  (8-35s)  Alternar entre múltiplos apps, mostrar fluxo de dados
Proof (35-45s) Estado final do resultado
Close (45-50s) Logo
```

Aplicação: anúncios de integração, demonstrações de parceria. O dispositivo visual principal é split-screen + disparo via @mention.

#### Modo C: Short Card Social (8-15s)

```
Cena única: fundo de marca + texto animado/ícone reveal
Sem demonstração de produto, pura informação de marca/anúncio
```

Aplicação: promoção de eventos, anúncios breves, declarações de marca. "Thank You" (8.2s, 12.7M visualizações) segue este modo.

#### Modo D: Demonstração Profunda para Desenvolvedores (60-90s)

```
Hook        → Terminal já está rodando (narrativa inversa)
Setup       → Usuário digita comando avançado
Execution   → Saída do terminal + preview em split-screen
Magic       → Árvore de tarefas se expande, múltiplas sub-tarefas em paralelo
Result      → Estado de conclusão + interface de auditoria/rastreamento
Close       → Card de marca
```

Aplicação: funcionalidades técnicas voltadas a desenvolvedores. Estética de terminal, fonte monoespaçada, diff de código destacado.

### 3.2 Cinco Variantes Narrativas Especiais

| Variante | Vídeo Representativo | Visualizações | Técnica Central |
|----------|---------------------|---------------|-----------------|
| Comando e Execução | Computer Use | 77.9M | Esquerda para direita: celular → fluxo de processamento → desktop |
| Reveal de Galeria | Claude Design | 63.5M | Reveal progressivo do abstrato ao complexo |
| Narrativa de Terminal | Managed Agents | 21.6M | Contar história através de comandos CLI e saída |
| Momento de Gratidão | Thank You | 12.7M | Resonância emocional minimalista em 8.2s |
| Scan de Ecossistema | Office GA | 27.7M | Apresentar sequencialmente Excel → PowerPoint → Word |

### 3.3 Regras Inflexíveis de Abertura e Encerramento

**Abertura:**
- Sem logo intro — o produto é exibido nos primeiros 2 segundos
- Os primeiros 2 segundos devem ter apelo visual
- 50% fundo de marca + fade-in de texto, 30% materialização de janela UI

**Encerramento:**
- Sem hard cut para tela preta
- Não usar card de CTA tradicional de encerramento (na vasta maioria)
- Terminar com o conteúdo ou fundo quente + logo fade-out
- Reforçar posicionamento de marca "premium e confiante"

---

## 4. Transições e Gramática de Animação

### 4.1 Regras de Transição

**Regra inflexível: hard cut como protagonista, zero transições elaboradas.**

| Tipo de Transição | Frequência de Uso | Cenário |
|-------------------|-------------------|---------|
| Hard cut | ~60% | Método principal de alternância entre cenas |
| Fade para fundo quente | ~15% | Encerramento de marca, mudança de ritmo |
| Slide (horizontal/vertical) | ~10% | Expansão de painel, sidebar |
| Draw animation | ~5% | Reveal de ícone, conexão de traços |
| Zoom para UI | ~5% | Do overview ao detalhe |
| Dissolve/slow fade-in | ~0% | **Nunca utilizado** |

Todas as transições são controladas em até 2 segundos. Sem flip 3D, morph, efeitos de partícula.

### 4.2 Vocabulário Central de Animação

**Simulação de Cursor (Cursor Simulation)**
```
Timeline:
  -0.46s: Definir ponto de partida, opacity: 0→1
  -0.38s: Voando ao destino, ease: power3.out
   0.00s: Chegada, animação clickPulse
  +0.12s: Leve escala (yoyo)
  +0.82s: Cursor fade-out
```
Essencial: o cursor deve "chegar antecipadamente", sem hesitação.

**Task Sequence — o Coração do Magic Moment**
```
Entrada  → Elemento desliza de baixo, opacity: 0→1, 0.28s
Cor      → Círculo de estado muda de cinza para verde, 0.16s
Check    → Marca de verificação aparece, 0.10s
```
Cada linha de tarefa tem timing independente, com possibilidade de stagger (0.05s).

**Entrada de Modal (Modal Entrance)**
```
Início: y:34, scale:0.965, opacity:0
Animação: y→0, scale→1, opacity→1, 0.42s, ease: back.out(1.35)
```

**Revelação Escalonada (Staggered Reveal)**
```
y:16 → y:0, opacity: 0→1, 0.28s, stagger: 0.05s
```
Utilizado para listas de integração, listas de arquivos, cards de ferramentas.

**Animação de Desenho (Draw-on)**
```
SVG stroke-dasharray:
  strokeDashoffset: 200 → 0, 0.8s, ease: power2.inOut
```
Uso: doodle manuscrito conectando duas áreas de UI, ícone de wireframe para preenchido.

### 4.3 Regras de Movimento de Câmera

**Padrão: imagem estável, sem drift contínuo.**

Movimento de câmera usado apenas com propósito narrativo claro:
- Pan/zoom global focando área do produto, duração 0.3-0.6s
- Zoom na imagem inteira ou região do produto, não ampliar apenas um botão
- Após a câmera chegar, manter estável para que o texto e estado da UI sejam legíveis
- Entre cenas, priorizar hard cut, troca de camadas, entrada de animação de conteúdo

---

## 5. Hook Architecture (Os primeiros 3 segundos decidem tudo)

### 5.1 Cinco Estratégias de Abertura

| Estratégia | Técnica | Efeito | Vídeo Representativo |
|-----------|---------|--------|---------------------|
| **Minimalismo Extremo** | Espaço negativo enorme + ícone minúsculo | Maior curiosidade, maior taxa de retenção | Computer Use (77.9M), Design (63.5M) |
| **Reveal de Marca** | Fundo quente + fade-in de elementos | Contido, premium, consistente | Maioria dos vídeos de funcionalidade padrão |
| **Produto Direto** | Screenshot de UI ou device mockup direto | Sem enrolação, orientado à eficiência | Cowork Windows, Chrome |
| **Pergunta de Dor** | Texto levantando problema do usuário | Guiado por empatia | "Tired of tedious work?" |
| **Declaração Ousada** | Declaração de marca ou posicionamento | Propagação por controvérsia | "Keep Thinking" (5.2M) |

### 5.2 Hook "Menos é Mais" — O Modelo Mais Poderoso

Os dois vídeos com maior visualização (77.9M e 63.5M) usaram a mesma estratégia:

1. Primeiro frame: fundo quente com um elemento minúsculo (ícone de cursor/ícone wireframe)
2. Nenhum texto — forçar o espectador a parar e "decodificar" o que é
3. Segundo beat (0.8-1.2s depois): reveal do texto com o nome da funcionalidade

**Princípio:** Minimalismo extremo → Lacuna cognitiva → Curiosidade → Permanência → Conclusão de visualização.

---

## 6. Motor de Ritmo

### 6.1 Regras de Duração de Cena

| Tipo de Vídeo | Duração por Cena | Sensação de Ritmo |
|---------------|-----------------|-------------------|
| Demonstração longa (60-96s) | 4-8s/cena | Mensurado, estilo tutorial |
| Demonstração média (40-60s) | 3-5s/cena | Velocidade média, estilo narrativo |
| Anúncio curto (<20s) | 2-3s/cena | Rápido, impactante |
| Short card social (<12s) | Cena única | Mínimo |

### 6.2 Relação entre Duração e Engajamento

**Descoberta contra-intuitiva: a duração em si não determina o engajamento.**

- Os vídeos com maior engajamento são de 73s (Computer Use) e 81.5s (Design)
- Um vídeo de 10 segundos alcançou 10M visualizações (Remote Control)
- Um vídeo de 96 segundos teve apenas 12.5M (Excel/PowerPoint)

**O que realmente determina o engajamento:**
1. Qualidade do hook de abertura (primeiros 3 segundos)
2. Universalidade da funcionalidade (apelo interdisciplinar)
3. Ritmo narrativo (sem arrastar, cada cena com densidade de informação)
4. Refinamento visual (4K vs 1080p tem correlação, mas não causalidade)

### 6.3 Posição do Magic Moment

**O Magic Moment deve aparecer nos primeiros 15 segundos.**

O Magic Moment é o instante visualizado de "o que o sistema está realizando pelo usuário" — não um spinner de loading, mas sim:
- Tarefas completadas linha por linha (check verde)
- Arquivos gerados automaticamente
- Comandos de terminal executados autonomamente
- Dados fluindo entre múltiplos aplicativos

Se em 15 segundos não houver um momento "uau" para o espectador, ele desliza para o próximo.

---

## 7. Fórmulas de Engajamento

### 7.1 Cinco Características Compartilhadas por Vídeos de Alto Engajamento

Extraídas dos dados de 77 vídeos:

1. **Resolução 4K** — 3840x2160 tem forte correlação com altas visualizações
2. **Abertura minimalista extrema** — curiosidade como motor de retenção
3. **Funcionalidade universal** — apelo interdisciplinar, não apenas para desenvolvedores
4. **Narrativa rítmica de 70-80 segundos** — espectadores estão dispostos a ver a demonstração completa
5. **Composição espacial/horizontal de narrativa** — fluxo visual da esquerda para a direita

### 7.2 Fatores que NÃO Determinam Engajamento

- Duração em si (não é quanto mais curto melhor)
- Aspect ratio (horizontal e vertical ambos têm altos e baixos)
- Foco em desenvolvedores (Code Review 23.5M)
- Custo de produção (vídeo ao vivo 14.6M vs vídeo refinado 2M)

### 7.3 Níveis de Engajamento

| Nível | Visualizações | Proporção | Características Compartilhadas |
|-------|---------------|-----------|-------------------------------|
| Super | 50M+ | ~3% | 4K, abertura minimalista extrema, funcionalidade universal, narrativa espacial |
| Alto | 10-30M | ~15% | Produção refinada, demonstração clara de funcionalidade, narrativa forte |
| Médio | 2-10M | ~40% | Produção padrão, narrativa média |
| Baixo | <2M | ~42% | Baixa densidade de informação ou público restrito |

---

## 8. Guia de Níveis de Produção

### Tier 1: Lançamento Flagship (4K, 60-90s)

- **Cenário:** Lançamento de funcionalidades importantes, apresentação de novos produtos
- **Características:** 3840x2160, composição de device mockup, animações complexas mult Cena, trilha sincronizada ao beat
- **Ciclo de produção:** 1-2 semanas
- **Equipe:** Motion designer + UI designer + áudio

### Tier 2: Demonstração de Funcionalidade (1080p, 30-60s)

- **Cenário:** Demonstração de funcionalidade única, anúncio de integração
- **Características:** 1920x1080, layout split-screen, 3-5 cenas, trilha leve
- **Ciclo de produção:** 3-5 dias
- **Equipe:** Motion designer

### Tier 3: Short Card Social (1080p ou quadrado, 8-15s)

- **Cenário:** Anúncios, promoção de eventos, mensagem de marca
- **Características:** Cena única, animação de texto como protagonista, sem demonstração de produto
- **Ciclo de produção:** 1 dia
- **Equipe:** Motion designer (pode acumular funções)

### Tier 4: Comunidade ao Vivo (qualidade original, variável)

- **Cenário:** Hackathons, eventos comunitários, demonstrações reais de produto
- **Características:** Pós-produção mínima, pessoas reais em cena, gravação de tela crua
- **Ciclo de produção:** No mesmo dia
- **Equipe:** Equipe de produto/engenharia grava por conta própria

---

## 9. Checklist de Anti-Padrões

Extraídos da análise de 78 vídeos — coisas que o Claude NÃO fez e que você NÃO deveria fazer:

1. **Não usar entrada apenas com logo** — produto ou promessa de funcionalidade deve aparecer nos primeiros 2 segundos
2. **Não usar card de CTA no encerramento** — terminar com estado de conteúdo/produto ou marca simples
3. **Não usar transições elaboradas** — hard cut, troca de camadas, entrada de animação de conteúdo primeiro
4. **Não usar fundos gradiente decorativos** — manter o canvas contido, o produto é o protagonista
5. **Não mostrar pessoas reais sem necessidade** — apenas 1 dos 78 vídeos tem rosto humano
6. **Não gravar tela real** — reconstruir UI perfeita, remover todo ruído
7. **Não deixar o processo de geração de AI vazio** — deve visualizar task / progress / preview
8. **Não usar copy de marketing genérico** — usar nomes reais de funcionalidade e labels do produto
9. **Não usar câmera com drift contínuo** — apenas pan / zoom curtos e precisos
10. **Não ampliar apenas um único botão** — zoom na imagem inteira ou região do produto

---

## 10. Análise de Evolução Temporal: 18x mais reproduções em 8 meses

### 10.1 Panorama de Dados

| Período | Nº de Vídeos | Média de Reproduções | Máximo | Total |
|---------|-------------|---------------------|--------|-------|
| 2025 Q4 | 21 | **0.7M** | 2.7M | 14M |
| 2026 Q1 | 41 | **9.1M** | 77.9M | 373M |
| 2026 Q2 | 15 | **12.6M** | 63.5M | 190M |

A média de reproduções aumentou 18x em 8 meses. Isso não é sorte de um viral — é a metodologia iterando.

### 10.2 Mudanças Qualitativas em Três Fases

#### 2025 Q4 — "Conseguimos fazer vídeos"

Período inicial. Produção tosca, mas estabeleceu a linguagem base:
- Janelas de aplicativo flutuantes em fundo de marca (como animação de PowerPoint)
- Cor terracota + modo escuro estabelecidos como padrão
- Títulos em serifa + sentence case com ponto final
- Apenas 1 vídeo com pessoa real (engenheiro do Opus 4.5)
- Máximo de 2.7M reproduções (Claude Code on Web)

**Característica: seguro — todos os vídeos pareciam iguais, como feitos a partir de um template.**

#### 2026 Q1 — "Encontramos a fórmula do viral"

Fase de mudança qualitativa:
- De janelas flutuantes para **device mockup 3D** (celular/notebook/monitor compostos em fundo quente)
- A filosofia de marca "Keep Thinking" surgiu — de vender funcionalidade para vender atitude
- Série Cowork definiu a narrativa de "workflow de AI para não técnicos"
- **Dois virais de nível evento:** Lançamento do Cowork (49.7M), Computer Use (77.9M)
- Vídeo de segurança 26.2M — a palavra "segurança" tem propagação natural
- Vídeo ao vivo (demo Cowork, 14.6M) provou que "realismo" bate "refinamento"

**Descoberta-chave: não é a produção que quanto mais refinada melhor, é a narrativa que quanto mais forte melhor.**

#### 2026 Q2 — "Menos é mais" foi validado

A evolução da fase final é de subtração:
- Abertura minimalista extrema se tornou o Hook mais forte (Computer Use com apenas um ícone de cursor + vasto espaço vazio)
- Claude Design (63.5M) abriu com ícone wireframe de paleta, não dizendo o que é
- Narrativa espacial amadureceu: fluxo visual da esquerda para a direita (celular → processamento → desktop)
- Conector doodle manuscrito se tornou elemento icônico
- Office GA (27.7M) demonstrou narrativa de "scan de ecossistema"

**Insight central: quanto menos informação nos primeiros 2 segundos, mais tempo o espectador permanece.**

### 10.3 Evolução da Posição Narrativa

```
Q4 2025: "Olha, o Claude consegue fazer X"           → Explicativa
Q1 2026: "Imagine, você só precisa dizer uma frase"   → Demonstrativa
Q2 2026: "(mostrar silenciosamente, sem falar)"        → Sugestiva
```

De "explicativa" para "demonstrativa" para "sugestiva" — energia de marca cada vez maior, vídeos cada vez mais silenciosos.

### 10.4 Análise de Ritmo de Publicação: Estratégia de Publicação em Pulso

**Dados globais: 77 vídeos, 222 dias, média de 1 a cada 2.9 dias.**

Mas a "média" é enganosa — as publicações da Anthropic não são uniformemente distribuídas, mas sim em pulso denso + intervalos longos.

#### Distribuição Mensal

| Mês | Nº de Vídeos | Características |
|-----|-------------|-----------------|
| 2025-10 | 5 | Início, 1 por semana |
| 2025-11 | 5 | Estável, 1 por semana |
| 2025-12 | 11 | Aceleração, sprint de fim de ano |
| 2026-01 | 9 | Estável para alto |
| 2026-02 | **23** | **Mês de explosão — 30% do total** |
| 2026-03 | 9 | Recuo, mas mantém nível alto |
| 2026-04 | 10 | Estável |
| 2026-05 | 5 | Início do mês até o momento (dados até 10 de maio) |

**Fevereiro de 2026 é o ponto de inflexão** — 23 vídeos em um mês, 30% de todos os 77. Não é coincidência: lançamento do Opus 4.6, disponibilização do Sonnet 4.6, promoção intensiva da série Cowork, hackathon — tudo concentrado neste mês.

#### Apenas 51 dos 222 dias tiveram publicação de vídeo

Isso significa que **77% dos dias são "dias vazios"** — sem publicação de nenhum vídeo. A densidade de publicação não é linear, mas pulsada.

#### Três Campanhas de Publicação Intensiva

| Campanha | Período | Dias | Nº de Vídeos | Conteúdo Principal |
|----------|---------|------|-------------|-------------------|
| Semana de lançamento do Opus 4.6 | 2-6 de fevereiro | 5 dias | 9 vídeos | Opus 4.6, Sonnet 4.6, matriz de funcionalidades |
| Semana de promoção do Cowork | 17-20 de fevereiro | 3 dias | 10 vídeos | Série de funcionalidades Cowork, demo ao vivo, 7 vídeos em 20/02 |
| Semana flagship do Q1 | 23-25 de março | 3 dias | 3 vídeos | Computer Use (77.9M), Design (63.5M), total 93.1M |

**A terceira campanha foi a mais extrema** — 3 vídeos em 3 dias, mas 93.1M de reproduções totais. Validação perfeita de qualidade > quantidade.

#### Maiores Intervalos

| Intervalo | Duração | Período |
|-----------|---------|---------|
| Maior | 28 dias | 2025-10-28 → 2025-11-25 |
| Segundo maior | 19 dias | 2025-12-29 → 2026-01-17 |
| Terceiro | 14 dias | 2025-11-11 → 2025-11-25 |

Esses longos intervalos aparecem no início (Q4 2025), indicando que a equipe ainda estava descobrindo o ritmo. De 2026 Q1-Q2, o maior intervalo encurtou para 7-10 dias.

#### Lógica de Fundo da Estratégia de Pulso

```
Período normal: 1-2 vídeos por semana, manter presença de marca
     ↓
Lançamento de produto: 3-5 dias intensivos, 2-3 vídeos por dia, criar densidade de informação
     ↓
Período de resfriamento: voltar ao ritmo normal
```

**Por que usar pulso em vez de publicação uniforme?**

1. **Efeito algoritmo** — algoritmos de redes sociais recompensam "concentração de tópico", múltiplos vídeos em curto tempo = mais feeds
2. **Densidade narrativa** — uma grande funcionalidade com 3-5 vídeos de diferentes ângulos cobre mais que um único vídeo
3. **Ritmo da equipe** — produção de vídeo é trabalho em lote, fazer um lote de uma vez é mais eficiente que um pouco por dia
4. **Percepção do usuário** — "Claude está por toda parte ultimamente" tem mais impacto que "1 por semana estável"

**Insight prático:** Não busque publicar um vídeo por dia. Acumule um lote, publique intensivamente em 3-5 dias, depois volte ao ritmo silencioso. Pulso > Uniforme.

#### Análise de Horário de Publicação (preciso por hora, fuso PST)

Horários de publicação extraídos com precisão do snowflake ID de 77 tweets, estatísticas por Pacific Standard Time (PST):

**Distribuição por faixa de horário de publicação:**

| Faixa (PST) | Nº de Vídeos | Média de Reproduções | Significado |
|-------------|-------------|---------------------|-------------|
| Madrugada 0-6h | 10 | **13.1M** | Publicação agendada antecipadamente |
| Manhã 6-9h | 33 | 6.3M | **Janela principal de publicação** (43% dos vídeos) |
| Meio da manhã 9-12h | 24 | 8.4M | Janela secundária |
| Tarde 12-15h | 10 | 3.8M | Publicação de cauda |

**Todos os 77 vídeos estão concentrados nas 10 horas de PST 04:00-14:00.** Zero publicações após as 15h.

**Distribuição precisa por hora:**

| Hora (PST) | Nº de Vídeos | Média de Reproduções | Vídeo Representativo |
|------------|-------------|---------------------|---------------------|
| **05:00** | **9** | **12.9M** | Design 63.5M, Financial Services 13.5M |
| **08:00** | **18** | 7.2M | Office GA 27.7M, Cowork GA |
| 07:00 | 9 | 6.0M | Managed Agents 21.6M |
| 09:00 | 11 | 3.0M | Code Review 23.5M |
| 10:00 | 8 | 10.3M | Thank You 12.7M |
| **11:00** | **5** | **17.1M** | Computer Use 77.9M, Hackathon |
| 13:00 | 8 | 3.4M | Excel 23.4M |
| Outros | 9 | 5.1M | Distribuídos em 04/06/12h |

**Três picos de publicação:**

| Pico | Horário PST | Nº de Vídeos | Média de Reproduções | Características |
|------|------------|-------------|---------------------|-----------------|
| **Primeira onda da manhã** | 05:00-06:00 | 15 | 10.0M | Maior média de reproduções, vídeos flagship publicados aqui |
| **Pico de expediente** | 08:00-09:00 | 29 | 5.4M | Maior densidade, atualizações de funcionalidades concentradas aqui |
| **Onda pré-almoço** | 10:00-11:00 | 13 | 12.9M | Ainda com vídeos de alta reprodução, possivelmente janela "segunda opção" |

**Interpretação:**

1. **05:00 PST = horário de início na Europa** — publicar neste horário cobre os dois lados do Atlântico: costa oeste dos EUA ainda de madrugada, mas Europa (CET 14:00) em pico de atividade à tarde. Os 9 vídeos publicados às 05:00 com média de 12.9M incluem **dois vídeos de nível 50M+**, indicando que o agendamento antecipado permite que o conteúdo ferva na Europa primeiro, depois reflua para os EUA.

2. **08:00 PST = início de expediente nos EUA** — janela mais densa (18 vídeos), coincidindo com 11:00 na costa leste e 8:00 na costa oeste. Este é o horário de publicação "padrão".

3. **11:00 PST = antes do almoço** — maior média de reproduções (17.1M), mas apenas 5 vídeos. Este horário pode ser usado como "segunda janela" para grandes lançamentos — se o horário da manhã foi perdido, a publicação pré-almoço ainda é eficaz.

4. **Tarde quase sem publicações** — após 13:00 apenas alguns vídeos esparsos, zero após 14:00. Isso indica que a equipe de vídeo da Anthropic concentra o horário de trabalho na manhã.

**Insight prático:**
- **Lançamentos flagship:** agendar para 05:00 PST (cobrindo EUA e Europa)
- **Atualizações de rotina:** PST 08:00-09:00 (pico de expediente nos EUA)
- **Evitar publicação à tarde:** após 14:00 quase ninguém assiste
- **Se o objetivo é o mercado asiático:** 05:00 PST = 21:00 em Pequim, 22:00 em Tóquio, exatamente horário nobre da noite

---

## 11. Análise de Popularidade: Por que o Top 10 Explodiu

### 11.1 Visão Geral do Top 10

| # | Vídeo | Reproduções | Duração | Em uma frase |
|---|-------|-------------|---------|-------------|
| 1 | Computer Use | 77.9M | 73s | "AI consegue usar seu computador" |
| 2 | Claude Design | 63.5M | 82s | "Falar já faz design" |
| 3 | Lançamento do Cowork | 49.7M | 69s | "Não-programadores também usam AI para trabalhar" |
| 4 | Office GA | 27.7M | 87s | "AI no Excel/Word/PPT" |
| 5 | Code Security | 26.2M | 50s | "AI encontra vulnerabilidades de segurança" |
| 6 | Code Review | 23.5M | 45s | "Review automático de PR" |
| 7 | Lançamento do Excel | 23.4M | 44s | "Pergunte à AI diretamente no Excel" |
| 8 | Managed Agents | 21.6M | 59s | "AI gerenciando AI" |
| 9 | Computer Use (Code) | 16.1M | 45s | "AI operando autonomamente no CLI" |
| 10 | Atualização do Cowork | 14.6M | 120s | "Colaboração em equipe AI empresarial" |

### 11.2 Cinco Padrões de Explosão

#### Explosão 1: Conteúdo > Produção

**As palavras-chave dos virais são "novas possibilidades", não "atualização de funcionalidade".**

- Top 10 todos são "Introducing..." ou "You can now..." — **primeiro anúncio**
- Bottom 10 todos são "now available on..." ou "is now in beta" — **extensão de funcionalidade existente**

| Tipo de Conteúdo | Média de Reproduções | Exemplo |
|-----------------|---------------------|---------|
| Lançamento de novo produto/capacidade | **30M+** | Computer Use, Design, Cowork |
| Atualização de funcionalidade importante | **5-15M** | Code Review, Security |
| Extensão de plataforma/parceria | **1-5M** | Excel on Pro, Chrome |
| Atualização incremental/pequena funcionalidade | **<1M** | Skills Dir, /stats, guest passes |

**As pessoas pagam por "nova espécie", não por "atualização de versão".**

#### Explosão 2: Tamanho do público determina o teto

As funcionalidades do Top 10 são universais e interdisciplinares:
- Computer Use (77.9M) — todos entendem "AI operando seu computador"
- Cowork (49.7M) — público dez vezes maior que o do Claude Code
- Office GA (27.7M) — base global de usuários do Office

As funcionalidades do Bottom 10 são nicho:
- Skills Directory (77K) — apenas usuários existentes se importam
- Guest Passes (62K) — apenas usuários Max se importam
- Comando /stats (70K) — apenas usuários CLI se importam

**Um tópico relevante para 1 milhão de pessoas, por mais refinada que seja a produção, não bate um tópico relevante para 100 milhões de pessoas.**

#### Explosão 3: 60-80 segundos é o sweet spot

| Faixa de Duração | Proporção no Top 10 | Características |
|-----------------|---------------------|-----------------|
| 40-50s | 3/10 | Foco em funcionalidade, demonstração rápida |
| 60-80s | 4/10 | Narrativa completa, com Demo e Magic |
| 80-90s | 2/10 | Demonstração de ecossistema, múltiplos produtos conectados |

**Não é quanto mais curto melhor.** Bottom 10 com média de 35 segundos, Top 10 com média de 67 segundos. O problema dos vídeos curtos não é "curto demais", mas "densidade de informação muito baixa" — 35 segundos dizendo apenas "now available on Android", sem demo que valha a pena assistir.

#### Explosão 4: Emoção > Funcionalidade (ocasionalmente)

**A maior taxa de likes (likes/reproduções) não é do Top, mas do Bottom.**
- Taxa média de likes do Top 10: 0.22%
- Taxa média de likes do Bottom 10: 0.60%

Porque o Bottom atinge usuários core — que já seguem @claudeai e naturalmente dão like. O Top atinge massa — a maioria é público casual.

Mas há uma exceção: **"Thank You" (8.2s, 12.7M, taxa de likes 0.38%)**. O conteúdo é apenas uma frase "as próximas duas semanas terão o dobro de capacidade nos horários de pico". Sem nova funcionalidade, apenas um obrigado.

**"Ser agradecido" é uma experiência escassa.** A maioria das empresas publica vídeos dizendo "veja a nova funcionalidade", a Anthropic disse "obrigado".

#### Explosão 5: Ao Vivo > Refinado (ocasionalmente)

A demo ao vivo do Cowork (14.6M) é o vídeo com a produção mais tosca — pessoa real gravando a tela em um quarto. Mas superou muitos vídeos 4K refinados em reproduções.

**Em um feed cheio de mockups perfeitos, algo "real" é escasso.** Não significa não fazer vídeos refinados — mas intercalar ocasionalmente conteúdo ao vivo cria reação química.

### 11.3 Prioridade dos Fatores de Explosão

Ordenado por impacto:
1. **Conteúdo de "nova espécie"** — anunciar capacidade inteiramente nova pela primeira vez
2. **Tamanho do público** — quanto mais gente entender, melhor
3. **Abertura minimalista extrema** — menos informação nos primeiros 2 segundos
4. **Ritmo de 60-80 segundos** — suficiente para desenvolver, sem arrastar
5. **Gatilho emocional** — ocasionalmente dizer "obrigado" é mais forte que "veja a funcionalidade"
6. **Intercalação de realismo** — colocar um vídeo ao vivo no meio de vídeos refinados


## 12. Análise Multidimensional Orientada por Dados

Usando dados estruturados de 77 vídeos, análise cruzada em 7 dimensões — taxa de engajamento, resolução, duração, dia de publicação, palavras-chave de conteúdo, viralidade e utilidade — para extrair padrões de marketing de vídeo da Anthropic.

### 12.1 Dimensão de Taxa de Engajamento: Quem está realmente engajando

Taxa de engajamento = número de engajamentos / reproduções. Mais indicativo que valores absolutos de qualidade de conteúdo — filtra o ruído de "algoritmo empurrou para público casual, mas casual não se importou".

| Métrica | Fórmula | Significado |
|---------|---------|-------------|
| Taxa de likes | likes / reproduções | Aprovação instantânea |
| Taxa de bookmarks | bookmarks / reproduções | "Isso é útil, vou ver depois" |
| Taxa de retweets | retweets / reproduções | "Quero que outros vejam" |
| Taxa de replies | replies / reproduções | "Quero discutir isso" |

**Descoberta-chave: alta reprodução != alta taxa de engajamento.**

- **Maior taxa de bookmark** não são os virais, mas conteúdo de desenvolvedor: Built with Opus 4.6 (0.47%), Code with Claude Conference (0.35%), Hackathon (0.34%), Agent View (0.32%)
- **Maior taxa de reply** também tendem a nicho: Claude Code run (0.045%), Claude for Public (0.041%)
- **Maior taxa de like** é conteúdo relacionado ao Opus 4.6 (1.46%) e aniversário do Claude Code (1.19%)

**Interpretação:** Embora o grupo de desenvolvedores seja menor em número, a profundidade de engajamento supera em muito o público casual. Taxa de bookmark alta = "é uma ferramenta, vou usar". Isso mostra que os vídeos do Claude servem simultaneamente a dois grupos: público casual olha reproduções, usuários core olham profundidade de engajamento.

### 12.2 Dimensão de Resolução: 4K tem correlação mas não causalidade

| Resolução | Nº de Vídeos | Média de Reproduções | Máximo |
|-----------|-------------|---------------------|--------|
| 3840x2160 (4K) | 16 | 9.2M | 77.9M |
| 1920x1080 (1080p) | 40 | 8.5M | 63.5M |
| Outras resoluções | 21 | 1.7M | 26.2M |

- Diferença de reproduções médias entre 4K e 1080p não é grande (9.2M vs 8.5M)
- **Segundo vídeo com mais reproduções (Design, 63.5M) é 1080p, não 4K**
- "Outras resoluções" com média de apenas 1.7M — mas porque são em maioria vídeos iniciais ou formatos especiais (vertical, quadrado)

**Na prática:** Priorizar 4K, mas se recursos são limitados, 1080p não prejudica significativamente. O que realmente importa é qualidade de conteúdo e narrativa, não número de pixels.

### 12.3 Dimensão de Duração: 60-90 segundos é o sweet spot

| Faixa de Duração | Nº de Vídeos | Média de Reproduções | Taxa de Likes | Taxa de Bookmarks |
|-----------------|-------------|---------------------|---------------|-------------------|
| <15s | 13 | 3.0M | 0.56% | 0.17% |
| 15-30s | 7 | 1.9M | 0.54% | 0.20% |
| 30-60s | 27 | 7.3M | 0.43% | 0.15% |
| **60-90s** | **19** | **15.6M** | **0.48%** | **0.13%** |
| >90s | 11 | 2.9M | 0.55% | 0.19% |

**A média de reproduções de 60-90 segundos (15.6M) é 2-8x maior que todas as outras faixas.**

Mas a faixa >90s cai drasticamente para 2.9M. Isso indica:
- Curto demais (<30s): densidade de informação insuficiente, sem Demo completa → reproduções baixas
- 60-90s: suficiente para narrativa completa (Hook → Demo → Magic → Result) → reproduções mais altas
- Longo demais (>90s): decaimento de atenção, salvo conteúdo especialmente denso → reproduções recuam

**Taxa de bookmarks diminui com duração**: vídeos curtos têm bookmark mais alto (<15s tem 0.17%, 60-90s tem apenas 0.13%). Vídeo curto = consumo rápido, vídeo longo = assiste e sai, sem bookmark.

### 12.4 Dimensão de Dia de Publicação: Segunda e Sexta são as mais fortes

| Dia da Semana | Nº de Vídeos | Média de Reproduções | Total |
|---------------|-------------|---------------------|-------|
| **Monday** | **15** | **12.6M** | **189.5M** |
| Tuesday | 17 | 5.5M | 93.6M |
| Wednesday | 16 | 4.7M | 74.8M |
| Thursday | 13 | 5.1M | 65.9M |
| **Friday** | **15** | **9.4M** | **141.0M** |
| Saturday | 1 | 12.7M | 12.7M |

- **Segunda-feira com maior média de reproduções (12.6M)** — primeiro dia útil após o fim de semana, alta atividade do usuário
- **Sexta-feira em segundo (9.4M)** — possivelmente relacionado ao padrão de "publicar na sexta, ferver no fim de semana"
- Sábado com apenas 1 vídeo (Thank You, 12.7M), amostra pequena demais para conclusão
- Terça a quinta relativamente planos

**Na prática:** Grandes lançamentos na segunda ou sexta. Atualizações de rotina de terça a quinta para manter presença.

### 12.5 Dimensão de Palavras-Chave de Conteúdo: Quais tópicos têm propagação natural

| Palavra-Chave | Significado | Nº de Vídeos | Média de Reproduções |
|--------------|-------------|-------------|---------------------|
| **Introducing** | **Anúncio de estreia** | **9** | **23.6M** |
| Design | Design | 5 | 19.7M |
| Cowork | Cowork/Empresa | 10 | 17.7M |
| Excel | Excel/Office | 4 | 16.1M |
| Security | Segurança | 2 | 15.5M |
| Claude Code | Ferramenta de dev | 26 | 9.9M |
| can now | Extensão de capacidade | 16 | 7.9M |
| Agent | Relacionado a Agent | 11 | 7.6M |
| now available | Funcionalidade disponibilizada | 8 | 4.6M |

**"Introducing" é garantia absoluta de reproduções** — média de 23.6M, 5x maior que "now available" (4.6M).

Isso valida a descoberta do Capítulo 11: **primeiro anúncio >> extensão de funcionalidade**. "Introducing" insinua "nova espécie", "now available" insinua "coisa velha em lugar novo".

**Ordenação de apelo por tópico:**
1. Design (19.7M) — universal e interdisciplinar, usuários não técnicos também se importam
2. Cowork (17.7M) — "não-programadores também usam AI", público extremamente amplo
3. Excel (16.1M) — base global de usuários do Office
4. Segurança (15.5M) — "segurança" tem ansiedade e atenção natural
5. Claude Code (9.9M) — exclusivo para desenvolvedores, público restrito mas lealdade alta

### 12.6 Viralidade vs Utilidade: Dois Sinais Completamente Diferentes

**Taxa de retweet alta = "Quero que outros vejam" (viralidade)**

| Ranking | Conteúdo | Taxa de RT | Reproduções |
|---------|---------|-----------|-------------|
| 1 | Claude for Public | 0.098% | 0.1M |
| 2 | Code with Claude Conference | 0.094% | 1.1M |
| 3 | Aniversário do Claude Code | 0.078% | 0.8M |
| 4 | Built with Opus 4.6 | 0.077% | 1.0M |
| 5 | Ads are coming to AI | 0.076% | 5.2M |

**Taxa de bookmark alta = "Isso é útil, vou precisar depois" (utilidade)**

| Ranking | Conteúdo | Taxa de BM | Reproduções |
|---------|---------|-----------|-------------|
| 1 | Built with Opus 4.6 | 0.47% | 1.0M |
| 2 | Code with Claude Conference | 0.35% | 1.1M |
| 3 | Hackathon | 0.34% | 1.6M |
| 4 | Trabalho Crossbeam | 0.32% | 0.5M |
| 5 | Agent View | 0.32% | 2.3M |

**Descoberta:** Tanto a taxa de retweet quanto a de bookmark mais altas são quase sempre conteúdo de desenvolvedor nicho, não virais de massa. Isso indica:
- Virais de massa (77.9M Computer Use) não têm taxa de retweet e bookmark tão altas — as pessoas assistiram, se impressionaram, e seguiram em frente
- Conteúdo de desenvolvedor (0.1M-2M) tem as maiores taxas de retweet e bookmark — as pessoas assistiram, salvaram, e compartilharam com colegas

**Dois padrões de sucesso:**
- **Exposição de marca:** olhar reproduções e volume absoluto de retweets → Computer Use (77.9M, 14,467 rt)
- **Impacto profundo:** olhar taxa de bookmark e taxa de reply → Agent View (0.32% bm, 686 replies)

### 12.7 Pontuação de Engajamento Combinada: Avaliação Ponderada

Atribuir pesos diferentes a comportamentos de engajamento (bookmark = 3x, reply = 5x, retweet = 2x, like = 1x), calcular pontuação combinada:

```
Pontuação Combinada = (likes + bookmarks×3 + retweets×2 + replies×5) / reproduções × 100
```

**Top 5 Engajamento Combinado:**

| Ranking | Conteúdo | Pontuação | Reproduções | L | B | RT | R |
|---------|---------|-----------|-------------|---|---|----|---|
| 1 | Built with Opus 4.6 | 2.70% | 1.0M | 9.9K | 4.9K | 800 | 370 |
| 2 | Code with Claude Conference | 2.39% | 1.1M | 10.8K | 3.9K | 1,057 | 460 |
| 3 | Agent View | 2.13% | 2.3M | 20.3K | 7.3K | 1,571 | 686 |
| 4 | Aniversário do Claude Code | 2.04% | 0.8M | 9.7K | 1.4K | 641 | 310 |
| 5 | Hackathon | 2.01% | 1.6M | 10.7K | 5.5K | 937 | 622 |

**Padrão:** Conteúdo com pontuação combinada mais alta compartilha uma característica — voltado a desenvolvedores ou eventos comunitários. Reproduções não são altas (0.8M-2.3M), mas cada pessoa que assiste se engaja profundamente.

**Isso oferece dois caminhos para estratégia de marketing:**
1. **Caminho de amplitude:** fazer vídeos de funcionalidade universal, buscar reproduções e exposição de marca (Computer Use, Design, Cowork)
2. **Caminho de profundidade:** fazer conteúdo de desenvolvedor/comunidade, buscar taxa de bookmark e discussão (Agent View, Hackathon, Built with Opus 4.6)

Ambos os caminhos devem existir — amplitude atrai novos usuários, profundidade retém.


## 13. Comparação de Estratégias de Vídeo com Concorrentes

### 13.1 Diferenças de Linguagem de Vídeo das Quatro Grandes Empresas de AI

| Dimensão | Anthropic (Claude) | OpenAI (ChatGPT) | Google (Gemini) | Apple (Apple Intelligence) |
|----------|-------------------|------------------|----------------|--------------------------|
| **Cor principal** | Branco quente + terracota | Azul frio + preto gradiente | Branco + multicolorido | Preto puro + branco puro |
| **Humor** | Acadêmico, quente, reflexivo | Tech, cool, cutting-edge | Vibrante, amigável, popular | Minimalista, premium, contido |
| **Estratégia de fonte** | Título em serifa (sensação editorial) | Sem-serifa (sensação tech) | Google Sans (sensação de marca) | SF Pro (sensação de sistema) |
| **Exibição de UI** | Modo escuro constante | Misto claro/escuro | Principalmente claro | Segue o sistema |
| **Pessoas reais** | Muito raro (1/78) | Ocasional | Frequente | Nunca |
| **Estilo narrativo** | Contido, mostrar > contar | Explicativo, sensação de tutorial | Estilo de vida, guiado por cenário | Produto como narrativa |
| **Estilo de transição** | Hard cut como protagonista | Gradiente + hard cut | Animações vibrantes | Hard cut preciso |
| **Encerramento** | Sem CTA, fade-out | Às vezes com CTA | Com CTA | Card de marca |

### 13.2 Interpretação da Estratégia de Diferenciação do Claude

**Por que cores quentes?**
A linguagem visual padrão de produtos AI é fria (azul/preto) — transmitindo "sensação tech" e "inteligência". A Anthropic faz o oposto: cores quentes transmitem "pensamento", "acadêmico", "humanístico". Isso não é preferência estética, é expressão visual de posicionamento de marca: Claude é "AI que pensa", não "máquina que calcula".

**Por quase não usar pessoas reais?**
Apenas 1 dos 78 vídeos tem rosto humano. Razões:
- Pessoas reais distraem — espectadores começam a prestar atenção na "pessoa" em vez da "funcionalidade"
- UI/texto/animação em si podem carregar a personalidade da marca
- Não usar pessoas = escalabilidade infinita — não impactado por mudanças de equipe
- Exceção: quando há necessidade de "transferência de confiança" (engenheiro falando sobre Opus 4.5), aí se introduz pessoa real

**Por que não usar CTA no encerramento?**
Marketing de vídeo tradicional usa CTA ("Cadastre-se agora!") para criar urgência. Claude não usa:
- CTA é sinal de "você precisa do espectador" — reduz energia de marca
- Fade-out para logo = "nosso produto fala por si" — aumenta energia de marca
- Isso é um **sinal de escassez**: quanto menos você pede, mais a pessoa quer ver

### 13.3 "Keep Thinking" como Filosofia de Marca

"Keep Thinking" não é apenas um slogan, é a lógica subjacente de toda a estratégia de vídeo:
- Sem logo intro → "Não precisamos nos apresentar"
- Sem CTA de encerramento → "Não precisamos convencê-lo"
- UI em modo escuro → "Trabalhamos em ambiente sério"
- Abertura minimalista → "Espaço para você pensar"
- Animação contida → "Não interferimos no seu julgamento"

Cada decisão de produção pode ser rastreada até esta filosofia de marca. Este é o nível mais alto da metodologia — não é "como fazer", mas "por que fazer assim".

---

## 14. Psicologia de Engajamento: Por que Esses Padrões Funcionam

### 14.1 Princípio de Lacuna Cognitiva do "Menos é Mais"

Os dois vídeos com maior reprodução (77.9M e 63.5M) usaram abertura minimalista extrema. Princípio:

```
Imagem minimalista → Informação insuficiente → Lacuna cognitiva → Cérebro preenche automaticamente → Curiosidade → Permanece assistindo
```

É a aplicação da **Teoria da Lacuna de Informação (Information Gap Theory)**:
- O cérebro odeia padrões incompletos
- Quando a imagem tem apenas um ícone minúsculo + vasto espaço vazio, o cérebro é forçado a trabalhar para "entender" a imagem
- Esse investimento cognitivo cria conexão emocional — o espectador já "investiu" atenção e não quer desistir

**Na prática:** Primeiro frame com apenas um elemento, sem texto. Reveal do texto após 0.8-1.2s.

### 14.2 Construção de Confiança pela "Visualização de Processo"

Por que visualizar processo (lista de tarefas, saída de terminal) gera mais engajamento que mostrar apenas o resultado?

- **Transparência = Confiança:** mostrar o que a AI "está pensando" é mais persuasivo que apenas dizer "terminei"
- **Satisfação adiada:** espectador vê barra de progresso avançando, gerando expectativa de "quase pronto"
- **Verificabilidade:** saída de terminal, diff de código faz o espectador sentir "isso é real, não é demo"

**Na prática:** Não pule o processo de geração. Use Task Sequence, indicadores de progresso, scroll de terminal para visualizar.

### 14.3 Instinto de Leitura da "Narrativa Espacial"

Por que o fluxo visual da esquerda para a direita (celular → processamento → desktop) funciona?

- A direção de leitura de texto horizontal é esquerda para direita (inglês/chinês horizontal)
- O cérebro interpreta "esquerda para direita" como "relação causal" ou "passagem do tempo"
- Essa timeline implícita reduz carga cognitiva — não precisa explicar "o que fazer primeiro e depois"

**Na prática:** Quando há múltiplos passos, use layout espacial da esquerda para a direita para insinuar o fluxo, em vez de numerar ou usar setas.

### 14.4 Efeito Psicológico do Hard Cut

Por que o Claude usa quase apenas hard cut, nunca dissolve lento/gradiente?

- **Hard cut = Confiança:** sem enrolação, insinua "cada frame vale parar para ver"
- **Dissolve = Incerteza:** dissolve insinua "este frame não vale parar, vamos passar rápido"
- **Sensação de ritmo:** hard cut cria sensação de batida, como percussão musical
- **Sensação moderna:** dissolve lento é estética dos anos 2000 — usar hoje parece ultrapassado

---

## 15. Estratégia de Áudio/Trilha Sonora

### 15.1 Soluções de Áudio para Cinco Tipos de Vídeo

| Tipo de Vídeo | Estilo de Trilha | Voz | Base de Referência |
|---------------|-----------------|-----|-------------------|
| Animação de ritmo acelerado | Eletrônica/percussiva sincronizada ao beat | Sem | Lançamento do Cowork (49.7M) |
| Demonstração de produto | Música ambiente leve | Sem ou voiceover | Maioria dos vídeos de funcionalidade |
| Terminal/developer | Mínima ou silenciosa | Sem | Agent View, Managed Agents |
| Declaração de marca | Tom único ou silêncio | Possível | "Keep Thinking" |
| Ao vivo/pessoas reais | Narração vocal | Sim | Demo ao vivo do Cowork |

### 15.2 Princípios de Produção de Áudio

1. **Preservar versão silenciosa** — completar primeiro a versão puramente visual sem trilha, depois sobrepor música separadamente
2. **Música não rouba a cena** — a trilha reforça o ritmo, não domina a narrativa
3. **Fade-in/fade-out no início e fim** — evitar início/término abrupto de música
4. **Alinhamento ao beat** — troca de cena em vídeos de ritmo acelerado deve coincidir com o beat da música
5. **Funciona no silêncio** — a maioria das reproduções em redes sociais é muda, o vídeo deve transmitir informação mesmo sem som

---

## 16. Checklist Prático

### 16.1 Verificação Pré-Produção

- [ ] Definir tipo de vídeo (Modo A/B/C/D)
- [ ] Fixar orçamento de duração
- [ ] Confirmar canal de destino e aspect ratio
- [ ] Escolher estratégia de abertura (minimalismo extremo / reveal de marca / produto direto / pergunta de dor)
- [ ] Escrever em uma frase "o que o espectador deve sentir ao ver este vídeo"

### 16.2 Verificação Durante Produção

- [ ] Toda UI é versão reconstruída perfeita, não gravação de tela real
- [ ] Remover UI irrelevante: caixas de debug, tabs extras, barras de aviso
- [ ] Primeiros 2 segundos com apelo visual
- [ ] Primeiros 15 segundos com Magic Moment
- [ ] Pesos de fonte apenas 500/600/700, com `font-synthesis: none`
- [ ] Títulos em sentence case com ponto final
- [ ] Sem logo intro
- [ ] Movimento de cursor natural (chegada antecipada)
- [ ] Câmera sem drift contínuo
- [ ] Sem ampliação de apenas um único botão

### 16.3 Verificação Pós-Produção

- [ ] Sem card de CTA no encerramento
- [ ] Sem hard cut para tela preta
- [ ] Último frame com marca visível
- [ ] Consegue transmitir informação em modo silencioso
- [ ] Versão com trilha preserva a versão silenciosa original
- [ ] Exportação em múltiplas resoluções (4K + 1080p)
- [ ] Exportação em múltiplos aspect ratios (16:9 + 4:5 ou 1:1)

### 16.4 Estratégia de Publicação

- [ ] X/Twitter: 16:9 ou 1:1, primeiros 3 segundos decidem permanência
- [ ] YouTube: 16:9, título e thumbnail igualmente importantes
- [ ] Instagram: 4:5 vertical, visual como prioridade
- [ ] Horário de publicação: seguir faixa de atividade do público-alvo

---

## 17. Guia de Adaptação: Como Usar no Seu Próprio Produto

### 17.1 Pode Reaproveitar Diretamente

| Abordagem do Claude | Princípio Universal | Pode Usar Diretamente |
|--------------------|---------------------|----------------------|
| Hard cut como protagonista | Restrição de transições | Diretamente |
| Sem logo intro | Produto nos primeiros 2s | Diretamente |
| Sem CTA de encerramento | Terminar com conteúdo | Diretamente |
| Título sentence case com ponto | Copy com sensação de conversação | Diretamente |
| Pesos 500/600/700 | Estabilidade tipográfica | Diretamente |
| Task Sequence | Visualização de processo | Diretamente |
| Cenas de 3-8s | Ritmo compacto | Diretamente |
| Checklist de anti-padrões | Evitar erros comuns | Diretamente |

### 17.2 Precisa Adaptar

| Abordagem do Claude | Por Que Não Copiar Diretamente | Como Adaptar |
|--------------------|-------------------------------|-------------|
| Paleta branco quente + terracota | É a cor de marca do Claude | Substituir pela cor principal da sua marca, mas manter hierarquia de "canvas quente + UI escura" |
| Modo escuro constante | Seu produto pode ter UI clara | Manter realce/escurecimento real da UI do produto, usar cor quente apenas no canvas externo |
| Fonte de título em serifa | Sua marca pode não combinar com serifa | Usar a fonte da sua marca, mas manter hierarquia de "título grande + corpo pequeno" |
| Composição de device mockup | Requer capacidade de renderização 3D | Degradar para screenshot + sombra, efeito um pouco inferior mas barreira muito menor |
| Abertura minimalista extrema | Requer reconhecimento de marca como suporte | Se sua marca não é conhecida, coloque o nome da funcionalidade primeiro, depois faça minimalismo |

### 17.3 Mentalidade Central

Não imite a "aparência" do Claude, imite a "lógica de decisão" do Claude:

- **Por que cores quentes?** → Porque concorrentes usam cores frias, diferenciar
- **Sua versão:** Encontre linguagem de cores que concorrentes não usam

- **Por que não usar pessoas reais?** → Porque a UI em si pode contar histórias
- **Sua versão:** Se sua UI não é bonita o suficiente, conserte a UI antes de fazer vídeo

- **Por que não usar CTA?** → Porque a energia de marca é alta o suficiente
- **Sua versão:** Se a marca não é conhecida, CTA moderado é razoável

- **Por que hard cut como protagonista?** → Porque cada frame tem valor
- **Sua versão:** Se uma cena não sustenta 3 segundos, encurte-a ou corte-a

**A essência da metodologia não é uma lista de regras, mas "cada decisão deve ter um motivo".**

## Apêndice A: Referência Rápida de Tipos de Vídeo

| O Que Você Precisa Fazer | Qual Framework Usar | Duração | Vídeo de Referência |
|-------------------------|---------------------|---------|---------------------|
| Lançar uma nova funcionalidade | Modo A: Anúncio de Funcionalidade Padrão | 30-60s | Opus 4.6, Code Review |
| Anunciar uma integração | Modo B: Scan de Ecossistema | 30-50s | Excel/PowerPoint, Work Tools |
| Anúncio breve/evento | Modo C: Short Card Social | 8-15s | Thank You, Remote Control |
| Funcionalidade para desenvolvedores | Modo D: Demonstração Profunda Developer | 60-90s | Managed Agents, Agent View |
| Declaração de marca/posicionamento | Variante do Modo C | 10-60s | "Keep Thinking", "Ads" |

## Apêndice B: Template de Vídeo de Funcionalidade 30s

| Tempo | Conteúdo | Animação |
|-------|---------|----------|
| 0-3s | Ícone minimalista + reveal do nome da funcionalidade | Ícone bounce-in + fade-in de texto |
| 3-7s | Problema/contexto | Barra de legenda captionAt() |
| 7-18s | Demonstração do produto | clickAt() × 2-3, showPreviewAt() |
| 18-25s | Magic Moment | Task Sequence (linhas ficando verdes) |
| 25-28s | Estado de resultado | Painel showRightAt() |
| 28-30s | Encerramento com logo | Final Card (versão simplificada) |

## Apêndice C: Template de Vídeo de Funcionalidade 60s

| Tempo | Conteúdo | Animação |
|-------|---------|----------|
| 0-3s | Abertura minimalista (ícone em espaço negativo) | Ícone scale bounce-in |
| 3-8s | Nome da funcionalidade + contexto | cameraTo() + captionAt() |
| 8-20s | Operação do usuário (2-3 passos) | clickAt() × 2-3 |
| 20-40s | Processamento do sistema (Magic Moment) | Task Sequence + Pulse de respiração |
| 40-50s | Demonstração de resultado | showPreviewAt() + Staggered Reveal |
| 50-55s | Validação secundária/prova | Painel showRightAt() |
| 55-60s | Encerramento com logo | Final Card

---
