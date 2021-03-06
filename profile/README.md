# ESPRIT-FGSC 
## MicroServices Spring Boot with docker
A team of esprit students developing microservices for a project implementing an Odoo clone.
## [Using swagger for documentation](https://fgsc-gateway.herokuapp.com/swagger-ui.html#/)
## Authors

- [@firasbelhiba](https://www.github.com/firasbelhiba)
- [@ghadakhedri1](https://www.github.com/ghadakhedri1)
- [@sadek-selmi](https://www.github.com/sadek-selmi)
- [@chihabhajji](https://www.github.com/chihabhajji)

  
## Tech Stack

**Client Side:** Angular 12 , RxJs, NgRx, NgPrime, RsocketClient

**Server Side:** Spring, Zuul, Eureka, MongoDB (reactive), Flux, RSocketServer ,Nodejs

![This is an image](https://cdn-images-1.medium.com/max/800/1*oxaA7PahX1-zo956FYLHFA.jpeg)

  
## Features

Our project is for Human Resource Management,it  contains 12 microservices with Zuul gateway and an Eureka server ,our microservices are in one container docker and they are using api from each other .

1. Auth/User management Microservice
2. Employees microservice
3. Job microservice
4. Attendance microservice
5. Leave microservice
6. Project microservice
7. Client microservice
8. Invoice microservice
9. Claim microservice
10. Department microservice
11. Notification microservice
12. Client satisfaction microservice

###### Description:

- Auth / Usermanagement  Microservice : manage user authentification and register [![Maven & Docker CI](https://github.com/ESPRIT-TWIN-MICROSERVICES-FGSC/AUTH-SERVICE/actions/workflows/maven.yml/badge.svg)](https://github.com/ESPRIT-TWIN-MICROSERVICES-FGSC/AUTH-SERVICE/actions/workflows/maven.yml)
- Employees microservice : manage employees 
- Job microservice : manage posting jobs 
- Attendance microservice : manage attendance for employees
- Leave microservice : manage leaves for employees
- Project microservice : manage projects for each client
- Client microservice :manage clients 
- Invoice microservice :manage invoices for the company
- claim microservice :manage claims 
- Department microservice :manage departements
- Client feedback acquisition : [![Maven & Docker CI](https://github.com/ESPRIT-TWIN-MICROSERVICES-FGSC/CUSTOMER-SATISFACTION/actions/workflows/maven.yml/badge.svg)](https://github.com/ESPRIT-TWIN-MICROSERVICES-FGSC/CUSTOMER-SATISFACTION/actions/workflows/maven.yml) [![CodeQL](https://github.com/ESPRIT-TWIN-MICROSERVICES-FGSC/CUSTOMER-SATISFACTION/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/ESPRIT-TWIN-MICROSERVICES-FGSC/CUSTOMER-SATISFACTION/actions/workflows/codeql-analysis.yml)
- Notification microservice :manage notification for admin [![Maven & Docker CI](https://github.com/ESPRIT-TWIN-MICROSERVICES-FGSC/RSOCKET-BROKER/actions/workflows/maven.yml/badge.svg)](https://github.com/ESPRIT-TWIN-MICROSERVICES-FGSC/RSOCKET-BROKER/actions/workflows/maven.yml)v
- Eureka serveur : [![Maven & Docker CI](https://github.com/ESPRIT-TWIN-MICROSERVICES-FGSC/EUREKA-SERVER/actions/workflows/maven.yml/badge.svg)](https://github.com/ESPRIT-TWIN-MICROSERVICES-FGSC/EUREKA-SERVER/actions/workflows/maven.yml)
- Zuul gateway : [![Maven & Docker CI](https://github.com/ESPRIT-TWIN-MICROSERVICES-FGSC/GATEWAY/actions/workflows/maven.yml/badge.svg)](https://github.com/ESPRIT-TWIN-MICROSERVICES-FGSC/GATEWAY/actions/workflows/maven.yml)
###### Sonar Cloud:
![img.png](sonar-cloud.png)
###### Github actions:
![img_1.png](github-actions.png)

