# 1.3 Linear Algebra

**Duration:** 8-10 weeks  
**Prerequisites:** Basic algebra, some calculus helpful  
**Weekly Commitment:** 20-25 hours

> *"Linear algebra is the branch of mathematics concerning linear equations... and their representations in vector spaces and through matrices. Linear algebra is central to almost all areas of mathematics."* - Wikipedia

Linear algebra is arguably the **most important** mathematical prerequisite for modern deep tech. It's the language of:
- **Machine Learning** - Data matrices, principal components, neural networks
- **Quantum Computing** - Quantum states as vectors, operations as matrices
- **Computer Graphics** - 3D transformations, projections, rotations
- **Data Science** - Dimensionality reduction, recommendation systems
- **Signal Processing** - Digital filters, image compression

## Learning Objectives

By completing this section, you will:
- **Solve linear systems** using multiple methods (elimination, matrix operations)
- **Think geometrically** about vectors, subspaces, and transformations
- **Master eigenvalues** and their applications to dynamics and data analysis
- **Apply linear algebra** to real-world problems in ML, physics, and engineering
- **Understand abstract concepts** like vector spaces and linear transformations

## Dual-Learning Approach

### Pass 1: Applied Linear Algebra (Weeks 1-5)
**Focus:** Geometric intuition, computational skills, applications

### Pass 2: Abstract Linear Algebra (Weeks 6-10)  
**Focus:** Vector spaces, proofs, theoretical foundations

## Week-by-Week Schedule

### Week 1: Linear Equations and Matrices
**Applied Focus - Strang Ch 1-2**

#### Topics
- Systems of linear equations
- Gaussian elimination
- Matrix operations (addition, multiplication)
- LU decomposition

#### Key Concepts
- **Matrix-vector multiplication** as linear combination of columns
- **Elimination matrices** and their inverses
- **Back substitution** and forward elimination

#### Applications
- Solve traffic flow problems
- Network analysis (currents, voltages)
- Economic equilibrium models

#### Problem Set 1
- 20 problems on elimination and matrix operations
- Implement Gaussian elimination in Python/MATLAB
- Traffic flow application problem

### Week 2: Vector Spaces and Subspaces  
**Applied Focus - Strang Ch 3**

#### Topics
- Vector spaces R^n
- Subspaces and their properties
- Column space and nullspace
- Linear independence

#### Key Concepts
- **Column space** C(A) - all possible outputs of Ax
- **Nullspace** N(A) - all inputs that give zero output
- **Linear independence** - no vector is a combination of others

#### Geometric Intuition
- Visualize subspaces in 2D and 3D
- Lines and planes through the origin
- Intersection of subspaces

#### Problem Set 2
- Find bases for column space and nullspace
- Geometric problems in 2D/3D
- Linear independence tests

### Week 3: The Four Fundamental Subspaces
**Applied Focus - Strang Ch 4**

#### Topics
- Column space C(A) and left nullspace N(A^T)
- Row space C(A^T) and nullspace N(A)
- Rank and dimension relationships
- Basis and dimension

#### The Big Picture
```
C(A^T) ⊥ N(A)    (row space ⟂ nullspace)
C(A) ⊥ N(A^T)    (column space ⟂ left nullspace)
```

#### Applications
- Understanding least squares
- Data analysis fundamentals
- Network flow problems

#### Problem Set 3
- Find all four subspaces for given matrices
- Verify orthogonality relationships
- Dimension and rank calculations

### Week 4: Orthogonality and Projections
**Applied Focus - Strang Ch 5**

#### Topics
- Orthogonal vectors and subspaces
- Projections onto lines and subspaces
- Least squares method
- QR decomposition

#### Key Applications
- **Least squares regression** - best fit through data points
- **Signal processing** - project signals onto basis functions
- **Computer graphics** - orthogonal projections for 3D rendering

#### Geometric Understanding
- Projection as "shadow" of vector onto subspace
- Orthogonal complement relationships
- Gram-Schmidt process for orthogonalization

#### Problem Set 4
- Compute projections onto lines and planes
- Solve least squares regression problems
- Apply QR decomposition

### Week 5: Eigenvalues and Eigenvectors
**Applied Focus - Strang Ch 6**

#### Topics
- Definition: Ax = λx
- Computing eigenvalues and eigenvectors
- Diagonalization
- Applications to differential equations

#### Physical Interpretation
- **Eigenvectors** - directions that don't change under transformation
- **Eigenvalues** - how much stretching occurs in those directions
- **Principal axes** of ellipses and ellipsoids

#### Applications
- **Population dynamics** - long-term behavior
- **Vibrating systems** - natural frequencies
- **Google PageRank** - dominant eigenvector
- **Principal Component Analysis** - data compression

#### Problem Set 5
- Find eigenvalues and eigenvectors
- Diagonalize matrices
- Population dynamics modeling
- Introduction to PCA

### Week 6: Abstract Vector Spaces
**Theoretical Focus - Axler Ch 1-2**

#### Transition to Abstraction
Move from concrete R^n to abstract vector spaces:
- Vector spaces over fields
- Linear transformations as functions
- Formal definitions and proofs

#### Topics
- Vector space axioms
- Linear transformations T: V → W
- Kernel and image of transformations
- Isomorphisms

#### Key Insights
- **Basis independence** - concepts don't depend on coordinate choice
- **Linear transformations** generalize matrix multiplication
- **Dimension** as fundamental invariant

#### Problem Set 6
- Prove vector space properties
- Work with polynomial and function spaces
- Abstract linear transformation problems

### Week 7: Finite-Dimensional Vector Spaces
**Theoretical Focus - Axler Ch 3**

#### Topics
- Span and linear independence (revisited)
- Bases and dimension
- The matrix of a linear transformation
- Change of basis

#### Advanced Concepts
- Every finite-dimensional vector space is isomorphic to R^n
- Matrix representation depends on basis choice
- Change of basis formula: B = P^(-1)AP

#### Problem Set 7  
- Prove dimension theorems
- Change of basis calculations
- Matrix representations of abstract transformations

### Week 8: Inner Product Spaces
**Theoretical Focus - Axler Ch 6**

#### Topics
- Inner product definition and properties
- Orthonormal bases
- Gram-Schmidt process (revisited)
- Orthogonal projections (revisited)

#### Deeper Understanding
- Why orthogonality is so important
- Connection to geometry and physics
- Bessel's inequality and Parseval's identity

#### Problem Set 8
- Work with various inner products
- Prove orthogonality theorems
- Applications to function spaces

### Week 9: Operators on Inner Product Spaces
**Theoretical Focus - Axler Ch 7**

#### Topics
- Self-adjoint operators
- Normal operators
- Spectral theorem
- Positive operators

#### Connection to Applications
- **Symmetric matrices** are self-adjoint
- **Spectral theorem** guarantees orthogonal eigenvectors
- **Positive definite** matrices in optimization

#### Problem Set 9
- Classify operators by type
- Apply spectral theorem
- Optimization applications

### Week 10: Integration and Singular Values
**Applied Focus - Strang Ch 7 + Advanced Topics**

#### Topics
- Singular Value Decomposition (SVD)
- Applications to data analysis
- Low-rank approximation
- Principal Component Analysis

#### SVD Applications
- **Image compression** - approximate images with fewer values
- **Data science** - find patterns in high-dimensional data
- **Recommender systems** - Netflix, Amazon recommendations
- **Machine learning** - dimensionality reduction

#### Final Project Options
1. **Image Compression** - Implement SVD image compression
2. **Data Analysis** - PCA on real dataset
3. **Markov Chains** - Google PageRank algorithm
4. **Vibration Analysis** - Modal analysis of mechanical system

## Primary Resources

### Pass 1: Applied Approach
**Introduction to Linear Algebra (5th Edition) by Gilbert Strang**
- [MIT OCW Course](https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/)
- [Video Lectures](https://www.youtube.com/playlist?list=PL49CF3715CB9EF31D) - 35 lectures
- [PDF Notes](https://math.mit.edu/~gs/linearalgebra/) - Free from author

**Why Strang:**
- Geometric intuition before computation
- Applications to engineering and data science
- Excellent video lectures with visual explanations
- Focus on the "why" behind methods

### Pass 2: Theoretical Approach  
**Linear Algebra Done Right (4th Edition) by Sheldon Axler**
- [Author's Website](https://linear.axler.net/) - Additional resources
- [Video Lectures](https://www.youtube.com/playlist?list=PLGAnmvB9m7zOBVCZBUUmSinFV0wEir2Vw)

**Why Axler:**
- Avoids determinants until the end (cleaner approach)
- Proof-based, abstract treatment
- Builds deeper mathematical understanding
- Excellent for preparing for graduate study

## Supplementary Resources

### Video Content
- **3Blue1Brown Essence of Linear Algebra** - Beautiful visual explanations
- **Khan Academy Linear Algebra** - Good for review and basics
- **MIT 18.065 Matrix Methods** - Advanced applications

### Interactive Tools
- **Linear Algebra Visualizer** - See transformations in action
- **GeoGebra** - 3D visualization of subspaces
- **Python/NumPy** - Computational practice
- **MATLAB** - Industry standard for linear algebra

### Books for Additional Practice
- **Linear Algebra and Its Applications** by Lay - More computational
- **Linear Algebra** by Hoffman & Kunze - Very theoretical
- **Matrix Analysis** by Horn & Johnson - Advanced applications

## Programming Component

Linear algebra is best learned by doing. Programming exercises include:

### Python/NumPy Assignments
1. **Week 2:** Implement Gaussian elimination
2. **Week 3:** Find four subspaces computationally  
3. **Week 4:** Least squares regression from scratch
4. **Week 5:** Eigenvalue algorithms (power method)
5. **Week 10:** SVD image compression project

### MATLAB/Octave (Alternative)
- More traditional in engineering
- Built-in linear algebra functions
- Excellent for matrix visualization

## Assessment Strategy

### Weekly Components (70%)
- **Problem Sets** - 15-20 problems per week
- **Programming Assignments** - Implement key algorithms
- **Conceptual Quizzes** - Test understanding without computation

### Major Assessments (30%)
- **Midterm Exam** (Week 5) - Applied linear algebra
- **Final Project** (Week 10) - Choose from application areas
- **Theory Assessment** (Week 8) - Proof-based problems

### Grading Rubric
- **Computational Skills (40%)** - Can you solve problems?
- **Conceptual Understanding (40%)** - Do you understand why?
- **Applications (20%)** - Can you apply to real problems?

## Key Insights to Master

### The Big Picture
1. **Linear transformations** are the central concept
2. **Matrix multiplication** is composition of transformations
3. **Eigenvalues** reveal fundamental behavior
4. **Orthogonality** provides geometric insight

### Geometric Intuition
- Matrices transform space
- Eigenvalues show stretching factors
- Eigenvectors show invariant directions
- Subspaces are geometric objects

### Computational Power
- Most of data science is linear algebra
- Machine learning = linear algebra + statistics + optimization
- Computer graphics = 3D linear transformations

## Common Pitfalls

### Mistake: Memorizing without Understanding
**Solution:** Always ask "what does this mean geometrically?"

### Mistake: Focusing Only on Computation  
**Solution:** Study both Strang (intuition) and Axler (theory)

### Mistake: Skipping Proofs
**Solution:** Proofs reveal why methods work and when they fail

### Mistake: Not Practicing Programming
**Solution:** Implement algorithms to truly understand them

## Advanced Topics (Optional)

For students wanting deeper understanding:
- **Matrix Calculus** - Derivatives of matrices
- **Tensor Analysis** - Generalization to higher dimensions  
- **Lie Groups** - Continuous symmetry groups
- **Spectral Graph Theory** - Eigenvalues of network graphs

## Real-World Connections

### Machine Learning
- **Data matrices** - rows are samples, columns are features
- **Principal Component Analysis** - find directions of maximum variation
- **Neural networks** - layers are linear transformations + nonlinearity

### Quantum Computing  
- **Quantum states** are vectors in complex vector space
- **Quantum gates** are unitary matrices
- **Measurement** projects onto eigenvector basis

### Computer Graphics
- **3D rotations** via rotation matrices
- **Perspective projection** onto 2D screen
- **Lighting models** use dot products (cosine of angles)

### Economics/Finance
- **Portfolio optimization** - quadratic forms and positive definite matrices
- **Input-output models** - Leontief matrices
- **Principal component analysis** of market factors

## Success Metrics

### Week 5 Checkpoint
- Can solve 2×2 and 3×3 eigenvalue problems by hand
- Understand geometric meaning of eigenvalues/eigenvectors
- Can apply least squares to fit lines through data

### Week 10 Final Goals
- Mastery of four fundamental subspaces
- Can prove basic theorems about vector spaces
- Successfully complete programming project using SVD
- Ready for applications in machine learning, quantum computing, etc.

---

**Ready to master the language of modern technology?**

Linear algebra unlocks machine learning, quantum computing, computer graphics, and countless other deep tech fields.

🚀 **Start with geometric intuition: [Gilbert Strang's Video Lectures](https://www.youtube.com/playlist?list=PL49CF3715CB9EF31D)**

## Quick Links

- [Week 1-2: Linear Systems & Vector Spaces](week-1-2-systems-spaces.md)
- [Week 3-4: Subspaces & Projections](week-3-4-subspaces-projections.md)  
- [Week 5: Eigenvalues & Applications](week-5-eigenvalues.md)
- [Week 6-9: Abstract Theory](week-6-9-abstract-theory.md)
- [Week 10: SVD & Final Project](week-10-svd-project.md)
- [Programming Assignments](programming-assignments.md)
- [Problem Sets & Solutions](problem-sets.md)