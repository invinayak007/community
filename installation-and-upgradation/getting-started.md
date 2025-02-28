---
description: 'Shows you a list of things to help you get started with cQube V 5.0:'
---

# Getting Started

cQube v5.0, the latest version of cQube, enables monitoring of 9 out-of-the-box state and national education programs for performance improvement. All of these programs will be tailored to the user role and jurisdiction. Any new program can also be added by the state for monitoring purposes.

The product overview of cQube has been linked [here](../) for further details.

## Skills Needed

Following technical skills are required to install and manage cQube v5.0:

1. **Docker**: This is required to install cQube v5.0 or upgrade from cQube v4.1 to v5.0. These are the links that can help you learn Docker - [Link 1](https://www.youtube.com/watch?v=rOTqprHv1YE) | [Link 2](https://www.youtube.com/watch?v=pTFZFxd4hOI) | [Link 3](https://www.youtube.com/watch?v=3c-iBn73dDE).
2. **TypeScript / Python / NiFi**: Either of these skills are required to create the adapters to be able to ingest state data into cQube as per cQube schemas. These are the links that can help you learn Typescript - [Link 1](https://www.youtube.com/watch?v=ahCwqrYpIuM) | [Link 2](https://www.youtube.com/watch?v=d56mG7DezGs). These are the links that can help you learn Python - [Link 1](https://www.youtube.com/watch?v=kqtD5dpn9C8) | [Link 2](https://www.youtube.com/watch?v=\_uQrJ0TkZlc). Here is a reference to help you learn NiFi - [Link](https://www.youtube.com/watch?v=fblkgr1PJ0o). Python & Apache NiFi will also be used if the cQube adopter wants to add a new program, report or indicator.
3. **Postman**: This is required to access the cQube APIs to be able to ingest state data into cQube. These are the links that can help you learn Postman - [Link](https://www.youtube.com/watch?v=VywxIQ2ZXw4).
4. **Nest.js:** This is required if the cQube adopter wants to add a new program, report or indicator. Here is a reference to help you learn Nest.js - [Link](https://www.youtube.com/watch?v=GHTA143\_b-s).
5. **SQL:** This is required if the cQube adopter wants to add a new program, report or indicator. These are a few links to help you learn SQL - [Link 1](https://www.youtube.com/watch?v=p3qvj9hO\_Bo) | [Link 2](https://www.youtube.com/watch?v=7S\_tz1z\_5bA).

## Team Composition

If the cQube adopter doesn't require to add any new program, report or indicator, following is the suggested team composition:

| Type              | Language / Skills                             | Experience | Full-time people |
| ----------------- | --------------------------------------------- | ---------- | ---------------- |
| Backend Developer | TypeScript                                    | 3+ years   | 1                |
| DevOps            | Docker                                        | 3+ years   | 1                |
| QA                | UAT                                           | 3+ years   | 1                |
| Tech Lead         | All of the above, including management skills | 5+ years   | 1                |

If the cQube adopter needs to add a new program, report or indicator, then they will need the following additional members:

| Type               | Language / Skills          | Experience | Full-time people |
| ------------------ | -------------------------- | ---------- | ---------------- |
| Backend Developer  | Nest.js, Python, NiFi, SQL | 4+ years   | 1                |
| Frontend Developer | Angular                    | 3+ years   | 1                |

## Supported Servers & Clouds

1. AWS - The steps to deploy cQube v5.0 on AWS have been mentioned [here](step-wise-installation-process.md).
2. Azure - The steps to deploy cQube v5.0 on Azure have been mentioned here.
3. On premise (State Data Centre, Local) - The steps to deploy cQube v5.0 on 'On premise' (State Data Centre, Local) have been mentioned here.

Oracle will also be made available soon for cQube v5.0.&#x20;
