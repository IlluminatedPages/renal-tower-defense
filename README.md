# Renal Tower Defense

A browser tower defense game about protecting kidney health. Threats travel through the bloodstream toward the kidney; you place healthy-habit towers along the vessel to stop them.

## Play

Open `index.html` in any modern browser. No build step or dependencies.

## How it works

- **5 stages × 5 waves = 25 waves.** Each stage generates a new vessel map with more turns: 2, 4, 6, 8, then 10. Towers are refunded in full when the map changes.
- **Health:** kidney function shown as eGFR, using the KDIGO stage bands (G1 ≥90 to G5 <15). The game ends if eGFR falls below 15.
- **Towers:** Healthy diet (fast, single target), Hydration (long range, slow, splash), BP control (slows).
- **Sound:** synthesised in the browser with Web Audio (background music and effects), with separate music and effects toggles.
- **Enemies and score points:**

| Enemy | Role | Points |
|---|---|---|
| Salt | Swarm | 1 |
| Sugar | Sturdier swarm | 1 |
| Dehydration | Very fast, fragile; Hydration deals triple damage (from stage 2) | 1 |
| Painkiller | Fast | 2 |
| Smoking | Smoke cloud slows nearby towers and hides enemies inside it (from stage 3) | 2 |
| Obesity | Mini-boss; splits into salt and sugar when stopped (from stage 4) | 3 |
| Hypertension | Boss | 3 |
| Diabetes | Boss | 3 |

- **Controls:** keys 1–3 pick a tower, Space starts a wave, Esc cancels. Speed ×1 to ×5, pause, and an auto-start option for the next wave.

## Note

The eGFR figure is a game score, not a medical reading. Health facts in the game are educational summaries and do not replace advice from a doctor.
