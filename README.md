# epanet-wdns
Water distribution networks in EPANET-compatible file format.

### Analyze water distribution networks
There are some auxiliary (conversion, snooping, etc.) scripts in the *notebook* directory. You can run these notebooks from an [Anaconda](https://www.anaconda.com/) environment by cloning the repo and invoking `conda env create --file environment.yaml` from the root directory of the repository.

After that, you have to activate the `epanet-wdns` environment and run a Jupyter Notebook server on your machine.

### Water distribution networks
|Name|Origin|Suppl. data|nodes|pipes|pumps|valves|tanks|reservoirs|
|---|---|---|---|---|---|---|---|---|
|Richmond|[link](https://emps.exeter.ac.uk/media/universityofexeter/emps/research/cws/downloads/Richmond_standard.inp)|[link](https://emps.exeter.ac.uk/engineering/research/cws/resources/benchmarks/operation/richmond.php)|872|949|7|1|6|1|
