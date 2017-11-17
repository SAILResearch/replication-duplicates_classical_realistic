# Replication Package for "Revisiting the Performance Evaluation of Automated Approaches for the Retrieval of Duplicate Issue Reports"

Mohamed Sami Rakha, Cor-Paul Bezemer, Ahmed E. Hassan  
[IEEE Transactions on Software Engineering, Pre-Print, Issue 99](http://dx.doi.org/10.1109/TSE.2017.2755005)

Abstract: Issue tracking systems (ITSs), such as Bugzilla, are commonly used to track reported bugs, improvements and change requests for a software project. To avoid wasting developer resources on previously-reported (i.e., duplicate) issues, it is necessary to identify such duplicates as soon as they are reported. Several automated approaches have been proposed for retrieving duplicate reports, i.e., identifying the duplicate of a new issue report in a list of n candidates. These approaches rely on leveraging the textual, categorical, and contextual information in previously-reported issues to decide whether a newly-reported issue has previously been reported. In general, these approaches are evaluated using data that spans a relatively short period of time (i.e., the classical evaluation). However, in this paper, we show that the classical evaluation tends to overestimate the performance of automated approaches for retrieving duplicate issue reports. Instead, we propose a realistic evaluation using all the reports that are available in the ITS of a software project. We conduct experiments in which we evaluate two popular approaches for retrieving duplicate issues (BM25F and REP) using the classical and realistic evaluations. We find that for the issue tracking data of the Mozilla foundation, the Eclipse foundation and OpenOffice, the realistic evaluation shows that previously proposed approaches perform considerably lower than previously reported using the classical evaluation. As a result, we conclude that the reported performance of approaches for retrieving duplicate issue reports is significantly overestimated in literature. In order to improve the performance of the automated retrieval of duplicate issue reports, we propose to leverage the resolution field of issue reports. Our experiments show that a relative improvement in the performance of a median of 7-21.5% and a maximum of 19-60% can be achieved by leveraging the resolution field of issue reports for the automated retrieval of duplicates.

## Bibtex (Pre-print)

```bibtex
@ARTICLE{Rakha17,
author={M. S. Rakha and C. P. Bezemer and A. E. Hassan},
journal={IEEE Transactions on Software Engineering},
title={Revisiting the Performance Evaluation of Automated Approaches for the Retrieval of Duplicate Issue Reports},
year={2017},
volume={PP},
number={99},
pages={1-1},
doi={10.1109/TSE.2017.2755005},
ISSN={0098-5589},
}
```

## Data and Scripts

The replication package containing all data and source code used in our experiments can be downloaded [here](https://github.com/SAILResearch/replication-duplicates_classical_realistic/releases/latest)
