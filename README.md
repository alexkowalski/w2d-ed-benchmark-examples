# Results from ED benchmark calculations with the w2dynamics CT-HYB solver

The ED DMFT calculations and generation of impurity problem input data were performed using the scripts found in [this repository](https://github.com/alexkowalski/w2d-ed-benchmark-generator).

## Benchmark results

For all examples, the inter-orbital interaction parameter for different spins is U' = U - 2J and the inverse temperature beta = 100 if not otherwise specified.

### Two-orbital calculations

For all two-orbital examples, 5 bath sites per orbital were used in the ED DMFT calculations.

* Bethe lattice half-bandwidths [1.0, 1.0], local levels [0.0, 0.0], density interaction with Hubbard U = 1.0 and Hund's coupling J = 0.25, chemical potential mu = 0.875 [here](2orb_bws1.0_lvls0.0_densU1.0_J0.25_mu0.875)

* Bethe lattice half-bandwidths [1.0, 1.0], local levels [0.0, 0.0], Kanamori interaction with Hubbard U = 1.0 and Hund's coupling J = 0.25, chemical potential mu = 0.875 [here](2orb_bws1.0_lvls0.0_kanU1.0_J0.25_mu0.875)

* Bethe lattice half-bandwidths [1.0, 1.0], local levels [0.0, 0.0], density interaction with Hubbard U = 1.0 and no Hund's coupling, chemical potential mu = 0.5 [here](2orb_bws1.0_lvls0.0_densU1.0_J0.0_mu0.5)

* Bethe lattice half-bandwidths [1.0, 1.0], local levels [0.0, 0.0], density interaction with Hubbard U = 8.0 and Hund's coupling J = 2.0, chemical potential mu = 7.0 [here](2orb_bws1.0_lvls0.0_densU8.0_J2.0_mu7.0)

* Bethe lattice half-bandwidths [1.0, 1.0], local levels [0.0, 0.0], density interaction with Hubbard U = 8.0 and no Hund's coupling, chemical potential mu = 4.0 [here](2orb_bws1.0_lvls0.0_densU8.0_J0.0_mu4.0)

* Bethe lattice half-bandwidths [1.0, 1.0], local levels [0.0, 0.0], density interaction with Hubbard U = 1.55 and Hund's coupling J = 0.3875, chemical potential mu = 1.6 [here](2orb_bws1.0_lvls0.0_densU1.55_J0.3875_mu1.6)

* Bethe lattice half-bandwidths [1.0, 2.0], local levels [0.0, 1.5], density interaction with Hubbard U = 5.0 and Hund's coupling J = 1.25, chemical potential mu = 4.0 [here](2orb_bws1.0_2.0_lvls0.0_1.5_densU5.0_J1.25_mu4.0)

* Bethe lattice half-bandwidths [1.0, 2.0], local levels [0.0, 1.5], density interaction with Hubbard U = 5.0 and no Hund's coupling, chemical potential mu = 2.538 [here](2orb_bws1.0_2.0_lvls0.0_1.5_densU5.0_J0.0_mu2.538)

* Bethe lattice half-bandwidths [2.0, 4.0], local levels [0.0, 0.0], density interaction with Hubbard U = 1.0 and Hund's coupling J = 0.25, chemical potential mu = 0.875 [here](2orb_bws2.0_4.0_lvls0.0_densU1.0_J0.25_mu0.875)

* Bethe lattice half-bandwidths [2.0, 4.0], local levels [0.0, 0.0], density interaction with Hubbard U = 1.0 and no Hund's coupling, chemical potential mu = 0.5 [here](2orb_bws2.0_4.0_lvls0.0_densU1.0_J0.0_mu0.5)

* Bethe lattice half-bandwidths [2.0, 4.0], local levels [0.0, 0.0], density interaction with Hubbard U = 8.0 and Hund's coupling J = 2.0, chemical potential mu = 7.0 [here](2orb_bws2.0_4.0_lvls0.0_densU8.0_J2.0_mu7.0)

* Bethe lattice half-bandwidths [2.0, 4.0], local levels [0.0, 0.0], Kanamori interaction with Hubbard U = 8.0 and Hund's coupling J = 2.0, chemical potential mu = 7.0 [here](2orb_bws2.0_4.0_lvls0.0_kanU8.0_J2.0_mu7.0)

* Bethe lattice at beta = 10, half-bandwidths [2.0, 4.0], local levels [0.0, 0.0], Kanamori interaction with Hubbard U = 8.0 and Hund's coupling J = 2.0, chemical potential mu = 7.0 [here](2orb_beta10_bws2.0_4.0_lvls0.0_kanU8.0_J2.0_mu7.0)

* Bethe lattice half-bandwidths [2.0, 4.0], local levels [0.0, 0.0], density interaction with Hubbard U = 8.0 and no Hund's coupling, chemical potential mu = 4.0 [here](2orb_bws2.0_4.0_lvls0.0_densU8.0_J0.0_mu4.0)

* Bethe lattice half-bandwidths [0.75, 1.25], local levels [0.5, 0.0], density interaction with Hubbard U = 1.55 and Hund's coupling J = 0.3875, chemical potential mu = 1.7 [here](2orb_bws0.75_1.25_lvls0.5_0.0_densU1.55_J0.3875_mu1.7)

### Three-orbital calculations

For all three-orbital examples, 3 bath sites per orbital were used in the ED DMFT calculations.

* Bethe lattice half-bandwidths [1.0, 1.0, 1.0], local levels [0.0, 0.0, 0.0], density interaction with Hubbard U = 1.0 and Hund's coupling J = 0.25, chemical potential mu = 1.25 [here](3orb_bws1.0_lvls0.0_densU1.0_J0.25_mu1.25)

* Bethe lattice half-bandwidths [1.0, 1.0, 1.0], local levels [0.0, 0.0, 0.0], density interaction with Hubbard U = 5.0 and Hund's coupling J = 1.25, chemical potential mu = 6.25 [here](3orb_bws1.0_lvls0.0_densU5.0_J1.25_mu6.25)

* Bethe lattice half-bandwidths [2.0, 2.0, 4.0], local levels [0.0, 0.0, 0.0], density interaction with Hubbard U = 1.0 and Hund's coupling J = 0.25, chemical potential mu = 1.25 [here](3orb_bws2.0_2.0_4.0_lvls0.0_densU1.0_J0.25_mu1.25)

* Bethe lattice half-bandwidths [2.0, 2.0, 4.0], local levels [0.0, 0.0, 0.0], density interaction with Hubbard U = 5.0 and Hund's coupling J = 1.25, chemical potential mu = 6.25 [here](3orb_bws2.0_2.0_4.0_lvls0.0_densU5.0_J1.25_mu6.25)

* Bethe lattice half-bandwidths [2.0, 2.0, 4.0], local levels [0.0, 0.0, 0.0], Kanamori interaction with Hubbard U = 1.0 and Hund's coupling J = 0.25, chemical potential mu = 1.25 [here](3orb_bws2.0_2.0_4.0_lvls0.0_kanU1.0_J0.25_mu1.25)

* Bethe lattice half-bandwidths [1.0, 2.0, 4.0], local levels [0.0, 0.0, 0.0], Kanamori interaction with Hubbard U = 5.0 and Hund's coupling J = 1.25, chemical potential mu = 6.25 [here](3orb_bws1.0_2.0_4.0_lvls0.0_kanU5.0_J1.25_mu6.25)

* Bethe lattice half-bandwidths [2.5, 3.0, 3.5], local levels [1.0, 0.5, 0.0], density interaction with Hubbard U = 4.0 and Hund's coupling J = 1.0, chemical potential mu = 5.00 [here](3orb_bws2.5_3.0_3.5_lvls1.0_0.5_0.0_densU4.0_J1.0_mu5.00)

* Bethe lattice half-bandwidths [2.5, 3.0, 3.5], local levels [1.0, 0.5, 0.0], Kanamori interaction with Hubbard U = 4.0 and Hund's coupling J = 1.0, chemical potential mu = 5.00 [here](3orb_bws2.5_3.0_3.5_lvls1.0_0.5_0.0_kanU4.0_J1.0_mu5.00)
