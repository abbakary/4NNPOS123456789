# TODO: Improve Edit Vehicle and Customer Edit Pages

## Tasks
- [x] Update customer_edit.html to use full width (col-12) and improve layout organization
- [x] Update vehicle_form.html to use full width (col-12) and better field spacing
- [ ] Test the updated layouts for responsiveness and full space utilization

## Completed
- [x] Analyze current templates and identify issues
- [x] Create improvement plan
- [x] Get user approval for plan



# ARDHI UNIVERSITY
# DEPARTMENT OF COMPUTER SYSTEMS AND MATHEMATICS
# INDUSTRIAL TRAINING REPORT

**Student Name and Registration Number:** MASSAWE, John (22201/T.2023)  
**Company/Organization Name:** Superdoll Trailer Manufacturing Co. Ltd.  
**Company Physical Address:** Along Nyerere Road, Dar es Salaam  
**Industrial Supervisor's Name:** Mr. Justin Frank  
**University Supervisor's Name:** Mr. Daud Fayi  
**Training Period:** [Insert Start Date] to [Insert End Date]

---

## ABSTRACT

This industrial training report provides a comprehensive summary of the practical experience acquired during my attachment at Superdoll Trailer Manufacturing Co. Ltd., within the Information and Communication Technology (ICT) Department. The primary objective is to bridge theoretical knowledge from Ardhi University with real-world ICT practices, fostering professional growth and technical competence.

The training encompasses a wide range of ICT functions, with a major focus on full-stack software development using the Django framework. The core project involves designing and developing a customer and order management tracking system. This system features advanced modules for automated invoice data extraction and digital signature integration, aimed at streamlining workflows and enhancing data accuracy.

Additional responsibilities include providing routine IT support—troubleshooting hardware and software issues, configuring systems, and assisting with network tasks—and gaining proficiency in Microsoft technologies like Power Apps and SharePoint for process automation and collaboration.

Key achievements include the successful development and deployment of functional system modules that reduce manual data entry, minimize errors, and improve operational efficiency. The training also presents several challenges, such as adapting to new technologies under time constraints and navigating limited resources, which I overcome through self-directed learning, supervisor consultation, and collaborative problem-solving.

Overall, the attachment is immensely beneficial. It significantly strengthens my software development skills, deepens my understanding of ICT operations in a manufacturing setting, and enhances my professional soft skills.

---

## ACKNOWLEDGEMENT

I begin by expressing my profound gratitude to God Almighty for granting me the strength, wisdom, and good health necessary to successfully complete this industrial training.

My sincere appreciation goes to Ardhi University and the Department of Computer Systems and Mathematics for providing this invaluable opportunity to gain practical experience. I am particularly indebted to my University Supervisor, Mr. Daud Fayi, for his unwavering guidance, insightful feedback, and consistent support throughout the attachment period.

I extend my heartfelt thanks to Superdoll Trailer Manufacturing Co. Ltd. for hosting me. I am especially grateful to my Industrial Supervisor, Mr. Justin Frank, for his exceptional mentorship, patience, and for generously sharing his vast knowledge and professional expertise. His guidance is instrumental in honing my practical skills in software development and ICT operations.

I also wish to thank the entire staff of the ICT Department for their cooperation, support, and camaraderie. Their assistance and willingness to collaborate greatly enrich my learning experience.

Finally, I appreciate my colleagues and fellow students for their teamwork and the shared learning journey, which makes the training period both productive and enjoyable. This experience is a cornerstone in my academic and professional development, and I am truly thankful to all who contribute.

---

## TABLE OF CONTENTS

ABSTRACT ........................................................................................................................ ii  
ACKNOWLEDGEMENT .................................................................................................. iii  
TABLE OF CONTENTS ................................................................................................... iv

CHAPTER 1: INTRODUCTION ...................................................................................... 1  
1.1 Organization Background ........................................................................................ 1  
1.2 Vision and Mission .................................................................................................. 1  
1.3 Organizational Structure and the Role of the IT Department ................................. 1  
1.4 Assigned Tasks and their Relevance to IT ............................................................. 2

CHAPTER 2: ASSIGNED TASKS .................................................................................. 3  
2.1 Development of a Customer and Order Management System (Django) ............... 3  
2.2 Automated Invoice Upload and Data Extraction Module ...................................... 5  
2.3 Digital Signature Integration .................................................................................. 6  
2.4 Use of Microsoft Power Apps and SharePoint ....................................................... 7  
2.5 Routine ICT Support and Technical Assistance ..................................................... 7

CHAPTER 3: CHALLENGES ........................................................................................ 8  
3.1 Psychological Challenges ...................................................................................... 8  
3.2 Physical Challenges ............................................................................................... 8  
3.3 Technical Challenges ............................................................................................. 9  
3.4 Suggestions for Future Trainees and the Department ........................................... 9

CHAPTER 4: RECOMMENDATIONS AND CONCLUSION ........................................ 10  
4.1 Recommendations for Future Learning ................................................................ 10  
4.2 Recommendations for Task Assignment and Internship Procurement ................. 10  
4.3 Recommendations for the Industrial Training Program ........................................ 11  
4.4 Conclusion ............................................................................................................ 11

REFERENCES ................................................................................................................ 13

---

## CHAPTER 1: INTRODUCTION

### 1.1 Organization Background

The industrial training takes place at Superdoll Trailer Manufacturing Co. Ltd., a leading manufacturer of heavy-duty trailers located along Nyerere Road in Dar es Salaam, Tanzania. Established in 1992, Superdoll is one of the most reputable and long-established manufacturing companies in East and Central Africa. It specializes in the production of trailers, distribution of vehicle spare parts, and provision of automotive technical services.

### 1.2 Vision and Mission

**Vision:** To be the leading provider of innovative, safe, and reliable transport solutions in Africa.

**Mission:** To deliver high-quality products and services that meet global standards while providing exceptional value, durability, and customer satisfaction through continuous improvement, modern technology, and professional expertise.

### 1.3 Organizational Structure and the Role of the IT Department

Superdoll operates through several key departments, including Trailer Manufacturing, Spare Parts Division, Technical Services, Sales and Marketing, and the Information and Communication Technology (ICT) Department. The ICT Department serves as the technological backbone of the company. Its core responsibilities include:

- Managing and maintaining the company's computer network and server infrastructure
- Developing and supporting enterprise applications used in production, sales, and service centers
- Providing technical support and training to staff across all departments
- Managing telematics and tracking platforms for fleet and logistics monitoring
- Ensuring data security, system backups, and network integrity

### 1.4 Assigned Tasks and their Relevance to the IT Department

During the attachment, I am assigned to the ICT Department and engage in tasks directly aligned with its objectives. My primary focus is on software development, where I contribute to building a Django-based customer and order management system. This project involves creating modules for automated invoice processing and digital signatures, aimed at digitizing and streamlining internal workflows. Additionally, I participate in routine IT support, including troubleshooting hardware and software issues, and gain experience with Microsoft Power Apps and SharePoint to support business process automation. These tasks are highly relevant as they contribute directly to the department's goals of improving efficiency, enhancing data management, and supporting the company's digital transformation.

---

## CHAPTER 2: ASSIGNED TASKS

### 2.1 Development of a Customer and Order Management System (Django)

**a) Problem Being Solved**
The company manages numerous customer records, service requests, and order transactions daily. Much of this information is handled using manual or semi-manual methods such as spreadsheets and physical files. This leads to delays, difficulty in tracking orders, data inconsistency, and challenges in retrieving historical records.

**b) Weaknesses of the Old System**
- **Time-Consuming:** Manual entry and searching for records are slow
- **Prone to Errors:** Data inconsistency and transcription errors are common
- **Lack of Transparency:** Difficulty in tracking the progress of orders or service requests across different units
- **Poor Data Centralization:** Information is siloed in different files or with different officers

**c) Proposed Solution**
I propose the development of a centralized, web-based Customer and Order Management System using the Django framework. The system is designed to digitalize the entire workflow, from customer registration to order fulfillment and tracking.

**d) Implementation Approach**
- I design and implement database models for Customers, Orders, Invoices, and Service Tracking
- I develop user-friendly interfaces for data entry, querying, and dashboard overviews using Django templates and Bootstrap
- I implement user authentication and role-based access control to secure sensitive information
- I integrate activity logs to track all changes and updates to orders

**e) Tools and Technologies Used**
- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Database:** SQLite (Development)
- **Version Control:** Git and GitHub

**f) Results and User Feedback**
The system significantly reduces the time required to process and track orders. Users appreciate the intuitive interface and the ability to access real-time information. Supervisors acknowledge the system's potential to enhance departmental productivity and data-driven decision-making.

**g) Benefits**
- **To the Organization:** It improves operational efficiency, enables better record-keeping, and enhances transparency between departments
- **To Me:** I gain hands-on, end-to-end experience in full-stack web development and project lifecycle management

### 2.2 Automated Invoice Upload and Data Extraction Module

**a) Problem Being Solved**
The manual extraction of key details (e.g., customer name, invoice number, amount) from uploaded invoices is a tedious and error-prone task for the administrative staff.

**b) Weaknesses of the Old Approach**
- High potential for human error during data entry
- Significant time spent on a repetitive, low-value task
- Difficulty in archiving and searching digital invoices systematically

**c) Proposed Solution**
I develop an automated invoice processing module within the Django system. This feature allows users to upload invoice images or PDFs, from which the system automatically extracts structured data and populates the relevant database fields.

**d) Implementation Approach**
- I create a secure file upload interface
- I implement text parsing logic using Python libraries to identify and extract key data points from the invoice documents
- I map the extracted data to the corresponding order and customer models

**e) Tools and Technologies Used**
- Python (Django, text parsing libraries)
- Django Models and Views

**f) Results and Feedback**
The module drastically reduces the manual workload and improves data accuracy. Staff feedback is overwhelmingly positive, highlighting the time saved and the reduction in entry mistakes.

**g) Benefits**
- **To the Organization:** It accelerates invoice processing and improves data integrity
- **To Me:** I acquire practical skills in data extraction, automation, and handling file uploads in a web application

### 2.3 Digital Signature Integration

**a) Problem Being Solved**
Many processes, such as order approvals and service confirmations, require handwritten signatures, which is slow and requires physical presence.

**b) Weaknesses Identified**
- **Delays:** Approval workflows are stalled awaiting physical signatures
- **Inconvenience:** It requires personnel to be physically present to sign documents
- **Poor Audit Trail:** Difficulty in maintaining and verifying a secure log of signed documents

**c) Proposed Solution**
I integrate a digital signature module into the management system, allowing authorized users to sign documents electronically directly within the platform.

**d) Implementation**
- I develop a signature capture interface using HTML5 Canvas
- I implement backend logic to securely store the signature as a unique hash
- I link digital signatures to specific documents and transactions for verification

**e) Tools and Technologies Used**
- HTML5 Canvas
- Django Backend
- Cryptographic hashing for security

**f) Benefits**
- **To the Organization:** It enables faster approval cycles, reduces reliance on paper, and creates a more robust audit trail
- **To Me:** I gain an understanding of implementing security features and digital workflow automation

### 2.4 Use of Microsoft Power Apps and SharePoint

I assist in creating simple business applications using Microsoft Power Apps to automate minor data collection tasks for the spare parts and sales departments. I also utilize SharePoint to help organize departmental documents and improve internal collaboration, which provides me with valuable experience in low-code development platforms and enterprise content management.

### 2.5 Routine ICT Support and Technical Assistance

My duties also include providing first-line IT support to staff. This involves:
- Troubleshooting software and hardware issues
- Installing and configuring operating systems and applications
- Assisting with network connectivity problems
- Setting up and maintaining peripherals like printers and scanners

These tasks are crucial in developing my problem-solving skills and ability to communicate effectively with non-technical users.

---

## CHAPTER 3: CHALLENGES

### 3.1 Psychological Challenges

- **Initial Anxiety and Pressure:** Adapting to a professional corporate environment and meeting the expectations of supervisors is initially intimidating
- **Communication Gaps:** At times, there is a lack of clear communication regarding task requirements or changes in project scope, leading to moments of uncertainty and rework

### 3.2 Physical Challenges

- **Resource Limitations:** On some occasions, there is a shortage of dedicated functional computers or necessary software licenses, which occasionally delays my development work
- **Infrastructure Issues:** Intermittent internet connectivity and occasional power outages in an industrial setting disrupt workflow and access to online resources

### 3.3 Technical Challenges

- **Steep Learning Curve:** While familiar with the basics, mastering the Django framework and integrating complex features like data extraction within a tight timeline is demanding
- **Task Complexity:** Some assigned problems require solutions that are beyond my initial skill level, necessitating intensive independent research and learning
- **Legacy Systems:** Interfacing with or understanding some of the company's existing legacy systems in the manufacturing unit poses a challenge due to a lack of documentation

### 3.4 Suggestions for Future Trainees and the Department

**For Future Trainees:**
- Proactively research the host organization's potential technology stack before starting the attachment
- Develop strong self-learning habits to quickly adapt to new tools and technologies
- Maintain open and regular communication with your industrial supervisor to clarify expectations

**For the ICT Department:**
- Consider developing a brief orientation and a structured plan for interns to help them integrate faster
- Where possible, ensure interns have access to reliable hardware and software development tools from the outset

---

## CHAPTER 4: RECOMMENDATIONS AND CONCLUSION

### 4.1 Recommendations for Future Learning

Based on this experience, I identify the following areas for my continued professional development:
- **Advanced Backend Development:** Deepening knowledge in API development, database optimization, and system architecture
- **Cybersecurity Fundamentals:** Gaining formal knowledge in securing web applications and data protection protocols
- **Project Management:** Learning formal methodologies like Agile/Scrum to manage development projects more effectively

### 4.2 Recommendations for Task Assignment and Internship Procurement

- **For the University:** Strengthen partnerships with a wider array of manufacturing and tech companies to provide students with more diverse internship opportunities
- **For Host Organizations:** Provide interns with a "project charter" for their main tasks, outlining objectives, scope, and expected outcomes to give them a clear sense of purpose and direction

### 4.3 Recommendations for the Industrial Training Program

- **Pre-Placement Bootcamp:** The university could organize a short, intensive bootcamp focusing on in-demand skills like web development (Django/Flask), basic networking, and professional ethics
- **Enhanced Supervision:** Implement a structured schedule for mid-term evaluations and site visits by university supervisors to assess progress and address challenges proactively
- **Structured Reporting:** Provide a detailed template for the final report (similar to this one) from the beginning to guide students in documenting their experience effectively

### 4.4 Conclusion

The industrial training at Superdoll Trailer Manufacturing Co. Ltd. is an invaluable experience that successfully bridges the gap between academic theory and professional practice. I gain profound practical skills in full-stack web development, including the design, implementation, and deployment of a functional management system. The exposure to real-world IT support and modern platforms like Microsoft Power Apps further broadens my technical perspective.

Despite facing challenges related to resources and a steep learning curve, the attachment fosters resilience, problem-solving abilities, and professional maturity. The experience not only consolidates my technical knowledge but also provides a clear insight into the critical role of ICT in a manufacturing environment. The skills and lessons learned are instrumental in preparing me for a successful career in the field of information technology, and I am confident that this experience is a significant asset in my future endeavors.

---

## REFERENCES

Django Software Foundation. (2023). *Django documentation*. Retrieved from https://docs.djangoproject.com/

Microsoft. (2023). *Power Apps documentation*. Retrieved from https://docs.microsoft.com/en-us/power-apps/

Microsoft. (2023). *SharePoint documentation*. Retrieved from https://docs.microsoft.com/en-us/sharepoint/

Python Software Foundation. (2023). *Python documentation*. Retrieved from https://docs.python.org/3/

W3Schools. (2023). *HTML, CSS, and JavaScript tutorials*. Retrieved from https://www.w3schools.com/

---

## APPROVAL SECTION

Submitted by:

_________________________
**MASSAWE, John**
Registration No: 22201/T.2023

Approved by:

_________________________
**Mr. Justin Frank**
Industrial Supervisor

_________________________
**Mr. Daud Fayi**
University Supervisor

Date: ____________________

---

**Industrial Training Report - Ardhi University - Department of Computer Systems and Mathematics**
