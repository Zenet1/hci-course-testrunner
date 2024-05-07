# Test-Runner Project Definition

## Content

- [Description](#description)
- [Justification](#justification)
- [Technical Characteristics](#technical-characteristics)
- [Context of the Jan-May 2024 School Period](#context-of-the-january-may-2024-school-period)
- [Team Composition](#team-composition)
- [Activities Management](#activity-management)
- [Deliverable Artifacts](#deliverable-artefacts)
    - [First Delivery](#first-delivery)
    - [Second Delivery](#second-delivery)

## Project Definition

### Description

Test-Runner is a Social Service project managed by Professor M.C. Edgar Cambranes Martínez. The system is defined as a **command line tool for code testing, based on input-output files**. The tool is oriented to support students in the first semesters of computer science university degrees, who present slight previous knowledge on the handling of programming languages and programming environments. Similarly, the support is extended to professors who teach subjects that involve the use of programming languages, with the automated code evaluation of large groups of students.


### Justification

The project starts as a direct response to a real problem present in the Faculty of Mathematics of the UADY, where teachers of subjects that involve in some way in the creation and execution of code (Algorithmics, Structured Programming, Object Oriented Programming) are **unable to evaluate the code of all students** who are assigned to their groups, all this every time an assignment is made. Therefore, students often **do not receive feedback on the correctness of their code answers**, leading to a lack of continuous improvement in their programming learning.

### Technical Characteristics

The system can be used through a local installation on the desired PC device, or through its configuration in GitHub Actions as part of a repository within this platform. The planned use of this tool, as a configuration within repositories, is through "template" repositories, which can be used by professors of computer-oriented university subjects, for the use of these repositories as a basis for assignments within the GitHub Classroom platform. Thus, the purpose of the tool is to be systematically embedded in the repositories generated by the students for the evaluation of their code each time they make changes within their remote repository.

Currently, the system is capable of test code in four programming languages: C, C++, Java & Python. The system is open to extension for the programming languages it can test code.  


### Context of the January-May 2024 School Period 

The project, within the school period January-May 2024, is used as a Social Service project, where 3 students are participating as part of the Development Team. Simultaneously, the project is being used by a team of students of the subject Human-Computer Interface, where they are considered as the Design Team of the project. Both teams are working simultaneously for the development of the project.

Based on the background of the project, it has been clear that **the system has usability issues**, which were determined through a test, consisted of a group of students performing different activities oriented to the use of the system. To mitigate this problem, it was determined that the way to proceed with the project is through the development of an extension of Visual Studio Code, aimed to students.
 

## Internal Project Management

### Team Composition 

The team consists of 5 members, enrolled in the HCI subject. For the management of this project, no specific roles are being considered for the team members, so each one is not limited in the activities they can perform.

### Activities Management

The activities carried out for the design and development of the project during the course were established, assigned, weighted and managed through a board in the Trello platform, following the Kanban format.

> **Link to the Trello board:** https://trello.com/b/msc8SngK/hci-course 

Additionally, in the repository there is a static table with a summary of the activities and those responsible for each of them. The Activity Schedule table is found [here](./Activities%20Management/Activity%20Schedule.md).

### Deliverable Artifacts
#### First Delivery
The deliverable artifacts for the **First Delivery** are presented below:
- [Activities Schedule](./Activities%20Management/Activity%20Schedule.md)
- [Activities Management Definition (Definition of Done, Metrics Implemented)](./Activities%20Management/README.md)
- [Survey results](./User%20Analysis/User%20Research/survey%20(students).md)
- [Profile of Personas (Students and Teachers)](./User%20Analysis/User%20Modeling/Personas%20Profiles.md)
- [Personas Scenarios (Students and Teachers)](./User%20Analysis/User%20Modeling/Personas%20Scenarios.md)
- [Analysis of the Personas methodology](./User%20Analysis/User%20Modeling/Personas%20Analysis.md)
- [Exploratory Test Design](./Tests/Exploratory%20Tests/Exploratory%20Test%20Design.md)
- [Exploratory Tests Reports](./Tests/Exploratory%20Tests/Exploratory%20Tests%20Reports/)
- [Requirements Definition](./Requirements/Requirements%20Definition.md)
- [First Delivery Presentation](./Presentations/First%20Delivery/FirstDelivery-Presentation.pdf)
- [First Delivery Team Reflections](./Reflections%20of%20the%20HCI%20Course/First%20Delivery/)

#### Second Delivery

The deliverable artifacts for the **Second Delivery** are listed below:
- [Activities Schedule](./Activities%20Management/Activity%20Schedule.md)
- [Quality Attributes Related to Non-Functional Requirements](./Requirements/Requirements%20Definition.md#qualiity-attributes-related-to-non-functional-requirements)
- [Metrics Related to Quality Attributes](./Requirements/Metrics%20Related%20to%20Quality%20Attributes.md)
- [Prototype & Design Guide](https://www.figma.com/design/BRmxXYkRPCorbYL4aXitR2/Test-Runner-VSCode-Extension-Prototype?node-id=0%3A1&t=bl2U2GImltkrJyJD-1)
- [Requirements Traceability Matrix](https://alumnosuady-my.sharepoint.com/:w:/g/personal/a16003750_alumnos_uady_mx/EfAJk9vs-mlMv1RFCb-AKEsBj6yE22bNO-mNJFSqDZK6ug?e=LwtM1r)
- [Usability Test Design](./Tests/Usability%20Tests/)
- [Guide for the Application of Usability Tests](./Tests/Usability%20Tests/Guide%20for%20the%20Application%20of%20Usability%20Tests.md)
- [Second Delivery Team Reflections](./Reflections%20of%20the%20HCI%20Course/Second%20Delivery/)