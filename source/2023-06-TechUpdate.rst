ISIS DAaaS Tech Update - June 2023
==================================

.. toctree::
   :maxdepth: 1
   
   software
   isis-data-cache

Platform
--------

As you may be aware, CentOS has reached its end of life. To ensure
continued security, stability, and support, we have migrated the DAaaS
platform to Rocky 8 Linux, a reliable and compatible alternative.

Scientific Software
-------------------

We have been containerising scientific software to make it easy to
install, upgrade and deploy to DAaaS platform.

If you are developing any software that aims to be deployed into DAaaS
workspaces, packing it in `an
Apptainer <https://apptainer.org/docs/user/latest/>`__ is the fastest
way to get it deployed. Please get in touch if you need any guidance.

A full list of scientific software on DAaaS platform is in section of 
:doc:`software`.


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

Training
--------

`DAaaS Training Site <https://training.analysis.stfc.ac.uk/>`__ has been
on trial since February 2023. This is a dedicated platform for resources
defined and allocated for training, workshops or conferences. It has
following features:

-  Training organizers can request and manage courses
-  Attendees can be anywhere in the world to access the resources
-  A bespoke workspace can be requested for the course
-  There is a dedicated storage for training materials
-  Training organizers can have assistants to help the attendees
-  Attendees can access the training workspace with an invitation click

Please get in touch for more details or trying out on the site.

Special thanks to ISIS Excitation Group and Research Software
Engineering Group helping us on testing the site.

Services
--------

Incidents
~~~~~~~~~

-  `April 26 - RAL Power
   Cut <https://daaas.statuspage.io/incidents/zfmjygvgv7pt>`__

-  `May 18 - User Office Site
   Unavailable <https://daaas.statuspage.io/incidents/l6td526zkx1d>`__

Maintenance
~~~~~~~~~~~

-  `January 4 - DAaaS Security
   Update <https://daaas.statuspage.io/incidents/pcb6f1bpszv6>`__

-  `March 23 - User Office Security
   Patching <https://daaas.statuspage.io/incidents/97yrj52wnhkq>`__

Uptime
~~~~~~

`Check out DAaaS Status
Page <https://daaas.statuspage.io/uptime/wx9ylxz0swdh?page=1>`__
