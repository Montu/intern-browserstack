## Usage

### Prerequisites

Node and npm

### Clone this repo

`git clone https://github.com/vedharish/intern-browserstack.git`

`cd intern-browserstack`

### Install intern

`npm install intern --save-dev`

### BrowserSack Authentication

Export the environment variables for the username and access key of your BrowserStack account.
These can be found on the automate accounts page on [BrowserStack](https://www.browserstack.com/accounts/automate)

`export BROWSERSTACK_USERNAME=<browserstack-username>`

`export BROWSERSTACK_KEY=<browserstack-access-key>`

### Run tests

`./node_modules/.bin/intern-runner config=tests/intern`
