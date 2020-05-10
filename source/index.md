# Installation Guide

Make sure your computer has Node.js 12.16.3 installed. See these instructions to install it [here](https://nodejs.org/es/).

### Installing Runnerty

Install Runnerty
```bash 
npm i -g runnerty
```
Note: It's possible you have to use super user permission. More: [fix npm permisions](https://docs.npmjs.com/getting-started/fixing-npm-permissions)

You can check the correct instalation with the command 
```bash 
runnerty --version
```

### Installing the Runnerty CLI

Install Runnerty CLI
```bash
npm i -g runnerty-cli
```

### Start a project

Create a new project
```bash
rty new my-workflow
```

Go to the directory  
```bash
cd my-workflow
npm install
```

Run Runnerty
```bash
runnerty
```
