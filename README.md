# ReSeq-profiles
For best results it is always advised to create your own profiles from a dataset very closely matching the desired sequencer, chemistry, fragmentation, adapters, PCR cycles, etc. Furthermore, training on the same or a closely related species, is best to be sure that the necessary profile space (e.g. range of GC content) is well populated. However, in many situations there is no specific case that should be simulated, but a wide variety of datasets is important. Under this condition finding good datasets is tedious work and recreating the same profile from a given dataset does not help to ensure the quality of the simulated data. Therefore, this repository is designed to provide high-quality profiles with detailed information on the original datasets. Whenever possible, method benchmarks should be performed on the simulated and the original dataset to verify that the simulation created realistic conditions for the particular use case.

| Dataset | Year | Sequencer | Adapter | Species | Read length | Fragment length | Coverage | Profile | Ipf |
|------------------------------------------------------------------------------------|-----------|------------|---------|-------------|-----|-----|-----|---|---|
| SRR490124                                                                          | &le; 2013 | HiSeq 2000 | TruSeq  | *E. coli*   | 100 | 164 | 449 | | |
| BaseSpace, HiSeq 4000: Nextera XT (B.cereus, E.coli, R.sphaeroides), Ecoli1_L001   | 2015      | HiSeq 4000 | Nextera | *E. coli*   | 151 |  -  | 508 | | |
| BaseSpace, HiSeq 4000: Nextera XT (B.cereus, E.coli, R.sphaeroides), Bcereus1_L001 | 2015      | HiSeq 4000 | Nextera | *B. cereus* | 151 |  -  | 508 | | |

In case you created a profile that reflects a given dataset well, please contact me to share it with others.
