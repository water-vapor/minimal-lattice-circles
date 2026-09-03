# Lattice circles

In Sep 2017, I asked a question on mathse about [minimal lattice circles](https://math.stackexchange.com/questions/2422341/finding-circles-on-lattice-points-with-arbitrary-origin). Unable to find public available resources, I restarted the research in Dec 2025. With the help of AI code optimization, I was able to extend the table beyond the current closed-source frontier (reference below). 

My codebase is currently messy, I plan to release it when I have more time to cleanup.

## Comparison with existing efforts

Compared with `enigmatic-code/lattice_circles` master (as of Sep 2026) at commit [`90f186a3a9dc79a967efbe6cf61e52159f8e1fcb`](https://github.com/enigmatic-code/lattice_circles/commit/90f186a3a9dc79a967efbe6cf61e52159f8e1fcb), this repo has:

- **58092** common n values have a strictly smaller radius
- **226998** additional non-trivial n values are included (303157 total vs 76159)
