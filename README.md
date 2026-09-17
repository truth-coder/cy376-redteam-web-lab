CY375 RED TEAM WEB LAB

Building a Red Team Rules of Engagement Document for a Simulated Engagement

PROJECT OVERVIEW

This project was developed as part of the CY375 Network Security, Auditing and Monitoring course at the University of Mines and Technology (UMaT).

The project demonstrates how a controlled red team security engagement can be planned, authorized, conducted, monitored, and documented using a simulated web application.

The testing was performed in a controlled laboratory environment for academic and educational purposes.

PROJECT OBJECTIVES

The main objectives of this project are to:

Define Rules of Engagement for a simulated red team assessment.

Identify the authorized target and testing boundaries.

Perform reconnaissance and service enumeration.

Analyze the behavior of the simulated web application.

Conduct controlled security testing.

Capture and analyze network traffic.

Collect and document security evidence.

Identify security observations and provide recommendations.

LAB ENVIRONMENT

Attacker Machine

Operating System: Kali Linux

Tools Used: Nmap, Wireshark and Python

Target Environment

Target: Locally hosted simulated web application

Organization: ABC Financial Services

Target Address: http://127.0.0.1:8080

The target application was created specifically for this academic security assessment.

WEB APPLICATION

The simulated application contains several routes used during the assessment.

Home page: /

Login page: /login

Search page: /search

Administrative page: /admin

API status endpoint: /api/status

The application was developed using Python and hosted locally on the testing machine.

RECONNAISSANCE AND ENUMERATION

Nmap was used to identify and examine the services running on the authorized target.

Example command:

nmap -sV 127.0.0.1 -p 8080

The scan identified the HTTP service running on the specified port.

Only the authorized laboratory target was tested during the engagement.

NETWORK TRAFFIC ANALYSIS

Wireshark was used to capture and analyze network traffic generated during the security assessment.

The traffic analysis was used to observe client and server communication, HTTP requests and responses, and other network activity generated during testing.

Screenshots and other relevant evidence from the assessment are stored in the screenshots directory.

RULES OF ENGAGEMENT

The security assessment was conducted according to defined Rules of Engagement.

Testing Scope

Testing was restricted to the authorized simulated target.

Target Address:

127.0.0.1:8080

Out of Scope Activities

Testing external systems.

Testing real organizations without authorization.

Denial of service attacks.

Destructive attacks.

Data destruction.

Unauthorized access to third-party systems.

Testing systems outside the defined scope.

AUTHORIZATION

All activities were performed within a controlled laboratory environment for academic and educational purposes.

No unauthorized external systems were intentionally targeted as part of this project.

EVIDENCE COLLECTION

Evidence collected during the engagement includes:

Nmap scan results.

HTTP request and response observations.

Wireshark traffic observations.

Application behavior.

Screenshots.

Security testing notes.

Relevant evidence is stored in the project repository where appropriate.

PROJECT STRUCTURE

cy376-redteam-web-lab

server.py

screenshots

README.md

HOW TO RUN THE LAB

Clone the repository using:

git clone https://github.com/truth-coder/cy376-redteam-web-lab.git

Enter the project directory:

cd cy376-redteam-web-lab

Run the simulated web application:

python3 server.py

After starting the server, open the following address in a web browser:

http://127.0.0.1:8080

SECURITY NOTICE

This project is intended strictly for authorized educational and laboratory use.

The techniques demonstrated in this project should not be used against systems without explicit permission from the system owner.

COURSE INFORMATION

Course: CY375 Network Security, Auditing and Monitoring

Institution: University of Mines and Technology (UMaT)

Project: Building a Red Team Rules of Engagement Document for a Simulated Engagement
