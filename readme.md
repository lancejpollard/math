# Math for the Layman

This resource aims to be a complete introduction to all of modern math. A broad overview so you can see the playing field and get to know the central structures.

Modern math is basically a bunch of terms for relatively simple things. The terms often involve people's names, which give no hint at the underlying structure. But it is necessary to use something like people's names because the structure is subtle with a long definition and properties which define it, so identifying that suite of properties by an ID other than a number is helpful so you don't mix things up.

## Overview of the Mathematical Objects, Actions, and Features

Math boils down to these sorts of objects, actions, and features:

- objects
  - list (vector)
  - list list (tensor, matrix)
  - unique list (set)
  - space (physical space)
  - point (in space)
    - vertex (point connected by lines)
  - link (edge)
  - relation
  - line
  - path
  - number
  - net
  - map
  - repeat
  - position
  - type
  - loop
    - cycle
  - field
    - curve
    - surface
    - volume
  - symmetry
  - machine (automata)
  - rule (if-then)
  - combinator (group)
    - 1-combinator (group)
    - 2-combinator (ring)
    - 4-combinator (field)
  - sequence
  - series
- actions
  - operations (actions on objects)
  - transformation
    - rotate
      - pitch
      - roll
      - yaw
    - skew
    - translate
    - scale
    - reflect
  - combination
    - add
    - subtract
    - multiply
    - divide
- features
  - associative
  - homeomorphic
  - complete
  - isogonal
    - each vertex is equivalent under symmetries of figure

Each of these has dozens or hundreds of sub-types focusing on different aspects of the structure.

## Renaming the Mathematical Structures

## Why _it_ is Interesting

This section outlines some of the reasons why specific objects, actions, or features in math are interesting.

- Lie groups
- Clifford algebras
- Vectors
- Matrices

### The Structure of Subatomic Particles

A [particle](https://en.wikipedia.org/wiki/Subatomic_particle) is an irreducible representation of the Poincar?? group. The local $SU(3)??SU(2)??U(1)$ gauge symmetry is an internal symmetry that essentially defines the Standard Model. The quantum chromodynamics (QCD) sector defines the interactions between quarks and gluons, which is a Yang???Mills gauge theory with $SU(3)$ symmetry. The electroweak sector is a Yang???Mills gauge theory with the symmetry group $U(1)????????SU(2)_L$. In the Standard Model, the Higgs field is a complex scalar of the group $SU(2)_L$.

The local SU(3) x SU(2) x U(1) gauge symmetry is important in the Standard Model of particle physics. The Standard Model describes the behavior of the three fundamental forces in nature (electromagnetism, weak nuclear force, and strong nuclear force) and the behavior of all known elementary particles. The SU(3) symmetry describes the strong nuclear force, which is responsible for holding the protons and neutrons in an atom's nucleus together. The SU(2) symmetry describes the weak nuclear force, which is responsible for certain types of radioactive decay. The U(1) symmetry describes the electromagnetic force.

The local nature of the symmetry means that the symmetry can be different at different points in space-time, which allows for the interactions between particles to be described by the exchange of gauge bosons. This theory has been extremely successful in explaining the behavior of particles and their interactions, and has been experimentally verified through a wide range of experiments.

### Drawing on the Computer Screen

Stereographic projection.

### Mapping the Earth's Surface

Mercator projection.

### Mapping Mouse Click to a Graphic

### The Structure of Spacetime

The Minkowski model of spacetime is based on the idea that spacetime can be represented as a four-dimensional vector space, with three dimensions of space and one dimension of time. This model is the foundation of special relativity, which is a theory that describes the fundamental properties of space and time in the absence of gravity. In this model, the spacetime interval between two events is given by a formula known as the Minkowski metric, which is used to measure the distance between events in spacetime. The Minkowski model of spacetime is also the foundation of the mathematical framework used in the study of quantum field theory and the theory of general relativity.

### The Amplituhedron

As a possible model of subatomic particles, this model is very new and interesting. The mathematical structure underlying the model of the amplituhedron is called a Grassmannian. A Grassmannian is a type of algebraic variety that consists of all subspaces of a given vector space of a fixed dimension. The amplituhedron is a particular type of Grassmannian called a positive Grassmannian. It is defined as the set of all subspaces of a given vector space that are positive in a certain sense. The amplituhedron model is based on the idea that the scattering amplitudes in certain quantum field theories can be represented as geometric objects in a positive Grassmannian, and this representation allows for a more efficient and intuitive calculation of these amplitudes. To work with the amplituhedron, one uses the tools of algebraic geometry and the theory of geometric representations of Lie groups.

An alternative to the amplituhedron is the associahedron, which is another geometric object that can be used to encode the amplitudes of certain theories, this time in the context of the study of the amplitudes of gravity and Yang-Mills theory. The associahedron is a convex polytope. It is a higher-dimensional generalization of the well-known two-dimensional pentagon (a five-sided polygon) and the three-dimensional cube. The associahedron can be defined as the convex hull of the set of all possible parenthesizations of a given sequence of elements.

### Spinors in Physics

The mathematics behind spinors is based on the theory of Clifford algebras and the representation of rotations in higher-dimensional Euclidean spaces. A spinor is a type of vector in a vector space equipped with a quadratic form, which can be used to represent rotations in the space. Spinors are used in various areas of physics, including quantum mechanics, general relativity, and particle physics. They are particularly useful in representing the symmetries of spacetime, as they can be used to represent the action of the Lorentz group, which is the group of all possible Lorentz transformations. In particular, in physics, spinors are used to represent states of particles with intrinsic angular momentum, known as spin.

### Grand-Unified Theories (GUTs) in Physics

[SO(10)](<https://en.wikipedia.org/wiki/SO(10)>) refers to a grand unified theory (GUT) based on the spin group $Spin(10)$.

In grand unification theories, [E6](<https://en.wikipedia.org/wiki/E6_(mathematics)>) appears as a possible gauge group which, after its breaking, gives rise to the SU(3) ?? SU(2) ?? U(1) gauge group of the standard model.

[AdS/CFT correspondence](https://en.wikipedia.org/wiki/AdS/CFT_correspondence)

### Quantum Mechanics

In quantum mechanics, symmetries play a crucial role in determining the behavior of physical systems. Group theory is a powerful mathematical tool that is used to describe and analyze these symmetries.

In quantum mechanics, Hilbert space is used to mathematically represent the state space of a quantum system. It is a complex vector space equipped with an inner product, and it is used to describe the wave function of a quantum system. The wave function, which is a mathematical function that describes the state of a system, is typically represented as a vector in Hilbert space. The inner product on Hilbert space allows for the calculation of probabilities and the creation of probability distributions. Additionally, the mathematical structure of Hilbert space allows for the use of linear algebraic techniques to study the time evolution of a quantum system. In short, the use of Hilbert space in quantum mechanics allows for a precise mathematical description of quantum systems, which is essential for understanding their behavior and making predictions about their future states.

### Quantum Computing

### Visual Object Recognition

In computer vision, visual object boundary detection is the process of detecting the boundaries of objects in images or videos. The math behind this process typically involves the use of image processing techniques such as filtering, thresholding, edge detection, and segmentation. One popular method for boundary detection is the Canny edge detection algorithm, which uses a combination of gradient magnitude and direction to identify edges in an image. Other methods include the use of active contours, also known as snakes, which are used to model the boundaries of objects, and deep learning-based methods that use convolutional neural networks to learn features from images and detect boundaries.

### Automatic Layouts

### Representing Knowledge Webs

### Compiling Software

### Automatic Software Verification

### Typing your Code

This makes it so the compiler detects errors before your program runs.

### Parsing Text

### The Block Chain

### String Theory

### Special and General Relativity

In physics, the unit hyperbola plays an important role in the theory of special relativity, where it is used to describe the relationship between space and time. The unit hyperbola is also used in the study of phase space in mechanics, where it is used to describe the possible states of a system.

### Hyperbolic Tessellations

### Cellular Automata

## Appendix

Here we go into a bunch of common mathematical structures, first starting with general high-level structures, then digging down into lists of structures in categories which have lots of named structures.

### Mathematical Structures

1. **Group**: a set with a binary operation that satisfies associativity, the existence of an identity element, and the existence of inverse elements.
1. **Ring**: a set with two binary operations, usually called addition and multiplication, that satisfy certain properties such as associativity, the existence of identity elements and inverse elements, and the distributive property.
1. **Field**: a commutative ring with a non-zero multiplicative identity and in which every non-zero element has a multiplicative inverse.
1. **Lattice**: a partially ordered set in which every two elements have a unique least upper bound and greatest lower bound
1. **Space**
1. **Algebra**: a set with one or more operations that satisfy certain properties such as associativity, distributivity, and the existence of identity elements and inverse elements.
1. **Knot**: a closed loop of a smooth curve in 3-dimensional space.
1. **Domain**
1. **Codomain**
1. **Mapping**
1. **Hyperbola**
1. **Parabola**
1. **Simplical Complex**
1. **Polytope**
1. **Polygon**
1. **Torque**
1. **Momentum**
1. **Sheaf**: a mathematical object that describes how local data on a topological space can be glued together to form global data.
1. **Vector Bundle**: a mathematical object that locally looks like a direct product of a topological space with a vector space, but globally may have a more complicated structure.
1. **Manifold**: a topological space that locally looks like Euclidean space of a certain dimension.
1. **Algebraic Variety**: the set of common solutions of a system of polynomial equations in several variables.
1. **Cohomology**: a mathematical tool that describes how global data on a topological space can be reconstructed from local data.
1. **Homotopy**: a mathematical tool that describes how different continuous functions between topological spaces are "similar" in some sense.
1. **Tensor**: a multidimensional array of numbers, with certain transformation properties under changes of coordinates.
1. **Spectral sequence**: a tool for computing the cohomology of a space by studying the cohomology of simpler spaces related to it
1. **Schemes**: a generalization of algebraic varieties in which the polynomial equations are replaced by more general equations
1. **Differential forms**: a mathematical tool used to integrate functions over manifolds
1. **Category**: a mathematical structure that describes how different mathematical objects are related to each other
1. **Functor**: a mathematical tool that describes how different mathematical structures are related to each other
1. **Homology**: a tool for studying topological spaces by associating algebraic structures to them.
1. **Graph**: a mathematical object consisting of a set of vertices and edges connecting them, used to model various relations between objects.
1. **Module**: a generalization of vector spaces where the scalars come from a ring rather than a field.
1. **Quiver**: a directed graph used to represent algebraic structures such as representations of algebras.
1. **Monoid**: a semigroup with an identity element.
1. **Semigroup**: a set with an associative binary operation.
1. **Magma**: a set with a binary operation.
1. **Vertex**
1. **Edge**
1. **Tree**
1. **List**
1. **Language**
1. **Automaton**
1. **Complex**
1. **Chain**
1. **Cochain**
1. **Hypercycle**
1. **Horocycle**
1. **Horosphere**
1. **Hypersurface**
1. **[Fiber bundle](https://en.wikipedia.org/wiki/Fiber_bundle)**
1. **[Submersion](<https://en.wikipedia.org/wiki/Submersion_(mathematics)>)**
1. Geodesic
1. Angle
1. Radius
1. Sector
1. Vector
1. Magnitude
1. Scalar
1. Determinant
1. Isomorphism
1. Homomorphism
1. Diffeomorphism
1. Monomorphism
1. Endomorphism
1. Morphism
1. Quaternion
1. Octonion

### Mathematical Geometries

#### List of Mathematical Geometries

1. **Hyperbolic geometry**: the study of the geometry of hyperbolic space, which is negatively curved.
1. **Elliptic geometry**: the study of the geometry of elliptic space, which is positively curved.
1. **Fractal geometry**: the study of geometric shapes that exhibit self-similarity at different scales.
1. **Sub-Riemannian geometry**: the study of Riemannian geometry with a constraint on the admissible directions.
1. **Tropical geometry**: the study of geometry over the tropical semiring and tropical varieties.
1. **Lorentzian geometry**: the study of smooth manifolds equipped with a Lorentzian metric, which allows for the calculation of spacetime intervals and the study of special relativity.
1. **K??hler geometry**: a type of Riemannian geometry that is particularly well-suited to complex manifolds and holomorphic functions.
1. **Tensor geometry**: the study of geometric properties that can be expressed using tensors, such as the Riemann curvature tensor.
1. **Euclidean geometry**: a type of geometry that deals with the properties and relations of points, lines, angles, and figures in two- and three-dimensional space, based on the axioms of Euclid.
1. **Non-Euclidean geometry**: a type of geometry that extends Euclidean geometry by dropping or modifying one or more of Euclid's axioms. Examples include hyperbolic and elliptic geometry.
1. **Riemannian geometry**: a type of geometry that deals with the properties and relations of points, lines, angles, and figures in a general smooth n-dimensional manifold, based on the concept of a Riemannian metric.
1. **Finsler geometry**: a type of geometry that generalizes Riemannian geometry by replacing the Riemannian metric with a Finsler metric, which is a function that assigns a non-symmetric norm to each tangent vector of the manifold.
1. **Projective geometry**: a type of geometry that deals with the properties and relations of points, lines, angles, and figures in a projective space, which is a space formed by taking the quotient of a vector space by a scalar multiplication action.
1. **Conformal geometry**: a type of geometry that deals with the properties and relations of points, lines, angles, and figures that are preserved under a conformal transformation, which is a type of transformation that preserves angles but not necessarily lengths or areas.
1. **Differential geometry**: a type of geometry that deals with the properties and relations of points, lines, angles, and figures in a smooth n-dimensional manifold, based on the concept of a differential structure, which is a way of defining a smooth function and a smooth vector field on the manifold.
1. **Algebraic geometry**: a type of geometry that deals with the properties and relations of points, lines, angles, and figures in an algebraic variety, which is a solution set of a system of polynomial equations in n variables.
1. **Synthetic geometry**: a type of geometry that deals with the properties and relations of points, lines, angles, and figures without the use of coordinates or measurements, based on the concept of primitive notions such as point, line, and incidence.
1. **Discrete geometry**: a type of geometry that deals with the properties and relations of points, lines, angles, and figures in discrete structures such as graphs, polyhedra, and tilings.
1. **Affine geometry**: the study of geometric properties that remain invariant under translation, rotation and scaling.

### Mathematical Groups

#### List of Mathematical Groups

1. **Finite groups**: A group with a finite number of elements.
1. **Infinite groups**: A group with an infinite number of elements.
1. **Abelian groups**: A group in which the group operation is commutative.
1. **Cyclic groups**: A group that is generated by a single element.
1. **Dihedral groups**: A group that is the symmetry group of a regular polygon.
1. **Quaternion groups**: A non-abelian group of order 8.
1. **Permutation groups**: A group of bijective functions from a set to itself.
1. **Matrix groups**: A group of invertible matrices under matrix multiplication.
1. **Lie groups**: Continuously differentiable groups that are also smooth manifolds.
1. **Symmetric groups**: The group of all permutations of a finite set.
1. **Automorphism groups**: The group of all automorphisms of a given group or algebraic structure.
1. **Galois groups**: The group of automorphisms of a field extension.
1. **Holomorph groups**: The group of holomorphic automorphisms of a complex manifold.
1. **Homotopy groups**: The group of homotopy classes of continuous maps between two topological spaces.
1. **Homology groups**: The group of cycles modulo boundaries in a chain complex.
1. **Simple groups**: A non-abelian group with no proper, non-trivial normal subgroups.
1. **Solvable groups**: A group that can be constructed from abelian groups using a finite number of extensions.
1. **Nilpotent groups**: A group in which the subgroups of all orders are normal subgroups.
1. **Supersolvable groups**: A solvable group in which all subnormal subgroups are abelian.
1. **p-groups**: A group in which the order of every element is a power of a prime p.
1. **Free groups**: A group with a set of generators and no relations.
1. **Direct product groups**: The direct product of two or more groups.
1. **Torsion groups**: A group in which every element has finite order.
1. **Torsion-free groups**: A group in which there are no elements of finite order.
1. **Hyperbolic groups**: A group that acts properly discontinuously on a hyperbolic space.
1. **Thompson groups**: A family of groups related to the study of homeomorphisms of the unit interval.
1. **Burnside groups**: A group in which the number of elements of a given order is bounded by a polynomial function.
1. **Thompson-Stein groups**: A group that contains a Thompson group and a Stein group as subgroups.
1. **Compact groups**: A group that is also a compact topological space.
1. **Compact Lie groups**: A Lie group that is also compact.
1. **Reductive groups**: A group that acts on a vector space in a certain way.
1. **Algebraic groups**: A group that can be defined by polynomial equations.
1. **Linear groups**: A group that can be represented by matrices.
1. **Unitary groups**: A group of unitary matrices.
1. **Orthogonal groups**: A group of orthogonal matrices.
1. **Special linear groups**: A group of matrices that preserve a nondegenerate bilinear form.
1. **Special unitary groups**: A group of matrices that preserve a Hermitian form.
1. **Special orthogonal groups**: A group of matrices that preserve an inner product.
1. **Projective groups**: A group that acts on a projective space.
1. **Conformal groups**: A group of conformal transformations of a space.
1. **Cremona groups**: A group of birational transformations of an algebraic variety.
1. **Braid groups**: A group related to the study of braids.
1. **Discrete groups**: A group whose underlying set is discrete.
1. **Continuous groups**: A group whose underlying set is topological.
1. **Locally compact groups**: A topological group whose underlying set is locally compact.
1. **Topological groups**: A group with a topological structure.
1. **Quantum groups**: A group that arises in the study of quantum mechanics.
1. **Lie groups**: A group that is also a smooth manifold.
1. **Compact matrix groups**: A subgroup of GL(n, C) that is compact as a topological space.
1. **Coxeter groups**: A group defined by a set of reflections and relations between them.
1. **Artin groups**: A group defined by a set of relations between generators.
1. **Mapping class groups**: A group of self-homeomorphisms of a surface.
1. **Outer automorphism groups**: A group of automorphisms of a group that are not inner automorphisms.
1. **Automorphism groups**: A group of automorphisms of a group.
1. **General linear groups**: A group of invertible matrices.
1. **[Indefinite orthogonal group](https://en.wikipedia.org/wiki/Indefinite_orthogonal_group)**

### Mathematical Matrices

#### List of Mathematical Matrices

1. **Square matrix**: A matrix with the same number of rows and columns.
1. **Diagonal matrix**: A square matrix where all the entries outside the main diagonal are zero.
1. **Identity matrix**: A square matrix with all the diagonal entries as 1 and all the other entries as 0.
1. **Triangular matrix**: A square matrix where all the entries below or above the main diagonal are zero.
1. **Lower triangular matrix**: A triangular matrix where all the entries above the main diagonal are zero.
1. **Upper triangular matrix**: A triangular matrix where all the entries below the main diagonal are zero.
1. **Scalar matrix**: A diagonal matrix where all the diagonal entries are the same scalar value.
1. **Symmetric matrix**: A square matrix that is equal to its transpose.
1. **Skew-symmetric matrix**: A square matrix where its transpose is its negation.
1. **Orthogonal matrix**: A square matrix where its inverse is equal to its transpose.
1. **Hermitian matrix**: A complex square matrix that is equal to its conjugate transpose.
1. **Skew-Hermitian matrix**: A square matrix where its conjugate transpose is its negation.
1. **Unitary matrix**: A complex square matrix that is equal to its inverse.
1. **Diagonalizable matrix**: A matrix that can be transformed into a diagonal matrix through similarity transformations.
1. **Tri-diagonal matrix**: A matrix where all the entries outside the main diagonal and the two diagonals immediately adjacent to it are zero.
1. **Block matrix**: A matrix composed of smaller matrices called blocks.
1. **Vandermonde matrix**: A matrix whose entries are powers of a given set of scalars.
1. **Hankel matrix**: A matrix whose entries are constant along each anti-diagonal.
1. **Toeplitz matrix**: A matrix whose entries are constant along each diagonal.
1. **Cauchy matrix**: A matrix whose entries are the ratio of the product of a given set of scalars and a given set of scalars shifted by one position.
1. **Circulant matrix**: A matrix whose elements are formed by taking cyclic shifts of a given set of scalars.
1. **Frobenius matrix**: A matrix whose eigenvalues are the same as the eigenvalues of its transpose.
1. **Jordan matrix**: A matrix in the Jordan normal form, which is a special form of a matrix consisting of Jordan blocks.
1. **Invertible matrix**: A matrix that has an inverse.
1. **Singular matrix**: A matrix that does not have an inverse.
1. **Rectangular matrix**: A matrix that has a different number of rows and columns.
1. **Transpose matrix**: A matrix that is obtained by interchanging the rows and columns of the original matrix.
1. **Adjugate matrix**: A matrix whose entries are the determinants of the sub-matrices of the original matrix.
1. **Cofactor matrix**: A matrix whose entries are the determinants of the sub-matrices of the original matrix multiplied by -1^(i+j) where i,j are the row and column of the entry in the matrix respectively.
1. **Eigen matrix**: A matrix whose eigenvectors and eigenvalues can be calculated.
1. **Normal matrix**: A matrix that commutes with its adjoint.
1. **Perturbation matrix**: A matrix that describes a small change in the original matrix
1. **Projection matrix**: A matrix that projects a vector.
1. **Positive definite matrix**: A symmetric matrix with all positive eigenvalues
1. **Positive semi-definite matrix**: A symmetric matrix with non-negative eigenvalues
1. **Negative definite matrix**: A symmetric matrix with all negative eigenvalues
1. **Negative semi-definite matrix**: A symmetric matrix with non-positive eigenvalues
1. **Indefinite matrix**: A matrix that is neither positive definite nor negative definite
1. **Sparse matrix**: A matrix with a large number of zero entries
1. **Density matrix**: A matrix used in quantum mechanics to describe the state of a quantum system
1. **Confusion matrix**: A matrix used in machine learning to evaluate the performance of a classification algorithm
1. **Incidence matrix**: A matrix used in graph theory to represent the edges of a graph
1. **Laplacian matrix**: A matrix used in graph theory to represent the connectivity of a graph
1. **Distance matrix**: A matrix used in data analysis to represent the distances between elements of a dataset
1. **Gram matrix**: A matrix used in linear algebra and machine learning to represent the inner products of a set of vectors
1. **Hessian matrix**: A matrix used in calculus to represent the second partial derivatives of a function
1. **Jacobian matrix**: A matrix used in calculus to represent the first partial derivatives of a function
1. **Kinematic matrix**: A matrix used in robotics and mechanics to represent the motion of a system
1. **Linear transformation matrix**: A matrix used to represent a linear transformation of a vector space
1. **Moment of inertia matrix**: A matrix used in physics to represent the distribution of mass in a rotating body.

### Mathematical Spaces

#### List of Mathematical Spaces

- https://en.wikipedia.org/wiki/List_of_topologies

1. **Euclidean space**: A mathematical space where the distance between two points is defined by the Euclidean distance formula, often used in geometry and physics.
1. **Affine space**: A mathematical space that is a generalization of Euclidean space, where the parallelism of lines is defined, but not the congruence of figures.
1. **Projective space**: A mathematical space formed by the set of lines passing through the origin of a vector space. It is used in projective geometry.
1. **Vector space**: A mathematical space that is closed under operations of vector addition and scalar multiplication, and it is used in linear algebra.
1. **Banach space**: A complete normed vector space, and it is used in functional analysis.
1. **Topological space**: A mathematical space that has a notion of continuity, and it is used in topology.
1. **Metric space**: A generalization of Euclidean space where a metric (distance function) is defined, and it is used in analysis.
1. **Normed vector space**: A vector space with a notion of length (or "size"), and it is used in functional analysis.
1. **Measure space**: A mathematical space that carries a measure, a way to assign a size to subsets, and it is used in measure theory and integration.
1. **Function space**: A mathematical space consisting of a set of functions, and it is used in various branches of mathematics, such as functional analysis and differential equations.
1. **Manifold**: A topological space that locally resembles Euclidean space, and it is used in differential geometry.
1. **Phase space**: A mathematical space in which all possible states of a physical system are represented, and it is used in classical mechanics and thermodynamics.
1. **Configuration space**: A mathematical space that describes the possible configurations of a mechanical system, and it is used in mechanics and physics.
1. **State space**: A mathematical space that describes the set of all possible states of a system, and it is used in systems theory and control theory.
1. **Moduli space**: A mathematical space that describes the set of all possible configurations of a system up to certain equivalence relations, and it is used in physics and mathematics.
1. **Representation space**: A mathematical space that describes the set of all possible ways to represent a certain object, and it is used in group theory and physics.
1. **Teichm??ller space**: A mathematical space that describes the set of all possible complex structures on a certain topological space, and it is used in complex analysis and geometry.
1. **Grassmannian**: A mathematical space that describes the set of all possible subspaces of a given vector space, and it is used in algebraic geometry and representation theory.
1. **Flag variety**: A mathematical space that describes the set of all possible flags of subspaces of a given vector space, and it is used in algebraic geometry and representation theory.
1. **Symmetric space**: A Riemannian manifold that is invariant under a transitive group of isometries.
1. **Quotient space**: A space formed by the set of all possible cosets of a subgroup of a group with respect to a given group action.
1. **Orbit space**: The set of all possible orbits of a group action on a space.
1. **Product space**: The cartesian product of two or more spaces, with the product topology.
1. **Normed space**: A topological vector space with a norm, which defines a notion of length for vectors.
1. **Compact space**: A space in which every open cover has a finite subcover.
1. **Connected space**: A space in which there is no separation into two nonempty disjoint open sets.
1. **path-connected space**: A space in which there is a path between any two points
1. **locally path-connected space**: A space in which for any point, there is a neighbourhood that is path-connected.
1. **Simply connected space**: A space that is path-connected and has no nontrivial loops.
1. **K-space**: A space in which all compact subsets are closed.
1. **Hausdorff space**: A space in which any two distinct points have disjoint neighborhoods.
1. **Alexandrov space**: A space in which any two points can be joined by a geodesic.
1. **Baire space**: A space in which the intersection of countably many dense open sets is dense.
1. **Stone space**: A space in which the continuous functions are precisely the functions that are determined by their values on a dense subset.
1. **Frechet space**: A complete metrizable locally convex topological vector space
1. **nuclear space**: A topological vector space that is the inductive limit of a sequence of finite-dimensional spaces.
1. **Fr??chet???Urysohn space**: A topological space in which for any two points, there is a sequence of points converging to both of them.
1. **Coarse space**: A topological space with a notion of large-scale or coarse geometry.
1. **Quaternionic projective space**: a smooth manifold consisting of all quaternionic lines passing through the origin in a quaternionic vector space of arbitrary dimension.

### Mathematical Rings

#### List of Mathematical Rings

1. **Commutative ring**: A ring in which the order of multiplication does not matter, i.e. ab = ba for all elements a, b in the ring.
1. **Integral domain**: A commutative ring in which the product of any two nonzero elements is nonzero.
1. **Field**: An integral domain in which every nonzero element has a multiplicative inverse.
1. **Principal ideal ring**: A ring in which every ideal is generated by a single element.
1. **Euclidean ring**: A ring in which there is a function (the Euclidean function) that satisfies certain properties, which can be used to define a notion of greatest common divisor.
1. **Unique factorization domain (UFD)**: A commutative ring in which every nonzero element can be factored into a product of primes (up to associates)
1. **Noetherian ring**: A ring in which every ideal is finitely generated.
1. **Artinian ring**: A ring in which every descending chain of ideals stabilizes.
1. **Semisimple ring**: A ring in which every left (or right) module is a direct sum of simple modules.
1. **Regular ring**: A ring in which every element is a regular element, meaning that it is not a zero divisor and that it has a left and right inverse.
1. **Von Neumann regular ring**: A ring in which every element a is such that there exists x, y such that a = a x a y.
1. **Division ring**: A ring in which every nonzero element has a multiplicative inverse, but not necessarily commutative.
1. **Skew field**: A non-commutative division ring
1. **p-adic ring**: A ring of formal power series in a variable p with coefficients from a field of characteristic p, with the p-adic metric topology.
1. **Z-algebra**: A ring that is finitely generated as an algebra over Z.
1. **Boolean ring**: A ring in which the additive and multiplicative operations are both idempotent, i.e. a+a = a and a\*a = a for all elements a in the ring.
1. **Incidence ring**: A ring formed from the set of points and lines of a given geometry, with the point-line incidence relation as the multiplication.
1. **Laplace ring**: A ring formed from the set of square matrices of a given size, with matrix multiplication and addition as the ring operations.
1. **Grassmann ring**: A ring formed from the exterior algebra of a vector space.
1. **Hecke ring**: A ring formed from the set of Hecke operators on a modular form or automorphic representation.
1. **Polynomial ring**: A ring formed from the set of polynomials in one or more variables, with polynomial addition and multiplication as the ring operations.
1. **Power series ring**: A ring formed from the set of formal power series in one or more variables, with power series addition and multiplication as the ring operations.
1. **Quaternion ring**: A non-commutative ring with four elements, generated by the elements 1, i, j, k with relations i^2 = j^2 = k^2 = ijk = -1.
1. **Hamilton quaternion ring**: A quaternion ring where the quaternions act as vector fields.
1. **Integral group ring**: A group ring where the coefficients are integers.

### Mathematical Properties

#### List of Mathematical Properties

1. Homogeneity
1. **Perpendicular**
1. **Parallel**
1. **Associative**: The property that states that the order of operations does not matter when combining three or more elements of a set.
1. **Commutative**: The property that states that the order of operations does not matter when combining two elements of a set.
1. **Identity**: An element that leaves other elements unchanged when combined with them.
1. **Inverse**: An element that undoes the effect of another element when combined with it.
1. **Distributive**: The property that states that the distribution of elements over each other is valid.
1. **Closure**: The property that states that for any two elements of a set, their combination is also an element of that set.
1. **Transitive**: The property that states that if a set has a relation "R" and a,b,c are elements of that set, if aRb and bRc then aRc
1. **Symmetric**: If a set has a relation "R" and a,b are elements of that set, aRb implies bRa
1. **Reflexive**: If a set has a relation "R" and a,b are elements of that set, aRa is always true.
1. **Antisymmetric**: If a set has a relation "R" and a,b are elements of that set, aRb and bRa implies a=b
1. **Connected**: A topological space that cannot be written as a union of two disjoint non-empty open sets.
1. **Compact**: A topological space that every open cover has a finite subcover.
1. **Hausdorff**: A topological space in which for any two distinct points, there are disjoint neighborhoods around each point.
1. **Finite**: An object that can be counted, has a finite number of elements.
1. **Integral**: A number that can be represented as a ratio of integers.
1. **Continous**: A function that preserves limits, meaning that the output of a function is the same as the limit of its inputs.
1. **Differentiable**: A function that has a derivative at every point in its domain.
1. **Smooth**: A function that has a derivative at every point in its domain, and all its derivatives are also continuous.
1. **Convex**: A set or function is called convex if for any two points within the set, the entire line segment connecting them is also within the set.
1. **Orthogonal**: A set of vectors that are perpendicular to each other.
1. **Orthonormal**: A set of vectors that are both orthogonal and have a length of 1.
1. **Cyclic**: A group is cyclic if it has a generator, an element that can generate the whole group by repeated application of the group operation.
1. **Cylindrical**: A set that can be written as a product of two sets, one of which is an interval.
1. **Homomorphism**: A function that preserves the algebraic structure of the domain.
1. **Isomorphism**: A bijective homomorphism.
1. **Automorphism**: An isomorphism from a set to itself.
1. **Homotopy**: A continuous deformation of one space into another
1. **Metric**: A function that defines a notion of distance between elements of a set.
1. **Norm**: A function that assigns a non-negative scalar value to each vector in a vector space, that satisfies certain properties such as subadditivity, homogeneity and positive-definiteness.
1. **Inner product**: A function that assigns a scalar value to each pair of vectors in a vector space, that satisfies certain properties such as linearity, symmetry and positive-definiteness.
1. **[Orientability](https://en.wikipedia.org/wiki/Orientability)**

### Mathematical Algebras

#### List of Mathematical Algebras

1. **Group algebra**: An algebra formed by taking the group algebra of a group, which is the vector space formed by taking the direct sum of the group's underlying set, with the group operation being the algebraic operation.
1. **Lie algebra**: An algebra formed by taking the Lie algebra of a Lie group, which is the vector space formed by taking the tangent space of the Lie group at the identity element, with the Lie bracket being the algebraic operation.
1. **Associative algebra**: An algebra where the binary operation is associative, meaning that the order of the operands does not affect the result.
1. **Commutative algebra**: An algebra where the binary operation is commutative, meaning that the order of the operands does not affect the result.
1. **Lie-admissible algebra**: An algebra that can be turned into a Lie algebra by defining a Lie bracket on it.
1. **Jordan algebra**: An algebra where the product of two elements is a linear combination of the commutator and the anti-commutator of the elements.
1. **Poisson algebra**: An algebra where the product of two elements is a Lie bracket of the elements.
1. **Superalgebra**: An algebra where the elements are graded by a Z_2 grading and the product is graded-commutative.
1. **Differential algebra**: An algebra where the elements are functions and the product is the usual function multiplication, but with the added condition that the derivative of the product is the product of the derivatives.
1. **Universal enveloping algebra**: An algebra that is associated to a Lie algebra, it is generated by the Lie algebra and the Lie bracket is extended to the universal enveloping algebra
1. **Clifford algebra**: An algebra that extends the vector space and the scalars with a new product that is defined in terms of a quadratic form.
1. **Grassmann algebra**: An algebra generated by the exterior product of a vector space, it is used to study geometric algebra
1. **Octonion algebra**: An algebra that extends the quaternion algebra with an additional imaginary unit and it is used to study geometric algebra
1. **Quaternion algebra**: An algebra that extends the complex numbers with an additional imaginary unit.
1. **Heisenberg algebra**: An algebra generated by the position and momentum operators of a quantum mechanical system and the commutation relations between them.
1. **Quantum algebra**: An algebra that is used to study quantum systems and it is generated by the observables of a system.
1. **Boolean algebra**: An algebra with two elements, 0 and 1, and operations such as conjunction, disjunction, and negation.
1. **Boolean-like algebra**: An algebra that is similar to Boolean algebra but with more than two elements.
1. **Boolean valued algebra**: An algebra where the elements are Boolean-valued.
1. **Non-associative algebra**: An algebra where the binary operation is non-associative, meaning that the order of the operands affects the result.
1. **Malcev algebra**: a type of algebra that is a generalization of Lie algebras and has a non-associative product.
1. **Alternative algebra**: a type of algebra where the binary operation is alternative, meaning it satisfies (xy)x=x(yx) for all x,y.
1. **Power-associative algebra**: a type of algebra where the product is associative when raising to a power.
1. **Superalgebra**: a type of algebra that has a Z2-grading and an additional operation.
1. **Leibniz algebra**: a type of algebra where the product is a derivation in one of the arguments
1. **Pre-Lie algebra**: a type of algebra where the product is a pre-Lie product
1. **Novikov algebra**: a type of algebra that is a generalization of Lie algebras and has a non-associative product.
1. **Dialgebra**: a type of algebra where the product is commutative and associative
1. **Bol algebra**: a type of algebra where the product is commutative and associative and has a left and right identity
1. **Colored algebra**: a type of algebra that has an additional coloring operation.
1. **Incidence algebra**: a type of algebra that studies the incidence relations between sets
1. **Boolean algebra**: a type of algebra where the product is a logical conjunction and the sum is a logical disjunction
1. **C\*-algebra**: a type of algebra that is used to study quantum mechanics and has an additional involution operation.
1. **Lattice algebra**: a type of algebra where the product is a lattice operation and the sum is a lattice operation
1. **Hom-algebra**: a type of algebra that studies the algebraic properties of Hom-sets
1. **Graded algebra**: a type of algebra that has a Z-grading and an additional operation.
1. **Fuzzy algebra**: a type of algebra that generalizes algebraic concepts to work in the setting of fuzzy sets.
1. **Differential Graded algebra**: a type of algebra that studies the algebraic properties of differential graded modules.
1. **Deformation algebra**: a type of algebra that studies the algebraic properties of deformed structures
1. **Differentially Graded algebra**: a type of algebra that generalizes the concept of differential graded algebra.
1. **Hopf algebra**: an algebra with a comultiplication and counit operations that make it a bialgebra and an antipode operation that makes it a Hopf algebra.
1. **Universal algebra**: A branch of mathematics that studies algebraic structures, such as groups, rings, and lattices, from a general point of view.

### Mathematical Homologies

#### List of Mathematical Homologies

1. **Singular homology**: a way to assign algebraic invariants to topological spaces by associating a group to each dimension of the space.
1. **Simplicial homology**: a way to assign algebraic invariants to simplicial complexes by associating a group to each dimension of the complex.
1. **Cech homology**: a way to assign algebraic invariants to open covers of topological spaces by associating a group to each dimension of the space.
1. **Relative homology**: A way to compute the homology of a pair of spaces by taking into account their relationship to one another.
1. **Alexander-Spanier homology**: A way to assign algebraic invariants to topological spaces by associating a group to each dimension of the space using a basis of open sets.
1. **Borel-Moore homology**: A way to assign algebraic invariants to locally compact topological spaces by associating a group to each dimension of the space using compact supports.
1. **De Rham homology**: a way to assign algebraic invariants to differentiable manifolds using differential forms.
1. **Morse homology**: a way to assign algebraic invariants to manifolds using the critical points of a Morse function.
1. **Floer homology**: a way to assign algebraic invariants to symplectic manifolds using the solutions of certain partial differential equations.
1. **Khovanov homology**: a way to assign algebraic invariants to knots and links using graded vector spaces.
1. **Heegaard Floer homology**: a way to assign algebraic invariants to 3-dimensional manifolds using the solutions of certain partial differential equations.
1. **Persistent homology**: a way to assign algebraic invariants to topological spaces using a filtration of the space.
1. **Hochschild homology**: a way to assign algebraic invariants to associative algebras using the Hochschild complex.
1. **Cyclic homology**: a way to assign algebraic invariants to noncommutative algebras using the cyclic complex.

### Mathematical Automata

#### List of Mathematical Automata

1. **Finite automaton**: a mathematical model of a machine with a finite number of states that can be in one of them at a time, and transition between states based on input symbols.
1. **Pushdown automaton**: an automaton that can also make use of a stack, which allows it to recognize context-free languages.
1. **Linear-bounded automaton**: a variation of pushdown automaton that has a restriction on the stack, that is, the stack is of fixed size.
1. **Turing machine**: a mathematical model of a machine that can read and write symbols on a tape, and move the tape left or right. It can recognize all recursively enumerable languages.
1. **Quantum finite automaton**: an automaton that uses quantum mechanical properties such as superposition and entanglement to perform its computations.
1. **Mealy machine**: a finite state machine whose output depends on both the current state and the current input symbol.
1. **Moore machine**: a finite state machine whose output depends only on the current state.
1. **Multi-tape Turing machine**: A variation of the Turing machine that can use more than one tape to perform its computations.
1. **Cellular automaton**: a discrete model of a system of cells, each of which can be in one of a finite number of states and whose state evolves over time according to a set of rules.
1. **Weighted automata**: a type of automaton that assigns weights or costs to transitions, allowing for the computation of the overall weight or cost of a path through the automaton.
1. **Nondeterministic automata**: a type of automaton that allows for multiple transitions from a single state based on the input.
1. **Probabilistic automata**: a type of automaton that assigns probabilities to transitions, allowing for the computation of the overall probability of a path through the automaton.

### Mathematical Manifolds

#### List of Mathematical Manifolds

- https://en.wikipedia.org/wiki/List_of_manifolds

1. **Euclidean manifold**: a manifold modeled on Euclidean space, which locally looks like a Euclidean space of any dimension
1. **Riemannian manifold**: a manifold equipped with a positive definite inner product on the tangent space at each point
1. **Complex manifold**: a manifold modeled on complex space, which locally looks like a complex space of any dimension
1. **K??hler manifold**: a complex manifold equipped with a Riemannian metric and a compatible complex structure
1. **Symplectic manifold**: a manifold equipped with a closed, non-degenerate 2-form
1. **Contact manifold**: a manifold equipped with a certain type of 1-form called a contact form
1. **Sasakian manifold**: a contact manifold equipped with a compatible Riemannian metric
1. **Quaternionic manifold**: a manifold modeled on quaternionic space, which locally looks like a quaternionic space of any dimension
1. **Hyperbolic manifold**: a manifold modeled on hyperbolic space, which locally looks like a hyperbolic space of any dimension
1. **Projective manifold**: a manifold modeled on projective space, which locally looks like a projective space of any dimension
1. **Grassmannian manifold**: a manifold consisting of all linear subspaces of a given dimension of a vector space
1. **Flag manifold**: a manifold consisting of all flags (complete chains of linear subspaces) of a given type in a vector space.
1. **Lorentzian manifold**: a smooth manifold equipped with a Lorentz metric, a smooth quadratic form of signature (n-1,1) on the tangent space at each point.
1. **K??hler manifold**: a complex manifold equipped with a Hermitian metric and a compatible almost complex structure.

### Mathematical Polynomials

#### List of Mathematical Polynomials

1. **Monomial**: A polynomial with only one term, such as x^2 or 3x.
1. **Binomial**: A polynomial with two terms, such as x^2 + 3x.
1. **Trinomial**: A polynomial with three terms, such as x^2 + 3x + 2.
1. **Multinomial**: A polynomial with more than three terms, such as x^3 + 2x^2 + 3x + 2.
1. **Linear polynomial**: A polynomial of degree 1, such as 2x + 3.
1. **Quadratic polynomial**: A polynomial of degree 2, such as x^2 + 3x + 2.
1. **Cubic polynomial**: A polynomial of degree 3, such as x^3 + 2x^2 + 3x + 2.
1. **Polynomials of higher degree**: A polynomial of degree 4 or higher, such as x^4 + 2x^3 + 3x^2 + 2x + 1.
1. **Constant polynomials**: A polynomial that always returns the same value, such as 5.
1. **Zero polynomials**: A polynomial that always returns zero, such as 0.
1. **Orthogonal polynomials**: polynomials that satisfy a certain orthogonality condition in some inner product space.
1. **Power series**: polynomials with infinite number of terms.
1. **Chebyshev polynomials**: polynomials that minimize the maximum deviation from zero on an interval.
1. **Hermite polynomials**: polynomials that arise in the solution of the Schr??dinger equation in quantum mechanics.
1. **Laguerre polynomials**: polynomials that arise in the solution of certain differential equations with boundary conditions.
1. **Legendre polynomials**: polynomials that arise in many areas of physics and engineering.
1. **Schur polynomials**: polynomials that arise in the representation theory of symmetric groups and general linear groups.
1. **Zonal polynomials**: polynomials that arise in the study of symmetric functions and symmetric spaces.
1. **Jacobi polynomials**: polynomials that arise in the study of partial differential equations and special functions.
1. **Rational polynomials**: polynomials with the ratio of two polynomials.
1. **Algebraic polynomials**: polynomials with algebraic coefficients, such as rational or complex numbers.
1. **Transcendental polynomials**: polynomials with coefficients that are not algebraic, such as exponential or trigonometric functions.
1. **Univariate polynomials**: polynomials with a single variable, such as x^2 + 3x + 1.
1. **Multivariate polynomials**: polynomials with multiple variables, such as x^2 + y^3 + z^4.
1. **Legendre polynomials**: a specific type of orthogonal polynomials named after Adrien-Marie Legendre, often used in physics and numerical analysis.
1. **Cyclotomic polynomials**: polynomials that are related to the roots of unity, often used in number theory and algebraic geometry.

### Mathematical Symmetries

#### List of Mathematical Symmetries

1. **Continuous symmetry**: Symmetries that are described by continuous groups of transformations, such as rotations and translations.
1. **Discrete symmetry**: Symmetries that are described by discrete groups of transformations, such as reflections and permutations.
1. **Point symmetry**: Symmetries that leave at least one point fixed, such as rotations about a point.
1. **Global symmetry**: Symmetries that are defined for the entire system, such as translations in space.
1. **Local symmetry**: Symmetries that are defined for a specific region of the system, such as rotations about a point in a specific subspace.
1. **Projective symmetry**: Symmetries that involve projective transformations, such as in projective geometry.
1. **Conformal symmetry**: Symmetries that preserve angles, such as in conformal geometry.
1. **Lie symmetry**: Symmetries that form a Lie group, such as in the study of differential equations.
1. **Quantum symmetry**: Symmetries that are relevant in quantum mechanics and quantum field theory.
1. **Super symmetry**: Symmetries that relate bosonic and fermionic degrees of freedom in physics.
1. **Group symmetry**: A group is a set of elements that can be combined under a binary operation (such as addition or multiplication) that is associative, has an identity element, and every element has an inverse. A symmetry of a mathematical object is a group of transformations that preserve the structure of the object.
1. **Lie symmetry**: A Lie group is a type of group that is also a smooth manifold, meaning that the group operation and the inverse operation are smooth. Lie symmetries are symmetries of a differential equation or differential system that form a Lie group.
1. **Riemannian symmetry**: A Riemannian manifold is a smooth manifold equipped with a Riemannian metric, which is a way to measure distance and angles. Riemannian symmetries are symmetries of a Riemannian manifold that preserve the metric structure.
1. **Poisson symmetry**: A Poisson manifold is a smooth manifold equipped with a Poisson bracket, which is a way to define a Lie algebra structure on the space of smooth functions on the manifold. Poisson symmetries are symmetries of a Poisson manifold that preserve the Poisson bracket.
1. **Conformal symmetry**: A conformal transformation is a type of transformation that preserves angles, but not necessarily lengths or areas. Conformal symmetries are symmetries of a mathematical object that preserve the conformal structure.
1. **Weyl symmetry**: A Weyl transformation is a type of transformation that preserves the conformal structure of a space while also preserving the scale. Weyl symmetries are symmetries of a mathematical object that preserve the Weyl structure.
1. **Galois symmetry**: Galois symmetry is a type of symmetry of a polynomial equation, where the solutions of the equation form a Galois group (a specific type of group).
1. **Noether symmetry**: Noether symmetry is a type of symmetry that is associated with a continuous symmetry of a physical system and its corresponding conserved quantity.
1. **Duality symmetry**: Duality symmetries are symmetries of a physical system that relate different descriptions of the same system.
1. **Symplectic symmetry**: A symmetry that preserves the symplectic form, often represented mathematically as a matrix.
1. **Orthogonal symmetry**: A symmetry that preserves the inner product, often represented mathematically as a matrix.
1. **Unitary symmetry**: A symmetry that preserves the inner product and the norm, often represented mathematically as a matrix.
1. **Quaternionic symmetry**: A symmetry that preserves the quaternionic product, often represented mathematically as a matrix.
1. **Hyperbolic symmetry**: A symmetry that preserves the hyperbolic metric, often represented mathematically as a matrix.
1. **Special conformal symmetry**: A symmetry that preserves angles and ratios of distances, but also includes inversions, often represented mathematically as a matrix.
