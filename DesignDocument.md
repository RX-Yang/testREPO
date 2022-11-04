# Design Document

**Author**: Team 6 (Alyssa Ayala, Juan Bermeo, Zheng Huang, Hongtao Jiang, Rongxin Yang)

## 1 Design Considerations

*The subsections below describe the issues that need to be addressed or resolved prior to or while completing the design, as well as issues that may influence the design process.*

### 1.1 Assumptions

*Describe any assumption, background, or dependencies of the software, its use, the operational environment, or significant project issues.*

### 1.2 Constraints

*Describe any constraints on the system that have a significant impact on the design of the system.*

### 1.3 System Environment

*Describe the hardware and software that the system must operate in and interact with.*

## 2 Architectural Design

### 2.1 Component Diagram

![](E:\QC\CS370\Project\370Fall22Sec34Team6\GroupProject\Docs\Images\Component diagram.png)

User component uses the services of ListManager component.

ListManager component uses the services of List component.

List component uses the services of Item component.

Item component uses the services of database.



### 2.2 Deployment Diagram

*This section should describe how the different components will be deployed on actual hardware devices. Similar to the previous subsection, this diagram may be unnecessary for simple systems; in these cases, simply state so and concisely state why.*

![](E:\QC\CS370\Project\370Fall22Sec34Team6\GroupProject\Docs\Images\Deployment diagram.png)

The data is store in Database Server by using SQL database. The User and ListManager components are in Android system.



## 3 Low-Level Design

*Describe the low-level design for each of the system components identified in the previous section. For each component, you should provide details in the following UML diagrams to show its internal structure.*

### 3.1 Class Diagram

*In the case of an OO design, the internal structure of a software component would typically be expressed as a UML class diagram that represents the static class structure for the component and their relationships.*

### 3.2 Other Diagrams

*Describe some dynamic aspects of your system using one or more behavioral diagrams, such as sequence and state diagrams.*

## 4 User Interface Design
*For GUI-based systems, this section should provide the specific format/layout of the user interface of the system (e.g., in the form of graphical mockups).*
