

- [What is software engineering?](#what-is-software-engineering)
- [Why we need software engineering](#why-we-need-software-engineering)
- [Key Processes in Software Engineering](#key-processes-in-software-engineering)
- [Software Evolution](#software-evolution)
- [Types of Software Maintenance](#types-of-software-maintenance)
- [Software Evolution Law](#software-evolution-law)
  - [Classification of softwares](#classification-of-softwares)
    - [E-Type software evolution](#e-type-software-evolution)
- [SDLC](#sdlc)
- [Characteristics of good software](#characteristics-of-good-software)
- [SDLC](#sdlc-1)
- [Process Models](#process-models)
  - [Waterfall Model](#waterfall-model)
  - [Iterative Model](#iterative-model)
  - [Spiral Model](#spiral-model)
  - [V-Model](#v-model)
  - [Big Bang Model](#big-bang-model)
- [Project Management](#project-management)
  - [Risks](#risks)
  - [Risk Management Process](#risk-management-process)
  - [Project Monitoring](#project-monitoring)
  - [Communication](#communication)
  - [Project Management Tools](#project-management-tools)
    - [Gantt Chart](#gantt-chart)
    - [PERT Chart](#pert-chart)
    - [Resource Histogram](#resource-histogram)
  - [Critical Path Analysis](#critical-path-analysis)
- [Crash-Review](#crash-review)

## What is software engineering?

- Software engineering is combination of two words `Software` and `Engineering`
- the later word is derived from engineer which simply means:
- someone who `desgin`, `build` and `maintain` structures 
- and `software`s simply are non-physical structures that help in communication with computers. 

> and `software engineering` is the systematic engineering approach for designing, building, and maintaining `softwares`

## Why we need software engineering

Software engineering is important because specific software is needed in almost every industry, in every business, and for every function. It becomes more important as time goes on – if something breaks within your application portfolio, a quick, efficient, and effective fix needs to happen as soon as possible.

## Key Processes in Software Engineering

- Requirements Definition
- Feasibility Study
- System and Software Design
- Implementation and Unit Testing
- Integration and System Testing
- Operation and Maintenance


![1](static/images/1.png)


## Software Evolution

Software Evolution is a term which refers to the process of developing software initially, then timely updating it for various reasons, i.e., to add new features or to remove obsolete functionalities etc.

Some of these factors include:

- Requirement changes
- Environment changes
- Errors or security breaches
- New equipment added or removed, and finally
- Improvements to the system

## Types of Software Maintenance

- Corrective
- Adaptive
- Perfective
- preventive
  - concerned with making changes that ensures the longevity of the software. This may include code optimizing, code restructuring, and documentation.



## Software Evolution Law

> According to Lehman's laws of software evolution, on the one side, the size and the complexity of a software system will continually increase in its life time; on the other side, the quality of a software system will decrease unless it is rigorously maintained and adapted.


### Classification of softwares

> static where specifications and solutions both are known, practical type are the ones where solutions and methods are to be worked upon, whereas in e types specifications as well as solutions and methods keep changing

Lehman has given laws for software evolution. He divided the software into three different categories:

- S-type (static-type) - This is a software, which works strictly according to defined specifications and solutions. The solution and the method to achieve it, both are immediately understood before coding. The s-type software is least subjected to changes hence this is the simplest of all. For example, calculator program for mathematical computation.
- P-type (practical-type) - This is a software with a collection of procedures. This is defined by exactly what procedures can do. In this software, the specifications can be described but the solution is not obvious instantly. For example, gaming software.
- E-type (embedded-type) - This software works closely as the requirement of real-world environment. This software has a high degree of evolution as there are various changes in laws, taxes etc. in the real world situations. For example, Online trading software.



#### E-Type software evolution
Lehman has given eight laws for E-Type software evolution -

- Continuing change - An E-type software system must continue to adapt to the real world changes, else it becomes progressively less useful.
- Increasing complexity - As an E-type software system evolves, its complexity tends to increase unless work is done to maintain or reduce it.
- Conservation of familiarity - The familiarity with the software or the knowledge about how it was developed, why was it developed in that particular manner etc. must be retained at any cost, to implement the changes in the system.
- Continuing growth- In order for an E-type system intended to resolve some business problem, its size of implementing the changes grows according to the lifestyle changes of the business.
- Reducing quality - An E-type software system declines in quality unless rigorously maintained and adapted to a changing operational environment.
- Feedback systems- The E-type software systems constitute multi-loop, multi-level feedback systems and must be treated as such to be successfully modified or improved.
- Self-regulation - E-type system evolution processes are self-regulating with the distribution of product and process measures close to normal.
- Organizational stability - The average effective global activity rate in an evolving E-type system is invariant over the lifetime of the product.

## SDLC


## Characteristics of good software

tested on the basis of following grounds:

- Operational
  - This tells us how well software works in operations.
    - Budget
    - Usability
    - Efficiency
    - Correctness
    - Functionality
    - Dependability
    - Security
    - Safety
- Transitional
  - This tells us how well software works when the software is moved from one platform to another
    - Portability
    - Interoperability
    - Reusability
    - Adaptability
- Maintenance
  - This aspect briefs about how well a software has the capabilities to maintain itself in the ever-changing environment
    - Modularity
    - Maintainability
    - Flexibility
    - Scalability

## SDLC
Software Development Life Cycle, SDLC for short, is a well-defined, structured sequence of stages in software engineering to develop the intended software product.
<br/>
Steps: [Key Processes in Software Engineering](#key-processes-in-software-engineering)

## Process Models

### Waterfall Model

> all the phases of SDLC will function one after another in linear manner

![1](static/images/1.png)

### Iterative Model

This model leads the software development process in iterations. It projects the process of development in cyclic manner repeating every step after every cycle of SDLC process.

![2](static/images/2.png)

The software is first developed on very small scale and all the steps are followed which are taken into consideration. Then, on every next iteration, more features and modules are designed, coded, tested and added to the software. Every cycle produces a software, which is complete in itself and has more features and capabilities than that of the previous one.

> a cycle includes small portion of whole software process


### Spiral Model

Spiral model is a combination of both, iterative model and one of the SDLC model

![3](static/images/3.png)

### V-Model

The major drawback of waterfall model is we move to the next stage only when the previous one is finished and there was no chance to go back if something is found wrong in later stages. V-Model provides means of testing of software at each stage in reverse manner.

![4](static/images/4.png)

### Big Bang Model

This model is the simplest model in its form. It requires little planning, lots of programming and lots of funds. This model is conceptualized around the big bang of universe. As scientists say that after big bang lots of galaxies, planets and stars evolved just as an event. Likewise, if we put together lots of programming and funds, you may achieve the best software product.

![5](static/images/5.png)

For this model, very small amount of planning is required. It does not follow any process, or at times the customer is not sure about the requirements and future needs. So the input requirements are arbitrary.

## Project Management

### Risks

- Experienced staff leaving the project and new staff coming in.
- Change in organizational management.
- Requirement change or misinterpreting requirement.
- Under-estimation of required time and resources.
- Technological changes, environmental changes, business competition.

### Risk Management Process

There are following activities involved in risk management process:

- Identify - Make note of all possible risks, which may occur in the project.
- Categorize - Categorize known risks into high, medium and low risk intensity as per their possible impact on the project.
- Manage - Analyze the probability of occurrence of risks at various phases. Make plan to avoid or face risks. Attempt to minimize their side-effects.
- Monitor - Closely monitor the potential risks and their early symptoms. Also monitor the effects of steps taken to mitigate or avoid them.

### Project Monitoring

- Activity Monitoring - All activities scheduled within some task can be monitored on day-to-day basis. When all activities in a task are completed, it is considered as complete.
- Status Reports - The reports contain status of activities and tasks completed within a given time frame, generally a week. Status can be marked as finished, pending or work-in-progress etc.
- Milestones Checklist - Every project is divided into multiple phases where major tasks are performed (milestones) based on the phases of SDLC. This milestone checklist is prepared once every few weeks and reports the status of milestones.

### Communication

Communication can be oral or written. Communication management process may have the following steps:



- Planning - This step includes the identifications of all the stakeholders in the project and the mode of communication among them. It also considers if any additional communication facilities are required.
- Sharing - After determining various aspects of planning, manager focuses on sharing correct information with the correct person on correct time. This keeps every one involved the project up to date with project progress and its status.
- Feedback - Project managers use various measures and feedback mechanism and create status and performance reports. This mechanism ensures that input from various stakeholders is coming to the project manager as their feedback.
- Closure - At the end of each major event, end of a phase of SDLC or end of the project itself, administrative closure is formally announced to update every stakeholder by sending email, by distributing a hardcopy of document or by other mean of effective communication.
  

###  Project Management Tools

#### Gantt Chart

It is a horizontal bar chart with bars representing activities and time scheduled for the project activities.

![6](static/images/6.png)

#### PERT Chart

PERT (Program Evaluation & Review Technique) chart is a tool that depicts project as network diagram. It is capable of graphically representing main events of project in both parallel and consecutive way. Events, which occur one after another, show dependency of the later event over the previous one.

![7](static/images/7.png)

#### Resource Histogram

This is a graphical tool that contains bar or chart representing number of resources (usually skilled staff) required over time for a project event (or phase). Resource Histogram is an effective tool for staff planning and coordination.

![8](static/images/8.png)
![9](static/images/9.png)


### Critical Path Analysis

This tools is useful in recognizing interdependent tasks in the project. It also helps to find out the shortest path or critical path to complete the project successfully. Like PERT diagram, each event is allotted a specific time frame. This tool shows dependency of event assuming an event can proceed to next only if the previous one is completed.

The events are arranged according to their earliest possible start time. Path between start and end node is critical path which cannot be further reduced and all events require to be executed in same order.



## Crash-Review
- What is Software Engineering?
- Phase 1 - Requirements Gathering & Analysis
  - Requirements Gathering Techniques
    - Use Case Analysis
    - User Stories
  - Requirements Analysis
  - Prototyping
- Phase 2 - Program Design & Planning
  - Modularization of Program
  - Coupling and Cohesion
  - Example: Coupling and Cohesion
  - Separation of Concerns: Benefits of a good design
- Phase 3 - Program Development
  - Programming Patterns
    - Example: Model-View-Controller (MVC) Pattern
    - Application of MVC
  - Code Readability
    - Example: Constants vs Magic Numbers
    - Example: Standardized Naming Conventions
  - Revision Control Systems (Git, Github)
- Phase 4 - Program Testing
  - Automated Testing
    - Unit Testing
    - Integration Testing
    - Example: Integration Testing
  - Black vs Glass Box Testing
  - GUI Testing
  - Security Testing
  - Code Coverage
  - Test-Driven Development (TDD)

<!-- ## Continue here -->
<!-- https://www.tutorialspoint.com/software_engineering/software_requirements.htm -->