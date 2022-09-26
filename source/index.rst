.. OpenEngine documentation master file, created by
   sphinx-quickstart on Mon Apr  4 10:30:32 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to the CBLab Documentation
======================================

.. _doc:

.. image:: ./content/media/logo.png

\


City Brain Lab (CBLab) is a toolkit for scalable traffic simulation. CBLab consists of three components: CBEngine,
CBData, and CBScenario, with which we make it possible to run large-scale traffic simulation on city-level road
networks based on only raw traffic data.

Now, the `code <https://github.com/CityBrainLab/CityBrainLab.git>` and the `dataset <https://drive.google.com/drive/folders/1IyTvWprOA1R_6PVkuh7v9R4xrHcZAmYT?usp=sharing>`
are all available. Feel free to start your large-scale traffic simulation!

\

.. image:: ./content/media/overview.png

\

Learn more about three components respectively:

- `CBEngine`_: Scalable traffic simulator
- `CBData`_: Pipelines providing simulation inputs and learning to simulate
- `CBScenario`_: Benchmark framework for large-scale traffic policies

.. _`CBEngine`: https://cblab-documentation.readthedocs.io/en/latest/content/cbengine/cbengine.html
.. _`CBData`: https://cblab-documentation.readthedocs.io/en/latest/content/cbdata/cbdata.html
.. _`CBScenario`: https://cblab-documentation.readthedocs.io/en/latest/content/cbscenario/cbscenario.html

Why CBLab?
----------

Traffic policies has made great progress in enhancing the performance of urban traffic. 
However, limited by the efficiency of traffic simulators and shortage in large-scale road network data, these policies
are only trained over small road networks (e.g. 4x3 or 4x4). 

CBLab supports very efficient traffic simulation and enriched large-scale road network data source for simulation.
With CBLab, users can run traffic simulation and train traffic policies on real world road networks with 1,000-10,000 intersections,
which brings about real improvement to the urban traffic. 

   .. toctree::
      :maxdepth: 2
      :caption: Contents
      
      content/cbengine/cbengine.rst
      content/cbdata/cbdata.rst
      content/cbscenario/cbscenario.rst
