# CDAP
# Cyber Defense and Attack Prevention program

Authors:
Milan Milivojević
Aleksa Novaković


Project is a mandatory assignment for course USP (Upravljanje softverskim projektima - Management of software projects).
Project is created to answer Horizon 2020 EU Commission Project Call - Secure societies - Protecting freedom and security of Europe and its citizens (H2020-EU.3.7).
There are a total of 6 participants in the project and project length is approx. 3 years.

Our project was made as an example of a distributed system, that will integrate protection of company servers from different types of attacks.
The project itself was done in three phases:
-1. Project plan, budget and assignments for each participant (Word,Excel)
-2. Detailed project planning in Microsoft Project
-3. Designing and coding a prototype of the project

First two phases are written in Serbian, in Microsoft Office tools.

The prototype contains the following:
-Company website made with MEAN stack (Angular for front-end and MongoDB, NodeJS and Express framework for backend).
-Company server for accepting reports and informing client companies of the attack (NodeJS)
-A prototype of a company server, simulation of a simple login interface (made in Java)
-A prototype of a company client, which sends credentials in a request to login (made in Java)

The prototype company server has a detection software which detects (D)DoS attacks and sends reports to the main server, which bans the client for a period of time (10 days, hardcoded within NodeJS server) and it also detects bruteforce attacks and issues bans for the attacker (31 days). Company personnel can login on the website and view attack history on their infrastructure and there are admins which can add company accounts to the system. 

Code is mostly in English language.

