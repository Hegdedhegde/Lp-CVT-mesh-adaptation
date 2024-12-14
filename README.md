This repo has 2 parts:
1. An analytical metric - where the mesh is adapted according to the analytical metric given. Interpolation process not required as metric can be obtained by just substituting the coordinates.
2. Discrete metric - where a target discrete metric field is given, according to which the mesh is adapted. It has 2 sections:
   2.1 With boundary discretization - the boundary edges are discretized first according to the metric field, after whihc the internal mesh vertices are adapted
   2.2 Without boundary discretization - direct adaptation of the internal vertices are performed.
