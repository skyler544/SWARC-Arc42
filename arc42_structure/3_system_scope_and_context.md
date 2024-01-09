[<< Back](/README.md)

# Scope and Context

## Scope 

The app will be available for both iOS and Android devices.

The app will allow users to create profiles, search for rides, and connect with nearby drivers.

The app will include a payment system to facilitate transactions between drivers and passengers.

The app will use location-based services to identify nearby drivers and passengers.

The app will provide real-time updates on ride availability and estimated arrival times.

## Business Context 

List of stakeholders: 

- Passangers (want the ride)
- Drivers (provide the ride)
- Approval center (approve driverss)
- Payment service

*______________________________*

**Insert UML**

*______________________________*

| Piece     | Purpose |
| :-------- | :------ |
| MOTUS | Our service to connect passangers and driver plus a payment service. |
| Approval Center | Legal approve if drivers are allowed to drive. Recieve a form and contact details of drivers via webinterface. |
| Payment Service | Handles payment of users and payout for drivers. Integrated over API with redirect to the payment provider. |
| Passanger | User can sign up to use our app. |
| Driver | Can be approved to earn money by deliering the driving service. | 

## Technical Context

- App users
- Developer
- Approval center (approve driverss)
- Payment service
- Analytics service 

*______________________________*

**Insert UML**

*______________________________*

| Piece     | Purpose |
| :-------- | :------ |
| MOTUS | Our service to connect passangers and driver plus a payment service. |
| Approval Center | Legal approve if drivers are allowed to drive. Recieve a form and contact details of drivers via webinterface. |
| Analytics service| A third party service to monitor the cloud and services running on it. |
| Payment Service | Handles payment of users and payout for drivers. Integrated over API with redirect to the payment provider. |
| App user| Conntect to our services over the internet from Andriod/iOS devices. |
| Developer | Human actor, responsible for App development, deployment and maintainance. |