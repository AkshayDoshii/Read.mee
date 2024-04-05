# Read.mee
A
Project Report on
Online e-Commerce Shopping 
At 
GTL INFOTECH
Submitted to
Savitribai Phule Pune University 
In the partial fulfillment of the requirement of the award of the degree of
M.Sc.(Computer Application)
 S.Y.M.Sc. - CA,  Sem IV
Academic Year 2022-23
By
Akshay Rajan Doshi
Under the guidance of
 Prof. Sarika Gadekar
Through
 
Alandi (D)- Pune 412105
 Alandi (D) - Pune 412105

CERTIFICATE

Department of Computer Application

This is to certify that , of S.Y.M.Sc. - CA,  Sem IV, MR. Akshay Rajan Doshi Exam Seat No.		, has successfully completed project work entitled  Online e-Commerce Shopping   in the partial fulfillment of the requirement of the degree of M.Sc. (Computer Application) for the Academic Year 2022-23



Prof. Sarika Gadekar                            	 Dr. Vikas Mahandule
       Project Guide					Head of the Department



Internal Examiner			   		   External Examiner


ACKNOWLEDGEMENT


The words are not enough to express my thanks to Dr. B. B. Waphare,Principal, MIT Arts Commerce and Science College Alandi (D) for providing me with the opportunity to avail the excellent facilities andinfrastructure of the institute.

It is my proud privilege to express my profound gratitude to Dr. Vikas Mahandule, HOD, Computer Application Department, for his astute guidance, constant encouragement and sincere support throughout my academic course.
I thanks to my honest gratitude to Prof. Sarika Gadekar for her inspiration, constructive suggestions and affectionate guidance in my project work completion.
Last but not the least, I express my sincere thanks to all my dear friends and family members for their constant motivation, moral support and invariable direction throughout my life.




 

	DECLARATION	

I,  Akshay Rajan Doshi  here,by declare that this project     Online e-Commerce  Shopping  work entitled submitted at MIT, Arts Commerce and Science College, Alandi(D), (Affiliated to Savitribai Phule Pune University) is a record of original work done by me under the supervision and guidance of Prof. Sarika Gadekar, Department of Computer Application.


Signature :
1) Name of Student : . Akshay Rajan Doshi
Exam Seat No.: 

2) Name of Student : . Akshay Rajan Doshi
Exam Seat No.: 

Place 	: Alandi (D), Pune
Date :
					  INDEX
Chapter no.	               Chapter Title	Page no 
CHAPTER   1	INTRODUCTION	6-7
                     1.2
                     1.3	1.2. EXISTING SYSTEM AND NEED FOR SYSTEM
LIMITATIONS OF EXISTING SYSTEM	
CHAPTER   2	PROPOSED SYSTEM	8
                     2.1
                     2.2
                     2.3
                     2.4
                     2.5
                     2.6
                     2.7
                     2.8   
                     2.9	2.1. PROBLEM STATEMENT
2.2. PRODUCT OVERVIEW
2.3. SUMMARY OF CAPABILITIES
2.4.ASSUMPTIONS AND DEPENDENCIES
2.5. OBJECTIVES OF SYSTEM
2.6.NON-FUNCTIONAL REQUIREMENTS

2.7. SCOPE OF THE SYSTEM

2.8. MODULE SPECIFICATIONS

2.9. OPERATING ENVIRONMENT	9-15
CHAPTER   3	3. REQUIREMENT DETERMINATION AND ANALYSIS	16
                     3.1
                     3.2	3.1. FACT FINDING TECHNIQUE
3.2. FEASIBILITY STUDY	17-25
CHAPTER   4	SYSTEM ANALYSIS AND DESIGN	26
                      4.1
                      4.2
                      4.3
                      4.4
                      4.5	4.1. USE CASE DIAGRAMS

4.2. SEQUENCE DIAGRAM

4.3. ACTIVITY DIAGRAM

4.4. COMPONENT  Diagram

4.5  DEPLOYMENT DIAGRAM	27-50
CHAPTER   5	USER MANUAL

	51
                       5.1
                       5.2	5.1 USER MANUAL

5.2	OperationalManual/Menu Explanation	51-54
		
		
		
		
		
		
		
 


1.2. INTRODUCTION
                                The main purpose to develop this project Online e-Commerce  Shopping(nikkiflower.com) is to sell the cake /flower/bucks /gift items online .This project is basically develop for metro-city . This project Online e-Commerce  Shopping provides all facilities to shopkeeper to manage the shop on website and control the entire e-Commerce  business transaction from website. It can also help to shopkeeper keep Daily Use Item  for sale as well as can updates from site with new ornaments time to time. This project manages various product category, product, special offer, gallery, order, payment and customer’s feedback. In this project, customers can easily view various product, add to cart product, place order. We have developed many modules in the project for performing all the operations of this system. Some of the modules are product management, type management, order management etc.
1.3. EXISTING SYSTEM AND NEED FOR SYSTEM
                       In existing system for giving any orders, users should visit product shop to know about product, give them order, and pay advance.  In this method, time and manual work is required. Maintaining critical information in the files and manuals is full of risk and a tedious processThe existing system serve a major drawback to the realization of efficiency and customer satisfaction. The experience of ordering in most shop is not pleasant for the customers.
NEED FOR SYSTEM
This online application enables the end users to register online, select the product from the Catalog, view the product or search the product and order product online by just selecting product which user wants. By using this application, Easy to solve customer query, any record is easy to store and manage, Easy to purchase product, Give the Discount Offer for Customer, and provide shipping method.


1.4. LIMITATIONS OF EXISTING SYSTEM

Due to manual system has following limitations:
1.	In the existing system all transactions of product, purchasing product which is done manually which is time consuming.

2.	There is no computer system for handling payments. All calculations performed manually, which may not be accurate always maintaining the record is really a tedious task.

3.	To buy product user has to collect information about it either by visiting the shop or by asking people, which is the better one.














































2. PROPOSED SYSTEM

2.1. PROBLEM STATEMENT
	Online Shopping (nikkiflower.com) designed for to overcome those problems using manual system such as the possibility the paper order is high. Many Cakes/flower/ gift shop use conventional system, which is on paper-based, for purchasing product. Customer can login to the system to maintain his account information, such as changing phone number, address, and check the status of his orders.	
	Therefore, Online Shopping developed to enhance the efficiency and accuracy of taking order. Besides that, conventional system cannot see the sales history therefore Online Shopping designed to view the sales history. Online Shop System Problem Statement Customer can browse through the product catalogue and add the items to shopping cart.

2.3. PRODUCT OVERVIEW

	In the Online Shopping of flower/cake/gift items , system provides customer to order the new and fresh peoduct. User can search the product or add the product to shopping cart or order the product if he/she want. Customer can pay the bill online or cash on delivery. Search the item on site and if order placed for product then customer have to register and then place order. Save the money or time of customer. Delivery boy deliver the product to customer and give the bill from customer if the payment type is cash on delivery and guest user only search the product or add in the shopping cart.

2.4. SUMMARY OF CAPABILITIES

1.	A detailed product description:
	 Online stores do not have a live store attendant (though some may offer live   chat), so the sale items need to have a product description that takes the place of your best sales person. The availability of a warranty, where applicable, also referred to in the description.

2.	Easy Use:
	Online sellers have minutes, if not seconds, to make a sale. Focus on the user experience by providing shopping categories, filters, and comparison capabilities.

3.	Category:
You have variety of options to choose gifts and cakes from category.

4.	Wish List:
	Wish list helps buyers save products for future reference. It can emerge as a popup when someone clicks on the wish list button. This is a best way to let shoppers view recently added products without diverting to another page.

5.	Money Back Policy:
	If the customer is not satisfied with product, they can return or exchange their purchase on 100% value.

2.5. ASSUMPTIONS AND DEPENDENCIES
	
	The product does require back-end database server MySQL for storing the user name and password for different types of user of the system as well as various databases regarding various insurance information.

1. User must trained for basic computer functionalities.
2. User must have the basic knowledge of English.
3. The system must be able to respond to database software within reasonable time.
	
2.6. OBJECTIVES OF SYSTEM
A Online Shopping is a web Application where the User can register themselves and online Purchase item main Objective of this system is maintaining the Products online and provide online payment facility to customer or cash on delivery facility. The objective of the system is to provide the customer with on-the-click functionality that helps them to search over a variety of products at a centralized location and buy the products that best suit their requirements in an easier and faster fashion.

The software system designed in such a way that anyone can view the updates of the products being offered on the website at any time that too easily. The software will help in easy maintaining and updating jewellery products in the website for the administrator.

2.7. FUNCTIONAL REQUIREMENTS

This section provides requirement overview of the system. Various functional modules that can implemented by the system will be -

1. Registration -
If customer wants to order the product/item then he/she must be register. Unregister customer cannot buy the product. 

2. Login -
Customer logins to the system by entering valid user id and password for order the products online.

3. Changes to Cart -
Changes to cart means the customer after login or registration can make order or cancel order of the item from the cart.  

5. Logout - 
After the payment or searching, the product the customer will logged out.

6. Report Generation -
After all transaction, the system can generate the portable document file (.pdf) and then sent one copy to the system database to calculate the monthly transaction.

2.8. NON-FUNCTIONAL REQUIREMENTS

1. Security -
The system use SSL (secured socket layer) in all transactions that include any confidential customer information. The system must automatically log out all customers after a period of inactivity.
The system should not leave any cookies on the customer’s computer containing the user’s password. The system’s back-end servers shall only be accessible to authenticated administrators.
Sensitive data will be encrypted before sent over insecure connections like the internet.

2. Reliability -
The system provides storage of all databases on redundant computers with automatic switch over. The reliability of the overall program depends on the reliability of the separate components. 
The system has a backup of the database, which is continuously maintained and updated to reflect the most recent changes.
Thus, the overall stability of the system depends on the stability of container and its underlying operating system.

3. Availability -
The system should be available at all times, meaning the user can access it using a web browser, only restricted by the down time of the server on which the system runs. In case of a hardware failure or database corruption, a replacement page will show. Also, in case of a hardware failure or database corruption, backups of the database should be retrieved from the server and saved by the administrator. Then the service will be restarted. It means 24 X 7 availability.
4. Maintainability -
A commercial database used for maintaining the database and the application server takes care of the site. In case of a failure, a re-initialization of the program will be done. In addition, the software design done with modularity in mind so that maintainability done efficiently.

5. Portability -
The application is HTML and scripting language based. Therefore, the end-user part is fully portable and any system using any web browser should be able to use the features of the system, including any hardware platform that is available or will be available in the future.
An end-user is using this system on any OS; it is either Windows or Linux. The system shall run on PC, Laptops, and PDA etc.

2.9. SCOPE OF THE SYSTEM

Purchasing and selling products and services over the internet without the need of going physically to the market is what online shopping all about. Online shopping stores offer product description, pictures, comparisons, price and much more. Few examples of these are Amazon.com, ebay.com, voylla.com and the benefits of online shopping is that by having direct access to customer, the online stores can offer special products to the customer, cookies can used for tracking the customer selection over the internet or what is of their interest when they visit the site again. Online shopping makes use of digital technology for managing the flow of information, products, and payment between customer, site owners and suppliers.

    	shopping cart is one of the important facilities provided in online shopping, this lets customer to browse different types of product and services and once they select an item to purchase, they can place the item in shopping cart, and continue browsing till the final selection. Customers can even remove the items from shopping cart that selected earlier before they place the final order. 

2.10. MODULE SPECIFICATIONS

 Admin:
•	Admin can manage user and customer account.
•	Admin can manage product.
•	Manage product category.
•	Admin can manage the orders of customers.
•	Generate bill.
•	View the feedback.

Customer:

•	Customer Registration.
•	Update the details.
•	Search the products as per there requirements.
•	Customer can view the product.
•	Customer can buy the products or give the order.
•	Pay the bill cash on delivery.
•	Give Feedback.


Employee/Delivery boy:

•	View order details.
•	Deliver order.
•	Give bill & Receive payment

Login Module:
•	User name.
•	Password.

Feedback:
•	Customer Give feedback.
•	Admin View Feedback.
•	Delivery boy feedback 







2.11. OPERATING ENVIRONMENT
2.11.1. SOFTWARE REQUIREMENT:

	Operating System    : Windows 10 
	Browser                   : Chrome, Internet Explorer or any compatible web browser                                    
	Database                  : MySQL
	Language/Technology: HTML5, AngularJs, CSS3, JQuery, .                 


2.11.2. HARDWARE REQUIRMENTS:

	RAM                       : 1GB
	Hard Disk               : 10 GB
	Processor               :  Intel
	Hosting                    Linux Hosting /    Window Hosting     












































4. REQUIREMENT DETERMINATION AND ANALYSIS
3.1. FACT FINDING TECHNIQUE:
Definition:
                “The specific methods, techniques analyst used for collecting data about requirements are called as fact finding/gathering techniques.”
                               Fact-finding is the formal process of collect information about system and requirements. It is also called information gathering or data collection. It has to be gathered in an organized way so that no system details are left out, right problems are identified, repetitive work is avoided and wrong or incomplete details are not collected. Information gathering is very important while developing any application.
                              To understand the drawbacks in the existing system study was conducted by using following fact-finding techniques.
Fact-finding techniques are:
1. Interview
•	Structured Interview
•	Unstructured Interview
2. Questionnaires
•	Open ended questionnaire
•	Close ended questionnaire
3. Observation
•	Record Review
3.1.1. Interview:
Definition:
                   “Interview technique is used to collect information from individuals or from groups.”
                           The interview is best method for producing qualitative information, opinions, policies, suggestions, subjective description of activities etc. Interview helpful for gathering information from individuals who do not communicate effectively in writing or who may not have time complete questioning.
Interview can be of two types:
1. Structured Interview:
                                        Structured interviews are used standardized question in either open response or close response format. It requires deep study and preparation.
2. Unstructured Interview:
                                       Unstructured interviews allow respondent to answer in their own words. Whereas a structure interview uses the set of prescribe answers. In this type of interview question are connected with last question so it does not require deep study and preparation.
2.1.2. Questionnaires:
Definition:
               “A questionnaire is a research instrument consisting of a series of question for the purpose of gathering information from respondent.”
                Questionnaire may be used as a supplement to interviews. Questionnaires are useful for understanding the requirements of the clients to develop the system.
1. Gathering numerical data.
2. Getting relatively simple opinion from a large number of people.
3. Obtaining collective opinion.
4. Standardized question format can produce more reliable data than other fact-finding techniques.


There are two types of questionnaires:
•	Open ended questionnaire:
                                  Use open-ended questionnaire to learn about feeling, opinion      and general experience or to explore a process or problem.

•	Close ended questionnaire:
                                   Close-ended questionnaire controls the frame of reference by presenting respondent with specific responses from which to select. This format is appropriate for collecting information.

2.1.3. Observation:
Definition:
                              “Observation methods is most useful when the analyst needs to be actually observed how documents are handle, how process is carried out and whether specified steps are actually followed or not.”
                   Observation provides close view of the working of the real system. System analyst observes people, objects, documents and occurrences of events. Observation allows analyst to get information, which they cannot obtained any other fact-finding technique.  

•	Record Review:
                        In record reviews, system analyst examines information that has been recorded about the system and about the users. The record review can take place at the beginning of the system study or in the later in the study for comparing actual operations with what the records indicate. Many records and reports can provide valuable information about organization and operation.Records may include written policy manuals, rules and regulations, standard operating procedures used in the organization and form and documents.
             We are maintaining the records of customer detail, supplier detail, purchase details, sale details, product details and service details etc.
3.2. FEASIBILITY STUDY:
                                    Feasibility study carried out whether there is complex problem. A feasibility study is undertaken to determine the possibility or probability of either improving the existing system or developing completely new system. Feasibility study evaluates the cost and benefits of the proposed system.
                       There are three aspects of feasibility study, which should be check. Following are the types of Feasibility Study:
1. Technical Feasibility
2. Economic Feasibility
3. Operational Feasibility

3.2.1. Technical Feasibility:                   
Definition:
                           “Technical feasibility is carried out to determine whether the company has the capability, in terms of software, hardware, personnel and expertise, to handle the completion of the project.”
                                  Technical feasibility determines whether it is possible to develop the project with available equipment, available software technology and the workers. If there is any kind of need in order to develop software in this case the cost of hardware, software and technical equipment are considered.
                 Our system used hardware, software which are we used the Windows 10 operating system, processor Intel® Core™ i3 CPU, RAM 4 GB, Hard Disk 500 GB, Front end and back end are PHP and MySQL respectively. Therefore, we do not require costly hardware.
                 There is lot of security, accuracy and reliability in system by considering the above reason the system is technically feasible.
3.2.2. Economic Feasibility:
Definition:
                     “Economic analysis is the most frequently used method for evaluating the effectiveness of a new system. Most commonly called as cost or benefit analysis, the procedure is to determine the benefits and saving that are expected from a candidate system and compare them with costs.”
It is the study of economical benefits of this software. More commonly known as cost/benefit analysis, the procedure is to determine the benefits and savings that are expected from a candidate system and compare them with costs. If benefits outweigh costs, then the decision is made to design and implement the system. An entrepreneur must accurately weigh the cost versus benefits before taking an action. These websites save our money and time. By this website, we can buy product in online. Today everybody is busy, so time saving is another important thing of our life
Economic feasibility consists of two types of cost are as follows:
•	One-time Cost:
One-time cost may include:
1. Feasibility study cost.
      2. The costs for converting from present system to new system.
      3. Construction or remodeling of computer room/facilities.
      4. Cost involved in software packages. 

3.2.3. Operational Feasibility:
Definition:
                         “Operational feasibility in a measure of how well a proposed system solves the problem and takes advantages of the opportunities identified during scope definition and how it satisfies the requirements identified in the requirements analysis phase of system development.”
               Operational feasibility is a measure of how well a proposed system solves the problems, and takes advantage of the opportunities identified during scope definition and how it satisfies the requirements identified in the requirements analysis phase of system development    
After implementing the system, the system-training program are arranged for the users. The people who are familiar with information system as well as the techniques carry this out. They are experienced persons like system analyst or managers. The cost of the training program as well as space requirement for implementation of the system and the other assets are considered. Therefore, our system is operationally feasible.
1. It is user-friendly system.
2. Does not require special training.
3. Provide better security.
4. Any user having technical knowledge or not can operate system.

• Legal/Ethical Feasibility Study: 
 Determines whether the proposed system conflicts with legal 
requirements. 
• Schedule Feasibility Study: 
 A project will fail if it takes too long to be completed before it is useful. 
Typically this means estimating how long the system will take to develop, and 
if it can be completed in given time period using some methods like payback 
period. Schedule feasibility is a measure of how reasonable the project 
timetable is. Given our technical expertise, are the project deadlines reasonable? 
Some projects are initiated with specific deadlines. You need to determine 
whether the deadlines are mandatory or desirable. 
• Resource Feasibility Study: 
 This involves questions such as how much time is available to built the 
new system, when it can be built, whether it interferes with normal business 
operations, type and amount of resources required, dependencies. 
• Cultural Feasibility Study: 
 In this stage, the project's alternatives are evaluated for their impact on 
the local and generated culture. For example, environmental factors need to be 
considered and these factors are to be well known. Further an enterprise's own 
culture can clash with the results of the project.











































4.1. USE CASE DIAGRAMS

1. Admin

	
 







2. Customer:


 







3. Delivery Boy:




 








4. Business Use case For Online Shopping(nikkiflower.com):


 
4.2. SEQUENCE DIAGRAM

 
4.3. ACTIVITY DIAGRAM


 







ERD Diagram 
 












4.5. COMPONENT Diagram

 
4.6 DEPLOYMENT DIAGRAM





























CLASS DIAGRAM














































Online Shopping System Modules: -

1.	Login Module:
 In this module, the DBA or the customer will have to authorize his access to the modules of the online software system.

2.	Customer Module: 
In this module, there is two types of users one is registered and second is unregister user. Registered user create account and buy the product. This module helps the customer to edit his/her profile details, view the orders.
 
3.	Admin Module: 
In this module, the work of admin can be proceeded with i.e. maintenance of the website, review customer’s feedback and queries, bill maintenance. 

4.	Product: 
In this module, we can add, edit and delete the products.

5.	Search Module: 
In this module, product search using high-performance search system with an option to search by selected attributes.

6.	Feedback: 
In this module, the customer can give some valuable feedback or ask a query pertaining to a product.

User Interface
 
 

 
 

 
 
 


Admin Panel

 
 

 


 

TABLE SPECIFICATIONS
4.13.1. Table Name: Customer
 	    Description: Information of Customer

Sr. No	Field Name	Field Type	Size	Constraint	Description
1.	CustId	Int	10	Primary Key	Customer ID
2.	FirstName	Varchar	50	Not Null	Customer
First Name
3.	LastName	Varchar	50	Not Null	Customer
Last Name
4.	Email 	varchar	50	Not Null	Mail Id
5.	Password	varchar	30	Not Null	Password
6. 	MobileNumber	Int	20	Not Null	Mobile Number
7.	Gender	Varchar	10	Not Null	Customer Gender
8.	DateOfBirth	Date	30	Not Null	Date of Birth
9.	Address	Varchar	50	Not Null	Customer Address
10.	Country	Varchar	20	Not Null	Customer Country
11.	State	Varchar	20	Not Null	Customer State
12.	City	Varchar	20	Not Null	Customer City
13	ZipCode	Int	10	Not Null	Customer Zip code





4.13.2. Table Name: Admin
 	 Description: Information of Admin

Sr. No	Field Name	Field Type	Size	Constraint	Description
1.	Aid	Int	10	Primary Key	Admin ID
2.	AName	Varchar	50	Not Null	Admin Name
3.	AAddress	Varchar	50	Not Null	Admin Address
4.	AEmailId	Varchar	50	Not Null	Admin Email ID
5	Password	Varchar	30	Not Null	Admin Password
6.	Aphno	Int	20	Not Null	Phone number

4.13.3. Table Name: Product
 	 Description: Information of Product

Sr. No	Field Name	Field Type	Size	Constraint	Description
1.	PId	Int	10	Primary Key	Jewellery Product ID
2.	CaId	Int	10	Foreign Key	Product Category ID
3.	PName	Varchar	50	Not Null	Product Name
4.	Price	Int	20	Not Null	Price of Product
5	Product Desc.	Varchar	50	Not Null	Product Description
6	Unit	Int	30	Not Null	Product Size
7	Gst	Int	20	Not Null	Gst



4.13.4. Table Name: Order
 	 Description: Information of Order

Sr. No	Field Name	Field Type	Size	Constraint	Description
1.	Order_Id	Int	10	Primary Key	Order ID
2.	PId	Int	10	Foreign Key	Product ID
3.	CustId	Int	10	Foreign Key	Customer ID
3.	Quantity	Int	20	Not Null	Product Quantity
5.	Total Amount	Int	30	Not Null	Product Amount
6.	Order_Date	Varchar	30	Not Null	Date of order


4.13.5. Table Name: Delivery Boy
 	  Description: Information of Delivery Boy

Sr. No	Field Name	Field Type	Size	Constraint	Description
1.	Did	Int	10	Primary Key	Delivery Boy ID
2	CustId	Int	10	Foreign Key	Customer Id
3.	DName	Varchar	20	Not Null	Delivery Boy Name
4.	DAddress	Varchar	40	Not Null	Address
5.	DEmailId	Varchar	50	Not Null	Email ID
6.	Dphno	Int	13	Not Null	Phone number
7	Order_id	Int	10	Foreign Key	Order Id

4.13.6. Table Name: Product Category
 	 Description: Information of Product Category

Sr. No	Field Name	Field Type	Size	Constraint	Description
1.	CaId	Int	10	Primary Key.	Category ID
2.	CaName	Varchar	20	Not Null	Category Name

4.13.7. Table Name: Feedback
 	 Description: Information of Feedback

Sr. No	Field Name	Field Type	Size	Constraint	Description
1.	Fid	Int	10	Primary Key	Feedback ID
2.	Cust_Name	Varchar	50	Not Null	Customer Name
3	Cust_Email	Varchar	30	Not Null	Customer Email
4	Cust_Mobile	Int	10	Not Null	Customer Mobile
5	Feedback	varchar	50	Not Null	Feedback/comment

4.14 Test Procedures and Implementation
1. Unit Testing
Unit testing concentrates verification on the smallest element of the program – the module.  Using the detailed design description important control paths are tested to establish errors within the bounds of the module.
In the system each sub module is tested individually as per the unit testing such as campaign, lead, contact etc. are tested individually. Their input field validations are tested.
2. Integration testing	
Once all the individual units have been tested there is a need to test how they were put together to ensure no data is lost across interface, one module does not have an adverse impact on another and a function is not performed correctly. 
After unit, testing each sub module is tested with integrating each other. 

System testing for the current system:
In this level of testing, we are testing the system as a whole after integrating all the main modules of the project. We are testing whether system is giving correct output or not. All the modules were integrated and the flow of information among different modules was checked. It was also checked that whether the flow of data is as per the requirements or not. It was also checked that whether any particular module is non-functioning or not i.e. once the integration is over each and every module is functioning in its entirety or not.
    In this level of testing, we tested the following: -
•	Whether all the forms are properly working or not.
•	Whether all the forms are properly linked or not.
•	Whether all the images are properly displayed or not.
•	Whether data retrieval is proper or not.

Specific knowledge of the application's code/internal structure and programming knowledge in general is not required. The tester is aware of what the software is supposed to do but is not aware of how it does it. For instance, the tester is aware that a particular input returns a certain, invariable output but is not aware of how the software produces the output in the first place. 
Test Cases
Test cases are built around specifications and requirements, i.e., what the application is supposed to do. Test cases are generally derived from external descriptions of the software, including specifications, requirements and design parameters. Although the tests used are primarily functional in nature, non-functional tests may also be used. The test designer selects both valid and invalid inputs and determines the correct output without any knowledge of the test object's internal structure.
Test Design Techniques
Typical black-box test design techniques include:
•	Decision table testing
•	All-pairs testing
•	State transition Analysis
•	Equivalence partitioning
•	Boundary value analysis
•	Cause–effect graph
•	Error guessing
•	Advantages
•	Efficient when used on large systems. 
•	Since the tester and developer are independent of each other, testing is balanced and unprejudiced. 
•	Tester can be non-technical. 
•	There is no need for the tester to have detailed functional knowledge of system. 
•	Tests will be done from an end user's point of view, because the end user should accept the system. (This testing technique is sometimes also called Acceptance testing.) 
•	Testing helps to identify vagueness and contradictions in functional specifications. 
•	Test cases can be designed as soon as the functional specifications are complete. 

Disadvantages
•	Test cases are challenging to design without having clear functional specifications. 
•	It is difficult to identify tricky inputs if the test cases are not developed based on specifications. 
•	It is difficult to identify all possible inputs in limited testing time. As a result, writing test cases may be slow and difficult. 
•	There are chances of having unidentified paths during the testing process. 
•	There is a high probability of repeating tests already performed by the programmer.
1] Test case For Admin Login Page:
Project Name: online Shopping)
Prepared Date: - 24-04-2022      Prepared By: - 
Module Name: Login.               Reviewed Date: - 24-04-2022   
Project Code: OJS

Total no of test Cases: -04
			Total no of test Cases Passed: -04
			Total no of test Cases failed: -00
			Total no of test Cases executed: -04
			Total no of test Cases pending: -00



Test Case ID	Test Case Procedure	Input
Data	Expected
Output	Actual Output	Test
Status
OJS-LG-01	Checking the functionality of Admin LOGIN Button	1.Enter valid Usernames in textbox
2. Enter valid Password in textbox  
3. Click on Admin LOGIN Button	Admin Panel should be displayed	Admin Panel should be displayed	Pass
OJS   -LG-02	Checking the functionality of Admin LOGIN Button	1.Enter invalid User Name in text box  
2. Enter valid Password in password textbox
3. Click on Admin LOGIN Button	Admin Panel should not be displayed	Admin Panel should not be displayed	Pass















OJS   -LG-03	Checking the functionality of Admin LOGIN Button	1.Enter valid User name in User name textbox  
2. Enter invalid Password in password textbox
3. Click on Admin LOGIN Button	Admin Panel should not be displayed	Admin Panel
 is not displayed	Pass
OJS -LG-04	Checking the functionality of Admin LOGIN Button	1.Enter invalid User name in User name textbox  
2. Enter invalid Password in password textbox
3. Click on Admin LOGIN Button	Admin Panel should not be displayed	Admin Panel
 is not displayed	Pass
























5. USER MANUAL
5.1. USER MANUAL

Firstly, user have to open the Online Shopping Website then user can see the various Products according to Product categories. User can see products with its features and description with its price. If user wants to order the product they have to login the account and if they are not already register themselves then they have to create account and login.

After login to page user can order the product  by adding product in cart. They can do the payment process by cash or by debit/credit card. After payment process, they receive the order confirmation message and within some specific time or day’s user can receive their product order.

To order some other product  that is not displayed on website then user can do the inquiry by calling to staff of shop contact information will be giving on the website. The contact details are shown in the website contact us menu. 

5.3	Operational Manual/Menu Explanation
5.2.1 Admin mainly

•	My Dashboard: Using this option admin switch to his main dashboard page.
•	Profile: In this admin can view and edit his profile & change password.
•	Manage: This option provides Add, Edit & Delete option functionality for Customer, Delivery Boy, Product, Product Category
•	View: This option provides Search option functionality for Customer, Product, Category
•	Feedback: This shows all feedback given by members


5.2.2 Customer 
•	Website: In that when user open the site then hi can see the menus of register, login, feedback about us, contact us.
•	My Account: When customer Register, he can see his/her account details and modify or he can see the order details which he will be placed
•	Account Settings: In account setting, he can see the account details means his/her name password, username, mobile number and they can edit the details.
•	Address Settings: In that customer can see the address where product will be shipping. Customer can change the address details.

DRAWBACKS AND LIMITATIONS
1.	Security shipping –
 The security of your payment is a serious issue and you have to make sure it is properly deal with by checking the security policy of the online shop. In many cases though, the supplier is as exposed to fraud, as the customer and even more, since he has to ship an expensive product before the payment is cleared. The customer has 3 to 7 days’ window to cancel the payment, while the shipping is irreversible. The shipping and insurance are handled by the supplier/admin and in most cases is free of charge. 
PROPOSED ENHANCEMENT

There are many places where we can improve. The following are the features that we are about to implement in near future.

1. In future, we provide search facilities like category wise searching or price wise searching.

2. Provide notifications to user about offers and discounts
3. We can develop mobile application for most of the users who uses smart phones rather than browsers.
4. In the future, I want to Enhanced my project with thee admin part of online jewellery shopping. 
5. Add more product  types in web site. 

CONCLUSION
                     In the fast-moving life where people do not have time to shop manually, online shopping has emerged as a time saving and convenient way of shopping. The increase trend of online shopping will only grow and expand in the future.  It concludes that people have substituted their needs to shop at local stores by shopping online. Customer is the king for every business and nobody wants to lose the profitable customers. The online shopping system provides various features to your customers to keep in the list of your 'regular customers’. Customers can enjoy the convenience of ordering Product online while sitting at their homes/offices. 

	The Online shopping System upload their product online so that they can be easily managed or changed and customers can order online. Customer can add products to shopping cart or order the product online. Discount can be given to product in online system and we can purchase the new fashion of the product.

	










BIBLIOGRAPHY

1. www.scribd.com
2.www.w3school.com
3. www.htmltutorial.com
4.www.csstutorial.com
5.www.caratlane.com
6. www.stackoverflow.com








