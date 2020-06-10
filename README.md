# dealii-adapter
<a style="text-decoration: none" href="https://travis-ci.org/precice/dealii-adapter" target="_blank">
    <img src="https://travis-ci.org/precice/dealii-adapter.svg?branch=master" alt="Build status">
</a>

Coupled structural solvers written with the C++ finite element library deal.II:

- `linear_elasticity` contains a linear-elastic solver based on the step-8 tutorial program of deal.II
- `nonlinear_elasticity` contains a nonlinear elastic solver, which builds on previous work of Jean-Paul Pelteret and Andrew McBride in their deal.II code gallery program 'Quasi-Static Finite-Strain Compressible Elasticity.' This solver supports shared-memory parallelization.

Applied coupling functionalities have been separated and can be found in the `adapter` directory.

## Start here
Our [wiki](https://github.com/precice/dealii-adapter/wiki) will help you start. If you are missing something, [let us know](https://www.precice.org/resources/#contact).

## Citing
preCICE is an academic project, developed at the [Technical University of Munich](https://www5.in.tum.de/wiki/index.php/Home) and at the [University of Stuttgart](https://www.ipvs.uni-stuttgart.de/). If you use preCICE, please [cite us](https://www.precice.org/publications/):

*H.-J. Bungartz, F. Lindner, B. Gatzhammer, M. Mehl, K. Scheufele, A. Shukaev, and B. Uekermann: preCICE - A Fully Parallel Library for Multi-Physics Surface Coupling. Computers and Fluids, 141, 250–258, 2016.*

If you are using deal.II, please also consider the information on the [deal.II webpage](https://www.dealii.org/publications.html)

## License

Please see the [LICENSE](https://github.com/precice/dealii-adapter/blob/master/LICENSE) file for details.
