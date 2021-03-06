## What
*  <WHAT CHANGED GOES HERE... >
*  <WHAT CHANGED GOES HERE... >


## How to Test
### Get the code
* Clone the repo and checkout the PR branch

  ```
  git clone https://github.com/kumaran-is/flex-scroll-layout.git
  cd flex-scroll-layout
  git fetch
  git pull
  git checkout feature/<NEW BRANCH NAME>
  npm install
  ```
### Test the code
* Run static code analyzer

    ```
    npm run lint
    ```
* Start the Angular SPA

  ```
  ng serve -o
  ```

* Angular SPA gets launched on port 4200.

## What to Check
Verify that the following are valid

*  `npm run lint` should pass 
*  Verify the code changes works as expected by testing the Angular SPA.
*  Application runs without any errors.
*  Verify the browser console for any errors.
* Review the code changes to makesure it is written as per Angular coding standard recommended in [angular.io](https://angular.io/) for syntax, conventions, and structuring Angular application.
* Review if any changes needed to Readme prescription or any project documents
* Review the changelog and application version
* Delete the branch after merging back with the master branch.
