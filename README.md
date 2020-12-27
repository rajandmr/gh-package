## gh-package

### Installation Instruction

- Create **.npmrc** file in your root directory
- Add the following code to the **.npmrc** file
  ```
  @YOUR_USERNAME:registry=https://npm.pkg.github.com/
  //npm.pkg.github.com/:_authToken=YOUR_TOKEN

  ```
 
- Replace @YOUR_USERNAME with your github **USERNAME**
- paste your generated GITHUB_TOKEN in place of YOUR_TOKEN
- Run the following command:
  
  ```
  npm i @YOUR_USERNAME/PACKAGENAME
  ```
In my case, i'll run:

  ```
  npm i @rajandmr/gh-package 
  ```
- Testing the package:
- Create an IndexJS file and paste the following code:

  ```
  let demoPackage = require('@rajandmr/gh-package');

  demoPackage.sayHello('Rajan');
  ```
