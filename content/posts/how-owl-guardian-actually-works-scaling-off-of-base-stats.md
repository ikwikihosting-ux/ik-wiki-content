---
title: "How Owl Guardian actually works - scaling off of base stats"
summary: "Owl Guardian is one of those talents that most experienced players default to, especially in builds centered around ultimate skill damage. The talent choice is on the same line as attack speed, so for some players this…"
categoryPath:
  - "Lord/Lady (Talents & Honor)"
  - "Basic talent builds"
type: guide
date: 2026-05-06
---
### Introduction

Owl Guardian is one of those talents that most experienced players default to, especially in builds centered around ultimate skill damage. The talent choice is on the same line as attack speed, so for some players this will be entirely irrelevant.. however for the many out there relying on energy regen understanding precisely how Owl Guardian works is important! Most players already lean toward energy regen because it benefits every immortal, while attack speed only shines in specific normal-attack builds.

**However, the real value of Owl Guardian is often misunderstood because the tooltip is inaccurate.** What it actually scales from is not your *current* Energy Regen stat, but something more fundamental. That is what this article will be all about!

![](https://ik-wiki.com/wp-content/uploads/2026/05/image-39-1024x463.png)

---

## The Core Mechanic: Base Energy Regen Scaling

After testing and comparing multiple immortals across different stat ranges, the pattern becomes clear: **Owl Guardian increases Energy Regen by 5% of the immortal’s *base* Energy Regen — not their total stat after bonuses.** Personally this came as a surprise for me, given how for example boost levels I would think where cooked in as flat value increases. I know that is surprising to many, so lets take a bit of a closer look at preciesly what scaling off of base energy regen means.

### What “Base Energy Regen” Means

Each immortal has a default, built-in Energy Regen value before:

- Tech bonuses
- Lord talents
- Boost levels
- Equipment
- etc.

Owl Guardian ignores all of those modifiers and only applies its bonus to this base value.

---

## Verified Examples

### Low Base Regen Immortal (Baldwin)

- Base Energy Regen: **66**
- 5% of 66 = **3.3**

![](https://ik-wiki.com/wp-content/uploads/2026/05/image-33-1024x754.png)

My Baldwin with boost levels and tech, etc. has 78.5 with Owl Guardian that gets to → 81.8. Not a 5%, instead a gain of **+3.3** **equal to 5% of his base energy regen** before any modifiers or boosts (66 x 0.05 = 3.3).

![](https://ik-wiki.com/wp-content/uploads/2026/05/image-38-1024x799.png)

![](https://ik-wiki.com/wp-content/uploads/2026/05/image-37-1024x811.png)

The increases line up perfectly once you calculate from base instead of total.

---

### High Base Regen Immortals (e.g. Hippolyta, Empress Wu, Qin)

These immortals share a key trait:

- Base Energy Regen: **100**
- 5% of 100 = **5**

![](https://ik-wiki.com/wp-content/uploads/2026/05/image-34-1024x717.png)

Despite my Empress Wu being at 115 without Owl Guardian she only gets to 120 when the talent is active. Again this lines up with 5% of her default base energy regen value of 100.

![](https://ik-wiki.com/wp-content/uploads/2026/05/image-35-1024x744.png)

![](https://ik-wiki.com/wp-content/uploads/2026/05/image-36-1024x749.png)

---

## Why the Tooltip Feels Misleading

The game shows Energy Regen as a final, combined stat, but Owl Guardian does not use that value in its calculation.

So when players see: “Energy Regen +5%”, they naturally assume the **current energy regen attribute shown on immortal page** **× 1.05**

But the real formula is: **Base Regen × 1.05 → then added to your total** through other modifiers and increases.

That difference is what causes lower-than-expected gains on upgraded immortals.

---

## Conclusion Summary

Owl Guardian does not scale from your total Energy Regen stat.

**It scales from base Energy Regen only.**

- Low-base immortals gain ~3–4 Energy Regen
- High-base immortals (100 base) gain exactly +5
- Buffs, tech, and gear do not increase the talent’s value

While the tooltip suggests a universal 5% increase, the actual behavior is **+5% of base Energy Regen, added on top of your total stat**

Even with this limitation, Owl Guardian remains the most reliable and widely applicable choice for most builds, because faster ultimate access consistently outweighs the niche benefits of attack speed.

---
