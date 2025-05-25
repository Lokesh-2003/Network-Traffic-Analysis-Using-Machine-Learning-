
Network Traffic Classification Analysis Using Machine Learning Algorithms

1   INTRODUCTION 

The Network Traffic Classification plays a dynamic role pertaining to threats associated with the emerging technology nowadays. The various machine learning based classification techniques are presented. It helps internet service providers to manage overall performance of the network by considering the factors associated with certain application protocol. It has its usage in recognizing the unknown network if any tries to intrude the specified traffic lane. By this way we get to study its properties as well. Using the above property of recognizing unknown network, one can also recognize the potential threats that a network can suffer due to certain security attacks. Management of network security and Quality of Service (QoS) is also essential task and can be achieved if we have good techniques to classify network. Blocking or allowance of certain network traffic can also be achieved if we classify our network well. Overall, classification of network helps in overall growth of the network and its efficiency. 
Over the past decades many network classification techniques had evolved and have been able to classify network traffic. Initially Port based technique was used to classify traffic and was characterized by the fact that it used ports to classify each network. It was a great technique initially. The port-based classification technique is used in  for results analysis. It worked on the fact that all the ports were registered to Internet Assign Number Authority (IANA) and then was used to classify them. But it started failing due to the facts that some of the ports were not registered on IANA platforms and was also not suitable for the dynamic ports. A short review for Internet traffic classification is also presented in. Thereafter, the results analysis for various machine learning algorithms is studied. The Internet traffic by introducing Denial of service (DoS) attacks is analyzed  while authors of  have developed a new machine learning based model for calculation of documents ranking. 
The second technique that come into existence is Payload based technique in which packets of the associated networks are used to analysis and according to them protocol is identified. This technique is known as Deep Packet Inspection technique due to the fact that it uses packets for analysis. This technique is failed primarily due to the fact that it requires costly hardware installations and this does not work well for the packets that are encrypted. These drawbacks give the way to machine learning technique that has been using nowadays due to its efficiency of the results and similarity with the practical facts. In this technique, labeled classes are turned to model and then are trained and tested to check the correctness using accuracy. 
The Contributions of the paper are explained as follows. We initially discuss the different techniques and then we employ machine learning techniques to network data set and do a comparative analysis on different algorithm on which one is best suited to analyze the network traffic. We collect the features using Wireshark tool and then we convert this data to csv file format then train and test using Python Libraries which help to predict and further the comparative analysis is carried out. We employ Decision Tree (DT), Naïve Bayes (NB), K-nearest neighbor (KNN), and Support Vector Machine (SVM) techniques. We find that KNN Technique outperforms for this application.
Objective of the project: 
In the world of networking, it sometimes becomes essential to know what types of applications flow through the network for performance of certain tasks. Network traffic classification sees its main usage among ISP’s to analyze the characteristics required to design the network and hence affects the overall performance of a network. There are various techniques adopted to classify network protocols, such as port-based, pay-load based and Machine Learning based, all of them have their own pros and cons. Prominent nowadays is Machine Learning technique due to its vastness in usage in other fields and growing knowledge among researchers of its better accuracy among others when compared. In this paper, we compare two of the basic algorithms, Naïve Bayes and K nearest algorithm results when employed to networking data set extracted from live video feed using Wireshark software. For an implementation of Machine learning algorithm, python sklearn library is used with numpy and pandas library used as helper libraries. Finally, we observe that K nearest algorithm gives more accurate prediction than Naïve Bayes Algorithm, Decision Tree Algorithm and Support Vector Machine.
¬¬¬2. LITERATURE SURVEY
A survey of techniques for internet traffic classification using machine learning
The research community has begun looking for IP traffic classification techniques that do not rely on `well known' TCP or UDP port numbers, or interpreting the contents of packet payloads. New work is emerging on the use of statistical traffic characteristics to assist in the identification and classification process. This survey paper looks at emerging research into the application of Machine Learning (ML) techniques to IP traffic classification - an inter-disciplinary blend of IP networking and data mining techniques. We provide context and motivation for the application of ML techniques to IP traffic classification, and review 18 significant works that cover the dominant period from 2004 to early 2007. These works are categorized and reviewed according to their choice of ML strategies and primary contributions to the literature. We also discuss a number of key requirements for the employment of ML-based traffic classifiers in operational IP networks, and qualitatively critique the extent to which the reviewed works meet these requirements. Open issues and challenges in the field are also discussed.

Network Traffic Classification techniques and comparative analysis using Machine Learning algorithms
Network Traffic Classification is a central topic nowadays in the field of computer science. It is a very essential task for Internet service providers (ISPs) to know which types of network applications flow in a network. Network Traffic Classification is the first step to analyze and identify different types of applications flowing in a network. Through this technique, internet service providers or network operators can manage the overall performance of a network. There are many methods traditional technique to classify internet traffic like Port Based, Pay Load Based and Machine Learning Based technique. The most common technique used these days is Machine Learning (ML) technique. Which is used by many researchers and got very effective accuracy results. In this paper, we discuss network traffic classification techniques step by step and real time internet data set is develop using network traffic capture tool, after that feature extraction tool is use to extract features from the capture traffic and then four machine learning classifiers Support Vector Machine, C4.5 decision tree, Naïve Bays and Bayes Net classifiers are applied. Experimental analysis shows that C4.5 classifiers gives very good accuracy result as compare to other classifies.

On different ways to classify Internet traffic
Traffic classification is an important tool for network management. It reveals the source of observed network traffic and has many potential applications in Quality of Service, network security, traffic visualization, and more. In the last decade, traffic classification evolved quickly due to the raise of peer-to-peer traffic. Nowadays, researchers still find new methods in order to withstand the rapid changes in the Internet. In this paper, we review 13 papers on traffic classification and related topics that were published during 2009-2012. We show diversity in recent algorithms and we highlight possible directions for the future research on traffic classification: relevance of multi-level classification, importance of experimental validation, and the need for common traffic datasets.

Comparative analysis of five machine learning algorithms for IP traffic classification
With rapid increase in internet traffic over last few years due to the use of variety of internet applications, the area of IP traffic classification becomes very significant from the point of view of various internet service providers and other governmental and private organizations. Now days, traditional IP traffic classification techniques such as port number based and payload based direct packet inspection techniques are seldom used because of use of dynamic port number instead of well-known port number in packet headers and various encryption techniques which inhibit inspection of packet payload. Current trends are use of machine learning (ML) techniques for this classification. In this research paper, real time internet traffic dataset has been developed using packet capturing tool and then using attribute selection algorithms, a reduced feature dataset has been developed. After that, five ML algorithms MLP, RBF, C4.5, Bayes Net and Naïve Bayes are used for IP traffic classification with these datasets. This experimental analysis shows that Bayes Net and C4.5 are effective ML techniques for IP traffic classification with accuracy in the range of 94 %.


Research of Decision Tree Classification Algorithm in Data Mining 
Decision tree algorithm is one of the most important classification measures in data mining. Decision tree classifier as one type of classifier is a flow- chart like tree structure, where each intenal node denotes a test on an attribute, each branch represents an outcome of the test, and each leaf node represents a class. The method that a decision tree model is used to classify a record is to find a path that from root to leaf by measuring the attributes test, and the attribute on the leaf is classification result.

A Naïve Bayesian Classifier for Educational Qualification
Manual classification of the individuals into different categories based on their educational qualification is a tedious task and it may vary respective to the considered scenario. This paper proposes a classification methodology utilizing the benchmark Naïve Bayesian classification algorithm for the classification of persons into different classes based on several attributes representing their educational qualification. The experimental results are appreciable indicating that the proposed classification method can be a promising one and can be applied elsewhere. The proposed method has been experimentally verified to be 90% accurate with a high kappa value thus proving its efficiency. This classification methodology can reduce the mundane manual labor and can easily assist in categorization.

Data classification using support vector machine
Classification is one of the most important tasks for different application such as text categorization, tone recognition, image classification, micro-array gene expression, proteins structure predictions, data Classification etc. Most of the existing supervised classification methods are based on traditional statistics, which can provide ideal results when sample size is tending to infinity. However, only finite samples can be acquired in practice. In this paper, a novel learning method, Support Vector Machine (SVM), is applied on different data (Diabetes data, Heart Data, Satellite Data and Shuttle data) which have two or multi class. SVM, a powerful machine method developed from statistical learning and has made significant achievement in some field. Introduced in the early 90's, they led to an explosion of interest in machine learning. The foundations of SVM have been developed by Vapnik and are gaining popularity in field of machine learning due to many attractive features and promising empirical performance. SVM method does not suffer the limitations of data dimensionality and limited samples. In our experiment, the support vectors, which are critical for classification, are obtained by learning from the training samples. In this paper we have shown the comparative results using different kernel functions for all data samples

The detection method of low-rate DoS attack based on multi-feature fusion
As a new type of Denial of Service (DoS) attacks, the Low-rate Denial of Service (LDoS) attacks make the traditional method of detecting Distributed Denial of Service Attack (DDoS) attacks useless due to the characteristics of a low average rate and concealment. With features extracted from the network traffic, a new detection approach based on multi-feature fusion is proposed to solve the problem in this paper. An attack feature set containing the Acknowledge character(ACK) sequence number, the packet size, and the queue length is used to classify normal and LDoS attack traffics. Each feature is digitalized and preprocessed to fit the input of the K-Nearest Neighbor (KNN) classifier separately, and to obtain the decision contour matrix. Then a posteriori probability in the matrix is fused, and the fusion decision index D is used as the basis of detecting the LDoS attacks. Experiments proved that the detection rate of the multi-feature fusion algorithm is higher than those of the single-based detection method and other algorithms.

Documents ranking using new learning approach
Aim of document similarity is to retrieve the list of ranked documents based on a query document. In the literature, it has been shown that document similarity method first compute similarity scores between the query and the documents based on a score function. Thereafter, documents are ranked according to their similarity scores. In the literature, TextTiling algorithm shown was basically done in three stages: tokenization into sentence-sized units, score calculation and detecting the boundaries of the subtopic. In this paper, we have evaluated two different approaches for documents ranking and further we checked this achieved results with other approach based on machine learning Firstly, Documents are ranked based on standard score calculation i.e using the tf-idf concept. Secondly, Documents are ranked based on Textiling approach. TextTiles have already been integrated into a user interface in an information retrieval system and have been used successfully for segmenting Arabic newspaper texts, which have no paragraph breaks, for information retrieval. Textiling is a far better technique than the standard score calculation when we try to summarize the documents. This helps in the improving the retrieval performance of the system. In this paper, we have shown the comparative analysis of two approaches. Further, we also tried to incorporate the statistically machine learning approach in our results, for handling a broad range of problems in information retrieval (IR).

Throughput analysis of AQM schemes under low-rate Denial of service attacks
Active Queue Management (AQM) scheme aims to achieve low loss rate and high throughput as well as high link utilization. We have tried to study the throughput for AQM schemes under denial-of-service (DoS) attacks. DoS is a very serious threat which degrade the TCP throughput in the Internet. DoS attacks consume resources such as network bandwidth, server CPU cycles, and server interrupt processing capacity. In this paper, we have presented a comparative performance analysis of existing AQM schemes under DoS attacks. We find RED achieved good performance even DoS attacks is permitted.




3 .SYSTEM ANALYSIS
3.1 Existing System

Over the past decades many network classification techniques had evolved and have been able to classify network traffic. Initially Port based technique was used to classify traffic and was characterized by the fact that it used ports to classify each network. It was a great technique initially. The port-based classification technique is used in for results analysis. It worked on the fact that all the ports were registered to Internet Assign Number Authority (IANA) and then was used to classify them. But it started failing due to the facts that some of the ports were not registered on IANA platforms and was also not suitable for the dynamic ports.
Disadvantages
1.Less accuracy
3.2 PROPOSED SYSTEM

We initially discuss the different techniques and then we employ machine learning techniques to network data set and do a comparative analysis on different algorithm on which one is best suited to analyze the network traffic. We collect the features using Wireshark tool and then we convert this data to csv file format then train and test using Python Libraries which help to predict and further the comparative analysis is carried out. We employ Decision Tree (DT), Naïve Bayes (NB), K-nearest neighbor (KNN), and Support Vector Machine (SVM) techniques. We find that KNN Technique outperforms for this application.
Advantages
1.High accuracy
Modules: 
To implement this project we have designed following modules
Upload Network Traffic Dataset: using this module we will upload dataset to application
Data Preprocessing: using this module we will clean dataset by removing missing values and ML algorithms will not take characters values so we need to process dataset to convert all non-numeric characters to numeric characters by assigning integer ID to each unique string data. After processing we will split dataset into train and test where 80% dataset will be used for training and 20% for testing
Run KNN Algorithm: using above train data we will train KNN algorithm and this trained model will be applied on test data to predict traffic type and then calculate accuracy of correct prediction
Run Naive Bayes Algorithm: using above train data we will train Naïve Bayes algorithm and this trained model will be applied on test data to predict traffic type and then calculate accuracy of correct prediction
Run Decision Tree Algorithm: using above train data we will train Decision tree algorithm and this trained model will be applied on test data to predict traffic type and then calculate accuracy of correct prediction
Run SVM Algorithm: using above train data we will train SVM algorithm and this trained model will be applied on test data to predict traffic type and then calculate accuracy of correct prediction
Comparison Graph: using this module we will show accuracy graph between all algorithms

3.3. PROCESS MODEL USED WITH JUSTIFICATION
SDLC (Umbrella Model):
  
SDLC is nothing but Software Development Life Cycle. It is a standard which is used by software industry to develop good software.
Stages in SDLC:
•	Requirement Gathering
•	Analysis 
•	Designing
•	Coding
•	Testing
•	Maintenance
Requirements Gathering stage:
The requirements gathering process takes as its input the goals identified in the high-level requirements section of the project plan. Each goal will be refined into a set of one or more requirements. These requirements define the major functions of the intended application, define operational data areas and reference data areas, and define the initial data entities. Major functions include critical processes to be managed, as well as mission critical inputs, outputs and reports. A user class hierarchy is developed and associated with these major functions, data areas, and data entities. Each of these definitions is termed a Requirement. Requirements are identified by unique requirement identifiers and, at minimum, contain a requirement title and textual description.
 
These requirements are fully described in the primary deliverables for this stage: the Requirements Document and the Requirements Traceability Matrix (RTM). The requirements document contains complete descriptions of each requirement, including diagrams and references to external documents as necessary. Note that detailed listings of database tables and fields are not included in the requirements document.
The title of each requirement is also placed into the first version of the RTM, along with the title of each goal from the project plan. The purpose of the RTM is to show that the product components developed during each stage of the software development lifecycle are formally connected to the components developed in prior stages.
In the requirements stage, the RTM consists of a list of high-level requirements, or goals, by title, with a listing of associated requirements for each goal, listed by requirement title. In this hierarchical listing, the RTM shows that each requirement developed during this stage is formally linked to a specific product goal. In this format, each requirement can be traced to a specific product goal, hence the term requirements traceability.
The outputs of the requirements definition stage include the requirements document, the RTM, and an updated project plan.
•	Feasibility study is all about identification of problems in a project.
•	No. of staff required to handle a project is represented as Team Formation, in this case only modules are individual tasks will be assigned to employees who are working for that project.
•	Project Specifications are all about representing of various possible inputs submitting to the server and corresponding outputs along with reports maintained by administrator.
Analysis Stage:
The planning stage establishes a bird's eye view of the intended software product, and uses this to establish the basic project structure, evaluate feasibility and risks associated with the project, and describe appropriate management and technical approaches.
 
The most critical section of the project plan is a listing of high-level product requirements, also referred to as goals. All of the software product requirements to be developed during the requirements definition stage flow from one or more of these goals. The minimum information for each goal consists of a title and textual description, although additional information and references to external documents may be included. The outputs of the project planning stage are the configuration management plan, the quality assurance plan, and the project plan and schedule, with a detailed listing of scheduled activities for the upcoming Requirements stage, and high level estimates of effort for the out stages.
Designing Stage:
The design stage takes as its initial input the requirements identified in the approved requirements document. For each requirement, a set of one or more design elements will be produced as a result of interviews, workshops, and/or prototype efforts. Design elements describe the desired software features in detail, and generally include functional hierarchy diagrams, screen layout diagrams, tables of business rules, business process diagrams, pseudo code, and a complete entity-relationship diagram with a full data dictionary. These design elements are intended to describe the software in sufficient detail that skilled programmers may develop the software with minimal additional input.


When the design document is finalized and accepted, the RTM is updated to show that each design element is formally associated with a specific requirement. The outputs of the design stage are the design document, an updated RTM, and an updated project plan.
Development (Coding) Stage:	
The development stage takes as its primary input the design elements described in the approved design document. For each design element, a set of one or more software artifacts will be produced. Software artifacts include but are not limited to menus, dialogs, and data management forms, data reporting formats, and specialized procedures and functions. Appropriate test cases will be developed for each set of functionally related software artifacts, and an online help system will be developed to guide users in their interactions with the software.
 

The RTM will be updated to show that each developed artifact is linked to a specific design element, and that each developed artifact has one or more corresponding test case items. At this point, the RTM is in its final configuration. The outputs of the development stage include a fully functional set of software that satisfies the requirements and design elements previously documented, an online help system that describes the operation of the software, an implementation map that identifies the primary code entry points for all major system functions, a test plan that describes the test cases to be used to validate the correctness and completeness of the software, an updated RTM, and an updated project plan.


Integration & Test Stage:
During the integration and test stage, the software artifacts, online help, and test data are migrated from the development environment to a separate test environment. At this point, all test cases are run to verify the correctness and completeness of the software. Successful execution of the test suite confirms a robust and complete migration capability. During this stage, reference data is finalized for production use and production users are identified and linked to their appropriate roles. The final reference data (or links to reference data source files) and production user list are compiled into the Production Initiation Plan.
           

The outputs of the integration and test stage include an integrated set of software, an online help system, an implementation map, a production initiation plan that describes reference data and production users, an acceptance plan which contains the final suite of test cases, and an updated project plan.
•	Installation & Acceptance Test:
During the installation and acceptance stage, the software artefacts, online help, and initial production data are loaded onto the production server. At this point, all test cases are run to verify the correctness and completeness of the software. Successful execution of the test suite is a prerequisite to acceptance of the software by the customer.
After customer personnel have verified that the initial production data load is correct and the test suite has been executed with satisfactory results, the customer formally accepts the delivery of the software.
 
The primary outputs of the installation and acceptance stage include a production application, a completed acceptance test suite, and a memorandum of customer acceptance of the software. Finally, the PDR enters the last of the actual labour data into the project schedule and locks the project as a permanent project record. At this point the PDR "locks" the project by archiving all software items, the implementation map, the source code, and the documentation for future reference.
Maintenance:
Outer rectangle represents maintenance of a project, Maintenance team will start with requirement study, understanding of documentation later employees will be assigned work and they will undergo training on that particular assigned category. For this life cycle there is no end, it will be continued so on like an umbrella (no ending point to umbrella sticks).
3.4. Software Requirement Specification 
 3.4.1. Overall Description
A Software Requirements Specification (SRS) – a requirements specification for a software system  is a complete description of the behaviour of a system to be developed. It includes a set of use cases that describe all the interactions the users will have with the software. In addition to use cases, the SRS also contains non-functional requirements. Non-functional requirements are requirements which impose constraints on the design or implementation (such as performance engineering requirements, quality standards, or design constraints). 
System requirements specification: A structured collection of information that embodies the requirements of a system. A business analyst, sometimes titled system analyst, is responsible for analyzing the business needs of their clients and stakeholders to help identify business problems and propose solutions. Within the systems development lifecycle domain, the BA typically performs a liaison function between the business side of an enterprise and the information technology department or external service providers. Projects are subject to three sorts of requirements:
•	Business requirements describe in business terms what must be delivered or accomplished to provide value.
•	Product requirements describe properties of a system or product (which could be one of several ways to accomplish a set of business requirements.)
•	Process requirements describe activities performed by the developing organization. For instance, process requirements could specify .Preliminary investigation examine project feasibility, the likelihood the system will be useful to the organization. The main objective of the feasibility study is to test the Technical, Operational and Economical feasibility for adding new modules and debugging old running system. All system is feasible if they are unlimited resources and infinite time. There are aspects in the feasibility study portion of the preliminary investigation:		
•	ECONOMIC FEASIBILITY	
A system can be developed technically and that will be used if installed must still be a good investment for the organization. In the economical feasibility, the development cost in creating the system is evaluated against the ultimate benefit derived from the new systems. Financial benefits must equal or exceed the costs. The system is economically feasible. It does not require any addition hardware or software. Since the interface for this system is developed using the existing resources and technologies available at NIC, There is nominal expenditure and economical feasibility for certain.
•	  OPERATIONAL FEASIBILITY 	
Proposed projects are beneficial only if they can be turned out into information system. That will meet the organization’s operating requirements. Operational feasibility aspects of the project are to be taken as an important part of the project implementation. This system is targeted to be in accordance with the above-mentioned issues. Beforehand, the management issues and user requirements have been taken into consideration. So there is no question of resistance from the users that can undermine the possible application benefits. The well-planned design would ensure the optimal utilization of the computer resources and would help in the improvement of performance status.	
•	  TECHNICAL FEASIBILITY
Earlier no system existed to cater to the needs of ‘Secure Infrastructure Implementation System’. The current system developed is technically feasible. It is a web based user interface for audit workflow at NIC-CSD. Thus it provides an easy access to .the users. The database’s purpose is to create, establish and maintain a workflow among various entities in order to facilitate all concerned users in their various capacities or roles. Permission to the users would be granted based on the roles specified.  Therefore, it provides the technical guarantee of accuracy, reliability and security.
 3.4.2. External Interface Requirements
User Interface
The user interface of this system is a user friendly python Graphical User Interface.
Hardware Interfaces
The interaction between the user and the console is achieved through python capabilities. 
Software Interfaces
The required software is python.
Operating Environment
Windows XP.
HARDWARE REQUIREMENTS:
•	Processor			-	Pentium –IV
•	Speed				-    	1.1 Ghz
•	RAM				-    	256 MB(min)
•	Hard Disk			-   	20 GB
•	Key Board			-    	Standard Windows Keyboard
•	Mouse				-    	Two or Three Button Mouse
•	Monitor			-    	SVGA
SOFTWARE REQUIREMENTS:
•	Operating System		-	Windows7/8
•	Programming Language	-	Python 
4. SYSTEM DESIGN
UML Diagram:
Class Diagram:
The class diagram is the main building block of object oriented modeling. It is used both for general conceptual modeling of the systematic of the application, and for detailed modeling translating the models into programming code. Class diagrams can also be used for data modeling. The classes in a class diagram represent both the main objects, interactions in the application and the classes to be programmed. In the diagram, classes are represented with boxes which contain three parts:
•	The upper part holds the name of the class
•	The middle part contains the attributes of the class
•	The bottom part gives the methods or operations the class can take or undertake
Class Diagram:
 


Use case Diagram:
A use case diagram at its simplest is a representation of a user's interaction with the system and depicting the specifications of a use case. A use case diagram can portray the different types of users of a system and the various ways that they interact with the system. This type of diagram is typically used in conjunction with the textual use case and will often be accompanied by other types of diagrams as well.
 


Sequence diagram:
A sequence diagram is a kind of interaction diagram that shows how processes operate with one another and in what order. It is a construct of a Message Sequence Chart. A sequence diagram shows object interactions arranged in time sequence. It depicts the objects and classes involved in the scenario and the sequence of messages exchanged between the objects needed to carry out the functionality of the scenario. Sequence diagrams are typically associated with use case realizations in the Logical View of the system under development. Sequence diagrams are sometimes called event diagrams, event scenarios, and timing diagrams.
         


Collaboration diagram:
A collaboration diagram describes interactions among objects in terms of sequenced messages. Collaboration diagrams represent a combination of information taken from class, sequence, and use case diagrams describing both the static structure and dynamic behavior of a system.
  
 

Component Diagram:
In the Unified Modelling Language, a component diagram depicts how components are wired together to form larger components and or software systems. They are used to illustrate the structure of arbitrarily complex systems.
Components are wired together by using an assembly connector to connect the required interface of one component with the provided interface of another component. This illustrates the service consumer - service provider relationship between the two components.

 


Deployment Diagram:
A deployment diagram in the Unified Modeling Language models the physical deployment of artifacts on nodes. To describe a web site, for example, a deployment diagram would show what hardware components ("nodes") exist (e.g., a web server, an application server, and a database server), what software components ("artifacts") run on each node (e.g., web application, database), and how the different pieces are connected (e.g. JDBC, REST, RMI).
The nodes appear as boxes, and the artifacts allocated to each node appear as rectangles within the boxes. Nodes may have sub nodes, which appear as nested boxes. A single node in a deployment diagram may conceptually represent multiple physical nodes, such as a cluster of database servers. 
 

Activity Diagram:
Activity diagram is another important diagram in UML to describe dynamic aspects of the system. It is basically a flow chart to represent the flow form one activity to another activity. The activity can be described as an operation of the system. So the control flow is drawn from one operation to another. This flow can be sequential, branched or concurrent
 
Data Flow Diagram:
Data flow diagrams illustrate how data is processed by a system in terms of inputs and outputs. Data flow diagrams can be used to provide a clear representation of any business function. The technique starts with an overall picture of the business and continues by analyzing each of the functional areas of interest. This analysis can be carried out in precisely the level of detail required. The technique exploits a method called top-down expansion to conduct the analysis in a targeted way.
As the name suggests, Data Flow Diagram (DFD) is an illustration that explicates the passage of information in a process. A DFD can be easily drawn using simple symbols. Additionally, complicated processes can be easily automated by creating DFDs using easy-to-use, free downloadable diagramming tools. A DFD is a model for constructing and analyzing information processes. DFD illustrates the flow of information in a process depending upon the inputs and outputs. A DFD can also be referred to as a Process Model. A DFD demonstrates business or technical process with the support of the outside data saved, plus the data flowing from the process to another and the end results.
 
 
	                          	
5. IMPLEMETATION
5.1 Python
Python is a general-purpose language. It has wide range of applications from Web development (like: Django and Bottle), scientific and mathematical computing (Orange, SymPy, NumPy) to desktop graphical user Interfaces (Pygame, Panda3D). The syntax of the language is clean and length of the code is relatively short. It's fun to work in Python because it allows you to think about the problem rather than focusing on the syntax.
History of Python:
Python is a fairly old language created by Guido Van Rossum. The design began in the late 1980s and was first released in February 1991.
Why Python was created?
In late 1980s, Guido Van Rossum was working on the Amoeba distributed operating system group. He wanted to use an interpreted language like ABC (ABC has simple easy-to-understand syntax) that could access the Amoeba system calls. So, he decided to create a language that was extensible. This led to design of a new language which was later named Python.
Why the name Python?
No. It wasn't named after a dangerous snake. Rossum was fan of a comedy series from late seventies. The name "Python" was adopted from the same series "Monty Python's Flying Circus".



Features of Python:
A simple language which is easier to learn
Python has a very simple and elegant syntax. It's much easier to read and write Python programs compared to other languages like: C++, Java, C#. Python makes programming fun and allows you to focus on the solution rather than syntax.
If you are a newbie, it's a great choice to start your journey with Python.
Free and open-source
You can freely use and distribute Python, even for commercial use. Not only can you use and distribute software’s written in it, you can even make changes to the Python's source code.
Python has a large community constantly improving it in each iteration.
Portability
You can move Python programs from one platform to another, and run it without any changes.
It runs seamlessly on almost all platforms including Windows, Mac OS X and Linux.
Extensible and Embeddable
Suppose an application requires high performance. You can easily combine pieces of C/C++ or other languages with Python code.
This will give your application high performance as well as scripting capabilities which other languages may not provide out of the box.
A high-level, interpreted language
Unlike C/C++, you don't have to worry about daunting tasks like memory management, garbage collection and so on.
Likewise, when you run Python code, it automatically converts your code to the language your computer understands. You don't need to worry about any lower-level operations.
Large standard libraries to solve common tasks
Python has a number of standard libraries which makes life of a programmer much easier since you don't have to write all the code yourself. For example: Need to connect MySQL database on a Web server? You can use MySQLdb library using import MySQLdb .
Standard libraries in Python are well tested and used by hundreds of people. So you can be sure that it won't break your application.
Object-oriented
Everything in Python is an object. Object oriented programming (OOP) helps you solve a complex problem intuitively.
With OOP, you are able to divide these complex problems into smaller sets by creating objects.
Applications of Python:
1. Simple Elegant Syntax
Programming in Python is fun. It's easier to understand and write Python code. Why? The syntax feels natural. Take this source code for an example:
a = 2
b = 3
sum = a + b
print(sum)
2. Not overly strict
You don't need to define the type of a variable in Python. Also, it's not necessary to add semicolon at the end of the statement.
Python enforces you to follow good practices (like proper indentation). These small things can make learning much easier for beginners.
3. Expressiveness of the language
Python allows you to write programs having greater functionality with fewer lines of code. Here's a link to the source code of Tic-tac-toe game with a graphical interface and a smart computer opponent in less than 500 lines of code. This is just an example. You will be amazed how much you can do with Python once you learn the basics.
4. Great Community and Support
Python has a large supporting community. There are numerous active forums online which can be handy if you are stuck. 
5.2 Sample Code:
Main.py
from tkinter import messagebox
from tkinter import *
from tkinter import simpledialog
import tkinter
from tkinter import filedialog
from tkinter.filedialog import askopenfilename
import numpy as np 
import matplotlib.pyplot as plt
import pandas as pd
from sklearn.preprocessing import LabelEncoder
from sklearn.preprocessing import normalize
from sklearn.metrics import accuracy_score
from sklearn.model_selection import train_test_split
import os
from sklearn.metrics import confusion_matrix
from sklearn.metrics import accuracy_score
from sklearn.tree import DecisionTreeClassifier
from sklearn.naive_bayes import GaussianNB
from sklearn.neighbors import KNeighborsClassifier
from sklearn import svm
from sklearn.metrics import precision_score
from sklearn.metrics import recall_score
from sklearn.metrics import f1_score

global filename

global X,Y
global dataset
global main
global text
accuracy = []
global X_train, X_test, y_train, y_test

main = tkinter.Tk()
main.title("Network Traffic Analysis Using Machine Learning") #designing main screen
main.geometry("1300x1200")

#traffic names VPN and NON-VPN
class_labels = ['BROWSING', 'CHAT', 'FT', 'MAIL', 'P2P', 'STREAMING', 'VOIP', 'VPN-BROWSING', 'VPN-CHAT', 'VPN-FT', 'VPN-MAIL', 'VPN-P2P',
                'VPN-STREAMING', 'VPN-VOIP']


#fucntion to upload dataset
def uploadDataset():
    global filename
    global dataset
    text.delete('1.0', END)
    filename = filedialog.askopenfilename(initialdir="Dataset")
    text.insert(END,filename+" loaded\n\n")
    dataset = pd.read_csv(filename)
    text.insert(END,"Dataset before preprocessing\n\n")
    text.insert(END,str(dataset.head()))
    label = dataset.groupby('class1').size()
    label.plot(kind="bar")
    plt.show()
    
#function to perform dataset preprocessing
def DataPreprocessing():
    global X,Y
    global dataset
    global X_train, X_test, y_train, y_test
    text.delete('1.0', END)
    #replace missing values with 0
    dataset.fillna(0, inplace = True)
    le = LabelEncoder()
    #traffic type selection
    dataset['class1'] = pd.Series(le.fit_transform(dataset['class1'].astype(str)))
    text.insert(END,"Dataset after preprocessing\n\n")
    text.insert(END,str(dataset.head()))

    temp = dataset.values
    X = temp[:,0:dataset.shape[1]-1] #taking X and Y from dataset for training
    Y = temp[:,dataset.shape[1]-1]
    X = normalize(X)
    indices = np.arange(X.shape[0])
    np.random.shuffle(indices)
    X = X[indices]
    Y = Y[indices]
    text.insert(END,"Dataset after features normalization\n\n")
    text.insert(END,str(X)+"\n\n")
    text.insert(END,"Total records found in dataset : "+str(X.shape[0])+"\n")
    text.insert(END,"Total features found in dataset: "+str(X.shape[1])+"\n\n")
    X_train, X_test, y_train, y_test = train_test_split(X, Y, test_size=0.2)
    text.insert(END,"Dataset Train and Test Split\n\n")
    text.insert(END,"80% dataset records used to train ML algorithms : "+str(X_train.shape[0])+"\n")
    text.insert(END,"20% dataset records used to train ML algorithms : "+str(X_test.shape[0])+"\n")

def runKNN():
    global X,Y
    global X_train, X_test, y_train, y_test
    global accuracy
    accuracy.clear()
    text.delete('1.0', END)
    cls = KNeighborsClassifier(n_neighbors = 2) 
    cls.fit(X, Y) 
    predict = cls.predict(X_test)
    a = accuracy_score(y_test,predict)*100
    accuracy.append(a)
    precision = precision_score(y_test, predict,average='macro') * 100
    recall = recall_score(y_test, predict,average='macro') * 100
    fmeasure = f1_score(y_test, predict,average='macro') * 100
    text.insert(END,"KNN Accuracy  :  "+str(a)+"\n")
    text.insert(END,"KNN Precision : "+str(precision)+"\n")
    text.insert(END,"KNN Recall    : "+str(recall)+"\n")
    text.insert(END,"KNN FScore    : "+str(fmeasure)+"\n\n")

def runNB():
    global X,Y
    global X_train, X_test, y_train, y_test
    global accuracy
    cls = GaussianNB() 
    cls.fit(X_train, y_train) 
    predict = cls.predict(X_test)
    a = accuracy_score(y_test,predict)*100
    accuracy.append(a)
    precision = precision_score(y_test, predict,average='macro') * 100
    recall = recall_score(y_test, predict,average='macro') * 100
    fmeasure = f1_score(y_test, predict,average='macro') * 100
    text.insert(END,"Naive Bayes Accuracy  :  "+str(a)+"\n")
    text.insert(END,"Naive Bayes Precision : "+str(precision)+"\n")
    text.insert(END,"Naive Bayes Recall    : "+str(recall)+"\n")
    text.insert(END,"Naive Bayes FScore    : "+str(fmeasure)+"\n\n")
    
def runDT():
    global X_train, X_test, y_train, y_test
    global accuracy
    cls = DecisionTreeClassifier() 
    cls.fit(X_train, y_train) 
    predict = cls.predict(X_test)
    a = accuracy_score(y_test,predict)*100
    accuracy.append(a)
    precision = precision_score(y_test, predict,average='macro') * 100
    recall = recall_score(y_test, predict,average='macro') * 100
    fmeasure = f1_score(y_test, predict,average='macro') * 100
    text.insert(END,"Decision Tree Accuracy  :  "+str(a)+"\n")
    text.insert(END,"Decision Tree Precision : "+str(precision)+"\n")
    text.insert(END,"Decision Tree Recall    : "+str(recall)+"\n")
    text.insert(END,"Decision Tree FScore    : "+str(fmeasure)+"\n\n")

def runSVM():
    global X_train, X_test, y_train, y_test
    global accuracy
    cls = svm.SVC() 
    cls.fit(X_train, y_train) 
    predict = cls.predict(X_test)
    a = accuracy_score(y_test,predict)*100
    accuracy.append(a)
    precision = precision_score(y_test, predict,average='macro') * 100
    recall = recall_score(y_test, predict,average='macro') * 100
    fmeasure = f1_score(y_test, predict,average='macro') * 100
    text.insert(END,"SVM Accuracy  :  "+str(a)+"\n")
    text.insert(END,"SVM Precision : "+str(precision)+"\n")
    text.insert(END,"SVM Recall    : "+str(recall)+"\n")
    text.insert(END,"SVM FScore    : "+str(fmeasure)+"\n\n")

    

def graph():
    height = accuracy
    bars = ('KNN Accuracy','Naive Bayes Accuracy','Decision Tree Accuracy','SVM Accuracy')
    y_pos = np.arange(len(bars))
    plt.bar(y_pos, height)
    plt.xticks(y_pos, bars)
    plt.title("Accuracy Comparison Graph")
    plt.show()

def GUI():
    global main
    global text
    font = ('times', 16, 'bold')
    title = Label(main, text='Network Traffic Analysis Using Machine Learning')
    title.config(bg='darkviolet', fg='gold')  
    title.config(font=font)           
    title.config(height=3, width=120)       
    title.place(x=0,y=5)

    font1 = ('times', 12, 'bold')
    text=Text(main,height=30,width=110)
    scroll=Scrollbar(text)
    text.configure(yscrollcommand=scroll.set)
    text.place(x=10,y=100)
    text.config(font=font1)

    font1 = ('times', 13, 'bold')
    uploadButton = Button(main, text="Upload Network Traffic Dataset", command=uploadDataset, bg='#ffb3fe')
    uploadButton.place(x=900,y=100)
    uploadButton.config(font=font1)  

    processButton = Button(main, text="Data Preprocessing", command=DataPreprocessing, bg='#ffb3fe')
    processButton.place(x=900,y=150)
    processButton.config(font=font1) 

    knnButton = Button(main, text="Run KNN Algorithm", command=runKNN, bg='#ffb3fe')
    knnButton.place(x=900,y=200)
    knnButton.config(font=font1) 

    nbButton = Button(main, text="Run Naive Bayes Algorithm", command=runNB, bg='#ffb3fe')
    nbButton.place(x=900,y=250)
    nbButton.config(font=font1)

    dtButton = Button(main, text="Run Decision Tree Algorithm", command=runDT, bg='#ffb3fe')
    dtButton.place(x=900,y=300)
    dtButton.config(font=font1) 

    svmButton = Button(main, text="Run SVM Algorithm", command=runSVM, bg='#ffb3fe')
    svmButton.place(x=900,y=350)
    svmButton.config(font=font1)

    graphButton = Button(main, text="Comparison Graph", command=graph, bg='#ffb3fe')
    graphButton.place(x=900,y=400)
    graphButton.config(font=font1)

    main.config(bg='forestgreen')
    main.mainloop()
    
if __name__ == "__main__":
    GUI()
6. TESTING
Implementation and Testing:
Implementation is one of the most important tasks in project is the phase in which one has to be cautions because all the efforts undertaken during the project will be very interactive. Implementation is the most crucial stage in achieving successful system and giving the users confidence that the new system is workable and effective. Each program is tested individually at the time of development using the sample data and has verified that these programs link together in the way specified in the program specification. The computer system and its environment are tested to the satisfaction of the user.
Implementation	
The implementation phase is less creative than system design. It is primarily concerned with user training, and file conversion. The system may be requiring extensive user training. The initial parameters of the system should be modifies as a result of a programming. A simple operating procedure is provided so that the user can understand the different functions clearly and quickly. The different reports can be obtained either on the inkjet or dot matrix printer, which is available at the disposal of the user. 	The proposed system is very easy to implement. In general implementation is used to mean the process of converting a new or revised system design into an operational one.

Testing
Testing is the process where the test data is prepared and is used for testing the modules individually and later the validation given for the fields. Then the system testing takes place which makes sure that all components of the system property functions as a unit. The test data should be chosen such that it passed through all possible condition. Actually testing is the state of implementation which aimed at ensuring that the system works accurately and efficiently before the actual operation commence. The following is the description of the testing strategies, which were carried out during the testing period.
System Testing 
Testing has become an integral part of any system or project especially in the field of information technology.  The importance of testing is a method of justifying, if one is ready to move further, be it to be check if one is capable to with stand the rigors of a particular situation cannot be underplayed and that is why testing before development is so critical. When the software is developed before it is given to user to use the software must be tested whether it is solving the purpose for which it is developed.  This testing involves various types through which one can ensure the software is reliable. The program was tested logically and pattern of execution of the program for a set of data are repeated.  Thus the code was exhaustively checked for all possible correct data and the outcomes were also checked.  
Module Testing
To locate errors, each module is tested individually.  This enables us to detect error and correct it without affecting any other modules. Whenever the program is not satisfying the required function, it must be corrected to get the required result. Thus all the modules are individually tested from bottom up starting with the smallest and lowest modules and proceeding to the next level. Each module in the system is tested separately. For example the job classification module is tested separately. This module is tested with different job and its approximate execution time and the result of the test is compared with the results that are prepared manually. The comparison shows that the results proposed system works efficiently than the existing system. Each module in the system is tested separately. In this system the resource classification and job scheduling modules are tested separately and their corresponding results are obtained which reduces the process waiting time.
Integration Testing
After the module testing, the integration testing is applied.  When linking the modules there may be chance for errors to occur, these errors are corrected by using this testing. In this system all modules are connected and tested. The testing results are very correct. Thus the mapping of jobs with resources is done correctly by the system.
Acceptance Testing
When that user fined no major problems with its accuracy, the system passers through a final acceptance test.  This test confirms that the system needs the original goals, objectives and requirements established during analysis without actual execution which elimination wastage of time and money acceptance tests on the shoulders of users and management, it is finally acceptable and ready for the operation.



Test Case Id	Test Case Name	Test Case Desc.	Test Steps	Test Case Status	Test Priority
			Step	Expected	Actual		
01	upload Network Traffic Dataset	Test whether the Traffic Dataset is uploaded  or not.	If Traffic Dataset is not uploaded	we cannot do further operations	If Traffic Dataset uploaded we will do further operations	High	High
 02	Data Preprocessing	Verify the Dataset is Pre-processed  
or not	Without loading the dataset	We cannot Pre-process Dataset	We Can Pre-process
Dataset successfully	High	High
03	Run KNN Algorithm	Verify the Run KNN Algorithm will run or not	Without training model 	we cannot Run KNN Algorithm	we can run KNN Algorithm	High	High





04	Run Naïve Bayes Algorithm	Verify the Run Naïve Bayes Algorithm will run or not	Without training model 	we cannot Run Naïve Bayes Algorithm	we can run Naïve Bayes Algorithm	High	High
05	Run Decision Tree Algorithm	Verify the Run Decision Tree Algorithm will run or not	Without training model 	we cannot run Decision Tree Algorithm	we can run Decision Tree Algorithm	High 	High 
06	Run SVM Algorithm	Verify the SVM Algorithm will run or not	Without training model 	we cannot Run SVM Algorithm	we can run SVM Algorithm	High	High
07	Comparison Graph	compare Accuracy Comparison Graph
	Without
Comparing Graph 	 We cannot get accuracy results	We can get accuracy results	High	High

7. SCREENSHOTS:
To run project double click on ‘run.bat’ file to get below screen
 
In above screen click on ‘upload Network Traffic Dataset’ button to upload dataset
 
In above screen selecting and uploading ‘NetworkTraffic.csv’ file and then click on ‘Open’ button to load dataset and to get below screen
 
In above screen we can see dataset loaded and dataset contains lots of non-numeric values so we need to process it and in graph x-axis we can see traffic type and y-axis represents total records in dataset for that traffic. Now close above graph and then click on ‘Data Preprocessing’ to clean dataset
 
In above screen we can see all dataset converted to numeric format and in last we can see total records and columns found in dataset and then splitted dataset percentage for train and test records. Now train and test data is ready and now click on ‘Run KNN Algorithm’ button to train KNN and get below result
 
In above screen with KNN we got 84% accuracy and now click on ‘Run Naïve Bayes Algorithm’ button to train it
 
In above screen for same dataset with naïve bayes we got 28% accuracy and now click on ‘Run Decision Tree Algorithm’ button to get below result
 
In above screen for same dataset with SVM we got 74% accuracy and now click on ‘Run SVM Algorithm’ button to get below result
 
In above screen with SVM we got 50% accuracy and now click on ‘Comparison Graph’ button to get below result
 
In above graph x-axis represents algorithm name and y-axis represents accuracy of those algorithms and in all algorithms KNN shows better result

8. CONCLUSION
The Network traffic classification techniques are discussed in this paper to enhance some idea about Machine Learning algorithms for network traffic data. The analysis carried out definitely helps to a new analyst to make the decision about which Machine Learning algorithm is more appropriate for this application. Initially, the network traffic extraction is carried out to evaluate the different Machine Learning algorithm which is trained in later phase. The Machine Learning algorithms are used for managing the performance of network and classification of unknown applications. 
We then employ four basic Machine Learning algorithms to analyze the protocol. Further, the classifiers using different Machine Learning algorithms are developed to compare the accuracy for this network traffic data. We find that K-nearest neighbor (KNN) algorithm outperforms Naïve Bayes algorithm, Decision Tree and Support Vector Techniques in terms of accuracy which is due to the fact that KNN uses better classification criterion than Naïve Bayes and Decision Tree Algorithm. We find that KNN is most robust among the algorithms: NB, DT, and SVM for out training data set. It is also able to maintain highest mean for accuracy.
9. REFERENCES

[1] Nguyen, Thuy TT, and Grenville Armitage. "A survey of techniques for internet traffic classification using machine learning." IEEE Communications Surveys & Tutorials, vol. 10, no. 4, pp. 56-76, 2008. 
[2] M. Shafiq, X. Yu, A. A. Laghari, L. Yao, N. K. Karn, and F. Abdessamia, “Network traffic classification techniques and comparative analysis using machine learning algorithms,” in Proc. IEEE International Conference on Computer and Communications (ICCC-2016), pp. 2451-2455, 2016. 
[3] Internet Assigned Numbers Authority (lANA), http://www.iana.orglassignments/port-numbers, as of August 12, 2008. 
[4] Pawel Foremski, “On different ways to classify Internet traffic: a short  review of selected publications Theoretical and Applied Informatics, ” 2013. 
[5] K. Sing and S. Agrawal, “Comparative Analyssis of Five Machine Learning Algorithms for IP Traffic Classification,” in Proc. IEEE International Conference on Emerging Trends in Network and Computer Communication (ETNCC-2011), pp. 33-38, 2011. 
[6] Q. Dai, C. Zhang and H. Wu, “Research of Decision Tree Classification Algorithm in Data Mining,” International Journal of Database Theory and Application, vol. 9, no.5, pp. 1-8, 2016. 
[7] Cristina Petri, “Decision Trees”, Cluj Napoca, 2010. 
[8] S. Karthika and N. Sairam, “A Naïve Bayesian Classifier for Educational Qualification,” Indian Journal of Science and Technology, vol. 8, no. 16, Jul. 2015; DOI: 10.17485/ijst/2015/v8i16/62055. 
[9] D. K. Srivastava and L. Bhambhu, “Data Classification Using Support Vector Machine,” Journal of Theoretical and Applied Information Technology, vol. 12, no. 1, Feb. 2010. 
[10] Wireshark tool: https://www.wireshark.org/docs/dfref/. 

