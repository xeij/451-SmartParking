# Sprint 1 Report
Video Link: [youtube.com/]

## What's New (User Facing)
* Users can register an account with a unique email and a role of either user or admin
* Users can register vehicles and link them to their account
* Users can book a parking slot in advance by selecting a vehicle, slot, start time, and end time
* Admins can create and manage parking slots across different levels and zones
* Payments are automatically generated for each booking upon creation
* Users can open a dispute against a booking

## Work Summary (Developer Facing)
This sprint was focused entirely on database design and implementation. We began by identifying the core entities from our functional requirements and mapping them into an ER diagram. From there we converted the ER model into six relational tables and implemented them in Oracle Live SQL. Each team member owned two tables end to end.

## Unfinished Work
No Sprint 1 items were left incomplete. All six user stories were finished, verified in Oracle Live SQL, and moved to Done on the Kanban board. The following four items from the product backlog were intentionally deferred to Sprint 2 and were never part of Sprint 1 scope: admin dispute resolution (PB-07), user booking history (PB-08), booking cancellation (PB-09), and admin account deactivation (PB-10).

## Completed Issues/User Stories
Here are links to the issues that we completed in this sprint:

* [https://github.com/xeij/451-SmartParking/issues/1]
* [https://github.com/xeij/451-SmartParking/issues/2]
* [https://github.com/xeij/451-SmartParking/issues/3]
* [https://github.com/xeij/451-SmartParking/issues/4]
* [https://github.com/xeij/451-SmartParking/issues/5]
* [https://github.com/xeij/451-SmartParking/issues/6]


## Incomplete Issues/User Stories
No issues were incomplete this sprint.

## Code Files for Review
Please review the following code files, which were actively developed during this sprint, for quality:
* [smartparking.sql](https://github.com/xeij/451-SmartParking/sprint1/smartparking.sql)

## Retrospective Summary
Here's what went well:
* The database schema was well-defined from the start. Having a clear requirements-to-data mapping document meant that table design required minimal revision.  
* Dividing table ownership clearly across team members (two tables each) avoidedover-lap and kept progress moving independently


Here's what we'd like to improve:
* Initial sprint planning did not include explicit acceptance criteria for each story, leading to some ambiguity about what ‘done’ meant for database-only task
* Communication between team members could have been improved. There was some
confusion which caused some duplication of effort early on when defining shared foreign key columns.
* The disputes table required two foreign keys pointing to the same users table (opener and assigned admin), which caused initial confusion about how to structure the rela-tionships correctly. 

Here are changes we plan to implement in the next sprint:
* Hold a short weekly check-in to stay synced across the team

