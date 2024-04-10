# DephasedEmbedding
This repository stores the codes used in the paper "Contextuality with vanishing coherence and maximal robustness to dephasing" by Vinicius P. Rossi, David Schmid, John H. Selby and Ana Belén Sainz.

# Files
- SimplexEmbedding.nb: Finds a simplex embedding for a depolarised version of the input accessible GPT fragment. From https://github.com/eliewolfe/SimplexEmbedding
- DephasedEmbedding.nb: Modification of SimplexEmbedding.nb for a dephased version of the input accessible GPT fragment. Works only for fragments restricted to the real hemisphere of the Bloch sphere.
- SD-depolarising-numeric.nb: Plots robustness to depolarisation for the minimum-error state discrimination scenario w.r.t. the parameter θ
- SD-dephasing-numeric.nb: Plots robustness to dephasing w.r.t. to the Z axis for the same scenario and parameter
- rotated-SD-dephased-numeric.nb: Plots robustnes to dephasing w.r.t. to the X axis for the same scenario and parameter
- SD-dephased&rotated.nb: Plots robustness to dephasing w.r.t. to a varrying axis that starts align with the Z axis and finishes align to the X axis, for the same scenario and parameter
- SD-dephased&mixed.nb: Plots robustness to dephasing w.r.t. the Z axis for the same scenario and dephasing, but with discriminating measurements depolarised by a parameter p.

# Acknowledgements
We thank Elie Wolfe for the ready support with the linear program functioning. DS, VR, and ABS were supported by the Foundation for Polish Science (IRAP project, ICTQT, contract no. MAB/2018/5, co-financed by EU within Smart Growth Operational Programme). JHS was supported by the National Science Centre, Poland (Opus project, Categorical Foundations of the Non-Classicality of Nature, project no.~2021/41/B/ST2/03149). 
