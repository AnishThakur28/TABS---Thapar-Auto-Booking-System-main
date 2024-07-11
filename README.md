# TABS---Thapar-Auto-Booking-System

![WhatsApp Image 2023-02-20 at 1 46 00 PM](https://user-images.githubusercontent.com/32153763/233845318-8970ba57-b654-4e55-aced-fdb8dd6f8af2.jpeg)

Transport is an integral part of our social living. The modern society cannot run without
transport facilities. There are many companies who give transport services to the
individual and corporate clients. In the current system, the client first contacts with the
transport company for getting transport service. The company then books the vehicle for
him on the requested date and time and then sends the vehicle to his place at the time.
The Online taxi booking system is the online service which will automate the process of
booking a taxi and will facilitate both the client and the company with reduced time and
efforts.


First the company will register his vehicles and the vehicles to the system. Then the client
will request for booking a vehicle on his required date and time, providing all necessary
information. The fare will be calculated and client should confirm it. Then the employee
will serve the client on the specific date and time. Finally the client will have an
opportunity to give a feedback for the service he got. The company can check it and take
appropriate action for the future improvements.


PURPOSE

The purpose of this SRS document is to specify software requirements of the Online Taxi
Booking. It is intended to be a complete specification of what functionality the system
provides. The main purpose of the system is to automate the process of booking a taxi
online. Specific design and implementation details will be specified in a future document.
Document Conventions
 Items that are intended to stay in as part of your document are in bold
 Explanatory comments are in italic text.
 Plain text is used where you might insert wording about your project


PROJECT SCOPE

This project’s aim is to automate the system, calculating the fare, collecting fare, collecting
all necessary information of the client and then serve the client. The data used by the
system is stored in a database that will be the centre of all information held clients and
employees and the base for the remainder of the process after the initial application has
been made. This enables things to be simplified and considerably quickened, making the
jobs of the people involved easier. It supports the current process but centralizes it and
makes it possible for decisions to be made earlier and easier way.
5
Project Goals
The main goals of the system is to automate the process carried out in the organization
with improved performance and realize the vision of online booking. Some of the goals of
the system are listed below:
 Manage large number of client details.
 Manage all details of clients who registered and requested for getting the service.
 Create employee accounts and maintain the data’s effectively.
 View all the details of the clients and employees.
 Showing available vehicles to book for the client.
 Calculating and showing the fare to client before booking.
 Create the statistical reports to facilitate the finance department work.
 Getting the feedback from the client to facilitate future improvement.
6FUNCTIONAL OR SPECIFIC REQUIREMENTS:
The system should satisfy the following requirements:
 Administrator Aspect
 Employee Aspect
 Client Aspect
Performance Requirements
Some Performance requirements identified is listed below:
 The database shall be able to accommodate a minimum of 10,000 records of
clientts.
 The software shall support use of multiple users at a time.
 There are no other specific performance requirements that will affect
development.
Security Requirements
Some of the factors that are identified to protect the software from accidental or
malicious access, use, modification, destruction, or disclosure are described below.
Specific requirements in this area could include the need to:
 Utilize certain cryptographic techniques
 Keep specific log or history data sets
 Assign certain functions to different modules
 Restrict communications between some areas of the program
 Check data integrity for critical variables
 Later version of the software will incorporate encryption techniques in the
user/license authentication process.
Portability Requirements
Some of the attributes of software that relate to the ease of porting the software to other
13
host machines and/or operating systems. This may include:
Apache is used to develop the product. So it is easiest to port the software in any
environment.
Reliability
Some of the attributes identified for the reliability is listed below:
 All data storage for user variables will be committed to the database at the time of
entry.
 Data corruption is prevented by applying the possible backup procedures and
techniques.
Usability requirements
Some of the usability requirements identified for this system are listed below:
 A logical interface is essential to an easy to use system, speeding up common
tasks.
 Error prevention is integral to the system and is provided in a number of formats
from sanity checks to limiting free-text input.
Availability
All cached data will be rebuilt during every startup. There is no recovery of user data if it is
lost. Default values of system data will be assigned when necessary.
Software System Attributes
There are a number of attributes of software that can serve as requirements. It is
important that required attributes by specified so that their achievement can be
objectively verified. The following items provide a partial list of examples.
The input system will allow for inputting numbers, operands, special symbols and letters
of the alphabet.
14
- XAMPP v3.3.0 as my local webserver that has a PHP Version 8.0.7
- PHP Language
- MySQL Database
- HTML
- CSS
- JavaScript
- jQuery
- Ajax
- Bootstrap
- AdminLTE
