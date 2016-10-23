Coding Dojo LCD Digits
----------------------

Implement the LCD Digits Kata using Test Driven Development and Pair Programming.
Two student begin, one being the driver one being the navigator. After every 8 minutes the driver becomes the navigator and another student becomes the driver.

Preparation
-----------
Install [mocha](https://mochajs.org/) and [istanbul](https://github.com/gotwarlost/istanbul) globally

    npm install -g mocha
    npm install -g mocha-cli
    npm install -g istanbul
    
Fork the repository, clone it into your workspace and install the dependencies

    git clone https://github.com/YOUR_NAME/coding-dojo-lcd-digits.git
    cd node-testing-workshop
    npm install

Execute `npm test` and `npm run coverage` to verify your setup.

Task
----
    
Create an LCD string representation of an integer value using a 3x3 grid of space, underscore, and pipe characters for each digit. Each digit is shown below (using a dot instead of a space)

    ._.   ...   ._.   ._.   ...   ._.   ._.   ._.   ._.   ._.
    |.|   ..|   ._|   ._|   |_|   |_.   |_.   ..|   |_|   |_|
    |_|   ..|   |_.   ._|   ..|   ._|   |_|   ..|   |_|   ._|


Example: 910

    ._. ... ._.
    |_| ..| |.|
    ._| ..| |_|

Start implementing the simplest test case, e.g. get the LCD representation for a one-digit number.
Run the test and let it fail. Write the minimally needed code to make the test succeed and run it again.
Implement the next test case and repeat the steps. Refactor if needed.
