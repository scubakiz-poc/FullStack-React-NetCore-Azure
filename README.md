# FullStack-React-NetCore-Azure

## Overview
The intent of this demo is to show how various technologies can integrate together seemlessly and complement each other.  In the process, the application aims to leverage as many different technologies (primarily Microsoft Azure technologies) to demonstrate connectivity between them.  

The Full Stack web application includes:

1. Front-end: React
2. Middle-tier: ASP.Net Core 3.0
3. Back-end data-tier: Azure SQL Server
4. Security: Azure AD, Azure Key Vault
5. Hosting: Microsoft Azure

## Web Appication Functionality
The purpose of the app itself is to provide an interface for viewing conferences and to allow registered users to sign up to attend sessions at each conference.  All sessions are free to attend, but have limited amounts of seats available.

## Software Design Principles
The design uses Onion Architecture software principle to implement the [Dependency Inversion Principle](https://en.wikipedia.org/wiki/Dependency_inversion_principle) of the [SOLID Principles of Object Oriented Design](https://en.wikipedia.org/wiki/SOLID).
