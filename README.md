# Learning Time

## Clean Code Book

06/09/22 (pg. 75-92)

* Code formatting is about communication, and communication is the professional developer's first order of business
* We would like a source file to be like a **newspapper article** - Newspapper Metaphor
* **Dependent Functions:** if one function calls another, they should be vertically close, and the caller should be above the call, if at all possible. This gives the program a better flow.


07/09/22 (pg. 93-101)

* Data Transfer Objects (**DTO's**): A data structure is a class with public variables and no functions. This is a DTO.
* **Objects** expose behaviour and hide data... **Data structure** expose data and have no significant behaviour.

08/09/22 (pg. 103-112)

* Instead of experimenting and trying out the new stuff in our production code, we could write some tests to explore our understanding of the third-party code. - Learning tests.
* It's better to depend on something you control than on something you don't control, lest it end up controlling you.

09/09/22 

* Review

13/09/22 (pg. 121-135)

* Test code is just as important as production code... It must be kept as clean as production code.
* Single concept per Test
* F.I.R.S.T : Fast, Independent, Repeatable, Self-Validating, Timely.
* Tests preserve and enhance the flexibility, maintainability, and reusability of the production code.


14/09/22 (pg. 135-151)

* There is seldom a good reason to have a public variable.
* Sometimes we need to make a variable or utility function protected so that it can be accessed by a test.
* The Single Responsability Principle (SRP) states that a class or module should have one, and only one, reason to change.
* SRP is one of the more important concept in OO design.


15/09/22 (pg. 153-170)

* 

19/09/22 (pg. 171-176)

* A design it's 'simple' if it follos these rulles:
  - Runs all the tests
  - Contains no duplication
  - Expresses the intent of the programmer
  - Minimizes the number of classes and methods
* Writting tests leads to better designs
* So take a little pride in your workmanship... Just take care of what you've created. Care is a precious resource.






