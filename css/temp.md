# Test Logs

## Test ID - unique identifier

## Description - summary of what's being tested (human friendly)

## Procedure

	+ Specific - clear priocedure, ideally only testing one thing
	+ Objective - stated in terms of what to do
	+ No prior knowledge
	+ Isolated (ideally) - doesn't depend upon other tests


## Expected Outcome

	+ Specific
	+ Objective

## Actual Outcome

	+ 'As expected' is fine if appropriate, but anything else needs lots of detail

## Time and Date

## By Whom

## Assigned To -- (if action is needed)




# Categories of Testing

## Black Box vs White Box

+ Black box testing is pure input vs output for a module - no knowledge of internals

+ White box testing - the source code is examined and we ensure that at least one test covers every single line of code

## Unit Testing

+ Testing each 'component' (function/method) for correct functionality

+ Tests must be __repeatable__ as they will usually be automated

+ Output is ideally zero __if__ the test passes

+ Purpose is to __find__ bugs. Unit testing should stress test, it should try to break things.

## Regression Testing

Checking that new code does not break old code or introduce new bugs in old code

+ Whenever new code is added (even trivial bug fixes) re-run __all__ unit tests. 

> Testing is best when is is cheap and painless, it will be done more often!

## Module Testing

Testing substantially larger units of the software for correct function (navigation and UI starts to become important)

## Integration Testing

What happens when we connect modules together?

## Acceptance Testing

Outcome should be customer/user acceptance. Is it what they wanted/anticipated? Does in function in their view?





