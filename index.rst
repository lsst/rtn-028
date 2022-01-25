:tocdepth: 1

.. sectnum::

Abstract
========

We have profiled the various pipetasks in the DRP pipeline and have characterized the memory and CPU time usage of those task for processing DESC DC2 data.  We have also studied the efficiency of running on Rome and Milan processors and various levels of node occupancy.  This information is used to estimate the node hours required to do the first year of DRP processing of the Rubin WFD survey.

Motivation and Background
=========================

This study was orginally motivated by the need for the Dark Energy Science Collaboration (DESC) to understand its computing resource needs for systematics studies that require pixel-level reprocessing of the first year (Y1) of Rubin data.  In practice, these studies would involve the reprocessing of several smaller datasets, using alternative algorithms and/or data selections, or could include simulated images.  Therefore, as rough guide to the needed resources, DESC settled on the goal of reprocessing 10% of Y1 data 10 times as the target value for this study.  For simplicity, we've recast this doing a full DRP processing of the Y1 Wide Fast Deep (WFD) Rubin survey observations.  This is ~80% of the Y1 data, and it provides a relatively homogenous data set that's relevant for DESC's need and which makes the resource estimation more straight forward.

Inputs to Estimating the Y1 WFD DRP Processing
==============================================

The basic input to this study is the cadence of observations during Y1.  We have used version v2.0 of the 10 year baseline cadence that is available from the `UW server <http://astro-lsst-01.astro.washington.edu:8080/>`__ as `baseline_v2.0_10yrs.db <http://astro-lsst-01.astro.washington.edu:8080/fbs_db/baseline/baseline_v2.0_10yrs.db>`__. 


Estimation Procedure
====================

Profiling the Individual Pipetasks
==================================

Processing Time Results
=======================

Disk Storage Needs
==================

Throughout Scaling with Node Occupancy
======================================

.. .. rubric:: References

.. Make in-text citations with: :cite:`bibkey`.

.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
..    :style: lsst_aa
