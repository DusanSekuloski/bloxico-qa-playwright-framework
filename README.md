# Playwright QA Automation Template Repository

## Table of Contents

- [Description](#description)
- [Prerequisites](#prerequisites)
- [How to run tests](#how-to-run-tests)
---

## Description

Template repository for Playwright QA automation framework using Mocha and Chai npm libraries

---

## Prerequisites 

**Node version 14 or above**

Check if you already have Node installed, run:  
```
node -v
``` 

**Playwright version 1.33.0**

Install Playwright dependencies, run:  
```
npm init playwright@latest
``` 

---
## How to run tests

To run tests, run:

```
npx playwright test
```

By default, tests will run in `headless` mode, to change that go to `playwright.config.js` file and change the `headless` parameter to `false`.
