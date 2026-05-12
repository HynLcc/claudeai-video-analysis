# Como a Anthropic faz vídeos que alcançam 78M de visualizações

Análise sistemática de 77 vídeos oficiais de produto da Claude (out 2025 – mai 2026). Metodologia extraída, sistema de design, frameworks narrativos e padrões de engajamento.

[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Français](README.fr.md) | [Documento completo de metodologia →](analysis/METHODOLOGY.pt.md)

---

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
