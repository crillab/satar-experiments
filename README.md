# SATAR: a tool for enumerating (minimal non-redundant) Association Rules
This repository has code for replicating the experiments in [*Declarative Decomposition Approach for Discovering Association Rules*](https://yizza.gitlab.io/files/ijcai20.pdf) - IJCAI20

## Run (under Linux OS): 

    ./satar -min-supp=MIN_SUPP -min-conf=NB_CONF -ncores=NB_CORES -mnr|-no-mnr DATASET

### To print ARs/MNRs models use:

    ./satar -min-supp=MIN_SUPP -min-conf=NB_CONF -ncores=NB_CORES -mnr|-no-mnr -verb=2 DATASET
   
  
## Citing SATAR  

If you use SATAT in a scientific publication, please consider citing the following paper:

Yacine Izza, Said Jabbour, Badran Raddaoui and Abdelhamid Boudane (2020).  [*Declarative Decomposition Approach for Discovering Association Rules*] (https://yizza.gitlab.io/files/ijcai20.pdf) - IJCAI 2020.

BibTeX entry:

```bibtex
@article{
  author    = {Yacine Izza and 
               Sa{\"{\i}}d Jabbour and
               Badran Raddaoui and 
               Abdelhamid Boudane},
  title     = {Declarative Decomposition Approach for Discovering Association Rules},
  booktitle = {IJCAI},
  year      = {2020}
}
```