# How Anthropic Makes Videos That Get 78M Views

Systematic analysis of 77 official Claude product videos (Oct 2025 – May 2026). Extracted methodology, design system, narrative frameworks, and engagement patterns.

[中文版方法论完整文档 →](analysis/METHODOLOGY.md)

---

## The 5 Big Insights

### 1. They never record real screens — they rebuild perfect UIs

Every "screenshot" in a Claude video is fabricated. Pixel-perfect UI mockups composited onto 3D-rendered device frames (MacBooks, iPhones, monitors), floating on warm backgrounds. No browser chrome, no bookmarks bar, no notification badges. This is the single biggest production difference between Claude videos and everything else.

**Why it works:** Eliminates visual noise. Every frame is brand-safe. No accidental tabs, no embarrassing bookmarks, no dated UI elements when the product ships an update next week.

### 2. The "Less Is More" hook is the highest-performing pattern

The two most-viewed videos (77.9M and 63.5M) both open the same way: a tiny icon on a vast warm background. No text. No animation. Just negative space and a single focal point.

This creates a **cognitive gap** — the brain can't parse the frame instantly, so it invests attention to figure it out. By the time the product name fades in at 0.8–1.2s, the viewer is already hooked.

The 10-second video that got 10M views? Same principle. Extreme minimalism. One element. Done.

### 3. No logo intro, no ending CTA — ever

Across 77 videos:
- **0** start with a logo animation
- **0** end with "Sign up now!" or any call-to-action

This is deliberate brand positioning. A logo intro says "we need to introduce ourselves." A CTA says "we need you." Claude does neither — the product appears in frame 1, and the video fades to a quiet logo on a warm background.

The message: *our product doesn't need to sell itself.*

### 4. "Show the thinking, not just the result" drives engagement

Videos that visualize the AI's process — task lists checking off green, terminal commands scrolling, node graphs expanding — consistently outperform videos that just show the final output.

This isn't just a production trick. It's **trust architecture.** Showing the process makes AI feel less like a black box. The viewer can verify: "yes, it actually did these steps."

The most extreme example: Computer Use (77.9M) shows Claude clicking through a real OS, app by app. Not simulated. Not sped up too much. Real cursor, real clicks, real hesitation.

### 5. Hard cuts only — zero fancy transitions

Across 77 videos:
- ~60% hard cuts between scenes
- ~15% fade to warm background
- ~10% slide-ins
- ~0% dissolves, morphs, 3D flips, particle effects

Every transition is under 2 seconds. No cinematic dissolves. No flashy motion graphics transitions. The philosophy: if each frame is worth looking at, you don't need to apologize for cutting to it.

---

## What This Repo Contains

```
analysis/
  METHODOLOGY.md        Full methodology: pipeline, design system, narrative
                        frameworks, motion grammar, hooks, engagement formula,
                        competitive analysis, psychology, audio, checklists
  ANALYSIS.md           Batch analysis of visual styles across 4 time periods
  DETAILED_ANALYSIS.md  Frame-by-frame breakdowns of 13 key videos

data/
  VIDEO_CATALOG.md      Complete catalog of all 77 videos with metadata
  metadata.json         Structured data: tweet IDs, views, likes, etc.
```

---

## The Production Formula (TL;DR)

```
Warm canvas (#FBFAF6) + Dark UI (#1A1A2E) + Terracotta accent (#D67C64)
+ Rebuilt perfect UI on 3D device mockups
+ Serif titles in sentence case with periods.
+ Hard cuts. No logo intro. No CTA.
+ Task sequence for "magic moments"
+ Hook in 0–3s. Magic moment by 15s.
= Claude video.
```

---

## Engagement Tiers (77 videos analyzed)

| Tier | Views | Videos | Pattern |
|------|-------|--------|---------|
| Super (50M+) | 63–78M | 2 | 4K, extreme minimalism hook, universal feature, spatial narrative |
| High (10–30M) | 11–27M | 11 | Polished production, clear demo, strong narrative arc |
| Mid (2–10M) | 2–7M | 11 | Standard production, decent storytelling |
| Low (<2M) | <2M | 53 | Niche audience or low information density |

**What correlates with high views:** 4K resolution, minimal hooks, features that cross professional boundaries, 70–80s pacing, left-to-right spatial composition.

**What doesn't correlate:** Video length, aspect ratio, developer vs. general audience.

---

## The Visual Identity That Took 8 Months to Build

```
2025 Q4  Floating app windows on brand backgrounds, simulated cursors
         → Terracotta + dark mode established as standard

2026 Q1  3D device mockups (phone/laptop/monitor) + dark UI + terracotta accents
         → "Keep Thinking" brand philosophy emerges
         → Cowork series defines "AI for non-developers" narrative

2026 Q2  Spatial narratives (left-to-right flow), hand-drawn squiggles
         → "Less is more" hooks proven (77.9M, 63.5M)
         → Product videos become brand philosophy statements
```

**The trajectory:** from "look what Claude can do" → "imagine what you could do."

---

## Competitive Positioning

| | Claude | ChatGPT | Gemini | Apple Intelligence |
|---|--------|---------|--------|-------------------|
| Color | Warm white + terracotta | Cool blue + black gradient | White + multicolor | Pure black + white |
| Mood | Academic, warm, thoughtful | Tech, cool, cutting-edge | Friendly, consumer | Minimal, premium |
| Typography | Serif titles (editorial) | Sans-serif (tech) | Google Sans (brand) | SF Pro (system) |
| Humans on screen | 1 out of 77 | Occasionally | Frequently | Never |
| Ending CTA | Never | Sometimes | Always | Brand card |

Claude's visual language is a deliberate departure from the AI industry's default cold-blue palette. Warm + intelligent = academic, not corporate.

---

## Adapt It to Your Product

**Borrow directly:** hard cuts, no logo intro, no CTA, sentence-case titles with periods, 500/600/700 font weights, task sequences, 3–8s scenes, anti-pattern list.

**Adapt to your brand:** color system (use your brand colors but keep the warm canvas + dark UI hierarchy), typography (use your brand font but keep the size hierarchy), device mockups (use screenshots with shadows if you can't do 3D renders).

**The underlying principle:** every production decision should have a reason. Claude's choices aren't arbitrary aesthetics — they're brand strategy expressed through motion. Copy the reasoning, not the pixels.
