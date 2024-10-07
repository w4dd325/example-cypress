# Installing Cypress for the first time

## Prerequisites
In order to create a Cypress project you must first, install Node.js and a code editor such as VS Code.

---

### Node.js
To install Cypress, first, you will need to install Node. Node.js is a cross-platform, open-source JavaScript runtime environment.

Cypress is built on Node.js and uses it to execute tests written in JavaScript. Node allows Cypress tests to run outside of a browser, enabling headless execution and server-side operations.

To install Node.js go to this link and follow the installation instructions:  
[https://nodejs.org/](https://nodejs.org/)

---

### VS Code
Visual Studio Code is a code editor. To install VS Code, go to this link and follow the installation instructions:  
[https://code.visualstudio.com/download](https://code.visualstudio.com/download)

---

## NPM
Node.js has a default package manager called NPM (Node Packet Manager). NPM allows you to easily install and manage dependencies for your projects. In this example, We will use NPM to install Cypress.

> [!NOTE]
> Npm installs and tracks JavaScript dependencies. NuGet manages dependencies for .NET projects.

---

## Install Cypress
Details on the Cypress NPM package can be found here:  
[https://www.npmjs.com/package/cypress](https://www.npmjs.com/package/cypress)

And the official GitHub repo can be found here:  
[https://github.com/cypress-io/cypress](https://github.com/cypress-io/cypress)

To install the Cypress NPM package open an empty folder in VS Code, then open a new terminal (and ensure that you are in the correct directory).

![new-terminal](https://github.com/user-attachments/assets/4ae433f5-a70e-40e1-849b-b8e72d2febd4)

### Install the Cypress NPM package using the following command: 

![install-cypress](https://github.com/user-attachments/assets/4c6ce99c-3190-441c-aa93-df231ad59b24)

### Launch Cypress by running the following command:

![run-cypress](https://github.com/user-attachments/assets/aaf5a409-5dfd-4932-b0a7-8c2a1af8bc04)

### Select 'E2E Testing'

![e2e](https://github.com/user-attachments/assets/dd0651cd-5a6d-462d-9b06-347e5d59e304)

### Accept the basic installation of the fixtures file etc.

![basic-install-config](https://github.com/user-attachments/assets/c1337378-5fd0-4a72-a8c2-db798e0c5c06)

### Select a browser

![select-browser](https://github.com/user-attachments/assets/ed0fc606-dd6e-47bb-b297-2f4e1603cbb3)

> [!NOTE]
> Electron is a built-in browser for Cypress and usually isn't affected by the same security/limitations as the other browsers. That said, we usually aim to use Chrome as this is the default for most of our apps etc.

### Select a spec option.

![e2e](https://github.com/user-attachments/assets/cd990252-30af-4587-95b0-273f818a6e23)

'Scaffold example specs' will provide multiple spec file examples.
'Create new spec' will provide a singular spec file example.

### Then enter the path of where to store the script (usually the default option) and click 'Create Spec'.

![spec-path-name](https://github.com/user-attachments/assets/ab480058-ef12-42f5-acab-37f4116a51b8)

### Then click 'Okay, run the spec'

![run-spec](https://github.com/user-attachments/assets/dad48f37-c12d-4ffd-8113-0bd0a2104e4f)

### At this point, the script should launch and run through the example test script (aka scaffolding script)

![kitchen-sink-screenshot](https://github.com/user-attachments/assets/fbc6a014-4788-4593-825d-e532a7122260)

### You should now have a folder structure in VS Code that looks like this: 

![folder-structure](https://github.com/user-attachments/assets/89dfb786-eb67-4b48-93d9-b9c3de28da91)

---

### Add a .gitignore file (to the root directory)
.gitignore tells git which files (or patterns) it should ignore. It's usually used to avoid committing transient files from your working directory that aren't useful to other collaborators, such as Cypress screenshots/videos, node_modules etc. or to ensure that passwords and secrets stored in a cypress.env.json file are not pushed to GitHub. 

