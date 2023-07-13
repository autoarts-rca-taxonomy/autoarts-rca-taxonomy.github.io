# ARTS Root Cause Taxonomy

ARTS (Azure Reliability Tagging System) is a hierarchical taxonomy of root cause tags used to label production incidents of Azure services.
This taxonomy is open-sourced as a part of our publication on AutoARTS, an ML-based tool to automatically label incident postmortem reports at Microsoft Azure.

[ARTS](https://autoarts-rca-taxonomy.github.io/taxonomy.html) provides a visualization of the hierarchy of root causes that we identified.

[ARTS Data File](https://autoarts-rca-taxonomy.github.io/taxonomy.html) contains a list of all the root cause tags in ARTS and their observed 
contributing frequency to production incidents.

## Contributing to ARTS

ARTS taxonomy is built from painstaking manual analysis of over 2000 incidents from across 468 services in Microsoft Azure. Even though it is comprehensive, 
we believe that a root cause taxonomy should be continously evolving. 

Please contribute to ARTS taxonomy to add new tags and refine existing tags to enable high quality annotations to incident postmortems and improve the understanding 
of production incident root causes across the larger development and research communities.

## Citing ARTS Taxonomy

If you think the ARTS taxonomy is helpful for your research or development, please consider citing our [paper](https://www.usenix.org/conference/atc23/presentation/dogga):

```text
@inproceedings {288815,
author = {Pradeep Dogga and Chetan Bansal and Richard Costleigh and Gopinath Jayagopal and Suman Nath and Xuchao Zhang},
title = {{AutoARTS}: Taxonomy, Insights and Tools for Root Cause Labelling of Incidents in Microsoft Azure},
booktitle = {2023 USENIX Annual Technical Conference (USENIX ATC 23)},
year = {2023},
isbn = {978-1-939133-35-9},
address = {Boston, MA},
pages = {359--372},
url = {https://www.usenix.org/conference/atc23/presentation/dogga},
publisher = {USENIX Association},
month = jul,
}
```
