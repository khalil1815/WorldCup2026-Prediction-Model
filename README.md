# WorldCup2026-Prediction-Model
A hybrid predictive engine for the 2026 FIFA World Cup. Combines a Poisson-based goal model with 10,000-iteration Monte Carlo simulations for knockout rounds. Features dynamic bracket resolution, host-nation performance boosts, and expert domain-knowledge overrides for high-precision tournament outcomes.

# 2026 FIFA World Cup Prediction Engine
An automated machine learning pipeline to predict the 2026 FIFA World Cup outcomes.

## Key Features
- **Poisson Simulation:** Uses Attack/Defense coefficients to model match probabilities.
- **Monte Carlo Engine:** Performs 10,000 simulations per knockout match to maximize point accuracy.
- **Dynamic Bracket:** Automatically resolves group stage outcomes and propagates teams through the knockout bracket.

## Methodology
The model anchors known group-stage results with manual overrides while using probabilistic modeling for the high-multiplier knockout rounds.
## Results
🏆 **Champion:** France
