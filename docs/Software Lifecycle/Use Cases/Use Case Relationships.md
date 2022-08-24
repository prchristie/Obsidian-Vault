#software-engineering #software-design #UML #use-case-diagram

These are for actions in a [[Use Case Diagram]] that are not initiated by an [[Actor]]

* Includes: Must always occur after a base [[Use Case]]
* Extends: A use case that may or may not occur after another use case, but does not always need to
* Generalization: Indicates a more specific instance of an actor or use case

**Includes**
We denote an includes relationship with a dotted line and arrow pointed to the included use case
![[Include Relationship Diagram.png]]

**Extends**
We denote extend the opposite way as an include relationship
![[Extended Relationship Diagram.png]]

**Generalization**
![[Generalization Relationship Diagram.png]]

Example:
If we have a login system, we can say that **verifying login details is an includes relationship**, while **displaying an error message if details are incorrect** is an extends relationship to login

References:
https://www.youtube.com/watch?v=sQgoFjxSdxo