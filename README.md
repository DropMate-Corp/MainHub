# DropMate Main Hub

This project was developed within the scope of the course 
**Software Testing** and **Quality Control** to put into practice 
the **Quality Assurance**, **Test-Driven Development** and **CI/CD** 
strategies learned in the practical classes.

This repository serves as main hub for the project, where the 
final report and documentation can be found inside the **/docs** 
folder. All the code is distributed across different 
repositories, which will be briefly disbribed in the 
[Project Structure](#Project-Structure) section.

## Project Abstract

Nowadays, pick-up points services are closely related to the main-stream and 
well-known courier services, serving as sub-systems. 
However, this fact limits potential partnerships with small 
stores and shops that are on efficient locations for pick-ups 
but are not seen as relevant to the big courier services. 
We are committed to develop a flexible solution that allows 
physical stores to approach us and make pick-up deals as well 
as allow online stores to solicit our services. 
This way we are thriving to achieve an efficient network 
of pick-ups that bring the purchased products closer and 
faster to the end users.

We developed an application named DropMate whose goal is 
to manage a network of associated collection points (ACP) 
and parcel lockers and provide a withdrawal B2B service to 
e-Stores.

The full-stack application DropMate consists of a REST API 
and a web application to be used by internal administrators 
and associated collection points operators. 
In addition, we developed an e-Store web instance of an 
online flower shop called Floral Fiesta as a proof-of-concept 
demonstrator of the full-stack application.

## How to Run

To run Dropmate and FloralFiesta applications locally:

- Setting up and running backend:
    1. Clone [Dropmate](https://github.com/DropMate-Corp/DropMate) and [Floral-Fiesta](https://github.com/DropMate-Corp/Floral-Fiesta) repositories
    2. Install Docker Compose
    3. Inside each repository run the command > ```docker compose up```

- Setting up and running frontend:
    1. Clone [Dropmate-UI](https://github.com/DropMate-Corp/DropMate-UI) and and [Floral-Fiesta-UI](https://github.com/DropMate-Corp/Floral-Fiesta-UI) repositories
    2. Install npm
    3. Inside each repository run the command > ```npm start```

## Project Team

- [André Butuc](https://github.com/abutuc) (andrebutuc@ua.pt) (DevOps master & Developer)
- [Artur Correia](https://github.com/afarturc) (art.afo@ua.pt) (QA Engineer & Developer)
- [Daniel Carvalho](https://github.com/danielfcarvalho) (dl.carvalho@ua.pt) (Team Coordinator, Product Owner & Developer)

## Project Structure

| Repository                                                                         | Description                                                            |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| [DropMate Backend Repository](https://github.com/DropMate-Corp/DropMate)           | Holds the code and CI/CD workflows for the DropMate platform backend   |
| [DropMate Frontend Repository](https://github.com/DropMate-Corp/DropMate-UI)       | Contains the code for the DropMate platform UI                         |
| [Floral-Fiesta Backend Repository](https://github.com/DropMate-Corp/Floral-Fiesta) | Code and CI/CD workflows for the Floral Fiesta, a simulated web store partnered up with the DropMate pick-up point service |
| [Floral-Fiesta Frontend Repository](https://github.com/DropMate-Corp/Floral-Fiesta-UI)| Contains the code for the Floral Fiesta platform UI                 |

## Other Important Links

- [DropMate API Documentation](https://documenter.getpostman.com/view/27813192/2s93sXcaR8)
- [Project Backlog](https://andrebutuc.atlassian.net/jira/software/projects/DM/boards/2/roadmap?shared=&atlOrigin=eyJpIjoiZmVmOTRiZDU4MWQ2NGQxMzk0NTE0ZGM5ZGZhMmE4ZDMiLCJwIjoiaiJ9)
- [Project Cloud Drive Workspace](https://uapt33090-my.sharepoint.com/:f:/g/personal/andrebutuc_ua_pt/Ei61Ll3_q8JFicrnFMo1yyABpXKcWBbOF21gDH7DTVC9-A?e=EHLWqc)
- [SonarCloud Dashboard](https://sonarcloud.io/organizations/dropmate-corp/projects)
