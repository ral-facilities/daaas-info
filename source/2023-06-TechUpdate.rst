ISIS DAaaS Tech Update - June 2023
==================================

.. toctree::
   :maxdepth: 1
   
   isis-data-cache

Platform
--------

As you may be aware, CentOS has reached its end of life. To ensure
continued security, stability, and support, we have migrated the DAaaS
platform to Rocky 8 Linux, a reliable and compatible alternative.


Workspaces
----------

We have also been working on upgrading workspaces to Rocky 8 Linux. This
will replace the aging CentOS7 Linux distribution we currently use.

In the coming months, we will work with each instrument group one-by-one
to upgrade your workspaces to Rocky 8 alongside redeploying all of the
scientific software on your group’s workspaces in Apptainer containers
(Python packages and other appropriate software can be installed with
Conda or Python virtual environments also). We will get in touch with
each group for this upgrade.

Data
----

In the new updated workspaces, we also plan to disconnect ISIS Archive
from workspaces. All new workspaces will use ISIS Instrument Data Cache,
which aligns with ISIS Data Policy.

Details about ISIS Instrument Data Cache can be found in section of
:doc:`isis-data-cache`.
