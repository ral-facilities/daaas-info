===============================
ISIS Instrument Data Cache 2024
===============================

updated: 2024-02

Highlights
----------

From 05/02/2024, IDAaaS users will use ISIS Data Cache: **/data/instrument** for instrument data. 

1. Desktop shortcut changes
~~~~~~~~~~~~~~~~~~~~~~~~~~~

* **Data - Instrument Data** (read-only, access-restricted data, copied from Instrument PCs. )
* **Data - Analysis Data**   ( writable for analysis. )
* **Data - Experiment Archive** (only for STFC staff)

2. New data structure for instrument data
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Instrument data are in /data/instrument/Year/RBnumber

**/data/instrument/ALF/2023/RB2300001**

3. Cycle folder is also available
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Cycle and RB directories are created under each instrument with soft links to all files in a RB folder.

**/data/instrument/ALF/2023/CYCLE20234/RB1234567/**

4. Unknown RB number data
~~~~~~~~~~~~~~~~~~~~~~~~~

Data are copied into unknown folder if not scheduled (i.e. no RB number present in NeXus file).

**/data/instrument/ALF/2023/unknown/RB12345**

(This is a temporary solution implemented.)

Reference
----------
* :doc:`isis-data-cache-2023`
* :doc:`isis-data-cache-2024`
