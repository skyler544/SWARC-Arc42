[<< Back](/README.md)

# 1. Introdcution and Goals



Describes the relevant requirements and the driving forces that software architects and development team must consider. These include

- underlying business goals, essential features and functional requirements for the system,
- quality goals for the architecture,
- relevant stakeholders and their expectations

## 1.1 Requirements Overview

### Contents

Short description of the functional requirements, driving forces, extract (or abstract) of requirements. Links to the (hopefully existing) requirements documents, with information where to find it.

### Motivation

From the point of view of the end users a system is created or modified to improve support of a business activity and/or improve the quality.

### Form

Short textual description, probably in tabular use-case format. If requirements documents exist this overview should refer to these documents.

Keep these excerpts as short as possible. Balance readability of this document with potential redundancy w.r.t to requirements documents. 

## 1.2 Quality goals

### Content

The top three quality goals for the architecture whose fulfillment is of highest importance to the major stakeholders considering the ISO 25010 standard.


| Priority |                    Quality                     |                                                                     Motivation                                                                     |
|:---------|:----------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------:|
| 1        | Usability | Userfriendly experience leads to higher user counts                                                 |
| 2        | Security | Payment services handle sensitive information,therefore a safe environment is required.                               |
| 3        | Availability | Easy scalability for peak times, therefore efficient use ofinfrastructure resources for cost reduction.                       |

### Motivation

In the ride-sharing app context, addressing usability, security, and availability aligns with the goal of providing a convenient, safe, and reliable transportation service. The app becomes not only a functional tool for connecting passengers with drivers but also a user-friendly and trustworthy platform that meets the diverse needs of its users.

## 1.3 Stakeholder

The table below provides an overview of all stakeholders involved in the M.O.T.U.S project.

| Name          |                                     Role                                     |                                                                     Expectations                                                                     |
|:--------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------:|
| Maryam Patel  |                     Investor at Venture Capital Firm XYZ                     |                                                          Profit, high return of Investment                                                           |
| Raj Gupta     |        Business Development Manager at Local Transportation Authority        |                             Expects the startup to contribute positively to the local transportation business landscape                              |
| Megan Chen    |               User Experience Designer at Creative Agency ABC                |                  Expects the startup to provide a good user experience, and wants to include this success in her agency's portfoli                   |
| Amirah Rahman | Environmental Activist and Representative of Sustainable Transportation NGOC | Advocating for eco-friendly and sustainable transportation solutions to mitigate environmental impact and promote a greener, more sustainable future |
| Javier Gomez  |     RideShare Driver and Representative of RideShare Driver Association      |                           Expects the startup to treat workers fairly and cooperate with the RideShare Driver Association                            |
| Developers    |                       Design, develop and maintain App                       |                 Clear and refined requirements, environment where developers can focus on their work, deliver high-quality software                  |