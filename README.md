# Renal Tower Defense

> **Branch `v2`: version 2.0 in testing.** Towers are animated kidney-bean mascots that take a 2×2 block, the kidney base reacts to its health, Hydration fires as a mortar, players can drag towers onto the board or tap to place them, mascots share kidney facts when tapped, and a Restart button replays a stage. The live game on `main` stays on v1.1.0 until this branch is merged.

A browser tower defense game about protecting kidney health. Threats travel through the bloodstream toward the kidney; you place healthy-habit towers along the vessel to stop them.

## Play

Open `index.html` in any modern browser. No build step or dependencies.

Works on phones, tablets and desktop browsers. On phones and tablets the weapons and wave controls sit in a tray pinned to the bottom of the screen, and towers are placed with two taps (preview, then confirm).

## How it works

- **Difficulty:** Easy, Medium or Hard, chosen on the title screen. Enemy health compounds each wave by 7%, 12% or 13%, with 160, 120 or 100 starting energy.

- **5 stages × 5 waves = 25 waves.** Each stage generates a new vessel map with more turns: 2, 4, 6, 8, then 10. Towers are refunded in full when the map changes.
- **Health:** kidney function shown as eGFR, using the KDIGO stage bands (G1 ≥90 to G5 <15). The game ends if eGFR falls below 15.
- **Towers:** Healthy diet (fast, single target), Hydration (long-range artillery with splash), BP control (slows).
- **Premium towers:** Exercise (rapid fire, stage 2), Quit smoking (clears smoke, 4× damage to Smoking, stage 3), Health screening (reveals enemies in smoke and makes them take +25% damage, stage 3), Medication (long-range sniper that ignores armour, stage 4).
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

- **Controls:** keys 1–7 pick a tower, Space starts a wave, Esc cancels. Speed ×1 to ×5, pause, and an auto-start option for the next wave.

## Note

The eGFR figure is a game score, not a medical reading. Health facts in the game are educational summaries and do not replace advice from a doctor.
