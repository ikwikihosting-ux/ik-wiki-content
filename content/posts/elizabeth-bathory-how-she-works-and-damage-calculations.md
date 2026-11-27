---
title: "Elizabeth Bathory - how she works and damage calculations"
summary: "Elizabeth Bathory’s & How Her Ultimate Damage Actually Works - damage estimates included: A practical damage model for real fights"
categoryPath:
  - "Immortals"
  - "Immortal Deepdives"
type: guide
date: 2026-01-08
---
***Elizabeth Bathory’s & How Her Ultimate Damage Actually Works - damage estimates included***: *A practical damage model for real fights*

## Introduction

Elizabeth Bathory is one of the hardest immortals in Infinity Kingdom to get a firm grasp on what to expect from. She can dish out massive damage through her ultimate ability, but it can be very hard to figure out how she compares to "normal" immortals that simply have a fixed % damage attached to their ultimates. This is not because her kit is unclear, but because her **damage does not behave like a normal nuke**. Her ultimate ramps over time, depends on previously hit targets, and is strongly dependent on having "time to ramp up" meaning energy regen and fight length.

This guide explains:

- basics of who Bathory is and what she does,
- how her DoT and explosion mechanics really interact,
- why you cannot assume “full coverage” or “double explosions every cast,”
- and what **average damage to expect over 2–3 casts**, which is how most real battles actually play out.  - All calculations below use **96 energy regen**, which is equal to a 23 boost level 55 Bathory on an account with decent technology upgrades. So nothing overly fancy.

---

## Elizabeth Bathory

Elizabeth Bathory is a Shadow-element Bowman whose strength lies in sustained damage rather than immediate burst. She performs best in longer battles where she can cast her ultimate multiple times and gradually build pressure through repeated applications of her damage-over-time effects and follow-up explosions. Evaluating her based on a single cast undersells what she is designed to do.

![](https://ik-wiki.com/wp-content/uploads/2026/01/image-48-1024x662.png)

As a Shadow immortal, Bathory benefits from elemental advantage against most of the roster. She deals increased damage to all non-Holy enemies and takes reduced damage from them, which gives her consistent performance across common matchups. Holy teams remain her weakest point, but outside of that niche she rarely feels inefficient or mismatched.

Being a Bowman shapes how Bathory should be built. Her best immortal talent is **Deadly Aim**, as critical damage scales exceptionally well with her kit. When paired with a **physical attack % artifact with Annihilation**, this setup provides the strongest damage amplification available.

![](https://ik-wiki.com/wp-content/uploads/2026/01/image-49.png)

![](https://ik-wiki.com/wp-content/uploads/2026/01/image-50-1024x617.png)

Both her DoT ticks and her burst explosions benefit from crit scaling, which makes crit-focused builds noticeably outperform flat attack alternatives over time.

Because her ultimate relies heavily on damage-over-time effects, Bathory is directly countered by immortals that can cleanse or suppress DoTs. Most notably, **Theodora hard-counters** **her**by removing or neutralizing DoT-based damage before it can fully ramp.

![](https://ik-wiki.com/wp-content/uploads/2026/01/image-51.png)

In matchups where Theodora is present, Bathory’s effective damage is dramatically reduced, and she often struggles to reach the point where her scaling becomes relevant.

Bathory is also one of the more accessible high-impact immortals. She can be unlocked through VIP chests or random immortal fragments, including Shadow and Shadow/Light fragments.

![](https://ik-wiki.com/wp-content/uploads/2026/01/image-52.png)

![](https://ik-wiki.com/wp-content/uploads/2026/01/image-55.png)

![](https://ik-wiki.com/wp-content/uploads/2026/01/image-56.png)

After unlocking her once, her fragments are available in the Marketplace for gems, making long-term upgrades straightforward and reliable. This combination of accessibility and scaling potential makes her an appealing option for players building toward sustained, late-fight damage rather than early burst.

Overall, Elizabeth Bathory rewards patience and proper team support. She is not a front-loaded carry, but in compositions that can survive long enough for multiple ultimate cycles, she steadily grows into a decisive damage dealer - so long as her DoTs are allowed to stay on the field that is. Anyways, enough with the basics. Let's dive into her ultimate ability "Vampiric Kiss" this is one of the most interesting ultimates in the game in my opinion but also a bit tricky to get a firm grasp on.

![](https://ik-wiki.com/wp-content/uploads/2026/01/image-57.png)

---

## The Ultimate, broken into parts

Bathory’s ultimate does two things:

1. **Applies a DoT**  - Targets: **2 random enemies** (out of 4)
- Damage: **250% ATK every 3s**
- Duration: **15s** (ticks at 3 / 6 / 9 / 12 / 15)
- Rule: **Only one Bathory DoT per enemy**  - Reapplying refreshes the timer
- It does *not* stack
2. **Triggers an explosion**  - If the target **has been attacked by Bathory’s DoT before**
- Deals **530% ATK to all 4 enemies**
- Triggers **per application**
- So a cast can trigger **0, 1, or 2 explosions**

This is the core reason her damage must be treated probabilistically rather than as a fixed number.

---

## Cast timing (why refresh matters)

At **96 regen**, Bathory casts every: 1000/96 = **10.4 seconds**

This matters because:

- The DoT lasts 15 seconds
- The *next cast happens before the last two ticks*

If a target is hit again on the very next cast, its DoT usually only ticks at: **3s, 6s, 9s**
The 12s and 15s ticks are cut off by the refresh.

But — and this is important — **not every target is refreshed**.

---

## Expected DoT damage per application

Take a single enemy that just received Bathory’s DoT.

- It **always** gets the first **3 ticks**
- It only gets the last **2 ticks** if it is **not selected again next cast**

Each cast hits 2 of 4 enemies, so the chance the same enemy is selected again next cast is **50%** likewise, the chance it is *not* refreshed is also **50%**

So the **expected number of ticks per application** is: 3+(2×0.5) = **4 ticks**

Each tick is 250%, so the expected DoT damage per application is 4×250% = **1000%**

Each cast applies the DoT to **2 enemies**, and as such the expected DoT per cast (assuming multiple alive enemy immortals...) is 2×1000% = **2000%**

This already accounts for cases like if the first cast hits enemy A and B and the second cast hits A and C. Then A refreshes early (and explodes), B is completing all the 5 ticks of the DoT and C starts a new DoT effect. Over many fights, this averages out cleanly to **2000% per cast**.

---

## Explosion damage: using A–B–C–D examples

Let's continue thinking about combat encounters where we lable our enemy immortals as: **A, B, C, D**. For examples:

### Cast 1

- Hits: A and B
- No one has been hit before
- **Explosions: 0**

### Cast 2: Now A and B are “tagged.”

If cast 2 hits:

- **C + D** → 0 explosions (this *can* happen)
- **A + C** → 1 explosion
- **A + B** → 2 explosions

All outcomes are valid.

When you average them properly:

- Expected explosions on cast 2 = **1**
- Each explosion = **530% × 4 = 2120% teamwide**

So that means that the value in damage terms, or the expected burst damage on the second cast is = 2120%

---

## Putting it together: real damage over short fights

### Per-cast expectations

So let's say we have Bathory in a sustain setup and she lives comfortably long enough to cast 2 or more ultimates on enemies that are all alive for all three casts (all four enemy immortals). We are then getting 2000% DoT damage from cast one with 0% chance of a burst proc. From the second cast we are getting another avg. 2000% DoT damage and we now on avg. get 2120% damage from burst procs for a total of 4120% damage value of the second cast. Since the Burst effect seems to be working only on enemies afflicted by the DoT effect, all subsequent casts (2+) holds a value of 4120%.

**Disclaimer**: I have watched a lot of Bathory replays to try and figure out if the burst procs are dependent on simple target history or on active DoT applications. For example, if target A had the DoT on the first cast, but by the third cast (20+ seconds) the 15s DoT has expired. **Does Immortal A count as having been "already attacked by this skill"?**

![](https://ik-wiki.com/wp-content/uploads/2026/01/image-47.png)

As far as I can tell watching repeated Bathory replays I cannot find an instance where a target previously hit by a DoT but which has expired by the time it is hit again triggers a burst. As such, I am assuming that the text is mistakenly written as attacked before and instead should read **"has an active application of Vampiric Kiss DoT effect"**. However, I could be wrong. It is quite hard to tell in replays, so if you have better eyes than me, reach out and correct me please!

---

## Closing perspective

Elizabeth Bathory is not an immortal you judge by her first ultimate. She is built around **attrition, repetition, and survival**, and her true value only becomes apparent once she has time to cycle her kit. This is also why she is most often found in earth-builds with access to strong mitigation and sustain.

Players who understand this and build teams that support longer battles with high energy regen and defensive mitigation will consistently get more out of her than players trying to force her into burst-oriented roles. If built right she can be a real monster! Personally I am having much succes with her on the battlefield. However, given the abundance of Theodora's currently, she has lost a lot of value as a main march immortal. But since those enemy players are using Theodora tend to use her in their main march, I have placed Bathory in my second march which means she will carry my second team to victory against most everything that is not an enemy main march - for that I have my own main. Works very well for me and I expect her value to increase once Fu Fei becomes more "normal" to have, i.e. in late-game where most replace Theodora with Fu Fei for control immunity.

---
