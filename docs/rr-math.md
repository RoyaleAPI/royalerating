## How this works

**Royale Rating** (RR) aims to give each player a score related to their skill. This allows us to rank players by that score.

Main formula:
```
RR = μ - 3σ
```
**Skill Score** (μ, mu):
- Winning increases your score.
- Losing decreases your score.
- Winning against a higher rated player gives a bigger increase.
- Losing against a lower rated player gives a bigger decrease.
- Draws against higher players increase your score, and decrease it when they are lower.

**Uncertainty** (σ, sigma):
- Playing more games gives a more precise rating, it decreases the uncertainty.
- Winning against higher players and losing to lower players gives a less precise rating, it increases the uncertainty.

**When the uncertainty (σ) decreases enough, your rating is considered to be precise, and RR ≈ μ.**

<img src="/img/rr/rr-curve@4x.png" style="width:100%; height: auto">
