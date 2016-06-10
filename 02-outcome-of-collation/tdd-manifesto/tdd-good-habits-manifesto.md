## TDD good habits manifesto

#### (principles)
- tests should test one thing only
	- test one logical assertion
	- don't mix assertions of state and collaboration in the same test
	- modifications of production code should only break related test cases
- each test should be self-contained, including data
- ensure tests are independent of each other
- don't refactor with a failing test
- organise your unit test projects to reflect your production code
- keep your tests and production code separate
	- do not use production data and code to test production code
- if your tests are difficult to write or maintain, consider changing the design

#### (red phase)
- create more specific tests to drive a more generic solution (Triangulate)
- give your tests meaningful names (behaviour / goal-oriented) that reflect your production system
- write the assertion first and work backwards
- see the test fail for the right reason
- ensure you have meaningful feedback from failing tests

#### (green phase)
- write the simplest code to pass the test
	- write any code that makes you get to the refactor phase quicker
	- it is okay to write any code that you might improve at a later stage

#### (refactor phase)
- refactor aggressively and constantly
- treat tests as first class code
- use the IDE to refactor quickly and safely
- refactor production and test code independently (except changing public interfaces)
