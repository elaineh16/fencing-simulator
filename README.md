# Fencing Simulation

Two browser-based épée tools, each a single self-contained HTML file.

## Épée Read Room (`index.html`)

A decision trainer for elite épée. Every exchange freezes before you act.

- **Decision tree.** A black-and-white, left-to-right chart: situation → what they might do → your answer → what beats it. The situation is the root. Nine branches cover what the opponent might do: preparation, direct attack, compound attack, attack on the blade, point in line, counter-attack, parry-riposte, draw, and hold. In each branch you rate the likelihood, choose your answer and write your reasoning.
- **Branch checks.** Each answer is graded Optimal, Sound, Suboptimal or Mistake for the current distance, score and clock. You also see every answer ranked, and the opponent actions that beat yours.
- **Play a branch.** You commit to the branch you believe in. The tree then reveals the opponent's real likelihoods, what they actually did, and the pressures behind it.
- **Opponents.** Five fictional opponent personas, each with a different style. They show genuine and decoy cues and adapt to your habits.
- **Bout rules.** Pool (5 touches, 3:00) and direct elimination (15 touches, 3×3:00). Doubles are annulled at the last touch. Ties at time go to a priority minute, and crossing your own end line gives the opponent a touch.
- **Scenario drills.** Set the score, clock, distance and how close you are to your end line, then repeat that one situation.
- **Live role-play.** When opened as a Claude artifact with permission, Claude writes the opponent's lines, the coach's feedback, tree reviews, debriefs and a corner-coach chat. Opened in a plain browser, built-in text is used instead.

## Piste Épée (`arcade.html`)

A real-time side-view épée bout against an AI opponent: footwork, lunges, parries, ripostes and a scoring box. Two hits within 40 ms count as a double touch.

## Running

Open either file in a browser. No build step and no dependencies beyond Google Fonts.
