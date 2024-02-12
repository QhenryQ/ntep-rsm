## Relevant publications

**A latent scale model to minimize subjectivity in the analysis of visual rating data for the National Turfgrass Evaluation Program**
*Yuanshuo Qu, Len Kne, Steve Graham, Eric Watkins, and Kevin Morris*
Front Plant Sci 2023 Jul 6;14:1135918

[Link](https://www.frontiersin.org/articles/10.3389/fpls.2023.1135918/full) to publication.
```
@article{qu2023latent,
   title     = {A latent scale model to minimize subjectivity in the analysis of visual rating data for the National Turfgrass Evaluation Program},
   author    = {Qu, Yuanshuo and Kne, Len and Graham, Steve and Watkins, Eric and Morris, Kevin},
   journal   = {Frontiers in Plant Science},
   volume    = {14},
   year      = {2023},
   publisher = {Frontiers Media SA}
}
```


## Folder Structure
* [data/](./ntep-rsm/data)                    
  * [processed/](./ntep-rsm/data/processed)
  * [raw/](./ntep-rsm/data/raw)
* [docs/](./ntep-rsm/docs)    
* [models/](./ntep-rsm/models) 
  * [no_consistent_rater_model_dist_matrix.stan](./ntep-rsm/models/no_consistent_rater_model_dist_matrix.stan)
* [notebooks/](./ntep-rsm/notebooks) 
* [reports/](./ntep-rsm/reports)  
  * [dataframes/](./ntep-rsm/reports/dataframes)
  * [figures/](./ntep-rsm/reports/figures)
  * [lmm/](./ntep-rsm/reports/lmm)
  * [param_recover/](./ntep-rsm/reports/param_recover)
  * [rsm/](./ntep-rsm/reports/rsm)
  * [cultivar_summary_statistics.csv](./ntep-rsm/reports/cultivar_summary_statistics.csv)
* [src/](./ntep-rsm/src) 
  * [constants.py](./ntep-rsm/src/constants.py)
  * [util.py](./ntep-rsm/src/util.py)
* [test/](./ntep-rsm/test) 
* [tools/](./ntep-rsm/tools)
