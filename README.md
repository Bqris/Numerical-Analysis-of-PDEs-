# Numerical-Analysis-of-PDEs-

<goal>
  Solving PDEs numerically with the use of FEM and other methods.
</goal>

  PDEs come with lots of shapes and sizes, there is no general method for solving nonlinear PDEs.
  Analytical methods do exist, and in some special cases we can even solve nonlinear PDEs explicitly.
  However, these cases are rare and a lot of physical phenomena that is described by such PDEs demand another approach.
  This is where the numerical methods come handy, we will try to approximate the solution of these PDEs by numerical means.
  There is a huge literature out there regarding numerical methods, and each method has its advantages and disadvantages.

  The goal of this project is to come up with and make us of algorithms that solves these PDEs 
  with as minimal error as possible with reasonably optimizated algorithms. 

  Since this project will take on the approach of constructing the whole ensemble of algorithms from stracth, 
  other readily available FEM libraries will not be made use of. 



  In order solve any PDE, initial conditions and boundary conditions should be given.
  The solution of PDE will be a function from some domain $\Omega$ $\subset$ $\mathbb{R}^2$ to $\mathbb{R}$. 
  (we will only deal with 2 dimensional cases). That means to obtain a solution we must first come up with 
  data structures that encodes the domain information of the PDE, in this step domain discretization will be 
  our primary focus. We will discretize our domain $\Omega$ by first sampling points from within and boundary of
  $\Omega$. Then we will use delaunay triangulation to mesh our domains. This will set the stage for solving PDEs.

  After this setup we will deal with nature of PDEs and their mathematical properties in order to extract useful 
  information that could lead us to approximate these PDEs. That will include the choice of basis functions, error
  estimation, and possible shortcuts in computation time that is enabled by mathematical tricks. 

