# What is DevOps
Devops requires a team of deveopment and operational engineer to manage the entire application development life cycle,i.e development ,testing,deployment and monitoring            It’s best to understand DevOps as a business drive to improve communication and collaboration among development and operations teams, in order to increase the speed and quality of software deployment. It’s a new way of working that has profound implications for teams and the organizations they work for.

# What is your understanding of a DevOps Culture in an Organization
** From the defination i stated above ,we understand that ***DevOps*** operations are in Stages like the devlopment stage testing,deployment and monitoring and each stages requires different skills and tools .For the life cycle of this operation to be succesufully achieved . ***DevOps*** organization came up with the practise to align their team,processess and tools to focus on it's goals which is to produce better and more relaiable product to the value of their customer.the heart of theis practise is called Devops culture .I will like to give a short defination of culture in an orgainization.Culture are practise or guideline that makes an organisation interaction .                             To be succesful in ***DevOps*** , it takes more than speeds,tools and a good skill set ,it takes a team of people that are willing to modify their regular work routine and behaviour patterns,they must be able to collaborate ,trust and take responsibility.This helps the organization communicate and collaborate effectively in an open way with different opinion.this helps the organization                                                                                                                                         ***DevOps*** entails shared responsibilities. Development and operations staff should both be responsible for the success or failure of a product. Developers are expected to do more than just build and hand off to operations — they are expected to share the responsibility of overseeing a product through the entire course of its lifetime, adopting a "you build it, you run it" mentality. They test and operate software and collaborate more with QA and IT Ops. When they understand the challenges faced by operations, they are more likely to simplify deployment and maintenance. Likewise, when operations understand the system’s business goals, they can work with developers to help define the operational needs of a system and adopt automation tools.                                                                                                                                      Autonomous teams are another important aspect of ***DevOps***. For the development and operations teams to collaborate effectively, they need to make decisions and implement changes without a cumbersome and lengthy approval process. This involves handing over trust to teams and establishing an environment where there is no fear of failure. These teams should have the right processes and tools in place to make decisions faster and easier, for each level of risk to the customer. **
# What does a DevOps Engineer do and what tools are available?
** To know what a devops engineer does , we need to know who  Devops engineers are  . DevOps team  consist of different proffesionals responsible for differnt element in a software development life cycle .There are two main roles in the team, we have the senior Devops engineer **who serves as the team leader , who architect and  plan the complete delivery process as well as which tools should be used** and the Devops engineers **who are resonsible for implementing and mainatining the entire process**.To answer the question, Devops engineer makes use of various tools to implement continuous integration and continuous deploment.Inother word ,Devops engineeer __PLAN,CODE,BUILD,TEST,DEPLOY,OPERATE and MONITOR__.                                                                                                                            
## TOOLS:                                                                                                                                                                           
* **Continuous Integration**:git,bitbucket,svn,usts 
* **Infrastructure Automation**:puppet,chef,ansible
* **Deployment Automation and orchestration**:jenkins,usts,octopus deploy
* **Container Concept**:lxd,docker 
* **Orchestration**:kubernates,mesos,swarm
* **Cloud**:aws,azure,googlecloud,openstack     

# Describe the Software development Life Cycle identifying where DevOps fit in 
** ***DevOps*** consist of various phasess such as *Continuous development*,*Continuous Integration*,*Continuous Testing*,*Continuous deployment*,*Continuous monitoring* constitute ***DevOps*** life cycle  .
* ## Continuous Development :

In the phase of development ,it involves the planning and coding of the software ,the planning deals with knowledge ,vision and the achitecture of the software.The developers begin with the writing of codes for the applicattion.The planning stgae does not require he use of tools but there are lot of toold for writing codes .The code can been writing with any slack depending on the requirement involves.The code is being mainteined using version control tools like git,svn,mercurial,cvsand jira.

* ## Continuous Testing :

This is the stage where the developed software is continuously tested for bugs. For Continuous testing, automation testing tools like Selenium, TestNG, JUnit, etc are used. These tools allow QAs to test multiple code-bases thoroughly in parallel to ensure that there are no flaws in the functionality. In this phase, Docker Containers can be used for simulating the test environment.
 Automation testing saves a lot of time, effort and labor for executing the tests instead of doing this manually. Besides that, report generation is a big plus. The task of evaluating the test cases that failed in a test suite gets simpler. We can also schedule the execution of the test cases at predefined times. After testing, the code is continuously integrated with the existing code.

* ## Continuous Integration :

This stage is the heart of the entire DevOps life cycle. It is a software development practice in which the developers require to commit changes to the source code more frequently. This may be on a daily or a weekly basis. Every commit is then built and this allows early detection of problems if they are present. Building code not only involves compilation but it also includes code review, unit testing, integration testing, and packaging.
* ## Continuous Deployment :

This is the stage where the code is deployed to the production servers. It is also important to ensure that the code is correctly deployed on all the servers. Before moving on, let us try to understand a few things about Configuration management and Containerization tools. These set of tools here help in achieving Continuous Deployment (CD).

* ## Continuous Monitoring :

Configuration Management is the act of establishing and maintaining consistency in an application’s functional requirements and performance. Let me put this in simpler words, it is the act of releasing deployments to servers, scheduling updates on all servers and most importantly keeping the configurations consistent across all the servers.

# What are the DevOps best practices?
** ***Devops*** best practices for implementation focuses on Agile project management .In this approach to project management and sofware development ,it helps team render value to their customer faster without stress .The best practice to this are as follows:
* Build with the right tools
* Implement automation
* Monitor the Devops pipeline and application
* Observability
* Gather contineous feedback
* Change culture

# What is the difference between a DevOps engineer and SRE engineer?
** DevOps Engineers are ops-focused engineers who solve development pipeline problems. Site Reliability Engineers are development-focused engineers who solve operational/scale/reliability problems.
