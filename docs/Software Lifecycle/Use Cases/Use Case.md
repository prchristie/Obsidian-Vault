#software-engineering #software-design #UML #use-case-diagram

Abbreviation: **UC**

Example: [[Loan book from library use case]]
Related: [[Use Case Diagram]]

A task that an [[Actor]] can perform with the help of the [[System]]. Set of actions that lead to the goal. Describes a singular feature provided by the system, where the feature could consist of multiple actions.

Use cases can be described at many different levels, notable named [[Use Case Descriptions]]. The most common are usually very high level.

They are often an alternative to [[User Stories]], or perhaps a higher level kind of user story which can be used to create user stories.

Example: Commenting on an article. Use case might be **Comment on article** but internally you need user auth, validation of entered data, etc

It is often a good idea to try and start with a [[Scenario]], a sentence description of the use case.

Start with simple use cases when starting a project. The simpler ones will create the foundation for future implementation

Use cases can have multiple steps if they are complex. Steps should be based in business world
Description of a use case should include
* Name of the use case/goal
* [[Actor]]s
* Preconditions
* Regular steps
* Alternative paths
* Post conditions


Represented as an oval inside the [[System]] in a use case diagram

![[Use case in use case diagram.png]]

References:
http://www.cs.cornell.edu/courses/cs5150/2015fa/slides/D2-use-cases.pdf

https://www.easyagile.com/blog/use-cases-vs-user-stories/#:~:text=User%20stories%20are%20simple%2C%20short,cases%20contain%20much%20more%20context. for use case description guide lines