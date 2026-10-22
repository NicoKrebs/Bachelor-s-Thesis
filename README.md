Abstract

Real-world high-dimensional data typically concentrates on a low-dimensional manifold. Generative
modelling learns a representation of this manifold in a low-dimensional latent space. Such a
manifold can carry non-trivial topology, for instance when the data generating process has a
compact symmetry group, which a contractible Euclidean latent space cannot encode continuously
without necessarily increasing in dimension. This thesis investigates the differential geometric
connection between the topology and the information geometry of latent spaces, by constructing
a latent space formalism to which the Chern–Gauss–Bonnet theorem applies. We develop an
intrinsic information geometric framework for latent spaces from the Fisher information metric
and construct two variational autoencoders whose latent spaces carry the prescribed topologies
of the two-dimensional sphere and the torus, together with the methodology needed to evaluate
the latent geometry. On datasets with enforced topology, the numerically integrated curvature
reproduces the correct Euler characteristic of the latent space and matching latent topology to data
topology improves reconstruction fidelity. Visualising the learned geometry shows that curvature
concentrates where a Euclidean latent space representation fails. The result is numerical access to
intrinsic geometric and topological quantities of learned representations.
