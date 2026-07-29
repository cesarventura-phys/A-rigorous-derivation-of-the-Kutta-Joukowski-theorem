# A-rigorous-derivation-of-the-Kutta-Joukowski-theorem

A recurring limitation in many fluid mechanics textbooks and lecture notes is the treatment of the classical lift derivation. While the final result (relating lift per unit span to density, freestream velocity, and circulation) is universally presented, the intermediate mathematical justifications are frequently abbreviated.  This document was written to fill that gap, providing a rigorous step-by-step derivation for the curious who are comfortable with complex variables.


Derivation framework:

🔹 Setting the stage: We begin by combining the velocity potential and stream function into a single complex potential. From this, the complex velocity follows naturally, together with the Cauchy-Riemann conditions that guarantee analyticity.

🔹 Looking at the far field: Next, we examine the behavior of the potential at infinity through it's Laurent expansion. Evaluating a contour integral around the body reveals the leading residue, which turns out to be the circulation.

🔹 From pressure to force: Bernoulli's equation relates the surface pressure to the velocity field. The resulting force integral can then be rewritten in the compact contour form given by Blasius, expressed in terms of the square of the complex velocity.

🔹 The final result: With the contour integral evaluated, the conclusion follows immediately. In ideal flow, the drag is identically zero, while the lift is simply the product of the fluid density, the freestream velocity, and the circulation.


This document is intended as a reference for students, engineers, and physicists seeking a clear, lecture-ready derivation with every mathematical step made explicit.
