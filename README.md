# The Prisoner's Duel: An Interactive Game Theory Simulator in one html page

## Introduction

Welcome to The Prisoner's Duel, an interactive game theory simulator based on the classic Prisoner's Dilemma. This project aims to provide an engaging way to explore fundamental concepts in game theory, decision-making, and strategic interaction. Enjoy it here: https://prisonersduel.netlify.app/

## The Birth of Game Theory

On September 3, 1949, an American weather monitoring plane collected air samples over Japan, finding traces of radioactive material. The United States Navy tested rainwater samples from ships and bases worldwide, detecting small amounts of Cerium-141 and Yttrium-91. These isotopes, with half-lives of one or two months, must have been produced recently, and the only place they could have come from was a nuclear explosion. The United States had not conducted any tests that year, so the only possible conclusion was that the Soviet Union had learned to build a nuclear bomb.

This was the news Americans had feared. Their military supremacy, achieved through the Manhattan Project, was rapidly fading. Some believed the best course of action was to launch an unprovoked nuclear strike against the Soviets while they still had the advantage. According to Navy Secretary Matthews, it was necessary to become "aggressors for peace."

John von Neumann, the founder of game theory, stated: "If you say why not bomb them tomorrow, I say why not bomb them today? If you say today at five o'clock, I say why not at one o'clock?" Something needed to be done about nuclear weapons, and quickly. In 1950, the RAND Corporation, a US-based think tank, studied this question using game theory. That same year, two mathematicians at RAND invented a new game that, unbeknownst to them at the time, closely resembled the US-Soviet conflict. This game is now known as the prisoner's dilemma. (more info here: https://youtu.be/mScpHTIi-kM?si=QtC0tk1n70no37os)

## Game Rules

The Prisoner's Duel is a two-player game where each player must choose to either "Cooperate" or "Betray" in each round. The payoffs for each combination of choices are as follows:

- Both Cooperate: Each player receives 3 points (R - Reward)
- Both Betray: Each player receives 1 point (P - Punishment)
- One Betrays, One Cooperates: The betrayer receives 5 points (T - Temptation), the cooperator receives 0 points (S - Sucker's payoff)

These payoffs satisfy the conditions for a Prisoner's Dilemma:
1. T > R > P > S
2. 2R > T + S

This structure creates a tension between individual and collective interests, as mutual cooperation yields the best collective outcome, but there's always a temptation to betray for individual gain.

## Strategies

The game includes several pre-programmed strategies, each with its own approach to the dilemma:

1. **Random**: Randomly chooses between cooperation and betrayal.
2. **Tit for Tat**: Starts by cooperating, then mimics the opponent's last move.
3. **Majority**: Chooses the action the opponent has used most frequently.
4. **Always Cooperate**: Always chooses to cooperate, regardless of the opponent's actions.
5. **Always Betray**: Always chooses to betray, aiming for the highest individual reward.
6. **Grudger**: Starts by cooperating but will always betray if the opponent ever betrays.
7. **Prober**: Initially probes with a betrayal, then plays Tit for Tat if the opponent retaliates, otherwise continues to betray.
8. **Pavlovian**: Repeats its previous action if it earned a high reward, otherwise switches.
9. **Random Tit for Tat**: Mostly plays Tit for Tat but occasionally introduces randomness.

## Game Mechanics

1. Each game consists of a set number of rounds (5, 10, 20, 50, or 100).
2. In each round, you choose to either cooperate or betray.
3. Your opponent (the computer) uses one of the pre-programmed strategies, chosen randomly at the start of each game.
4. Points are awarded based on the choices made by both players.
5. At the end of all rounds, the player with the highest total score wins.

## Strategy Editor

The game includes a strategy editor where you can modify existing strategies or create new ones. This feature allows you to experiment with different approaches and test their effectiveness against various opponents.

## Relevance to Game Theory

This simulator demonstrates several key concepts in game theory:

1. **Nash Equilibrium**: In a single round, mutual betrayal is the Nash Equilibrium, as neither player can improve their outcome by unilaterally changing their strategy.

2. **Pareto Optimality**: Mutual cooperation is Pareto optimal, as it produces the best collective outcome.

3. **Evolutionary Stability**: In repeated games, strategies like Tit for Tat can become evolutionarily stable, encouraging cooperation.

4. **The Shadow of the Future**: The possibility of future interactions (in multi-round games) can promote cooperation.

## Applications

The Prisoner's Dilemma has wide-ranging applications, including:

- International relations and arms races
- Business competition and collusion
- Environmental conservation efforts
- Public health initiatives
- Social psychology and trust-building

By playing this game and experimenting with different strategies, you can gain insights into these real-world scenarios and the complex dynamics of cooperation and conflict.

