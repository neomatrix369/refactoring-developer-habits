These are some of the invaluable suggestions from the outcome of the group discussion but fall a bit outside the TDD Red-Green-Refactor cycle.

### (preparation)

- have a good understanding of the context of the change (who is this change for)
- find out where the change needs to be made in the production code
- which level are the tests written for (unit, integration, ATDD, Acceptance, et...)
- add monitoring checks, if applicable
- commit and push after each passing test

### Red
- Organize your test in Arrange, Act and Assert blocks
-   Arrange aka Given – all necessary preconditions and inputs.
-   Act aka When – on the object or method under test.
-   Assert aka Then – that the expected results have occurred.
-   Structure the code in tests to reflect these concepts.


### Refactor
- Use the Rule of 3 to tackle duplication 
- Remember that duplication is cheaper than the wrong abstractions
