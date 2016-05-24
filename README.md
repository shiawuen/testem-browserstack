Testem with BrowserStack
========================

Run your tests on various browsers hosted on Browserstack!

Instructions
------------

1. Get a [BrowserStack](browserstack.com) account.
2. For BrowserStack Authentication export the environment variables for the username and access key of your BrowserStack account. These can be found on the automate accounts page on [BrowserStack](https://www.browserstack.com/accounts/automate) `export BROWSERSTACK_USERNAME=<browserstack-username> && export BROWSERSTACK_ACCESS_KEY=<browserstack-access-key>`
3. Install the dependencies by running `npm install browserstack browserstack-local`
4. Install testem globally by running `npm install testem -g`
5. Run the command `testem ci -l bs_chrome` to test out the setup with just the Chrome browser hosted BrowserStack.
6. Run `testem ci` to run it on all the listed browsers - see `testem launchers` for the full list.
