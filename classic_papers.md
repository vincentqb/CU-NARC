# NARC - Suggested Classical Numerical Analysis Papers for Presenting

This list is based on a posting by Nick Trefethen [1] and a course offered at
Stanford that reviewed these papers including the latter expanded list.  

## Primary list (via Trefethen)

1. Cooley & Tukey (1965)              the Fast Fourier Transform
2. Courant, Friedrichs & Lewy (1928)  finite difference methods for PDE 
3. Householder (1958)                 QR factorization of matrices
4. Curtiss & Hirschfelder (1952)      stiffness of ODEs; BD formulas
5. de Boor (1972)                     calculations with B-splines
6. Courant (1943)                     finite element methods for PDE
7. Golub & Kahan (1965)               the singular value decomposition
8. Brandt (1977)                      multigrid algorithms
9. Hestenes & Stiefel (1952)          the conjugate gradient iteration
10. Fletcher & Powell (1963)           optimization via quasi-Newton updates
11. Wanner, Hairer & Norsett (1978)    order stars and applications to ODE
12. Karmarkar (1984)                   interior pt. methods for linear prog.
13. Greengard & Rokhlin (1987)         multipole methods for particles


### Primary Citation List

 1. James W. Cooley and John W. Tukey, "An algorithm for the machine
    calculation of complex Fourier series," *Mathematics of Computation* 19
    (1965), 297-301.

 2. R. Courant, K. O. Friedrichs and H. Lewy, "Ueber die partiellen
    Differenzengleichungen der mathematischen Physik," Mathematische Annalen
    100 (1928), 32-74.  Translated as: "On the partial difference equations of
    mathematical physics," *IBM Journal of Resarch and Development* 11 (1967),
    215-234.

 3. A. S. Householder, "Unitary triangularization of a nonsymmetric matrix,"
    *Journal of the Association of Computing Machinery* 5 (1958), 339-342.

 4. C. F. Curtiss and J. O. Hirschfelder, "Integration of stiff equations,"
    *Proceedings of the National Academy of Sciences* 38 (1952), 235-243.

 5. C. de Boor, "On calculating with B-splines," *Journal of Approximation
    Theory* 6 (1972), 50-62.

 6. R. Courant, "Variational methods for the solution of problems of
    equilibrium and vibrations," *Bulletin of the American Mathematical Society*
    49 (1943), 1-23.

 7. G. Golub and W. Kahan, "Calculating the singular values and pseudo-inverse
    of a matrix," *SIAM Journal on Numerical Analysis* 2 (1965), 205-224.

 8. A. Brandt, "Multi-level adaptive solutions to boundary-value problems,"
    *Mathematics of Computation* 31 (1977), 333-390.

 9. Magnus R. Hestenes and Eduard Stiefel, "Methods of conjugate gradients for
    solving linear systems," *Journal of Research of the National Bureau of 
    Standards* 49 (1952), 409-436.

10. R. Fletcher and M. J. D. Powell, "A rapidly convergent descent method for
    minimization," *Computer Journal* 6 (1963), 163-168.

11. G. Wanner, E. Hairer and S. P. Norsett, "Order stars and stability
    theorems," *BIT* 18 (1974), 475-489.

12. N. Karmarkar, "A new polynomial-time algorithm for linear programming,"
    *Combinatorica* 4 (1984), 373-395.

13. L. Greengard and V. Rokhlin, "A fast algorithm for particle simulations,"
    *Journal of Computational Physics* 72 (1987), 325-348.

### Full List of Sources
  
 - **Linear Algebra** - systems of equations and least-squares
     - Frankel (1950)             optimal omega for SOR iteration
     - Hestenes & Stiefel (1952)              the conjugate gradient iteration
     - Young (1954)                           theory of classical iterative methods
     - Householder (1958)                     QR decomposition
     - Wilkinson (1961)                       error analysis for systems of eqs.
     - Golub (1965)                           least-squares problems
     - Strassen (1969)                        Gaussian elimination is not optimal
     - George (1973)                          nested dissection
     - Gill, Golub, Murray & Saunders (1974)  updating matrix factorizations
     - Concus, Golub & O'Leary (1976)         preconditioned conjugate gradients
     - Meijerink & van der Vorst (1977)       incomplete LU preconditioning
     - Skeel (1980)                           iterative refinement and stability
     - Saad & Schultz (1986)                  GMRES for nonsymmetric systems

 - **Linear Algebra** - eigenvalues and svd
     - Jacobi (1846)                      Jacobi's method for matrix eigenvalues
     - Henrici (1958)                         convergence of the Jacobi method
     - Rutishauser (1958)                     the LR algorithm
     - Kublanovskaya (1961)                   the QR algorithm
     - Francis (1961)                         the QR algorithm
     - Golub & Kahan (1965)                   computation of the SVD
     - Moler & Stewart (1973)                 QZ algorithm for gen'd eigenvalues
     - Cuppen (1981)                          divide and conquer for eigenvalues
  
 - **Optimization**
     - Dantzig (1951)                         simplex method for linear programming
     - Davidon (1959)                         variable metric methods
     - Fletcher & Powell (1963)               DFP quasi-Newton update formula
     - Broyden/Fletcher/Goldfarb/Shanno (`70) BFGS quasi-Newton update formula
     - Karmarkar (1984)                       interior pt methods for linear
     prog.

 - **Integration**
     - Golub & Welsch (1969)              Gauss quadrature rules
     - de Boor (1971)                         adaptive quadrature algorithms
  
 - **Approximation**
     - Remes (1934)                           Remes algorithm for Chebyshev approx.
     - Schoenberg (1946)                      splines
     - Powell (1967)                          near-optimality of Chebyshev interp.
     - Reinsch (1967)                         smoothing with splines
     - Cox (1972)                             calculation with B-splines
     - de Boor (1972)                         calculation with B-splines

 - **Other**
    - Aitken (1932)                          Aitken extrapolation
    - Cooley & Tukey (1965)                  the fast Fourier transform
    - Greengard & Rokhlin (1987)             fast multipole methods

 - **ODEs**
     - Curtiss & Hirschfelder (1952)          stiffness and BD formulas
     - Dahlquist (1956)                       stability and convergence
     - Dahlquist (1963)                       A-stability
     - Butcher (1965)                         Runge-Kutta methods
     - Gear (1969)                            stiff ODEs
     - Wanner, Hairer & Norsett (1978)        order stars and stability theorems
  
 - **Elliptic PDEs**
     - Peaceman & Rachford (1955)             ADI
     - Douglas (1955)                         ADI
     - Strang (1971 or 1973)                  finite elements and approx. theory
     - Buzbee, Golub & Nielsen (1970)         fast Poisson via cyclic reduction
     - Hockney (1965)                         fast Poisson via FFT
     - Fedorenko (1961)                       multigrid methods
     - Brandt (1977)                          multigrid methods

 - **Parabolic and Hyperbolic pdes**
     - Courant, Friedrichs & Lewy (1928)      the CFL condition
     - Crank & Nicolson (1947)                finite differences for parabolic PDE
     - O'Brien, Hyman & Kaplan (1951)         Von Neumann stability analysis
     - Lax & Richtmyer (1956)                 general stability theory
     - Lax & Wendroff (1960,1962,1964)        methods for solving conservation laws
     - Kreiss (1962)                          more general stability theory
     - Orszag (1971)                          spectral methods
     - Kreiss and Oliger (1972)               spectral methods
     - Gustafsson, Kreiss & Sundstrom (1972)  stability of boundary conditions
     - Chorin (1973)                          vortex methods for CFD
     - Engquist & Majda (1977)                absorbing boundary conditions
  