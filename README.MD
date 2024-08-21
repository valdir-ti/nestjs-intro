<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="80" alt="Nest Logo" /></a>
</p>

## Introduction course of NestJS

[YouTube Link](https://www.youtube.com/watch?v=8_X0nSrzrCw)

## Chapter 1:

Q: What's NestJS?
A: NestJS is a framework built on top of NodeJS

NestJS is very opinionated well-structured architecture, TypeScript support, scalability and strong community.
NestJS combines eements of OO(Object Orientation), FP(Functional Programming) and FRP(Functional React Programming)

Update or install your Node version: [Node Site](https://nodejs.org/en)

Create and open a new project on vscode: [VSCode Site](https://code.visualstudio.com/)

Install nestjs locally:
```bash
    $ npm i -g @nestjs/cl
```

Create a new project:
```bash
    $ nest new project-name
```

### After installation
- After creating a new project, get a look for the created files
- The main.ts file is on the src folder
- The file called app.module.ts is on the src folder, and control the others files, like controllers and services.
- The controller file has the routes of module
- On the service file we have the methods called on controllers

### Compile and run the project
```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

### Try access the first route of project
- Install Thunder Client extension
- Add a new request to localhost:3000 and the response will be "Hello World"

### To create our own module
- Open a new terminal and enter this code
```bash
$ nest g module users
```
- This create a new folder called "users" on the project with a file called "users.module.ts", and update the app.module.ts with this new module

### To create our own controller
- Open a new terminal and enter this code
```bash
$ nest g controller users
```
- This will update the folder called "users" on the project with a file called "users.controller.ts", and update the users.module.ts with this new controller


### To create our own service
- Open a new terminal and enter this code
```bash
$ nest g service users
```
- This will update the folder called "users" on the project with a file called "users.service.ts", and update the users.module.ts with this new service 