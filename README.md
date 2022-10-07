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


20/09/22 (pg. 177-191)

* Concurrency can sometimes improve performance, but only when there is a lot of wait time that can be shared between multiple threads or multiple processors.
* A good way to avoid shared data is to avoid sharing the data in the first place. In some situations it is possible to copy objects and treat them as read-only.
* Attempt to partition data into independent subsets than can be operated on by independent threads, possibly in different processors.
* First and foremost, follow the Single Responsability Principle.


23/09/22 (pg. 193-250)

* Successive Refinement:
  - To write clean code, you must first write dirty code and then clean it
  - Test-Driven Development. One of the central doctrines of this approach is to keep the system running at all times.
  - Refactoring is a lot like solving a Rubik's cube. There are a lots of little steps required to achieve a large goal. Each step enables the next.
  - This separation of concerns makes the code much simpler to understand and maintain.
  - So the solution is to continuously keep your code as clean and simples as it can be. Never let the rot get started.


23/09/22 (pg. 251-265)

* The Boy Scout Rule tell us we should leave it cleaner than we found it.
* Often one refactoring leads to another that leads to the undoing of the first. Refactoring is na iteractive process full of trial and error, inevitably converging on something that we feel is worthy of a professional.
* each os us has the responsability to leave the code a little better than we found it

29/09/22 (pg. 267-284)
 
 * 

01/10/22 (pg. 285-319)
 
 * 

06/10/22 (pg. 320-333)

* 

07/10/22 (pg. 334-431)

* 










