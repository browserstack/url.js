BrowserStack-Runner Mocha Sample
==============

Sample project to run Mocha tests on BrowserStack using BrowserStack-Runner

###Clone this repository
- `git clone https://github.com/UmangSardesai/url.js.git`

###Install browserstack-runner
- `npm install browserstack-runner`

###Configuring the json
 - Open `browserstack.json`
 - Since these are Mocha tests, `test_framework` parameter will be `mocha`
 - Add `username` and `automate-key`. These credentials are available [here](https://www.browserstack.com/accounts/automate), after you haved logged in to your account.

###Sample test
 - To run: `browserstack-runner`
 
More details on BrowserStack-Runner available [here](https://github.com/browserstack/browserstack-runner).
