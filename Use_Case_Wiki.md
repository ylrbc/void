Use Case Descriptions
=====================
All use cases derived from queries

***
1
==================

Title
-----
 View Total Number of Commits: Members v. Non-Members

Description
-----------
Defines the events for an actor who wants to view the total number of commits for a project from both members as well as non-members. Actor will search for a project and be given the option on how to view the commit data for that project. The actor can show the data as member v. non-member commits, just member commits or only non-member commits on selected project.

Triggers
--------
Stakeholder wants to know the amount of commits made by project members vs non-members. Progress status reports for stakeholders with monetary stake in the project.

Actors
------
Project Members, Companies, Non-Project Members, Project Managers/Maintainers

Preconditions
-------------
Flags for extremely high commits in a short time. Flag for non-member commit greater than 60% v. member commits.

Main Success Scenario
---------------------
User is able to see total number of member and non-member commits to a project.

Alternate Success Scenarios
---------------------------
User is able to total commits for only members. User is able to see total commits for non-members.

Failed End Condition
--------------------
The data is not specific enough to have any meaningful information to resolve any of the stakeholders orginal triggers.

Extensions
----------
No extensions for this use case. No scenarios would lead the actor beyond this use case.  View all of total number of commits a member has for all of the projects they have contributed to.

Steps of Execution
------------------
1. Select Project
2. Select Commit Comparison
3. View Total Commit Graph
  * View Member Commits
  * View Total Non-Member Commits
  * View Commits of Member v. Non-Members

Diagram
-------


![Use Case Diagram 1](https://github.com/dduenow/hello_world/blob/master/Commit%20UseCase.jpg)
***
2
==================
Title
-----
View Activity Level of all Contributors

Description
-----------
Defines the events for an actor who wants to see if a project has a significant number of contributors and evaluate which contributors are the most active for that project.

Triggers
--------
Actor wants to evaluate if the given project is growing or has stagnated based on a finite time frame.

Actors
------
Project Members, Companies, Non-Project Members, Project Managers/Maintainers

Preconditions
-------------
Project has been created and has at least 1 contributor.

Main Success Scenario
---------------------
Actor is able to see the activity level of all contributors.

Alternate Success Scenarios
---------------------------
Actor is able to see a list of all contributors.

Failed End Condition
--------------------
Actor is unable to make a fair assessment on each contributor’s level of activity on the project being viewed.

Extensions
----------

Steps of Execution
------------------
1. Select Project
2. Select contributor view
3. View visualization of pulls, commits, comments by all contributors

Diagram
-------

![Use Case Diagram 2](https://github.com/dduenow/hello_world/blob/master/UseCaseDiagram2.jpg)
***
3
==================
Title
-----
View Number of Contributors/Committers for a project

Description
-----------
Defines the events that would allow the actors to see how many people have committed code in a specified project. When searching for a specific project or selecting a project the user is following, the relevant visualization of the number of contributors will be visible. This information could be used to make a decision based on this information alone as well as by combining this information with other relevant parameter results.   

Triggers
--------
The actor wants to know how many people have been committing to a project and possibly use that information in conjunction with other parameters available.

Actors
------
Company/recruiters, Researchers, Project Members, Non-Project Members, Project maintainers, Developers

Preconditions
-------------
Project has been created and the actor has searched for it and selected the parameter for viewing the number of contributors/committers.

Main Success Scenario
---------------------
The actor is able to determine how many contributors have made commits within the project.  

Alternate Success Scenarios
---------------------------
The actor compares different projects of interest on how many contributors they have.

Failed End Condition
--------------------
The actor is unable to see any contributors because no commits have been made to the project selected or searched for.

Extensions
----------
The actor may use this information in conjunction with the other parameters to make decisions or inferences based on the amount of contributors.

Steps of Execution:
-------------------
1. Search for or select a flagged project
2. Select the parameter ‘number of contributors’
  * Select another parameter to use in conjunction with ‘number of contributors’
3. View Visualization of the selected information

Diagram
-------

![Use Case Diagram 3](https://github.com/ldsz89/testRepo/blob/master/Use%20Case%20Diagram%203.jpg?raw=true)

***
4
==================
Title
-----
View Pull Requests for a Project

Description
-----------
Defines the events that an actor would follow to discover the amount of pull requests a project has garnered. The actor will be able to search and select a project they wish to see pull request data for. The actor will be able to view the data for the selected project as all pull requests, all closed pull request, open pull requests vs. accepted pull requests, see acceptance percentage for pull requests and all open pull requests.

Triggers
--------
Actor wants to see number of open pull requests v. accepted. Actor wants a visual representation of open, closed and accepted pull requests. Actor wants to know pull request acceptance rate.

Actors
------
Non-Project Members, Project Members, Researchers, Developers, Project Maintainers, Project Managers, Company/Recruiters

Preconditions
-------------
Actor is searching for projects with active acceptance of pull requests. Actor wants to find project with high acceptance ratio for pull requests. Flag for high number of unresolved pull requests. Flag for a rapid amount of resolved pull requests in a finite time frame. Flag for excessively high or low acceptance rate of pull requests.

Main Success Scenario
---------------------
Actor is able to see all pull requests for selected project.

Alternate Success Scenarios
---------------------------
Actor is able to see all closed pulled requests. Actor is able to see open pull requests v. accepted. Actor is able to see acceptance ratio of pull requests for a project. Actor is able to see all open pull requests.

Failed End Condition
--------------------
The actor is unable to view the open pull requests because there are none open. The actor is unable to view the acceptance rate because there have not been any accepted pull requests.

Extensions
----------
Actor can click on the charts of any of the aforementioned success scenarios which would then take them to the project page and display all of the pull requests in a form consistent with the graph clicked. 

Steps of Execution
------------------
1. Search for or select a project or flagged project
2. Select the parameter “View Status Pull Requests”
3. View visualization of all open, closed, and accepted pull requests for project.

Diagram
-------

![Use Case Diagram 4](https://github.com/ldsz89/testRepo/blob/master/Use%20Case%20Diagram%204.jpg?raw=true)

***
5
==================

Title
-----
View Number of Issues Raised vs. Number of Issues Closed

Description
-----------
Defines the events an for actor who wants to judge the success of a given project.

Triggers
--------
Actor wants to know the amount of issues raised for a project and compare that with the amount of project issues closed.

Actors
------
Project Members, Companies, Non-Project Members, Project Managers/Maintainer

Preconditions
-------------
Project has been created and has been active for sufficient period of time.

Main Success Scenario
---------------------
Actor is able to ascertain the successfulness of given project.

Alternate Success Scenarios
---------------------------
Actor is able to view total number of issues raised and/or total number of issues resolved.
Failed End Condition: Actor is not able to discern successfulness of project due to short life-span of project.

Extensions
----------
Actor is able to select 'issues resolved' or 'issues raised' and see more detailed information for the respective selection, such as usernames of who has raised an issue and timestamps of when this was done, potentially to track the amount of time it takes to resolve issues on average.

Steps of Execution
------------------
1. Search for or select project
2. Select parameter “Number of Issues”
3. View visualization of issues resolved vs issues raised

Diagram
-------

![Use Case Diagram 5](https://github.com/ldsz89/testRepo/blob/master/Use%20Case%20Diagram%205.jpg?raw=true)

***
6
==================

Title
-----
View Issue: Response Rate

Description
-----------
Defines the events that an actor would follow to discover the average time it takes to open and fix issues and bugs.

Triggers
--------
Actor would like to see the time it takes to open and commit fixes to issues and bugs.

Actors
------
Project Members, Companies, Non-Project Members, Project Managers/Maintainer

Preconditions
-------------
Project has been created and has been active for sufficient period of time.

Main Success Scenario
---------------------
Actor is able to determine how quickly bugs are being seen and taken care of and may be able to ascertain the overall health of the system.

Alternate Success Scenarios
---------------------------
Actor is able to view the length of bug fixing and issue correcting.

Failed End Condition
--------------------
Actor is unable to view any time data due to short length of project and no commits or issues are made or opened.

Extensions
----------
The actor may use this information in conjunction with the other parameters (such as the one above) to make decisions or inferences based on the amount of issues and their length of ‘birth’ (finding of) to their completion.

Steps of Execution
------------------
1. Search for or select project
2. Select parameter “View Issue Response Rate”
3. View visualization of either of the choices:
    1. Average days until member comments on issue with tag: bug
    2. Average days until member comments on issue with/out tag
    3. Time between opening and response from committer on specific issue
        * User entered issue id

Diagram
-------
![Use Case Diagram 6](https://github.com/ldsz89/testRepo/blob/master/Use%20Case%20Diagram%206.jpg?raw=true)