# syssnap
System Design snapshots for software engineers design diffs

## System Design

#### Problem Opportunity Areas
* SWEs, SDEs, whatever you want to callem don't have great all in one resources for system design
* There's not a strong platform or community for SDEs to get feedback and review from experienced SDEs on their system design
* It is difficult for SDEs to manage the system design review lifecycle, keeping track of worthy comments and making sure that
* It is hard for reviewers to see the progression and the iterative designing
* Managing communicating changes to system designs plus the reason for it, has friction

#### Functional Requirements
* Users should be able to
* User should be able to see a human-readable change log for the currently selected snapshot
* 
* Users should be able to toggle a split screen comparison of currently selected snapshot
* Editors should be able to create a new project (empty diagram and document)
* Editors should be able to add/edit/remove system design nodes
* Editors should be able to draw connections/edges and set their type such as REST, RPC, pub/sub, stream, etc
* Editors should be able to edit node/edge properties such as SLA, region, replics, etc
* Editors should be able to write a design document bound to the same version as the diagram
* Editors should be able to commit a snapshot with a commit message
* Editors should be able to revert the working state to a previous version
* Editors should be able to request a review
* Reviewers should be able to see a diff (added, removed, system changed design components) for a proposed change
* Reviewers should be able to leave comments on system design document sections
* Reviewers should be able to approve, request changes or only comment on a review
* Users should be able to invite collaborators by email and assign roles (viewer, commenter, editor)
* Users should be able to see when active viewers are accessing the snapshot
* Users should be able to search for projects, services/nodes and versions by keyword/tag
* Users should be able to export a view to PNG/PDF
* Admin should be able to view usage analytics (version count, documents created, active users, etc)
* 
* Premium feature: users should be able to link their system design snapshot to their code repository for version control sync
* Premium feature: system design should auto update based off of changes in code repository
* Premium feature: users should be able to see the design auto highlight a component of the system design once it has been pushed to production or implemented
* ...
* Note to self, dream up AI/ML integrations, cyclical training on system design data for a specialized model, "implementation highlight" feature and more

#### Non-Functional Requirements
