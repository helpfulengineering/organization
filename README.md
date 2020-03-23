# Helpful Engineers GitHub Community



## Effort and account duplication
As far as we know, there are currently three different communities that refer to the Helpful Engineering project: Helpful-Engineers, helpfulengineering (that is the good one) and HelpfulEngineers, that was made by the ventilator project/s and is being merged.

The first two communities were already merged, with the expected clash of the organizational structures, but, thankfully, both organizations were nearly empty at the time. Currently, we have some issues referring to the repository naming conventions and structure:

https://github.com/helpfulengineering/resources/issues/67
https://github.com/helpfulengineering/free-for-covid/issues/1 
https://github.com/helpfulengineering/experience-tagger/issues/1 
https://github.com/helpfulengineering/devops/issues/1 

Please refer to the naming convention proposal on the «kinds of repository» section, and use it as a guideline to take further decisions about the renaming and merging of the current repositories. Better yet, head to the «structure proposal» below.

To avoid this happening again, we should make an announcement to all the project teams (if not the entire community) explaining how to use the community. Preferably with a link to this document, once it makes its way to GitHub. 

## Repository creation

### Organization specific
* Creation policy: we should embrace the Unix philosophy of «do one thing and do it well» to segment the organization needs into concisely scoped repositories.

* Naming: these repositories should be named in a consistent way (kebab-case) and, ideally, share a common prefix like (organization).

* Access privileges: this has to be discussed, please refer to the «owner and member policy» section below.

* Quirks: the most important repositories can be pinned so they are easy to find.

* Teams: People can be added to teams they work on, and be added to skills. This way, specific skill sets can be tagged in issues and pull requests across projects and across the organization. Is there any way we can automate the already available info about all the members?

### Project specific
* Creation policy: there should be a maximum of one repository by project (a soft limit to keep things sane), and a minimum of zero, as we shouldn’t be creating repositories for projects that don’t need one or are using other tools and don’t want to migrate.

* Naming: repository names should match the Slack channels they are affiliated with where possible (i.e. Slack channel #project-awesome-thing would yield project-awesome-thing). 

* Access privileges: each project will designate a few users, covering different time zones whenever possible, that will have triage-level access to the project repository.

## Repository licensing guide
This has been solved by the legal team, and they suggest to leave already established licenses as they are and use these licenses for the new projects: https://helpfulengineering.slack.com/archives/CUR6CGMBL/p1584975246127600 

Considering the huge uncertainties in how society will respond to the COVID-19 pandemic, we have decided to use permissive licenses where at all possible. This is founded on a desire to collaborate with established manufacturers and technology companies in order to create the best responses we can.

We have kindly used Safecast's licensing structure for inspiration and content. We also believe that there is a chance large manufacturing or technology companies may wish to pick up our designs in this moment of crises. On this basis, we are recommending permissive licenses for you to use.

### Hardware Projects
Everything needed or used to design, make, test or prepare the Medical Hardware or other Contributions  to be made or distributed whether hardware designs, software, schematics or anything else is licensed under the CERN 2.0 Permissive licence (CERN-OHL-P).
That includes both firmware and any software that normally comes with the  hardware or other item as well as software used to test it. We recommend placing a TXT file in the root of the repository, by the repository owner, with this license in it.

### Software Projects
Software that is not necessary for the functioning of the hardware but may be loaded onto it, or be used by another device to communicate with it is licensed under the permissive Blue Oak License 1.0.0 unless another open source license is used. We recommend placing a TXT file in the root of the repository, by the repository owner, with this license in it.
Guides, instructional videos, and other materials
Accompanying materials such as instruction manuals, videos and other copyrightable works that are useful for but not necessary to design, make, test or prepare the Medical Hardware for distribution should be published under a Creative Commons Attribution 4.0 License. 

A reference to this license should be included at the bottom of vital documents, and we recommend the following;
All copyrightable materials  other than software, and everything needed to design, make, test and prepare the hardware for distribution, such as instructional videos and manuals, are published under a Creative Commons Attribution 4.0 License.
As a follow up, we will be asking all contributors to acknowledge that their designs are open source.

## Owner and member permission policy
We currently rely on the serendipity principle to find new owners/members, but we should find a balance between federation and control, following the concerns that arose during the last standup.

All the new members should be just public (visible) members unless stated otherwise, and the maximum per-repository permission for specific contributors should be triage.


## Structure proposal


<!--
## Scope and usage of the community
Currently we don’t have a standardized project management tool, and everybody has a personal preference about which tool to use for which purpose. This freedom is what makes us progress quickly by working with the tools we’re accustomed to use, and going against that may not be a good idea at all, but probably we should encourage the use of GitHub for certain tasks (apart from code version control):

* Continuous integration and continuous deployment.
* Project-level issue management and collaboration.
* Project-level documentation (on the wiki or a documentation folder).
* Community-level issue management and collaboration: organization repository.
* Front-page hosting: as long as https://helpfulengineers.org remains static, having it served by GitHub pages would simplify the submission of improvements and updates.
-->


## Repositories
  organization: top-level issue tracking, wiki, and organization management, should have a refined version of this document as the README and should be pinned.

  proposals: will be the new name of resources, and is going to be used to host the project proposals (both hardware and software) in its early stages; should be pinned.

  <!-- project-skill-pool: will be the new name of experience-tagger, that will become a top-level folder inside; the Slack channel #project-user-profile-database will be renamed accordingly.-->
  <!--organization-cloud-management: will be the new name of devops; yet to decide the future of the repository, as it’s currently a bit empty.-->


## Teams

* finance
* legal
* operations
* projects
  * project-experience-tagger <= needs renaming as per the structure proposal
* skills
  * skill-communication
  * skill-design-ux-ui
  * skill-engineering-hardware
  * skill-engineering-software
  * skill-fluid-dynamics
  * skill-graphic-designer
  * skill-infosec
  * skill-medical-personnel
  * skill-outsystems-experts
  * skill-project-planning
  * skill-software-backend
  * skill-software-datascience
  * skill-software-devops
  
## Tags

When creating a repository, generic tags like organization, project, hardware, software, and skill-* should be applied.

