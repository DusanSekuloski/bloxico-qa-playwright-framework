# Playwright QA Automation Template Repository

## Table of Contents

- [Description](#description)
- [Prerequisites](#prerequisites)
- [How to run test](#how-to-run-test)
- [Branch naming conventions](#branch-naming-convention)

---

## Description

Template repository for Playwright QA automation framework using Mocha and Chai npm libraries

---

## Prerequisites 

**Node version 14 or above**

Install Node modules, run:  
```
npm i
``` 
Check if you already have Node installed, run:  
```
node -v
``` 

**Playwright version 1.33.0**

Install Playwright dependencies, run:  
```
npx playwright install
``` 


---
## How to run test

To run Smoke test, run:

```
npx playwright test
```

By default, tests will run in `headless` mode, to change that go to `playwright.config.js` file and change the `headless` parameter to `false`.




