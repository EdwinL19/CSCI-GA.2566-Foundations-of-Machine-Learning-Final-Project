# Abstract
Many learning algorithms optimize surrogate losses instead of the target loss of interest, such as
the 0–1 loss in classification. Thus, a central theoretical question is how minimizing surrogate
risk translates into guarantees on target risk. This paper surveys recent advances in H-consistency
bounds, which provide quantitative, non-asymptotic guarantees relating surrogate excess risk to
target excess risk over restricted hypothesis classes. We review the framework introduced by
Awasthi et al. (2022) and subsequent refinements by Mao et al. (2024b), emphasizing the role
of the tight H-estimation error transformation that characterizes optimal transfers between losses.
We highlight a universal result showing that for a broad class of smooth, convex margin-based
and multi-class comp-sum losses, the transformation exhibits quadratic growth near zero, implying
local square-root bounds on 0–1 excess risk. Beyond classical bounds, we present the Enhanced H-
Consistency Bounds (EHCB) framework introduced by Mao et al. (2024a), which allows instance-
and hypothesis-dependent reweighting and yields strictly sharper guarantees, including improved
convergence exponents under Tsybakov noise conditions. In addition to synthesizing existing theory, 
we contribute several small theoretical supplements, including a proof of the converse of a
previous result for calibrated margin losses and the identification of a gap in a previously published
theorem. Finally, we present original numerical experiments that empirically validate the theoretical 
bounds derived by Mao et al. (2024a) on logistic regression and ReLU neural networks, and
suggest even faster practical behavior in low-noise regimes.
