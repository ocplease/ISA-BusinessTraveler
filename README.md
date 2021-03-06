## SECTION 1 : PROJECT TITLE
## Business Traveler

<img src="./img/snapshot1.png"
     style="float: left; margin-right: 0px;" />

---

## SECTION 2 : EXECUTIVE SUMMARY
According to statistics, the cost of business trip expenditure accounts for about 28% of the total corporate expenditure, and has become the second largest controllable cost of an enterprise. The following graph shows the business trip cost one day in top5 expensive Asia city, as we can see , hotel cost has occupied a significant part(over 50%) among all the main business trip costs like hotel meals and transportation. As a result, the primary task for business trip process and cost optimization is to optimize the process and management for the internal business trip hotel booking for an enterprise.

<img src="./img/snapshot2.png"
     style="float: left; margin-right: 0px; height:600px" />


 *Fig 1-1: Business Trip Cost composition in major Asia Cities*

 Nowadays, there are three main types of business trip hotel booking process in different companies according to their different scale and business trip management of an enterprise. 

Firstly, for most of the large company , with adequate budget in business trip management system/ platform, the employee can search and book hotel directly by their own through internal business trip management system/platform. employees don’t need to advance payment for their business trip expense, therefore the financial process is also optimized by reducing the reimbursement processing and invoice processing. In addition such big company usually have signed cooperation agreement with travel agent so that they can get a discount on the price.

 However for many SME, without enough budget and human resources to implement and maintain a business trip management system/platform, will adopt the following methods to do hotel booking management for employees. One method is employee do advance payment by themselves when booking business trip hotel, then claim reimbursable expense on invoice to the finance, thus the employee get the reimbursement. Another one is booking business trip hotel through internal booking operator. Employees who are going for a business trip will provide his/her hotel reservation information to the booking operator, then booking operator will find out target hotel booking information, send back structured booking information to the requester, finally make a reservation for the hotel  after the booking request is approved and confirmed.

 The pros of the last process is employee don’t need to do advance payment for hotel booking, which can simplify the finance reimbursement process. While the cons is the booking operator need handling large quantities of booking request, reading hundreds of emails, collecting and arranging booking information manually, which are high frequency and repetitive tasks. Manually performing this work is prone to inefficiency and errors.

 Our project team is dedicated in assisting booking operator get rid of the monotonous repetitive task and improving the efficiency and accuracy for the hotel booking process . The solution called Business Traveler – Hotel Booking Agent, introducing robotic process automation(RPA) to process extracting semi-structured data from email, collecting and formatting data into csv file, searching hotel information via different travel agents, comparing the price and writing email for booking confirmation. What’s more, we further use google natural language process API to do name entity recognition from the email text to improve the accuracy of information extraction. 

In this solution, we use RPA to process these high frequency and repetitive tasks, significantly improve work efficiency of booking operator, and by comparing hotel prices among different travel agent we can get a relatively favorable price, further reduce the business trip cost. 

---

## SECTION 3 : CREDITS / PROJECT CONTRIBUTION

| Official Full Name  | Student ID (MTech Applicable)  | Work Items (Who Did What) | Email (Optional) |
| :------------ |:---------------:| :-----| :-----|
| Li Jiayi |           A0215492E           | • Data preprocessing after extracting information from business travelers' email application<br/>• Use web automation to crawl hotel information according to travel needs of business travelers<br/>• RPA Development <br/>• Provide Travel Agent URL and hotel information<br/>• Project report writing – RPA2, Challenge & Recommendation | e0535582@u.nus.edu |
| Lin Xi | A0215403W | • Project idea generation<br/>• Product prototype design <br/>• System architecture design <br/>• RPA Development <br/>• Cloud AI Development <br/>• Project management <br/>• Project report writing | linxi@u.nus.edu |
| Zuo Zhen | A0215464H | System construction implement<br/>UI design & UI implement<br/>System  control logic build<br/>implement of RPA3 for sending email <br/>User guide construction<br/>System integration<br/>System test | e053335554@u.nus.edu |

---

## SECTION 4 : VIDEO OF SYSTEM MODELLING & USE CASE DEMO

[![ISA-Business Traveler](https://res.cloudinary.com/marcomontalbano/image/upload/v1605785567/video_to_markdown/images/youtube--VSkym8S0G6U-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=VSkym8S0G6U&feature=youtu.be "ISA-Business Traveler")

---

## SECTION 5 : USER GUIDE

`Refer to appendix <Installation & User Guide> in project report at Github Folder: ProjectReport`

### To run the system in other/local machine (windows):
#### Requirements


> Enter folder
>
> $ cd SystemCode/
>
> Install dependencies
>
> $ pip install -r requirements.txt
>
> $ pip install --upgrade google-cloud-language
>
> Get your google GOOGLE_APPLICATION_CREDENTIALS
>
> * refer to https://cloud.google.com/natural-language/docs/quickstart-client-libraries
>
> * Create or select a project
>
> - Enable the Google Natural Language API for that project.
> - Create a service account.
> - Download a private key as JSON.
> - Place the JSON file under folder "SystemCode"
> - Rename the JSON file as "proj3NER-0fda29a98082.json"
>
> run the application
>
> $ python main.py

## SECTION 6 : PROJECT REPORT / PAPER

`Refer to project report at Github Folder: ProjectReport`

**Sections for Project Report**

- Executive Summary
- Project Description
  - Project Objective
  - Team Members
- Project Solution
  - Business Process Solution
    - As Is Process
    - To Be Process
  - System Architecture
- Project Implementation
  - User Interface
  - Robotic Process Automation
    - RPA1 Extract Structured Booking Info from Email
    - RPA2 Compare Hotel Price in different Travel Agents
    - RPA3 Send Confirmation Email to Requestor

  * Google Natural Language Process API
- Performance & Validation
- Challenge & Recommendation
  - Challenges
    - Data Acquisition via Web Automation
    - Reaching out to the Business Companies
  - Future Improvements
    - Optimize the screening process
- APPENDIX OF REPORT

---
## SECTION 7 : Miscellaneous

`Refer to Github Folder: Miscellaneous`

---



**Lecturer: [GU Zhan (Sam)](https://www.iss.nus.edu.sg/about-us/staff/detail/201/GU%20Zhan "GU Zhan (Sam)")**

[![alt text](https://www.iss.nus.edu.sg/images/default-source/About-Us/7.6.1-teaching-staff/sam-website.tmb-.png "Let's check Sam' profile page")](https://www.iss.nus.edu.sg/about-us/staff/detail/201/GU%20Zhan)

**zhan.gu@nus.edu.sg**

