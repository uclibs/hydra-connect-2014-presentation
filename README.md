Hydra Connect 2014 Presentation
===============================

## Details

* **Date:** Thursday, October 2 at 9am
* **Title:** One Year with Hydra: what we know now; what we wish we knew earlier
* **Format:** 20 minute presentation
* **Audience:** new partners and managers
* **Speaker(s):**  Glen Horton and Thomas Scherz
* **Description:** Our first year of developing a Hydra-based institutional repository yielded many surprises, frustrations, and eureka moments.  We will tell you what we wish someone had told us about the Hydra community, Rails applications, System/Stack deployment, and Developer collaboration.  

## Topics

#### Hydra community
* don’t reinvent the wheel - look at what others have done
    * rake tasks, config files, Travis config
* IRC chat / committers calls / tech list / camps / git repos
* Set up a sandbox server to try out other Hydra projects

#### Rails applications (Thomas)
* managing updates - things change without changing your code
    * gem versions - lock down
    * dependencies
    * environment
* understanding rails conventions
    * MVC
    * spec testing
    * DRY - don't repeat yourself
    * rake tasks

#### System/Stack deployment (Glen)
* managing sensitive information
    * bamboo scripts / environment variables
    * config vault - private storage
* virtual deployment environments
    * mimick production environment
    * scalability - jetty -> passenger
    * standard environment for developers
    * try a production environment before the real one is ready
    * vagrant, puppet
* Fedora and solr core
    * easy when inside jetty, but difficult in production
    * tweaks for production
    * security and aaccess
    * learn early on so it’s not so hard later
* collaboration with sys ops
    * sys ops unfamiliar with managing and configuring hydra stack components
    * double-check and verify backup procedures - checksums
    * root access?


#### Developer collaboration
* Gitflow
    * good commit messages
    * good branch names / strategy
    * good collaboration structure
* develop a script for QA
    * don’t rely on spec tests alone
* being a good contributer
    * squashing commits
    * talking the talk
    * pull requests - don’t merge your own
    * get involved in a gem
* Collaboration tables and monitors
* Agile: lots of value in swarms and scrums
