# joanesquivel-automationproject

Exercises based on this site 
[TESTCAFE TUTORIAL For Beginners 6](https://www.youtube.com/watch?v=by5BAWbn0k0&list=PLYDwWPRvXB8_TDgPmQyMNjN6gaI8yS7KQ&index=6)

## The original Project 
Other sites for suppor are:
 - [testcafe-blink-diff](https://github.com/tacoss/testcafe-blink-diff)
 - [automationproject](https://joanesquivel@bitbucket.org/joanesquivel/automationproject/src/master/) in bitbucket

 ## Steps to start
 1. Install NPM and NODEJS in your system 
    [nodejs](https://nodejs.org/en/download/current/)
 2. check in $path or %path% the nodeJS and npm are on it
    ```bash
    C:\Program Files\nodejs
    ```
 3. Install Testcafe as local in the working directory
    using a command window locate in the work site and run this:
    ```bash
    npm install --save-dev testcafe
    ```
 4. Install the testcage-blink-diff
    ```bash
    npm i testcafe-blink-diff --save-dev
    ```
    or 
    ```bash
    npm install testcafe-blink-diff
    ```
 5. In the work directory run this command to get all dependencies:
    ```bash
    npm install
    ```
    more info in this site:
    [Testcafe guides](https://devexpress.github.io/testcafe/documentation/guides/basic-guides/install-testcafe.html)
 6. I ran this command to get a html file with info
   ```bash
   npx testcafe-blink-diff src/images/Snapshots reports/google --compare base:actual --open -threshold 0.03 #<- 3% is OK
   ```

## License
[MIT](https://choosealicense.com/licenses/mit/)