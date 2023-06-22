# ISIS DAaaS Tech Update - June 2023

## Platform
We are upgrading the DAaaS platform to run on Rocky 8 Linux. Up until now, we have upgraded our pre-production environment and will roll out the changes to production during the summer.

## Scientific Software and Workspaces
We have been containerising scientific software to make it easy to install, upgrade and deploy. 

If you are developing any software that aims to be deployed into DAaaS workspaces, packing it in an Apptainer is the fastest way to get it deployed. Please get in touch if you need any guidance.

We have also started working on upgrading workspaces to Rocky 8 Linux. This will replace the aging CentOS7 Linux distribution we currently use. In the coming months, we will work with each instrument group one-by-one to upgrade your workspaces to Rocky 8 alongside redeploying all of the scientific software on your group's workspaces in Apptainer containers (Python packages and other appropriate software can be installed with Conda or Python virtual environments also). We will get in touch with each group by email before we begin this process.

## Data
TO DO


## Training

[DAaaS Training Site](https://training.analysis.stfc.ac.uk/) is live since February 2023. This is a dedicated platform for resources defined and allocated for training, workshops or conferences. It has following features:

- Training organizers can request and manage course
- Attendees can be anywhere in the world to access the resources
- A bespoke workspace can be requested for the course
- A dedicated storage for training materials
- Training organizers can have assistants to help the attendees
- Attendees can access the training workspace with an invitation click

Please get in touch for more details or trying out on the site.

Special thanks to ISIS Excitation Group and Research Software Engineering Group helping us for the testing.

## Service (2023 January-June)

### Incidents

- [April 26 - RAL Power Cut](https://daaas.statuspage.io/incidents/zfmjygvgv7pt)

- [May 18 - User Office Site Unavailable](https://daaas.statuspage.io/incidents/l6td526zkx1d)

### Maintenance

- [January 4 - Security Update](https://daaas.statuspage.io/incidents/pcb6f1bpszv6)

- [March 23 - User Office Security Patching](https://daaas.statuspage.io/incidents/97yrj52wnhkq)

### Uptime
[Check out DAaaS Status Page ](https://daaas.statuspage.io/uptime/wx9ylxz0swdh?page=1)



