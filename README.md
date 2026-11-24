# Exact clustering on Darby Bailey's Quesquahedron

This experiment uses the supplied `quesquahedron.html`. It introduces an exact discrete message for a cluster of constraints. The original page simulates waves. Its displayed coherence depends on vertex phases, which advance at prescribed frequencies between resets.

## What is proved

Let q be any odd integer at least 7. Build a system H(q) on V=3q points named A(i), B(i), C(i), with indices modulo q. Matching s has triples (A(i), B(i+s), C(i+2s)) for s=0,1,2,3. Every triple must contain both binary colors. Each matching partitions the points. Two points determine at most one triple. Shifts 0 and 1 connect the system. Giving the A and B groups opposite colors exhibits colorability.

**Recognition from unordered triples.** Assume arbitrary point labels and no names or ordering. At most 64V seed guesses suffice. Each guess completes uniquely in linear time. The algorithm reconstructs the circular layout, the group labels, and the shift arithmetic. A same-degree 39-point control fails all 2,496 seeds. A 3,003-point scrambled instance was reconstructed and verified against all 4,004 triples.

**Exact message transfer.** Actors exchange discrete messages along the fixed 12-cycle from the HTML page. Each actor computes a transfer table. Cyclic closure is enforced by the trace. Counts match a direct oracle on q=7 and q=13.

**Affine dimension.** Every satisfying affine flat on these systems has dimension d ≤ 2V/5. The gap below the universal bound 5V/12 is at least V/60.

## Status

Restricted positive results on one explicit cyclic family. The uniform Residual Exclusion Problem remains open.

Working paper. Independent review remains open.
