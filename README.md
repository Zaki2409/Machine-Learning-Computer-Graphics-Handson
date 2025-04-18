# Machine-Learning-Linear-Transformations-Computer-Graphics
 Application of Linear Transformations
A large number of basic geometric shapes is used in computer graphics. Such shapes (e.g. triangles, quadrilaterals) are defined by their vertexes (corners). Linear transformations are often used to generate complex shapes from the basic ones, through scaling, reflection, rotation, shearing etc. It provides opportunity to manipulate those shapes efficiently.

The software responsible for rendering of graphics, has to process the coordinates of millions of vertexes. The use of matrix multiplication to manipulate coordinates helps to merge multiple transformations together, just applying matrix multiplication one by one in a sequence. And another advantage is that the dedicated hardware, such as Graphics Processing Units (GPUs), is designed specifically to handle these calculations in large numbers with high speed.
