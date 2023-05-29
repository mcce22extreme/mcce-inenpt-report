# Report on OpenStack infrastructure

This is a report about a service realized in the OpenStack infrastructure of FH Burgenland. It was created as part of the Master program 'Cloud Computing Engineering' in the course 'Infrastructure Engineering PT'.

## Assignment

An infrastructure with its own network(s) and multiple instances is to be created on the OpenStack installation of the UAS.
One or more services should run on it.
Ideally, these services are related to the topic of the work that is being created for the InEn ILV.
Therefore, the participation groups are also the same as in the ILV.
This is not directly possible with this year's requirement that everything should run on an external cloud platform.
Therefore, for example, the results could be presented in a wiki or similar.
However, it is also permissible that the services have nothing to do with ILV at all.

Caution. Everything for the delivery should take place in the delivery project.
The project InEn-22107810xx is still available for personal experiments until the end of the semester.

Further, a report is to be turned in describing the infrastructure.
This should be designed in such a way that someone who takes over this infrastructure (e.g. as a successor of the admin in a company) can manage it without further inquiries.
So all aspects like networks, IP addresses, security groups etc. should be described.
Also, the services should be usable after reading this report.
The report can be written either in German or English.

There will be a draft submission of the report, which should already have the complete scope.
This will allow me to give feedback before the final submission.
The services do not have to be working at the time of the draft.

## Realized service

As the Software Development Lifecycle is all over the place nowadays, also in this program, we decided to run a local GitLab instance in OpenStack to, among other things, host git repositories and run CI tasks.
