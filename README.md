# Benchmark-Models-PEtab
A collection of mathematical models with experimental data in the [PEtab](https://github.com/PEtab-dev) format as benchmark problems in order to evaluate new and existing methodologies for data-based modelling. The publication for the introduction and analysis of the benchmark problem collection is available at https://academic.oup.com/bioinformatics/article/35/17/3073/5280731.

Contributions to the collection are very welcome. For this, please create a new branch, add your model and test your files with the provided functions, and start a pull request. We will then check your model and merge it into the collection. We are continuously working on the extension of the collection.

## Overview
| PEtab Problem ID                                                                             |   Conditions |   Estimated Parameters |   Events |   Preequilibration |   Postequilibration |   Measurements |   Observables | Noise distribution(s)   |   Species | References                                                                                                                                                                                 |
|:---------------------------------------------------------------------------------------------|-------------:|-----------------------:|---------:|-------------------:|--------------------:|---------------:|--------------:|:------------------------|----------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Alkan_SciSignal2018](Benchmark-Models/Alkan_SciSignal2018/)                                 |           73 |                     56 |        0 |                  0 |                   0 |           1733 |            12 | normal                  |        36 | [\[1\]](http://identifiers.org/doi/10.1126/scisignal.aat0229)                                                                                                                              |
| [Bachmann_MSB2011](Benchmark-Models/Bachmann_MSB2011/)                                       |           36 |                    113 |        0 |                  0 |                   0 |            541 |            20 | normal                  |        25 | [\[1\]](http://identifiers.org/doi/10.1038/msb.2011.50)                                                                                                                                    |
| [Beer_MolBioSystems2014](Benchmark-Models/Beer_MolBioSystems2014/)                           |           19 |                     72 |        0 |                  0 |                   0 |          27132 |             2 | normal                  |         4 | [\[1\]](http://identifiers.org/doi/10.1039/c3mb70594c)                                                                                                                                     |
| [Bertozzi_PNAS2020](Benchmark-Models/Bertozzi_PNAS2020/)                                     |            2 |                      3 |        0 |                  0 |                   0 |            138 |             1 | normal                  |         3 | [\[1\]](http://identifiers.org/pubmed/32616574)                                                                                                                                            |
| [Blasi_CellSystems2016](Benchmark-Models/Blasi_CellSystems2016/)                             |            1 |                      9 |        0 |                  0 |                   1 |            252 |            15 | normal                  |        16 | [\[1\]](http://identifiers.org/doi/10.1016/j.cels.2016.01.002)                                                                                                                             |
| [Boehm_JProteomeRes2014](Benchmark-Models/Boehm_JProteomeRes2014/)                           |            1 |                      9 |        0 |                  0 |                   0 |             48 |             3 | normal                  |         8 | [\[1\]](http://identifiers.org/doi/10.1021/pr5006923)                                                                                                                                      |
| [Borghans_BiophysChem1997](Benchmark-Models/Borghans_BiophysChem1997/)                       |            1 |                     23 |        0 |                  0 |                   0 |            111 |             1 | normal                  |         3 | [\[1\]](http://identifiers.org/doi/10.1016/s0301-4622(97)00010-0)                                                                                                                          |
| [Brannmark_JBC2010](Benchmark-Models/Brannmark_JBC2010/)                                     |            8 |                     22 |        0 |                  1 |                   0 |             43 |             3 | normal                  |         9 | [\[1\]](http://identifiers.org/doi/10.1074/jbc.M110.106849)                                                                                                                                |
| [Bruno_JExpBot2016](Benchmark-Models/Bruno_JExpBot2016/)                                     |            6 |                     13 |        0 |                  0 |                   0 |             77 |             5 | normal                  |         7 | [\[1\]](http://identifiers.org/doi/10.1093/jxb/erw356)                                                                                                                                     |
| [Chen_MSB2009](Benchmark-Models/Chen_MSB2009/)                                               |            4 |                    155 |        0 |                  0 |                   0 |            120 |             3 | normal                  |       500 | [\[1\]](http://identifiers.org/doi/10.1038/msb.2008.74)                                                                                                                                    |
| [Crauste_CellSystems2017](Benchmark-Models/Crauste_CellSystems2017/)                         |            1 |                     12 |        0 |                  0 |                   0 |             21 |             4 | normal                  |         5 | [\[1\]](http://identifiers.org/doi/10.1016/j.cels.2017.01.014)                                                                                                                             |
| [Elowitz_Nature2000](Benchmark-Models/Elowitz_Nature2000/)                                   |            1 |                     21 |        0 |                  0 |                   0 |             58 |             1 | normal                  |         8 | [\[1\]](http://identifiers.org/doi/10.1038/35002125)                                                                                                                                       |
| [Fiedler_BMC2016](Benchmark-Models/Fiedler_BMC2016/)                                         |            3 |                     22 |        0 |                  0 |                   0 |             72 |             2 | normal                  |         6 | [\[1\]](http://identifiers.org/doi/10.1186/s12918-016-0319-7)                                                                                                                              |
| [Froehlich_CellSystems2018](Benchmark-Models/Froehlich_CellSystems2018/)                     |         9169 |                   4231 |        0 |                  0 |                9169 |           9169 |             1 | normal                  |      1396 | [\[1\]](http://identifiers.org/doi/10.1126/scisignal.aat0229)                                                                                                                              |
| [Fujita_SciSignal2010](Benchmark-Models/Fujita_SciSignal2010/)                               |            6 |                     19 |        0 |                  0 |                   0 |            144 |             3 | normal                  |         9 | [\[1\]](http://identifiers.org/doi/10.1126/scisignal.2000810)                                                                                                                              |
| [Giordano_Nature2020](Benchmark-Models/Giordano_Nature2020/)                                 |            1 |                     50 |        0 |                  0 |                   0 |            313 |             7 | normal                  |        13 | [\[1\]](http://identifiers.org/pubmed/32322102)                                                                                                                                            |
| [Isensee_JCB2018](Benchmark-Models/Isensee_JCB2018/)                                         |          123 |                     46 |        0 |                  1 |                   0 |            687 |             3 | normal                  |        25 | [\[1\]](http://identifiers.org/doi/10.1083/jcb.201708053)                                                                                                                                  |
| [Laske_PLOSComputBiol2019](Benchmark-Models/Laske_PLOSComputBiol2019/)                       |            3 |                     13 |        0 |                  0 |                   0 |             42 |            13 | normal                  |        41 | [\[1\]](http://identifiers.org/biomodels.db/BIOMD0000000463) [\[2\]](http://identifiers.org/biomodels.db/MODEL1307270000) [\[3\]](http://identifiers.org/doi/10.1371/journal.pcbi.1006944) |
| [Lucarelli_CellSystems2018](Benchmark-Models/Lucarelli_CellSystems2018/)                     |           16 |                     84 |        0 |                  0 |                   0 |           1755 |            65 | normal                  |        33 | [\[1\]](http://identifiers.org/doi/10.1016/j.cels.2017.11.010)                                                                                                                             |
| [Okuonghae_ChaosSolitonsFractals2020](Benchmark-Models/Okuonghae_ChaosSolitonsFractals2020/) |            1 |                     16 |        0 |                  0 |                   0 |             92 |             2 | normal                  |         9 | [\[1\]](http://identifiers.org/doi/10.1016/j.chaos.2020.110032)                                                                                                                            |
| [Oliveira_NatCommun2021](Benchmark-Models/Oliveira_NatCommun2021/)                           |            1 |                     12 |        0 |                  0 |                   0 |            120 |             2 | normal                  |         9 | [\[1\]](http://identifiers.org/doi/10.1038/s41467-020-19798-3)                                                                                                                             |
| [Perelson_Science1996](Benchmark-Models/Perelson_Science1996/)                               |            1 |                      3 |        0 |                  0 |                   0 |             16 |             1 | normal                  |         4 | [\[1\]](http://identifiers.org/doi/10.1126/science.271.5255.1582)                                                                                                                          |
| [Rahman_MBS2016](Benchmark-Models/Rahman_MBS2016/)                                           |            1 |                      9 |        0 |                  0 |                   0 |             23 |             1 | normal                  |         7 | [\[1\]](http://identifiers.org/doi/10.1016/j.mbs.2016.07.009)                                                                                                                              |
| [Raimundez_PCB2020](Benchmark-Models/Raimundez_PCB2020/)                                     |          170 |                    136 |        0 |                  4 |                   0 |            627 |            79 | normal                  |        22 | [\[1\]](http://identifiers.org/doi/10.1371/journal.pcbi.1007147)                                                                                                                           |
| [SalazarCavazos_MBoC2020](Benchmark-Models/SalazarCavazos_MBoC2020/)                         |            4 |                      6 |        0 |                  0 |                   0 |             18 |             3 | normal                  |        75 | [\[1\]](http://identifiers.org/doi/10.1091/mbc.E19-09-0548)                                                                                                                                |
| [Schwen_PONE2014](Benchmark-Models/Schwen_PONE2014/)                                         |           19 |                     30 |        0 |                  0 |                   0 |            286 |             4 | normal                  |        11 | [\[1\]](http://identifiers.org/doi/10.1371/journal.pone.0133653)                                                                                                                           |
| [Sneyd_PNAS2002](Benchmark-Models/Sneyd_PNAS2002/)                                           |            9 |                     15 |        0 |                  0 |                   0 |            135 |             1 | normal                  |         6 | [\[1\]](http://identifiers.org/doi/10.1073/pnas.032281999)                                                                                                                                 |
| [Weber_BMC2015](Benchmark-Models/Weber_BMC2015/)                                             |            2 |                     36 |        0 |                  1 |                   0 |            135 |             8 | normal                  |         7 | [\[1\]](http://identifiers.org/doi/10.1186/s12918-015-0147-1)                                                                                                                              |
| [Zhao_QuantBiol2020](Benchmark-Models/Zhao_QuantBiol2020/)                                   |            7 |                     28 |        0 |                  0 |                   0 |             82 |             1 | normal                  |         5 | [\[1\]](http://identifiers.org/pubmed/32219006)                                                                                                                                            |
| [Zheng_PNAS2012](Benchmark-Models/Zheng_PNAS2012/)                                           |            1 |                     46 |        0 |                  1 |                   0 |             60 |            15 | normal                  |        15 | [\[1\]](http://identifiers.org/doi/10.1073/pnas.1201240109)                                                                                                                                |

## License

Any original content in this repository may be used under the terms of the [BSD-3-Clause license](LICENSE).
Different terms may apply to models and datasets, for which we refer the user to the original publications
that are referenced in the respective SBML files.

## Installation

See [INSTALL.md](INSTALL.md).
