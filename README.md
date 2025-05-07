Dataset from https://www.kaggle.com/datasets/kimdaegyeom/5g-traffic-datasets/data

Code description:

* `figures/` contain the figures I generated for the project report.
* `src/` contains the code I wrote.
  * `cg_dl.ipynb` contains the code for downlink packet inter-arrival time distribution estimation with SVI and MAP.
  * `cg_ul.ipynb` contains the code for uplink packet inter-arrival time distribution estimation with SVI and MAP.
  * `cg_dl_map.ipynb and cg_up_map.ipynb` are the codes I used for MAP estimation, but later they are merged in to the files above.
  * `utils.py` is the code for data processing and loading.
  * `print_ip_info.py` is the code for ip address statistics.
  * `plot_src_dst_dist.py` is the code for data visualization.
  * `pyro_intro.ipynb` is the code where I learn the `pyro` library.
* `scripts/` contains the script for data ip address analysis.
