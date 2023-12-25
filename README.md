# Automated Tests of Mobile App with WebdriverIO and Browserstack

## Summary of Repo

This repository contains automated mobile tests created using WebdriverIO and BrowserStack. The tests cover login, drag-and-drop scenarios.

## Requirements

- Node.js
- NPM

## Steps to Install

1. Clone the repository
2. Install dependencies:

```bash
npm install
```

3. Rename the .env.example file to .env and fill with your browserstack credentials ([how to get app id](https://www.browserstack.com/docs/app-automate/api-reference/appium/apps#upload-an-app)):

```plaintext
BROWSERSTACK_USERNAME=your_browserstack_username
BROWSERSTACK_ACCESS_KEY=your_browserstack_access_key
BROWSERSTACK_APP_ID=your_browserstack_app_id
```

Now, you can execute the tests using the following scripts:

- Run tests:

```bash
npm run test
```

- Run tests on Samsung device:

```bash
npm run test:samsung
```

## Creating the report

Generate and view the test report:

```bash
npm run report
```

- Generate Allure report:

```bash
npm run report:generate
```

- Open Allure report:

```bash
npm run report:open
```

Example of Allure report:

![image](https://github.com/MaxixV2/wdio_mobile_task/assets/99399536/202cb60a-c395-4c39-8b10-d9188449dd6f)
