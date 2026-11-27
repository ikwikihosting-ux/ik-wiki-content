---
title: "How “Trigger Probability Increase” Actually Works in Infinity Kingdom"
summary: "Trigger-based skills sit at the center of many Tower of Knowledge builds, particularly in magic-heavy or hybrid compositions where value is generated over time through repeated procs. On paper, increasing trigger…"
categoryPath:
  - "Tower of Knowledge"
  - "ToK Skill Explainers"
type: guide
date: 2026-05-01
---
### Introduction

Trigger-based skills sit at the center of many Tower of Knowledge builds, particularly in magic-heavy or hybrid compositions where value is generated over time through repeated procs. On paper, increasing trigger probability seems like one of the most straightforward ways to improve consistency—more activations should naturally translate into more damage, more healing, or more control.

![](https://ik-wiki.com/wp-content/uploads/2026/05/image.png)

![](https://ik-wiki.com/wp-content/uploads/2026/05/image-1.png)

In practice, however, the system is not as intuitive as it appears. The way trigger probability scales, and how different sources interact with each other, introduces some hidden limitations that can significantly affect build efficiency. Many players, myself included early on, assumed these bonuses worked additively and stacked freely. That assumption leads to overinvestment in trigger scaling and, ultimately, weaker overall builds.

This guide breaks down how trigger probability increases are actually calculated, what sources affect them, and how to approach them from a practical, tested perspective.

---

### Understanding Triggered Skills vs Passive Activations

Before getting into scaling mechanics, it’s important to clearly separate two types of effects that often get grouped together by newer players.

- **Triggered Skills**: These explicitly carry the *“Triggered”* tag in their description and list a percentage chance to activate. These are the only skills affected by trigger probability increases.

![](https://ik-wiki.com/wp-content/uploads/2026/05/image-2.png)

- **Passive Chance-Based Effects**: Some skills, such as *Chase*, also display a percentage chance to activate, but they are classified as passive effects rather than triggered skills.

![](https://ik-wiki.com/wp-content/uploads/2026/05/image-3.png)

This distinction is not just semantic—it directly determines whether a skill benefits from trigger probability bonuses at all.

For example:

- *Annihilation*: Triggered skill → affected by trigger probability boosts
- *Chase*: Passive effect → not affected

In actual gameplay, this matters more than it seems at first glance. A build that looks like it has multiple “proc-based” elements may only partially benefit from trigger scaling. If you’re not checking the skill classification carefully, it’s easy to overestimate how much value you’re getting from effects like Nine Tails or Abundant Spirit.

---

### How Trigger Probability Is Actually Calculated

#### Not Additive — It’s Relative to Base Chance

One of the most common misunderstandings is assuming trigger probability increases are additive. The logic is simple and intuitive. Let's use Annihilation as an example again, Annihilation has a 45% chance to trigger its effect (damage).

![](https://ik-wiki.com/wp-content/uploads/2026/05/image-4.png)

> 45% (base) + 10% (buff) = 55%

**But this is not how the system works.**

Instead, the increase is calculated as a percentage of the **base trigger rate**, not added as a flat value. The game effectively scales the original chance rather than stacking directly on top of it.

### Formula:

> Final Chance = Base Chance × (1 + Increase %)

### Example (Annihilation):

- Base: 45%
- Increase: 10%

> 45% × 1.10 = **49.5%**

So instead of gaining a flat +10 percentage points, you gain **+4.5 percentage points**.

![](https://ik-wiki.com/wp-content/uploads/2026/05/image-6-1024x347.png)

This has a few important implications:

- Higher base trigger skills **benefit more**in absolute terms
- Lower base trigger skills see relatively **small gains**

In longer fights, this difference becomes very noticeable. A skill you expected to trigger “more than half the time” still behaves closer to its original rate, which can affect both damage expectations and timing-based strategies.

---

### Sources of Trigger Probability Increase

There are currently two primary and widely used sources of trigger probability increases in the game. Both provide the same nominal value, but their interaction is where things become important.

#### 1. Nine Tails (Chaos Support Backline)

- **Passive**effect from ultimate
- Grants **+10% trigger probability** to all allied triggered skills

![](https://ik-wiki.com/wp-content/uploads/2026/05/image-5.png)

Nine Tails is often included in builds not just for utility, but specifically for this passive scaling. Because it applies team-wide, it’s especially valuable in compositions running multiple triggered skills.

#### 2. Abundant Spirit (Tower of Knowledge Skill)

- Grants **+10% trigger probability**

![](https://ik-wiki.com/wp-content/uploads/2026/05/image.png)

Abundant Spirit is typically considered when players want to reinforce proc consistency without dedicating a backline slot to Nine Tails. On paper, it looks like a flexible alternative—or even a stacking option.

At this stage, many players assume running both will result in a combined +20% effect. That leads directly into the next, and arguably most important, mechanic.

---

### Trigger Probability Buffs Do NOT Stack

Despite coming from completely separate systems—one being an immortal passive and the other a Tower of Knowledge skill—**trigger probability increases do not stack**.

![](https://ik-wiki.com/wp-content/uploads/2026/05/image-7-1024x656.png)

The game only applies **one instance** of the effect, even if multiple sources are active.

So if you run:

- Nine Tails (+10%)
- Abundant Spirit (+10%)

You do **not** get +20%. The system will still only apply a single **+10% (relative)** increase.

This behavior is not clearly stated in-game, which is why it’s often misunderstood. It also means that combining these two sources provides no additional benefit, even though it appears like it should.

---

### Player Perspective

From a practical standpoint, this mechanic has a direct impact on build efficiency and decision-making.

When I first tested this interaction, the expectation was straightforward: stacking both sources should push high-frequency triggered skills closer to consistency thresholds where they feel reliable every rotation. In actual testing, the results didn’t match that expectation. Proc rates plateaued in a way that didn’t align with a supposed +20% increase.

After comparing results across multiple setups and confirming with other experienced players, it became clear that only one modifier was being applied. Once you understand that, the optimal approach becomes much simpler.

In real builds:

- Running **Nine Tails already covers your trigger scaling needs**
- Adding **Abundant Spirit provides no additional value**

For example, in a magic AoE setup using Annihilation:

- With Nine Tails alone: ~49.5% proc rate
- Adding Abundant Spirit: remains ~49.5%

At that point, Abundant Spirit is effectively consuming a slot without contributing anything meaningful. In most cases, that slot is better used on:

- Raw damage amplification
- Energy regeneration for faster skill cycles
- Defensive or sustain tools for longer fights

This becomes especially important in competitive environments or extended engagements, where efficiency across all skill slots determines overall performance.

---

### Conclusion Summary

- Trigger probability increases scale **off the base rate**, not as flat additions
- A 10% increase means **+10% of the base value**, not +10 percentage points
- Multiple trigger probability buffs **do not stack**
- Only one source (e.g., Nine Tails *or* Abundant Spirit) is applied
- Running both leads to inefficient use of skill slots

In practical terms, once you include a source like Nine Tails in your lineup, trigger probability is already optimized within the limits of the system. From there, your focus should shift toward effects that provide clear, additive gains rather than trying to push proc rates beyond what the mechanics actually allow.

---
