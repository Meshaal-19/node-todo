# Node Todo App — DevOps Semester Project

This repository contains a **DevOps-enabled version** of an open-source Node.js Todo application.
The project focuses on applying **core DevOps practices** such as containerization, CI/CD automation,
and structured Git workflows to an existing application.

---

## Project Context

- **Course:** DevOps
- **Project Type:** Semester Project (Proposal Milestone)
- **Student:** Meshaal Shakeel and zoha ali
- **Original Repository:** https://github.com/scotch-io/node-todo
- **Forked Repository:** https://github.com/Meshaal-19/node-todo

---

## Project Objective

The objective of this project is to demonstrate how DevOps principles can be applied to an
existing open-source application in order to:

- Improve build and deployment consistency
- Automate validation through CI pipelines
- Enable reproducible multi-service environments
- Follow professional Git collaboration practices

---

## Application Overview

The Node Todo App is a simple single-page web application that allows users to manage todo items.

### Tech Stack
- **Frontend:** AngularJS
- **Backend:** Node.js + Express
- **Database:** MongoDB

The application follows a three-tier architecture consisting of a frontend UI, backend API,
and database layer.

---

## Module Breakdown & Responsibilities

Although developed as an individual project, the system is logically divided into modules
to reflect real-world DevOps team responsibilities.

| Module | Description | Owner |
|------|------------|------|
| Frontend | UI and client-side logic | zoha ali |
| Backend | REST API and business logic | zoha ali |
| Database | MongoDB data persistence | Meshaal Shakeel |
| DevOps | Docker, CI/CD, Git workflow | Meshaal Shakeel |

---

## Containerization Strategy

- The backend application is containerized using **Docker**
- MongoDB runs as a **separate container**
- **Docker Compose** is used to orchestrate multi-service execution
- Environment variables are used for configuration
- Volumes ensure database persistence


# Node Todo App

A Node app built with MongoDB and Angular. For demonstration purposes and a tutorial.

Node provides the RESTful API. Angular provides the frontend and accesses the API. MongoDB stores like a hoarder.

## Requirements

- [Node and npm](http://nodejs.org)
- MongoDB: Make sure you have your own local or remote MongoDB database URI configured in `config/database.js`

## Installation

1. Clone the repository: `git clone git@github.com:scotch-io/node-todo`
2. Install the application: `npm install`
3. Place your own MongoDB URI in `config/database.js`
3. Start the server: `node server.js`
4. View in browser at `http://localhost:8080`

## Tutorial Series

This repo corresponds to the Node Todo Tutorial Series on [scotch.io](http://scotch.io)

Each branch represents a certain tutorial.
- tut1-starter: [Creating a Single Page Todo App with Node and Angular](https://scotch.io/tutorials/creating-a-single-page-todo-app-with-node-and-angular)
- tut2-organization: [Application Organization and Structure](https://scotch.io/tutorials/node-and-angular-to-do-app-application-organization-and-structure)
- tut3-services: [Controllers and Services](https://scotch.io/tutorials/node-and-angular-to-do-app-controllers-and-services)

Happy Todo-ing!

![Todo-aholic](http://i.imgur.com/ikyqgrn.png)

### Run Using Docker Compose
```bash
docker compose up --build
