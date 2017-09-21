# cab-graphite
Graphite TSL model from Centro Atomico Bariloche

 Graphite   ARCAB     EVAL-SEP17 Marquez Damian, Granada               
                      DIST-                                            
----ENDF/B-VIII.beta  MATERIAL 31                                      
-----THERMAL NEUTRON SCATTERING DATA                                   
------ENDF-6 FORMAT                                                    
                                                                       
******************************************************************     
*                                                                *     
* Evaluation for thermal scattering in graphite, based on        *     
* experimental data from inelastic neutron scattering experiments*     
* by Rols [1]. The spectrum combines data from IN6 at ILL (low   *     
* energy region) BT-4 at NIST (intermediate energy) and IN1B at  *     
* ILL (high energy range). The alpha and beta grid was prepared  *     
* following the guidelines used in GASKET [2], with a linear     *     
* region up to alpha=5.0, beta=4.0 and a geometrical region up   *     
* to betamax = Emax/kT, alphamax = 4*Emax/(A*kT), with           *     
* Emax = 5 eV, kT=25.3e-3 eV, A = 11.898 for a total of 200      *     
* points in alpha and 200 points in beta.                        *     
*                                                                *     
* The coherent elastic component was computed using the code     *     
* NCrystal [3], which was used as a replacement of the subroutine*     
* coher() in LEAPR. The following structural parameters were     *     
* used:                                                          *     
*                                                                *     
* CELL: lengths 2.464 2.464 6.711 , angles 90. 90. 120.          *     
* SPACEGROUP: 194                                                *     
* ATOMPOSITIONS: 0. 0. 0.25; 0. 0. 0.75;                         *     
*                0.333333333333 0.666666666667 0.25;             *      
*                0.666666666667 0.333333333333 0.75              *     
* sigma_b = 6.6484 b                                             *     
*                                                                *     
* References:                                                    *     
* [1] S. Rols, et al. Phys. Rev. Lett. 85, 5222 (2000).          *     
* [2] JU. Koppel, et al. General Atomics Report GA-7417 (1967).  *     
* [3] X. X. Cai and T. Kittelmann, NCrystal,                     *     
*     https://doi.org/10.5281/zenodo.853186                      *     
*                                                                *     
******************************************************************     

For help installing and running NJOY with NCrystal, follow this
tutorial:

https://gist.github.com/marquezj/625407e8ff60fb4b41f1bf8f8db6a6c3
