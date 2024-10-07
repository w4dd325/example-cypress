# Installing Cypress for the first time

## Prerequisites
In order to create a Cypress project you must first, install Node.js and a code editor such as VS Code.

---

### Node.js
To install Cypress, first, you will need to install Node. Node.js is a cross-platform, open-source JavaScript runtime environment.

Cypress is built on Node.js and uses it to execute tests written in JavaScript. Node allows Cypress tests to run outside of a browser, enabling headless execution and server-side operations.

To install Node.js go to this link and follow the installation instructions: https://nodejs.org/

---

### VS Code
Visual Studio Code is a code editor. To install VS Code, go to this link and follow the installation instructions:
https://code.visualstudio.com/download

---

## NPM
Node.js has a default package manager called NPM (Node Packet Manager). NPM allows you to easily install and manage dependencies for your projects. In this example, We will use NPM to install Cypress.

> [!NOTE]
> Npm installs and tracks JavaScript dependencies. NuGet manages dependencies for .NET projects.

---

## Install Cypress
Details on the Cypress NPM package can be found here:
https://www.npmjs.com/package/cypress

And the official GitHub repo can be found here:
https://github.com/cypress-io/cypress

To install the Cypress NPM package open an empty folder in VS Code, then open a new terminal (and ensure that you are in the correct directory).

![GitHub Screenshot - new terminal](https://github.com/w4dd325/cypress/assets/86320001/34ccd791-d531-4dc1-84a4-2b1ae16d7e49)

### Install the Cypress NPM package using the following command: 

![image](https://github.com/w4dd325/cypress/assets/86320001/576ec015-0f5f-44a6-a3c7-4f487b2c7ba0)

### Launch Cypress by running the following command:

![image](https://github.com/w4dd325/cypress/assets/86320001/45a0ee35-6b50-47a2-a6ee-4cf968ab31f6)

### Select 'E2E Testing'

![image](https://github.com/w4dd325/cypress/assets/86320001/b8b85c4a-138f-4d0a-915c-7501527934fa)

### Accept the basic installation of the fixtures file etc.

![image](https://github.com/w4dd325/cypress/assets/86320001/1edeec0e-b3dd-4e2b-9680-6fe2556815d2)

### Select a browser

![image](https://github.com/w4dd325/cypress/assets/86320001/b098cfe9-d647-481d-8332-0054fdd3340b)

> [!NOTE]
> Electron is a built-in browser for Cypress and usually isn't affected by the same security/limitations as the other browsers. That said, we usually aim to use Chrome as this is the default for most of our apps etc.

### Select a spec option.

![image](https://github.com/w4dd325/cypress/assets/86320001/54a4a8f3-e853-4142-97a5-f464a4eddddc)

'Scaffold example specs' will provide multiple spec file examples.
'Create new spec' will provide a singular spec file example.

### Then enter the path of where to store the script (usually the default option) and click 'Create Spec'.

![image](https://github.com/w4dd325/cypress/assets/86320001/1ff5f9ff-35f9-4bd7-af9a-898fc2562829)

### Then click 'Okay, run the spec'

![image](https://github.com/w4dd325/cypress/assets/86320001/8050beee-7199-4162-9cfd-fa778de0a4be)

### At this point, the script should launch and run through the example test script (aka scaffolding script)

![image](https://github.com/w4dd325/cypress/assets/86320001/18291227-9fdc-4c0c-a3b9-d7897eec11a8)

### You should now have a folder structure in VS Code that looks like this: 

![image](https://github.com/w4dd325/cypress/assets/86320001/979dc93d-bda4-4ea5-a366-1712705b65a7)

---

### Add a .gitignore file (to the root directory)
.gitignore tells git which files (or patterns) it should ignore. It's usually used to avoid committing transient files from your working directory that aren't useful to other collaborators, such as Cypress screenshots/videos, node_modules etc. or to ensure that passwords and secrets stored in a cypress.env.json file are not pushed to GitHub. 

