# prob-synthesis

Numerical results for https://arxiv.org/abs/2303.10860.

These results are produced by Wolfram Mathematica 13.3 and the Ross-Selinger (RS) compiler (https://www.mathstat.dal.ca/~selinger/newsynth/).
To produce the results, follow the instruction provided below.

(1) set a target state, desired approximation error, a directory where programs (XXX_det.bat and XXX_prob.bat) for the RS compiler and their output data (XXX_det.txt and XXX_prob.txt) will be generated, and the file name (XXX) for the programs and the output data in the first input cell of prob_state_synth.nb.

(2) execute the first input cell of prob_state_synth.nb to generate two programs (XXX_det.bat and XXX_prob.bat).

(3) execute the two programs to generate two output data (XXX_det.txt and XXX_prob.txt), which is the description of gate sequences for the state synthesis.

(4) execute the second input cell of prob_state_synth.nb to compute the actual approximation error achieved by a single call of the RS compiler (the deterministic synthesis).

(5) execute the third input cell of prob_state_synth.nb to compute the actual approximation error achieved by the optimal probabilistic synthesis.

(6) execute the fourth input cell of prob_state_synth.nb to compare the approximation errors.
