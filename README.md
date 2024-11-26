This repository contains the database and potentials developed and is divided into two directories

The directory database/ contains the compressed files for the database.
The database is composed of 5259 structures for MoS2 and 6187 structures for MoSe2.
Each structure is an *.xsf file that could be visualized with XCrysDen or Vesta and each
structure constains information of Total Energy, Atomic Positions and Atomic Forces

The directory database/ contains the trained Neural Networks Potentials used on our simulations
and is divided into two subdirectories:
mos2: contains the *.ann files for simulations with MoS2 (one for each species)
mose2: contains the *.ann files for simulations with MoSe2 (one for each species)

Note that there are two different neural network for the "Mo" species, one for each compound.
The "Mo" Neural Network trained for MoS2 should not be used for MoSe2 simulations and vice versa

The reader can learn to compile LAMMPS with the aenet package and
run simulations with the *.ann potentials by visiting
the link: https://github.com/HidekiMori-CIT/aenet-lammps

# Author & contact information
Author: Gabriel Bruno Garcia de Souza, Departamento de Física, Universidade Federal de Minas Gerais
E-mail: gbsouza1997@ufmg.br or ga.bruno926@gmail.com
