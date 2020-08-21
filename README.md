# epanet-wdns
Water distribution networks in EPANET-compatible file format for my research (see eg. the [rl-wds](https://github.com/BME-SmartLab/rl-wds) project). All the water distribution networks are considered as pump-fed networks, thus the operable condition means that at least one pump station is available in the network and the boundaries are set properly for a successful hydraulic simulation.

### Analyze water distribution networks
There are some auxiliary (conversion, snooping, etc.) scripts in the *notebook* directory. You can run these notebooks from an [Anaconda](https://www.anaconda.com/) environment by cloning the repo and invoking `conda env create --file environment.yaml` from the root directory of the repository.

After that, you have to activate the `epanet-wdns` environment and run a Jupyter Notebook server on your machine.

### Water distribution networks
|Filename|Origin|Suppl. data|junctions|pipes|pumps|valves|tanks|reservoirs|operable|
|---|---|---|---|---|---|---|---|---|
|anytown|[link](https://emps.exeter.ac.uk/media/universityofexeter/emps/research/cws/downloads/anytown.inp)|[link](https://emps.exeter.ac.uk/engineering/research/cws/resources/benchmarks/expansion/anytown.php)|22|41|3|0|2|1|yes|
|c-town|[link](https://raw.githubusercontent.com/rtaormina/epanetCPA/master/ctown_map.inp)|[link](https://github.com/rtaormina/epanetCPA)|388|429|11|4|7|1|yes|
|d-town|[link](https://emps.exeter.ac.uk/media/universityofexeter/emps/research/cws/downloads/d-town.inp)|[link](https://emps.exeter.ac.uk/engineering/research/cws/resources/benchmarks/expansion/d-town.php)|399|443|11|5|7|1|yes|
|Richmond_standard|[link](https://emps.exeter.ac.uk/media/universityofexeter/emps/research/cws/downloads/Richmond_standard.inp)|[link](https://emps.exeter.ac.uk/engineering/research/cws/resources/benchmarks/operation/richmond.php)|865|949|7|1|6|1|yes|
|Rome|[link](https://web01-c815.uibk.ac.at/DynaVIBe-Web//projectdl/b34b6d60-ff22-4b47-9fdf-c8615eba413b.zip?_=1597411471818)|[link](https://web01-c815.uibk.ac.at/index.php/8-web-applications/3-dynavibe-web)|150630|157044|0|0|0|4|no|
|Wolf-Cordera Ranch|[link](https://emps.exeter.ac.uk/media/universityofexeter/emps/research/cws/downloads/wolf-initial-fig.inp)|[link](https://emps.exeter.ac.uk/engineering/research/cws/resources/benchmarks/expansion/wolf-cordera-ranch.php)|1782|1985|6|4|0|4|no|
