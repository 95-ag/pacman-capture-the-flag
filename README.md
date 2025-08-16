# Pacman: Capture the Flag

This project presents a heuristic-based multi-agent implementation for the UC Berkeley Pac-Man Capture the Flag game, focusing on attacker/defender roles and Bayesian inference for partial information environments.

## About

We developed a functional multi-agent solution for Pac-Man: Capture the Flag, combining Minimax-based planning, static role assignment (attacker/defender), and Bayesian inference to estimate opponent locations. The project analyzes advantages and drawbacks of static roles compared to dynamic switching in competitive play.

## Experimental Setup

- Built agents for the UC Berkeley Pacman Capture the Flag AI contest environment.
- Assigned two distinct roles: attacker (uses Minimax with alpha-beta pruning) and defender, both leveraging shared base functions.
- Employed Bayesian inference to update beliefs about hidden opponents using food disappearance, previous sightings, and other signals.
- Tuned parameters for best performance: attack/defend thresholds, step limits, escape heuristics.
- Evaluated effectiveness against varied strategies, highlighting trade-offs in static vs. dynamic team roles.

## Resources

- Full project report: [Multiagent_PacMan_report.pdf](./Multiagent_PacMan_report.pdf)
- Game rules/specifications: [http://ai.berkeley.edu/contest.html](http://ai.berkeley.edu/contest.html)

## References

- UC Berkeley AI: Contest Pacman Capture the Flag. [link](http://ai.berkeley.edu/contest.html)
- Russell, S. J., & Norvig, P., Artificial Intelligence: A Modern Approach. Prentice Hall.
- Edwards & Hart (1963), The Alpha-Beta Heuristic.
- Smyth, Heckerman, & Jordan (1997), Probabilistic Independence Networks.
- DeNero & Klein (2010), Teaching AI with Pacman.

## Acknowledgments

- Developed as part of **Artificial Intelligence and Multi Agent Systems** at KTH Royal Institute of Technology.
- Contributors: Aishwarya Ganesan, Alexander Willemsen
- Forked from original repo: https://github.com/befunger/pacman-ctf.git
- Based on the Pac-Man Capture the Flag framework: [http://ai.berkeley.edu/contest.html](http://ai.berkeley.edu/contest.html)
