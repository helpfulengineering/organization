# Helpful Engineers GitHub Community

## Scope and usage of the community
Currently we don’t have a standardized project management tool, and everybody has a personal preference about which tool to use for which purpose. This freedom is what makes us progress quickly by working with the tools we’re accustomed to use, and going against that may not be a good idea at all, but probably we should encourage the use of GitHub for certain tasks (apart from code version control):

* Continuous integration and continuous deployment.
* Project-level issue management and collaboration.
* Project-level documentation (on the wiki or a documentation folder).
* Community-level issue management and collaboration: organization repository.
* Front-page hosting: as long as https://helpfulengineers.org remains static, having it served by GitHub pages would simplify the submission of improvements and updates.

## Effort and account duplication
As far as we know, there are currently three different communities that refer to the Helpful Engineering project: Helpful-Engineers, helpfulengineering (that is the good one) and HelpfulEngineers, that was made by the ventilator project/s and is being merged.

The first two communities were already merged, with the expected clash of the organizational structures, but, thankfully, both organizations were nearly empty at the time. Currently, we have some issues referring to the repository naming conventions and structure:

https://github.com/helpfulengineering/resources/issues/67
https://github.com/helpfulengineering/free-for-covid/issues/1 
https://github.com/helpfulengineering/experience-tagger/issues/1 
https://github.com/helpfulengineering/devops/issues/1 

Please refer to the naming convention proposal on the «kinds of repository» section, and use it as a guideline to take further decisions about the renaming and merging of the current repositories. Better yet, head to the «structure proposal» below.

To avoid this happening again, we should make an announcement to all the project teams (if not the entire community) explaining how to use the community. Preferably with a link to this document, once it makes its way to GitHub. 
Repository creation
Organization specific
Creation policy: we should embrace the Unix philosophy of «do one thing and do it well» to segment the organization needs into concisely scoped repositories.

Naming: these repositories should be named in a consistent way (kebab-case) and, ideally, share a common prefix like (organization).

Access privileges: this has to be discussed, please refer to the «owner and member policy» section below.

Quirks: the most important repositories can be pinned so they are easy to find.

Teams: People can be added to teams they work on, and be added to skills. This way, specific skill sets can be tagged in issues and pull requests across projects and across the organization. Is there any way we can automate the already available info about all the members?

Project specific
Creation policy: there should be a maximum of one repository by project (a soft limit to keep things sane), and a minimum of zero, as we shouldn’t be creating repositories for projects that don’t need one or are using other tools and don’t want to migrate.

Naming: repository names should match the Slack channels they are affiliated with where possible (i.e. Slack channel #project-awesome-thing would yield project-awesome-thing). 

Access privileges: each project will designate a few users, covering different time zones whenever possible, that will have triage-level access to the project repository.
Repository licensing
This has been solved by the legal team, and they suggest to leave already established licenses as they are and use these licenses for the new projects:
https://helpfulengineering.slack.com/archives/CUR6CGMBL/p1584975246127600 
Owner and member permission policy
We currently rely on the serendipity principle to find new owners/members, but we should find a balance between federation and control, following the concerns that arose during the last standup.

All the new members should be just public (visible) members unless stated otherwise, and the maximum per-repository permission for specific contributors should be triage.
Structure proposal

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

