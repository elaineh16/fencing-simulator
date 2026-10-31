# Fencing Simulation

Browser-based épée training tools. Each one is a single self-contained HTML file.

## Épée Read Room, level 1 (`index.html`)

Single actions only. There is no bout, score or clock yet.

- **Four simple opponents.** Each has one attack, one defence and a preference between them:
  - Clara, counter-attacker
  - Pierre, parrier
  - Rafa, rusher
  - Lina, line holder
- **An editable decision tree,** read left to right: Opponent → They do → You answer → Result. You edit everything inside the tree's boxes:
  - how likely each branch is
  - your answer
  - your reasoning
- **Check** shows the result of your answer against that action and grades it as best, works, or loses. It also shows the better answer, and what happens if you misread and they do the other action instead.
- **Bet on a branch** to read one exchange. You get a cue that is honest 75% of the time, then the reveal.
- **Live coach explanations.** When the page is opened as a Claude artifact, Claude explains why your reasoning holds or doesn't.

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
