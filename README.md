![GitHub](https://img.shields.io/github/license/VicDCruz/carrental-app) ![GitHub top language](https://img.shields.io/github/languages/top/VicDCruz/carrental-app) ![Docker Image Size (latest by date)](https://img.shields.io/docker/image-size/VicDCruz/carrental-app) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/VicDCruz/carrental-app)

# Car rental App
## Objective
Practice my skills for backend (Spring boot), frontend (Next.js) and their communication.

## Description
A car rental clone application that replicates its functional and non-functional requirements.

### Actors
- Driver 🙋‍♂️ > Regular driver, VIP driver
- Automobile 🚗 > Solo automobile, family automobile, friends automobile
- Branch office 🏢

## User Stories
- [ ] As a **driver**, I want to search for cars in a branch office with specific details for my N-days stay, so that I can compare theire prices and specifications.
- [ ] As a **driver**, I want to reserve a car, so that I can use it when I arrive to the branch office.
- [ ] As a **driver**, I want to check all my reservations, so that I can have a history of my movements
- [ ] As a **branch office**, I want to get and validate an official driver's license, so that the validated driver can have the keys.
- [ ] As a **branch office**, I want to update the mileage when the car is returned.
- [ ] As a **driver**, I want to rent not-so-much used cars.

## Requirements

### Functional requirements
- [ ] Search for cars by showing price and name.
- [ ] Have availability of cars in a time period.
- [ ] Reserve, edit and cancel the reservation as a driver.
- [ ] Get an official driver's license.
- [ ] View all reservation movements of a single driver
- [ ] Cancel a last-time-minute reservation as a branche-office

### Non-Functional requirements
- [ ] Return a search query for non- and vip drivers. The vip drivers can see all types.
- [ ] Every car should by in a category of space (solo, family, friends).
- [ ] Authorization and authentication properties.
- [ ] A car has a rating from users.
- [ ] Send email of the reservation.
- [ ] All cars with a mileage over a threshold can't be rented any more.

## Tools
- TDD (Test-driven development) approach
- [Spring boot web-development](https://spring.io)
- [Next.js](https://nextjs.org)
- [Docker](https://www.docker.com)
- [MySql](https://www.mysql.com)
- A queue messaging service (Not defined yet...)
