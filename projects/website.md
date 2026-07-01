# CHAOSS Website Infrastructure Project

Project Owner: Adrian Edwards

## Background:
Prior to the creation of the Infrastructure Team within CHAOSS, the way in which the CHAOSS website was hosted was not very clearly documented and was under the control of a set of people that wasnt well documented and seemingly changed occasionally.

This was part of the reason for the creation of the Infrastructure team - to create a group of people who could collectively own the CHAOSS core infrastructure in a way that was documented and governed out in the open.

## Objectives of this project:
1. Bring the CHAOSS Website (https://chaoss.community) under the control of the infrastructure team
2. Document the operation of the CHAOSS website and the procedures surrounding it
3. Steward the infrastructure of the website in an ongoing basis, ensuring community members are able to contribute to its content while allowing necessary administrative and maintainance tasks to be performed.


## Phase 1: Adoption
Status: Complete

This phase mostly (but not completely) addresses the goals of objective 1. It has successfully brought the CHAOSS website under the control of one member of the infrastructure committee (Adrian). This moved the CHAOSS website from its previous hosting provider into a self-hosted docker container whose infrastructure is being donated to CHAOSS. This was done under relatively compressed circumstances to preserve website uptime and buy time for future migrations. The remaining piece of objective 1 (to ensure anyone on the infra team has the ability to control the infrastructure) will happen in a later stage as the infrastructure comes under a greater degree of community control.


## Phase 2: Stability

Status: In Progress

This phase helps stabilize the website infrastructure (moving out of a docker container to a more managed environment) and introduce some nice to have management features that the docker container would require us to largely do manually, such as:
- easy backup and restore
- separate development and production sites with easy copying between them.
- security updates and better monitoring
- support available from the managed provider should that be needed

These improvements should allow CHAOSS community leaders with administrative logins to wordpress to feel more confident in their ability to make changes without breaking things, allowing us to embark on projects such as:
- cleaning up old plugins
- keeping the site updated and secure
- trying bolder, new ideas
