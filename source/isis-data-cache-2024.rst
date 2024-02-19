===============================
ISIS Instrument Data Cache 2024
===============================

updated: 2024-02

Highlights
----------

From 05/02/2024, IDAaaS users will use ISIS Data Cache: **/data/instrument** for instrument data. 

1. Desktop changes
~~~~~~~~~~~~~~~~~~

* Data - Instrument Data is read-only, access-restricted data, copied from Instrument PCs. 
* Data - Analysis Data is writable for analysis. 
* Data - Experiment Archive (only for STFC staff)

2. New data structure for instrument data
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* Structure data in Instrument/Year/RBnumber

**/data/instrument/ALF/2023/RB2300001**

3. Cycle is also available
~~~~~~~~~~~~~~~~~~~~~~~~~~

**/data/instrument/ALF/2023/CYCLE20234/RB1234567/**

Cycle and RB directories are created under each instrument with soft links to all files in a RB folder.

4. Unknown RBnumber data

**/data/instrument/ALF/2023/unknown/RB12345**

Data are copied into unknown folder if not scheduled (i.e. no RB number present in NeXus file).

(This is going to be changed later.)

Reference
----------
* :doc:`isis-data-cache-2023`
* :doc:`isis-data-cache-2024`
