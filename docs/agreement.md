# Community iSnobal Maintainers Agreement
June 2, 2025

## Spirit of Agreement
The spirit of the iSnobal Community maintainers organization described here is to foster and maintain an iSnobal development community that will use, advance, and disseminate iSnobal for scientific research and operational purposes, and to centralize the knowledge and software that underpins iSnobal specifically, and snow modeling generally. We aim to maintain an open source code base that serves our respective needs, as well as the needs of the broader scientific and water resources communities.

## Maintainers Committee
The organizations and individuals listed below are the iSnobal Community Model committee, and will each have administrative access to and control of the iSnobal Community Model repositories.

    M3 Works: Micah Johnson, Micah Sandusky, Mark Robertson
    USDA-ARS: Andrew Hedrick
    Boise State University: Joachim Meyer
    University of Utah: McKenzie Skiles

Additional individuals will be added by the above committee wihtout needing to change this agreement and are controlled via the GitHub organization.

## Software Repositories
Location: https://github.com/iSnobal

## Guiding Principles
These are meant to be general guidelines, acknowledging that unique and extenuating circumstances may apply to individual applications.

* New features or major changes to default parameters or algorithms to the current release are discussed ahead of time in a separate GitHub issue and are sent out as Request For Comments (RFC) to all maintainer groups for input. The RFC should be approved by two maintainer organizations and describe all changes before any implementation occurs.
* New features to the existing code base should be optional. For example, a new density algorithm should be configured such that the legacy version is still available, and the user can choose between them. This is to provide continuity for users, but it also reduces the burden of publication prior to code release.
* Unless it is agreed upon in the RFC, new features should not be applied unless specified by the user. That is, whenever possible the default should be to existing functionality. Major releases of the software can change to the new functionality.
* New features can be published depending on the scope and importance of the work, with collaborators that assisted with the implementation and application. This would not have to be done prior to software release but should be part of the RFC.
* Code changes should be made through a pull request. At least two maintainer organizations would review and approve pull requests.
* The main release branch won’t be modified unless there is a pull request.
* Every new feature will be documented by an entry to the “CHANGES.md” log, establishing a history for reference. This entry can be as simple as referring to the logged RFC issue.
* Current documentation for iSnobal is not centralized or easy to access. This organization aims to create and maintain easily accessible documentation for the existing iSnobal software, and new software additions should also be well documented.

## New Maintainers Community Members
At this time the focus is on creating a functional maintainers community with the members listed above. Once a successful and efficient and iSnobal Community and related software and documentation has been established, new maintainer members can be added. We would like to limit potential new maintainers to those that are knowledgeable about snow science, modeling in general, and iSnobal specifically.

## Changes to this Agreement.
Changes to this Agreement should be made only with the consensus of the entire group.

