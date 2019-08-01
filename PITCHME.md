# Testing
![](assets/img/35e295b058d31873c4de0c9bbc97b6b01a7f7951-1-500x316.jpg)
---

## What you consider testing
- Check the required functionality is present
- Check the critical path works
---

## What we consider testing
1. Unit Tests
2. Integration Tests
3. Functional Tests
---

## 1. Unit Tests
- Tests the code in isolation
- Useful to test specific parts of the code that don't require the entire site to run
---

## 2. Integration tests
- Tests code when it's integrated (ie. installed into Magento)
- Tests against an actual running instance of Magento
- Generally more useful than Unit Tests
---

### 2.1. Integration tests cont.
- Good for testing if an upgrade breaks the code. Gives us a higher level of confidence that an upgrade didn't break our code
- Gives us high confidence that installing a module didn't break our code
- We currently run these using Travis...
---

### 2.2. Who's Travis?
- Travis is a (paid) service we use that automatically runs integration tests
- It tests and passes or fails the code
- We can't deploy code without a pass
---

## 3. Functional Tests
- We haven't started using these yet
- Tests are created to directly mimic user behaviour
  - e.g. search for hats, add a product to the basket, go to checkout, complete checkout
- These tests can be quickly adapted for each client and replicated across clients
---

### 3.1. Why functional testing?
- If the client browses the site a certain way, we can script that
- Write once and forget - write the test and it will rerun on every deploy
- Saves the CS team many hours of running through the same old tests scripts
---

![](assets/img/Software-Testing-Memes-7.jpg)
---

## How?
- There are several ways to achieve Functional testing
  - https://www.cypress.io/
  - https://ghostinspector.com/
---

### How? cont.
- These services allow technical and non-technical people to create the tests
- Cypress promises to allow us to create tests quickly
- Ghost Inspector allows non-technical people to create tests as well
---
