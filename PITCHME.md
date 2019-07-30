# Testing
![](assets/img/35e295b058d31873c4de0c9bbc97b6b01a7f7951-1-500x316.jpg)
---

## What you consider testing
- Check required functionality is there
- Check critical path works
---

## What we consider testing
- Unit Test
- Integration Tests
- Functional Tests
---

## Unit Tests
- tests the code in isolation.
- These are useful to test specific parts of the code that don't require Magent oto be booted up

## Integration tests
- Tests code when it's integrated (IE, installed into Magento)
- Good for testing if an upgrade breaks the code
- Generally more useful than Unit Testing
- Gives us a higher level of confidence that an upgrade didn't break our code
- Also gives us high confidence that installing another module didn't break our code

## Functional Tests
- We haven't started useing these yet
- Tests are created to mimic user behavior
  - IE, add a product to basket, go to checkout, complete checkout
- Many of these tests can be quickly adapted for each client

## Why functional testing?
- Saves Aggie many hours of running through the same tests scripts
![](assets/img/Software-Testing-Memes-7.jpg)
- If the client browses the site a certain way, we can script that