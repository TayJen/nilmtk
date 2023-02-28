# NILMTK: Non-Intrusive Load Monitoring Toolkit

Non-Intrusive Load Monitoring (NILM) is the process of estimating the
energy consumed by individual appliances given just a whole-house
power meter reading.  In other words, it produces an (estimated)
itemised energy bill from just a single, whole-house power meter.

NILMTK is a toolkit designed to help **researchers** evaluate the accuracy of NILM algorithms. If you are a new Python user, it is recommended to educate yourself on [Pandas](https://pandas.pydata.org/), [Pytables](http://www.pytables.org/) and other tools from the Python ecosystem.

**⚠️It may take time for the NILMTK authors to get back to you regarding queries/issues. However, you are more than welcome to propose changes, support!** Remember to check existing issue tickets, especially the open ones.

# Documentation

[NILMTK Documentation](https://github.com/nilmtk/nilmtk/tree/master/docs/manual)

If you are a new user, read the [install instructions here](https://github.com/nilmtk/nilmtk/blob/master/docs/manual/user_guide/install_user.md). It came to our attention that some users follow third-party tutorials to install NILMTK. Always remember to check the dates of such tutorials, many are very outdated and don't reflect NILMTK's current version or the recommended/supported setup.

# Why a toolkit for NILM?

We quote our [NILMTK paper](http://arxiv.org/pdf/1404.3878v1.pdf)
explaining the need for a NILM toolkit:

> Empirically comparing disaggregation algorithms is currently
> virtually impossible. This is due to the different data sets used,
> the lack of reference implementations of these algorithms and the
> variety of accuracy metrics employed.

# What NILMTK provides

To address this challenge, we present the Non-intrusive Load Monitoring
Toolkit (NILMTK); an open source toolkit designed specifically to enable
the comparison of energy disaggregation algorithms in a reproducible
manner. This work is the first research to compare multiple
disaggregation approaches across multiple publicly available data sets.
NILMTK includes:

- parsers for a range of existing data sets (8 and counting)
- a collection of preprocessing algorithms
- a set of statistics for describing data sets
- a number of [reference benchmark disaggregation algorithms](https://github.com/nilmtk/nilmtk/wiki/NILM-Algorithms)
- a common set of accuracy metrics
- and much more!

Конвертация данных ECO представлена в [Test.ipynb](./Test.ipynb). Эксперименты с алгоритмами в [comparing_nilm_algorithms.ipynb](./comparing_nilm_algorithms.ipynb)
