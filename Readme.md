[cypress testing lab]

**To Clone this project locally**.

-Make sure you install `Node` latest version .

Then in the IDE.

$ `git clone https://github.com/orensrauch/cypress-automation-lab-v1.0.git`

$ `npm install`

**To create this project step-by-step**

* Create a new local folder.

* Open the new folder at your favorite IDE.

* enter command $ `npm init` at the terminal, enter all desiered content as you wish.

* install Cypress $ `npm install --save-dev cypress` (should take 2-3 Minutes).

* Opening Cypress... $ `./node_modules/.bin/cypress open`, will display demo examples of the power of Cypress.

**Cypress files descriptions**

* `node_modules` folder : used to house dependencies (Packages). 

* `cypress.json` : Created in the projects root directory, enables us to change default settings.

* `videos` folder : Used to store videos of test recordings.

* `screenshots` folder : Used to store images of specific test(s).

* `support` folder : Used to store custom commands and files.

* `support > index.js` : The first file which cypress investigates, any imports, changes to cypress default behaviour, even the ability to add hooks etc.

* `support > commands.js` : Used to store common or custom commands(Functions), even the ability to override Cypress functions.

* `plugins > index.js` : if you wish to extend upon Cypress functionality; location where you can add plugins.

* `integration` folder : The main folder where we store our test files, Cypress test runner will look into this folder inorder to locate test files(s).

* `fixtures` folder : Where we keep our test data objects, mocked objects and any other data which we need for our tests (In most cases will be JSON files).




