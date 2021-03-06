#### Introduction
The development of g_mmpbsa package is initiated under [Open Source Drug Discovery Consortium (OSDD)](http://www.osdd.net/) which is a collaborative platform to discover new drugs for neglected tropical diseases like Malaria, Tuberculosis, Leshmaniasis, etc. g_mmpbsa is developed using two widely used open source software i.e. [GROMACS](http://www.gromacs.org/) and     [APBS](http://www.poissonboltzmann.org/apbs) and it has similar user interface like other GROMACS tools. The tool calculates components of binding energy using MM-PBSA method except the entropic term and energetic contribution of each residue to the binding using energy decomposition scheme. The output from the tool is used further as input in python scripts which is provided in this package, to get the final binding energy and energetic contribution of each residue.

#### For complete documentation, please visit [g_mmpbsa](http://rashmikumari.github.io/g_mmpbsa/).
#### Please post problems and queries in [g_mmpbsa forum](https://groups.google.com/d/forum/g_mmpbsa).

***
#### Features
* It is an open source tool and can be modified under the terms of the GNU public license 
* It is implemented through open source software [GROMACS](http://www.gromacs.org/) and [APBS](http://www.poissonboltzmann.org/apbs), making it accessible to large number of users. 
* Easy installation by downloading the compressed file [(zip/tarball)](https://github.com/RashmiKumari/g_mmpbsa/releases) and steps are given in this <strong>[link](http://rashmikumari.github.io/g_mmpbsa/Download-and-Installation.html)</strong>.
* It provides user to choose different van der Waal radii for solvation free energy calculation using implicit solvent models.
* It has options for several non-polar solvation model such as SASA, SAV and Weeks–Chandler–Andersen (WCA).
* Binding energy decomposition scheme is implemented through MM-PBSA scheme as contrast to other packages, in which scheme is implemented through MM-GBSA only. 
* It calculates different components of binding energy and residue wise energy contribution to binding simultaneously and thus is computationally less expensive.

This tool can be modified and/or redistributed under terms of GNU public license. 
***

#### Citations

##### _g\_mmpbsa_
Kumari _et al._ [g\_mmpbsa - A GROMACS tool for high-throughput MM-PBSA calculations] (http://pubs.acs.org/doi/abs/10.1021/ci500020m) _J. Chem. Inf. Model._ (2014).

##### GROMACS
Pronk _et al._ [GROMACS 4.5: a high-throughput and highly parallel open source molecular simulation toolkit](http://bioinformatics.oxfordjournals.org/content/29/7/845.abstract). _Bioinformatics_ (2013) 29:845-854.
##### APBS
Baker _et al._ [Electrostatics of nanosystems: Application to microtubules and the ribosome.](http://www.pnas.org/content/98/18/10037.abstract) _Proc. Natl. Acad. Sci. USA_ (2001) 98:10037-10041.
##### Double Cubic Lattice Method for Solvent Accessible Surface Area and Volume calculation
Eisenhaber _et al._ [The double cubic lattice method: Efficient approaches to numerical integration of surface area and volume and to dot surface contouring of molecular assemblies.](http://onlinelibrary.wiley.com/doi/10.1002/jcc.540160303/abstract) _J. Comput. Chem._ (1995) 16:273-284.
##### Weeks–Chandler–Andersen (WCA) type non-polar solvation model
Wagoner _et al._ [Assessing implicit models for nonpolar mean solvation forces: The importance of dispersion and volume terms.](http://www.pnas.org/content/103/22/8331.abstract) _Proc. Natl. Acad. Sci. USA_ (2006) 103:8331-8336.
***
[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/RashmiKumari/g_mmpbsa/trend.png)](https://bitdeli.com/free "Bitdeli Badge")
***
[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/b4a54ceb8ced19bac6811f06f58f000f "githalytics.com")](http://githalytics.com/RashmiKumari/g_mmpbsa)
