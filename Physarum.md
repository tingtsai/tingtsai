
This project aims to develop design of micro devices with mesh-like geometries. This is done in the frame of flexible electronics. These designs are usually performed in the frame of CAD design where lines, squares, circles are combined into a hierarchical and engineered arrangement. 

We explore Slime-mold dynamics, inspired by the blog post of Sage Jenson: https://sagejenson.com/physarum
The particles are initialized in the middle of the final perimeter we desire to fill with a mesh-like design. This perimeter is the wavey ring that can be seen in the animation.
In brief, slime mold particles are initialized with a given speed and position, and leave a slowly time-decaying trail as they move about. At the same time, they sense this trail, and depending on its strength, they follow these trails. This converges into interesting structures of which the line thickness, hole size and overall geometry can be controlled with initial parameters.

These structures are interesting because they are automatically generated (no lengthy manual work), and they do not have sharp corners, which is a key feature we pursue in achieving long-term mechanical stability.

The simulations are made with Taichi, a Python-package for efficient (and short code) GPU implementation of large scale simulations. The jupyter notebook is available here : https://github.com/tingtsai/tingtsai.github.io/blob/master/Taichi_slime_mesh_github.ipynb
