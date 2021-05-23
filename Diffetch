One way to achieve nanometer-sized structures is to start with a larger, lithographically made microstructure and wet etch in a chemical bath to reduce its size
However, during the etching, the initial shape is slightly distorted as certain parts of the geometry etch faster or slower. 
When studying cell-nanostructure interactions, it is important to properly control for curvature, size, etc. 

We are working on an etching simulation setup with Diff-Taichi. The simulation is differentiable, such that we can tie the input shape to the etched shape
in a way that allows gradient propagation. This means that we can start with an initial shape, simulate the etching, inspect the final etched shape and 
compare it to a geometry we would like to achieve. The discrepancy between the etched shape and our target shape can be then propagated through
the differential simulation in order to adapt the input shape. This is performed iteratively until convergence is reached.

These procedures would save a lot of time in cleanroom process development and provide a way to pre-deform the initial shape that we want to etch down to a smaller shape, in such a way that
the final etched shape is exactly the one we want.
