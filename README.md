# Fencing Simulation

Browser-based épée training tools. Each one is a single self-contained HTML file.

## Épée Read Room (`index.html`)

A decision simulator, not a game, built in levels. The aim is a complete view of what you can meet in a bout and how to answer it. Use the Levels menu in the top-right corner to switch between them.

- **Level 0 · Ground.** Shows every decision tree you have built, for every fencer, in one view. Each tree lists your answers, reasoning, verdicts and results. Trees are saved in your browser.
- **Level 1 · Single actions.** Map real scouted opponents: Nat, Nawal and Katya, plus any fencer you add yourself. For each opponent:
  - You edit the tree directly: Opponent → They do (with how often) → You answer → Result.
  - **Check** grades your answer. Results draw on your own experience against that fencer where you have given it, and on textbook outcomes otherwise. It also shows what the same answer gives against the fencer's other actions.
- **Level 2 · Real bout.** Locked for now.

When the page is opened as a Claude artifact, Claude writes the coach's explanations.

## Next stage (`next-stage/bout-trainer.html`)

The full bout version for later:
- nine opponent actions
- score, clock and piste position
- priority minute
- opponents that adapt to your habits
- detailed coach debriefs

## Piste Épée (`arcade.html`)

A real-time side-view épée bout game against an AI opponent.

## Running

Open any of the files in a browser. There is no build step.
