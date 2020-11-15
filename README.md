# Interview Preparation 
****S - Situation****   
****T - Task****   
****A - Action****   
****R - Result****
## Agile and SCRUM  
***Think about: What are the 3 amigos, personas,information Radiators, scrum artifacts, scrum events, scrum roles, sprint review and sprint retrospective, Starfish retrospective, Root cause analysis-part of retrospective, agile values and principles, user story, epic etc.***

### What is Agile? 
Agile is an iterative methodology utilised for software design and development. It is defined by 4 values which are: 
* Individuals and Interaction over processes and tools – Promoting team cohesion.
* Working software over comprehensive documentation – Focussing upon the building and testing rather than creating large documents. This is reflected in the practice of creating Epics and User Stories which typically summarise tasks on a single sticky note, as opposed to swathes of documentation.
* Customer collaboration over contract negotiation – Involving the customer in the process.
* Responding to change over following a plan – Being flexible and adaptable.

### What is Scrum? What are scrum roles, artifacts, and events?
Scrum is a framework used to implement an agile methodology. Scrum is designed to be more reflective of the people and the organisation therefore is typically more flexible to meet the ever-changing needs and complexities of projects. It is for this reason, scrum replaces many traditional algorithmic frameworks which tend to prioritise efficiency over value. The defining elements of scrum are its roles artifacts and ceremonies. In terms of roles, there are 3:
1. Product Owner - They represent the customers and stakeholders and a responsible for driving the product backlog. This is an ordered, dynamic list of everything that is to be completed during the course of the project.
2. Scrum Master - The leader of the scrum, responsible for making sure scrum is understood and implemented. They help the team understand the theory, practices and rules associated with Scrum.
3. Development Team – A self-organising and cross-functional team with no titles or sub-teams. The development team is responsible for accomplishing the tasks set out in the product backlog.
Scrum ceremonies include:
* **Sprint Planning Meeting** – This meeting is to discuss the overall project objective and ask questions such as “What are we going to work on and how are we going to do it?”. This information is then broken down into smaller increments which can be complemented in a sprint. The team will identify what tasks they wish to complete in the forthcoming sprint. The workload is typically sufficient for two days of work.
* **Daily Scrum** – This is a daily meeting, typically time-boxed to 15 minutes. It is organised by the scrum master. Typical questions will include ‘What has been done on the previous day?’ and ‘What needs to be done today?’. The aim of this is to ensure transparency as to what each team member has done and synchronise teamwork.
* **Sprint review** - This is conducted at the end of each sprint and stakeholders are invited to collectively review the sprint which has just been completed. The aim is to gain feedback and evaluate whether the increment has been delivered to meet the definition of done. Thus, questions would pertain to ‘what has been completed during this sprint?’ Feedback is then put back into the product backlog.
* **Sprint retrospective** – This ceremony occurs after the completion of a sprint and is typically time-boxed to 90 minutes. It allows the team to evaluate how well they worked and build a plan for improvement. Questions asked include, ‘What went well?’, ‘What did not go well?’, and ‘What can be improved?’.   

The Scrum ceremonies are designed to incorporate the values of agile, by creating an atmosphere which promotes collaboration through daily scrum, transparency via sprint backlogs ceremonies such as the sprint planning meeting and sprint review, which allows stakeholders to attend and review alongside the development team. The sprint retrospective promotes continuous improvement which is another agile principle.

The final factor of scrum are artifacts. Artifacts enable the scrum team and stakeholders to understand the development of the product and identify what tasks have been completed and what is yet to be completed. There are 3 main artifacts. These are:  
* **Product Backlog – This is an ordered list of everything that is to be completed in a project. This includes features, functions tests and requirements of the product. This list is dynamic therefore constantly evolving throughout the project.
* **Sprint Backlog** – The sprint backlog contains everything that is to be completed in ag given sprint as well as a plan for delivering the increment.
* **Increment** – This is the sums of all the product backlog item completed during the sprint, and all previous sprints. The increment must meet the ‘Definition of Done’ (DOD) at the end of a sprint. The Definition of Done is a predefined acceptance criterion which each product backlog item must meet. Theoretically each increment should be potentially releasable if it has met the DOD. 
Tools such as Trello, Jira, monday.com and more can be used for practical implementation of scrum. I have experiences in using Trello for the purposes of projects. One such example is a small project in which i was tasked with the creation of a bread_factory using Object Oriented Programming. The Trello board can be configured to create separate columns for the product backlog, sprint backlog and a done column to represent the increment. In order to complete the task, a set of user stories were created to represent the requirements. These guided the functions and classes created in the Python programme. The result was a python program which satisfied the user stories and also utilised Test Driven Development to ensure the program worked as one would expect. 

### What are the differences between Agile and Scrum? / How are the two related?
Agile is a methodology used in software development. Iteration lies at the heart of the Agile methodology. Meanwhile, scrum is a framework used to implement agile. Other frameworks include Kanban which is a more relaxed framework but still has agile values such as communication and transparency at the core. I have experienced using scrum for the purposes of small projects. One such example is  

### What are the 3 amigos
The 3 amigos refer to a practice in Agile wherein the aim is to bridge departments in the company. This allows for a more holistic Definition of Done. The 3 amigos are typically:
* The Business Analyst – They make sure everyone understands the user stories and has the same expectations.
* Developers – They are responsible for requirements so will discuss their understanding of these.
* Tester – They will try to find edge cases to enhance the testing process.

### What is Persona?
A person is a fictitious biography of a potential user of a product. They are typically visual and represent a certain category of user i.e. seniors, children etc. Contents may cover aspects such as age, gender and profession. The aim of a person is not to have a designer or developer cater to every category but provide an anchor to justify design decisions. 

### V model, Agile, Waterfall. What are the differences between them?
Systems V, Agile, and Waterfall are all methodologies used for design and development of products. The waterfall method follows a logical progression therefore stages are executed one after another. The Systems V also follows a similar approach of logical progression however it is more modern. The third type is agile which combines design, development and testing and iterates upon this through the course of the project lifecycle. I have experience in utilising both agile and the v-model. During university, I utilised the Systems-V model for several projects. One such example was a group project in my final year wherein the team was tasked with designing and manufacturing an unmanned aerial vehicle. We utilised Microsoft Project to create a Gantt Chart as a framework for implementing the model. This enabled us to define each stage of the project and break into smaller steps. Milestones were a key defining factor used to determine whether a key stage had been completed. Due to the nature of the systems model, one cannot move onto subsequent stages without completing prior stages. This was problematic as we were unable to complete the original scope fof the projet due to the onset of the pandemic which meant we were unable to access university facilities. Despite this, we pulled through as a team and altered our scope such that project completion would be feasible in a remote environment. As a result, we were able to complete project documentation and submit our final portfolio. Team members were marked on an individual basis and I was able to achieve a first class for this module. 

## SQL 
### What is a foreign key
A foreign key is used to link two tables together via referring to the primary key of one table. The purpose of this is to ensure consistency throughout the related tables. It is all too common to make simple spelling errors which would prevent the link from being formed. Using a foreign key ensures the data in the linking columns matches exactly. 
### What is DML, DDL, etc?
Operations which can be performed on a database are typically categorised into 4 categories relating to the type of action being performed:
* DDL - Data Definition Language - Actions includeCREATE, ALTER, DROP, TRUNCATE, RENAME
* DML- Data Manipulation Language - INSERT, UPDATE, DELETE, MERGE, CALL
* DQL - Data Query Language - SELECT
* DCL - Data Control Language - GRANT, REVOKE
I have experience in using these actions to create tables and query within the northwind database which is the default database within Microsoft Azure. One task I was asked to complete was CRUD a database within Python and then import data from a csv file. This task entailed creating a table within the database, importing data and allowing users to query via a specific search criterion, in this case, movie name. Users, could also implement DML and update the table with their own inputs. The result of this task was a functioning movie table which users could access within python. 


## Python
### What is OOP and what are the 4 pillars? Give an example of how you implemented OOP
OOP is an acronym for Object Oriented Programming.
The 4 pillars are:
1. Inheritance 
2. Encapsulation
3. Abstraction
4. Polymorphism  
The purpose of OOP is to prevent developers from rewriting a piece of code that already exists.We wish to automate routine tasks. In OOP, classes are used to represent concepts and objects are used to create instances of classes. OOP lies at the heart of Python with almost every thing being an object, from strings to dictionaries. Classes consist of attributes and methods. Attributes are the associated characteristics while methods are the associated functions. 
I have used OOP for several projects. One such example was a scrabble score calculator which could take an input and calculate the score the word would receive in a game of scrabble. Classes were used to define the score categories i.e one point letters, two points letters etc. Then simple control flow was used to determine the letters in the input and assign the relevant score. As a result, score categories could be assigned in one class and imported whenever required. 


## DevOps
### What is DevOps?
DevOps bridges the gap between development and operations teams enabling them to work closer together, share responsibility, deploy infrastructure as a code, and automate the pipeline.
Development team builds products which they will deploy to  development environment where they can check integration as well as other aspects. Developers are responsible for new product features, bug fixes, security updates and code refactoring. 
The issues lies in the fact that development environments do not fully reflect the production environment therein leading to errors and warnings.Meanwhile, operations teams are responsible for managing services, ensuring services and products are running correctly, monitoring, and growing capacity as per product or company needs. Similar to development, team operations teams face errors when deploying. Prior to the formation of DevOps, the two teams worked separately facing a lot of errors and not enough speed. The main facet of DevOps is to break these silos down and have the two work much closer together, share responsibilities, deploy infrastructure as a code, and automate the pipeline.
This leads to greater efficiency, provided they are supported by good engineering practices. These are continuous integration, continuous delivery, and continuous deployment CI/CD. 
Continuous Integration - We have development team building products, writing tests and storing code in a source control system for collaborative purposes. 
Continuous delivery -The next step is to  engage with the operations team and deploy onto on-premise or on the cloud utilising infrastructure as a code. Continuous Integration is also maintained by using GitHub for version control and collaboration. Also, at this stage, a CI/CD server can be introduced to automatically monitor changes to the GitHub and run as required. Once tests have been passed, we move to a pre-production environment and conduct the same tests to ensure quality throughout.  
Continuous Deployment - Combining the previous practices and running tests all the way through to production.
Ultimately, this leads to faster time to market, improved team collaboration, continuous release cycles, automate, scalable environments, and increased quality due to automated testing

### Why did you choose DevOps?
I do not have the conventional background as i completed a masters degree in aerospace engineering. Upon completion of my degree, i attended a 12-week academy wherein i was introduced to the technology sector, in particular emerging technologies in Industry 4.0. This was something which piqued my interest because I have always been fascinated with future technologies and the potential they have for improving modern life. More-so, the academy led me to broadening my horizons and searching for career opportunities outside the field of aerospace engineering. During my time at the academy, I was fortunate enough to be given the opportunity to take my AWS Certified Cloud Practitioners exam. This proved a critical learning opportunity as i did initially struggle with the qualification. I found that despite having revised the content, I was struggling to answer the exam questions. Although disheartening, I continued to spend time practicing exam questions and was able to pass the exam with relative ease the first time. Thus, despite the setbacks, i worked hard and focussed on my goals and was able to achieve them. I was very pleased to have passed and it gave me encouragement that I needed to really start pursuing a career in the tech industry. I was drawn to DevOps as it utilised technologies which i had some familiarity with such as cloud computing therefore i felt it would be best as I had some foundations which i could build upon.  




