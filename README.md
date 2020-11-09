# smartoll

## CHAPTER 1

### INTRODUCTION

The project title is SMARTOLL (AUTOMATED TOLL SYSTEM USING QR CODE) and
the main core of this project is paying toll amount through an Android mobile application. The
registered user will be able to pay the toll amount through the application and will get register with
the toll booth without having to wait in the queue which decreases the fuel-consumption and also
taking cash from them can be avoided. So by using our system user can get QRCODE by paying
online, and so that user doesn’t need to wait at toll gate. Our system is designed in such a way that
the user just have to scan the QR Code which provided to him/her and then pass through the toll
gate. The user has to select the source and destination and have to pay all toll tax coming between
the source and destination of his own. This will avoid traffic and also pollution

```
![alt text](https://github.com/zaidkhn/smartoll/blob/main/smartoll%20images/1.png)
Fig.1.1. Hardware Structure of the Project
```
```
!(https://github.com/zaidkhn/smartoll/blob/main/smartoll%20images/2.png)
Fig.1.2. Project Banner
```

### 1.1 ABOUT THE PROJECT

We have developed the project in various environments such as php, android, python, etc.
Our idea is to use a mobile application to pay tolls between ones journey which will avoid traffic
and also the pollution. Conventional tolling system requires the vehicle to stop at a toll gate and the
toll fee is manually paid. This is a slow system as manual processing often leads to delay and vehicles
have to wait near a toll gate area.
An improvement in the traditional system is the SMARTOLL (Automated Toll Collection System),
which requires users to have an android application. As the vehicle passes the toll gate, the user has to
scan the QRCODE and the toll amount is deducted from the prepaid account balance. This allows
speeding up the toll collection process up to a certain level. Our system aims to overcome the
limitations of the today’s toll system. Instead of a cash payment, our system uses a smart-phone based
toll payment app.

```
!(https://github.com/zaidkhn/smartoll/blob/main/smartoll%20images/3.png)
Fig.1.1.1. Registration for Toll Payment via Mobile Application.
```
```
Database
Analyzing
the user
details
```
```
Access Granted
```
```
Access Denied
```
```
If
Correct
```
```
If
Incorrect
Registration
using Mobile
Application
```

### 1.2 AIM & OBJECTIVE OF THE PROJECT

The system is going to provide replacement of old traditional toll system i.e. queuing up to pay
toll.

Conventional tolling system requires the vehicle to stop at a toll gate and the toll fee is manually
paid. This is a slow system as manual processing often leads to delay and vehicles have to wait
near a toll gate area.

```
 Today’s toll paying system requires manual labour.
 Travellers have to wait in queue to pay toll.
 Travellers need to carry exact change.
 Excessive pollution near toll booths.
 Hand-to-Hand transaction of amount is more time consuming.
```

### 1.3 ADVANTAGES

 Reduction in waiting time at toll queue.
The waiting time at the toll is the major issue. The main reason is number of increasing
vehicles day-to-day. Due to our system waiting time is reduced.

 Faster and more efficient services :
There is no requirement of human resources except for maintenance of the devices and
since using machines there is less chance of error which occur due to humans

 Reduces manual labour and delays occurring while paying amounts.
Human error while taking and giving money is reduced due to our system.

 Reduce pollution problem near toll booth.
Since our system is totally online and the payment does not require to be done at the toll
thus the pollution is reduced.

 Easy to use and simple to carry app in mobile devices.
 Reduces illegal toll gate entry.
 Avoid financial loss.


## CHAPTER 2

### EXISTING SYSTEM

Example 1:

One institute has designed, developed and manufactured two types of toll collection systems on
highways: “closed system” (where the presence of the vehicles is registered at the entrance to the
system, and the payment is performed at the exit), and “opened system” (the payment is performed
on one spot regardless of the distance traveled).

The whole system includes three levels:

1. Lane level.
2. Plaza level.
3. Central level.

```
!(https://github.com/zaidkhn/smartoll/blob/main/smartoll%20images/4.png)
Fig.2.1 System Overview of “opened and closed system”
```
Example 2:

Electronic Toll Collection System is designed in such a way that as the vehicle approaches the toll
plaza, the radio frequency field emitted from the antenna activates the transponder.


The transponder broadcasts the signal back to the lane antenna with some basic information. That
information is transferred from the lane antenna to the central database.

If the account is in good standing then toll is deducted from the prepaid account of the traveler. If
the toll lane has a gate, the gate opens. A green light indicates that the driver can proceed.

This entire process takes matter of seconds to complete. Electronic system records transaction
including time, date, plaza and toll charge of each vehicle.

But this system uses RFID tags which means if RFID tags fails the whole system fails.

```
!(https://github.com/zaidkhn/smartoll/blob/main/smartoll%20images/5.png)
Fig 2.2 System overview of “Electronic Toll System”
```
An improvement in these above mentioned system is the SMARTOLL (Automated Toll Collection
System), which requires users to have an android application. As the vehicle passes the toll gate,
the user has to scan the QRCODE and the toll amount is deducted from the prepaid account
balance. This allows speeding up the toll collection process up to a certain level. Our system aims
to overcome the limitations of the today’s toll system. Instead of a cash payment, our system uses
a smart-phone based toll payment app. The gate opens and closes as the vehicle is fully passed
through the toll gate which is recognized by the IR Scanners at both the entry and exit point of the

### toll gate.


## CHAPTER 3

### PROBLEM DEFINITION

The amount of traffic in recent years has been steadily increasing due to the ever increasing number
of vehicles. Every day; millions of commuters take to their own personal vehicles in place of public
transport systems .This leads to steady increase in vehicle traffic in developing countries. The only
possible solution is to build more number of wider roads. Often the government is in short of funds;
hence “tolling systems” are used to collect funds as the vehicles use these toll roads.
Conventional tolling system requires the vehicle to stop at a toll gate and the toll fee is manually
paid. This is a slow system as manual processing often leads to delay and vehicles have to wait
near a toll gate area.
➢ Today’s toll paying system requires manual labor.

➢ Travellers have to wait in queue to pay toll.

➢ Travellers need to carry exact change.

➢ Excessive pollution near toll booths.

➢ Hand-to-Hand transaction of amount is more time consuming.
An improvement in the traditional system is the SMARTOLL (Automated Toll Collection
System), which requires users to have an android application. As the vehicle passes the toll gate,
the user has to scan the QRCODE and the toll amount is deducted from the prepaid account
balance. This allows speeding up the toll collection process up to a certain level. Our system aims
to overcome the limitations of the today’s toll system. Instead of a cash payment, our system uses

### a smart-phone based toll payment app.


## CHAPTER 4

### DEVELOPED SYSTEM

### 4.1 ANALYSIS & DESIGN

System Analysis

Systems analysis is the study of interacting entitles, including computer systems analysis. This
field is closely related to requirements analysis or operations research. It also "an explicit formal
inquiry carried out to help someone (referred to as the decision maker) identify a better Service of
action and make a better decision than he might otherwise have made."

The terms analysis and synthesis come from Greek where they mean respectively to take apart"
and "to put together". These terms are in scientific disciplines from mathematics and logic to
economy and psychology to denote similar investigative procedure. Analysis is defined as the
procedure by which we break down an Intellectual or substantial whole into parts, synthesis is
defined as the procedure by which we combine separate elements or components in order to form
a coherent whole systems analysis researchers apply methodology to the analysis of systems
involved to form an overall picture, system analysis is used in every field where there is work of
developing something.

Characteristics of a System analysis

1) Organization: It says the Structure or order of built.
2) Interaction: Procedure in which the components interact.
3) Interdependence.
4) Integration.
5) Central objective.

Elements of System Analysis

There are 4 basic elements of system analysis, they are

1. Outputs


2. Inputs: The essential elements of Inputs are

2.1 Accuracy of data.

2.2 Timeliness.

2.3 Proper format.

2.4 Economy.

3. Files
4. Process

Analysis involved a detailed study of the current system, leading to specifications a new system.
Analysis is a detailed study of various operations performed by a system and their relationships
within and outside the system. During analysis, data are collected on the available files, decision
points and transactions handled by the present system. Interviews, on-site observation and
questionnaire are the tools used system analysis.

Using the following steps it becomes easy to draw the exact boundary of the new system under
consideration:

```
 Keeping in view the problems and new requirements
 Workout the pros and cons including new areas of the system
```
All procedures, requirements must be analysis and document in the form of detailed data flow
diagrams (DFDs), data dictionary, logic data structures and miniature specification. System
Analysis also includes sub-dividing of complex process involving the entire system, identification
of data store and manual processes

Code Generation

This is the phase where actual development of the system takes place. That is based on the design
documents prepared in the earlier phase code is written in the programming technology chosen.
After the code is developed generation of code also takes place in this phase. In other words the
code is converted into executable in this phase after code generation.


Code generation (compiler)

In computer science, code generation is the process by which a compiler's code generator converts
some intermediate representation of source code into a form (e.g. machine code)that can be readily
executed by a machine (often a computer).

Automatic programming

In computer science, the term automatic programming identifies a type of computer programming
in which some mechanism generates a computer program to allow human programmers write the
code at a higher abstraction level.

System Design
Introduction:
The purpose of the Design Phase is to a solution of the problem specified in the requirements
Document. This is the first step in moving from the problem domain to the solution domain The
design of a system is perhaps the most critical factor affecting the quality of the software, has a
major impact on the phases is the Design Document. This Document is similar to a blueprint or a
plan for the solution and is used later during implementation, testing and maintenance.
The goal of the design process is to produce a model of a system, which can be used later to build
that system. The produced model is called design of the system.
Overview:
The Design activity is often divided into separate phases -system Design and Detailed Design.
System Design is sometimes also called Top-Level Design. This system design aims to identify
and modules that should be in the system, the specifications of these modules, and how they
interact with each other to produce the desired result. At the end of the System Design all the major
data structures, file formats, and the major modules in the system and their specifications are
decided.

Scope:


This Application works in Multiple PC's installed on multiple computers but sharing same
database by which users of different department can use it sitting at different locations
simultaneously.
But in future we can make the Application where the database will be hosted in order to manage
the all departments which will be located in different places and by keeping domain of Application
as Online.

```
!(https://github.com/zaidkhn/smartoll/blob/main/smartoll%20images/6.png)
Fig.4.1.1 DFD Diagram
```
!(https://github.com/zaidkhn/smartoll/blob/main/smartoll%20images/7.png)
Fig.4.1.2. Activity Diagram.


### Use Case Diagram
!(https://github.com/zaidkhn/smartoll/blob/main/smartoll%20images/8.png)
Fig.4.1.3.

```
!(https://github.com/zaidkhn/smartoll/blob/main/smartoll%20images/9.png)
Fig.4.1.4. Gantt Chart.
```

### 4.2 REQUIREMENTS

The Software Requirements Specification is produced at the culmination of the analysis task. The
function and performance allocated to software as part of system engineering are refined by
establishing a complete information description. a detailed functional and behavioral description,
an indication of performance requirements and design constraints appropriate validation criteria
and other data pertinent to requirements.

Internet Facility
Our application requires Internet because it is a request response type application. When user
search toll the request goes to server and server response the tolls between the route and also for
the login and registration and for payment. When user scan the code at toll booth the
microcontroller must connected to internet to update the Qrcode.

### Hardware Requirement

The minimum hardware required for the development of the project is as follows-

```
QR Code Scanner
Wi-fi Module.
Microcontroller
Smart Phone.
Server (Recommended).
Core i3 or Higher.
RAM (1GB) or Higher.
HDD (100GB).
```
This all are the minimum hardware requirement required for our project. We want to make our
project to be used in any type of computer therefore we have taken minimum configuration to a
large extent 4GB ram is used so that we can execute our project in a least possible ram 5GB hard
disk is used because project takes less space to be executed or stored. Therefore, minimum hard
disk used. Other enhancement are according to the needs.


### Software Requirement

Various software’s are needed in this project for its development.

```
 Windows 7 or higher.
 Android Studio/ Eclipse.
```
We have implemented our project in various languages, below is the description of them:

 JAVA:
Java is a general-purpose computer programming language that is concurrent, class- based,
object-oriented, and specifically designed to have as few implementation dependencies as
possible. It is intended to let application developers "write once, run anywhere" (WORA)
meaning that compiled Java code can run on all platforms that support Java without the need
for recompilation Java applications are typically compiled to byte code that can run on any
Java virtual machine (JVM) regardless of computer architecture. As of 2016, Java is one of the
most popular programming languages in use, particularly for client-server web applications,
with a reported 9 million developers .Java was originally developed by James Gosling at Sun
Microsystems (which has since been acquired by Oracle Corporation) and released in 1995 as
a core component of Sun Microsystems' Java platform. The language derives much of its
syntax from C and C++, but it has fewer low-level facilities than either of them. The original
and reference implementation Java compilers virtual machines, and class libraries were
originally released by Sun under proprietary licences. As of May 2007, in compliance with the
specifications of the Java Community Process, Sun relicensed most of its Java technologies
under the GNU General Public License. Others have also developed alternative
implementations of these Sun technologies, such as the GNU Compiler for java (byte code
compiler), GNU Class path (standard libraries), and Iced Tea-Web (browser plugin for
applets).The latest version is Java 8 Update 121 which is the only version currently supported
for free by Oracle.
 BOOTSTARP:
Bootstrap is a free and open-source front-end web framework for designing websites and web
applications. It contains HTML-and CSS-based design templates for typography forms,


buttons navigation and other interface components, as well as optional JavaScript extensions.
Unlike many web frameworks, it concerns itself with front-end development only.
Bootstrap is the second most-started project on GitHub, with more than 107,000 stars and
48,000 forks Bootstrap, originally named Twitter Blueprint, was developed by Mark Otto and
Jacob Thomton at Twitter as a framework to encourage consistency across internal tools.
Before Boosting, various libraries were used for interface development, which led to
inconsistencies and a high maintenance burden. According to Twitter developer Mark Otto.
After a few months of development by a small group, many developers at Twitter began to
contribute to the project as a part of Hack Week, a hackathon-style week for the Twitter
development team. It was renamed from Twitter Blueprint to Bootstrap, and released as an
open source project on August 19, 2011. It has continued to be maintained by Mark Otto, Jacob
Thomton, and a small group of core developers, as well as a large community of contributors.

 PHP (Hypertext Pre-processor)
Hypertext Pre-processor (PHP), is a widely used, general-purpose scripting language that was
originally designed for web development, to produce dynamic web pages. It can be embedded
into HTML and generally runs on a web server, which needs to be configured to process PHP
code and create web page content from it. It can be deployed on most web servers and on
almost every operating system and platform free of charge.
PHP was originally created by Rasmus Lerdorf in 1995 and has been in continuous
development ever since. The main implementation of PHP is now produced by The PHP Group
and serves as the de facto standard for PHP as there is no specification is free software released
under the PHP License, which is incompatible with the GNU General Public License (GPL)
because of restrictions on the use of the term PHP.
PHP has evolved to include a command line interface capability and can also be used in
standalone graphical applications


### 4.3 IMPLEMENTATION

The incremental model is a method of software development where the product is designed,
implemented and tested incrementally until the product is finished. It involves both development
and maintenance. The product is defined as finished when it satisfies all the requirement. This
model combines the element of the waterfall model with the iterative philosophy of prototyping.
Planning is very important part of any project. There are different models which are used to plan
the schedule and other activities of the project. The model which is used in our project is
Incremental model consist of communication, planning, modeling, construction and
deployment.

1. Communication:
    For starting any project the specifications of the client or the audience for whom you are
    making the project is very important. As per the requirement of the client the software is
    made. After gathering information different factors which are necessary for management
    are considered and the software is made.
2. Planning:
    Planning schedule all the activities and keeps track of every activity. All the phase of the
    software development are planned. Sometimes the client is also involved. The
    responsibility is given to each and every member as per his capability. It includes the date
    of deployment according to which all the activities are planned. The risks in the project is
    taken into consideration and also the cost is decided.
3. Modelling: Modeling shows the overall structure of the software. According to the
    structure design and coding of the software is done. It is the skeleton of the project.
4. Construction:
    In this phase the model of the software made in earlier stage is converted into actual
    software. In this phase coding is done according to the design. While coding the bugs or
    errors found in the software are resolved.


5. Deployment:
    In this phase the software is deployed i.e. delivered to the client. With the product,
    documents are also delivered which includes guide for the product. After customer has
    used the product then the feedback is taken from the customers and support is provided if
    required.


## CHAPTER 5

### FUTURE WORK

We can give a static QR code which can be attached to vehicles, when vehicle pass from the toll
booth the scanner automatically scan that QR code and open the gate.

If in future some higher functionality scanner is introduced then we can directly scan the number
plate of vehicles instead of QR code which will require even lesser time and payment will be
deducted from the user’s bank account linked with that vehicle.


## CHAPTER 6

### CONCLUSION

After implementing the SMARTOLL (Automated Toll System Using QR Code), we have
understood the concept that how to develop a web based application as well as android application
and use of raspberry pie and the scripting of python.
While completing this project, we have understood the standards of coding.

We have implemented and understood the working of PHP, Python on server-side and have
completed different task to provide a better Toll System.


## CHAPTER 7

### REFERENCES AND BIBLOGRAPHY

 [http://www.google.com](http://www.google.com)
 [http://www.irjaes.com/pdf/IRJAES-V1N2Y16/IRJAES-V1N2P16Y16.pdf](http://www.irjaes.com/pdf/IRJAES-V1N2Y16/IRJAES-V1N2P16Y16.pdf)
 [http://www.slideshare.net/rohankale05/automatic-toll-collection-system-presentation](http://www.slideshare.net/rohankale05/automatic-toll-collection-system-presentation)
 [http://www.wikipedia.com](http://www.wikipedia.com)
 [http://www.stackoverflow.com](http://www.stackoverflow.com)
 [http://www.tutorialspoint.com](http://www.tutorialspoint.com)
 [http://www.w3schools.com](http://www.w3schools.com)


### 7.1 MEMBERS

#### 1) KHAN ZAID MEHMOOD.


#### 2) NATIQ ABIS PARVEZ


#### 3) SIDDIQUE MD. ZAID ALAM


#### 4) WAQUAR YUNUS


