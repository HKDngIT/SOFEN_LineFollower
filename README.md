
# LineFollower-Robot
![Zumo](./Images/Zumo.jpg)  
A robot, which follows a black line using line sensors.  
Special features include:
- A user interface on the OLED screen with 3 different running settings
- Gap Handling
- Time measurement and distance measurement for each run
- Clean error handling

Each week we held 2 meetings to discuss our problems or review the results. After every lecture each team member had a task for that week(depends) and had to create his or her own branch to implement/ solve the task. 
The GITLAB repository was modified so it was not possible to merge branches into the MAIN without the approval of at least one other team member. So before any merge the code and changes were thoroughly reviewed. 
In order for everyone to have a good overview what the other members are currently working on, we used a ![Kanban Board](https://de.wikipedia.org/wiki/Kanban-Board) using ![Gitlab issue boards](https://docs.gitlab.com/ee/user/project/issue_board.html).  

# Phases
The project was generaly divided into 4 phases(or ![epics](https://docs.gitlab.com/ee/user/group/epics/))
- Analysis
- Design
- Implementation
- Test

## Analysis
Creation of various documents or diagrams:
- ![Software-Requirement-Specification(SRS)](https://www.perforce.com/blog/alm/how-write-software-requirements-specification-srs-document)
- ![Use-Case-Diagrams](https://www.ionos.de/digitalguide/websites/web-entwicklung/anwendungsfalldiagramm/)
- ![Architecture Diagrams](https://aws.amazon.com/de/what-is/architecture-diagramming/)

## Design
Creation of the class diagrams

## Implementation
The implementation step included a lot of ![integration tests](https://de.wikipedia.org/wiki/Integrationstest).  
The implementation steps were roughly:
- state machine
- hardware layer(to ensure each hardware module was functioning properly)
- each state specifically(start-up, calibration, ready/ idle, error, finish, run)

## Test
Partly the test consisted of the integration tests during the implementation process.  
The other important part of tests were the unit tests implemented with the ![Unity Test Framework](https://docs.unity3d.com/Packages/com.unity.test-framework@1.1/manual/index.html) using the simulated Hardware using the HWSIM-classes(watch below in 'Image' section)

## What I was part of
- Implementation of the acting package in the hardware layer - the control over the motor module
- Implementation of the run state which is responsible for line-follow-handling/ gap handling etc.
- Implementation of the unit tests for the run state

## Goal of the Project
- The ability to realize a greater object-oriented softwareproject
- aswell as the know-how to use the distributed version control system GIT in a smaller team
- Clean documentation using [Doxygen](https://www.doxygen.nl/index.html)
- Clean coding with a specific coding-style given by the lecturer
- Using UML with [PlantUML](https://plantuml.com/de/)
- Well structured software development process - in this case the (V Model)

## Images

### The challenge track 
![Track](/Images/LineFollower.jpg)  

### *V Model* 
![V_Image](./Images/1_v-model.png)  

### *Example of a kanban or issue board*
![kanban](https://docs.gitlab.com/ee/user/project/img/issue_boards_core_v14_1.png)

### *The whole UML class diagram of the project(redacted)*  
![classDia](/Images/classDiagram.png)  


## Official Sources of Content and Images
[Polulul - Robotics and Electronics](https://www.pololu.com/docs/0J63/all)  
[V Model](https://builtin.com/software-engineering-perspectives/v-model)  
[PlantUML](https://plantuml.com/de/)  
[Official Zumo 32U4 Library](https://pololu.github.io/zumo-32u4-arduino-library/)

## Disclaimer

Due to privacy issues I will sum up all details and knowledge I have gained during the project.  
I DO NOT OWN ANY RIGHTS OF THE IMAGES USED - UPON REQUEST I WILL REMOVE THEM ASAP!
