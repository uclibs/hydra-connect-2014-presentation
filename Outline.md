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

#### Hydra Community
* Don’t reinvent the wheel
    * Look at what others have done
    * "Borrow" others' rake tasks, config files, Travis config, etc.
* Get involved
   * IRC chat
   * Committers calls
   * Hydra-tech email list
   * Hydra Camps
   * Git repositories
* Set up a sandbox server
    * Try out other Hydra projects

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
* Don't put sensitive content into Git
    * Git history will remember
    * Use .example or .sample files
    * Use "variables" that will be swapped during deploy
    * Store real content in a safe location
* Virtual server environments
    * Mimick a production environment locally
    * Reproduceable, standard environment
    * Can be used before real servers are available
    * Use tools like Vagrant and Puppet
* Fedora and Solr
    * They are easy to use inside hydra-jetty, but hard in production
    * Security needs to be addressed
    * Learn them early so it is not so hard later
* Collaboration with sysadmins
    * Many of these tools are unfamiliar to sysadmins (Fedora, Solr, Rescue, etc.)
    * Double-check and verify backup procedures - checksums
    * Negotiate how much command line access you need

#### Developer collaboration
* Use a development workflow
    * "Gitflow" is a good one
    * Use good commit messages
    * Use good branch names / strategy
    * Use a good collaboration structure
* Develop a script for quality assurance
    * Don’t rely on spec tests alone
    * Document steps to check your app before deploying to production
* Be a good contributer
    * Squash commits
    * Talk the talk
    * Don't merge your own pull requests
    * Get involved in a gem
* Collaboration tables and monitors
    * (show a pic of our set up)
    * Great for swarming
* Swarms and scrums
    * Schedule regular times to update and work with each other
