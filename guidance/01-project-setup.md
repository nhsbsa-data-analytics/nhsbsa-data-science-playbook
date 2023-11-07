# Initiative Setup

## Problem Identified
This could be identified by the DALL team, an internal NHSBSA customer, or an external customer.

For NHSBSA and external customers, please log each initiative request through Nhsbsa.dall@nhs.net before starting the work. The DALL team manager normally assigns these initiatives.

Internal ideas can come from the ideas register, exploratory project, or other sources. The customer of these initiatives is the DALL team manager unless a customer is found.

## Assign Critical Friend
Typical DALL initiatives usually involve 1-2 people working on the project. They also choose a "critical friend" to give an extra review of the coding and/or business understanding.

The Data Scientist usually chooses a Critical Friend with input from the DALL team manager. The manager knows who is available and has valuable knowledge about the upcoming project.

It is useful to assign a critical friend as early as possible. Ideally, they should have prior experience with similar data or techniques. This will help them offer more insight and review the project. If you are an initiative expert, you can choose a new team member as the Critical Friend so they can gain experience.

Make sure to include them in the project through regular catch ups. This way, they can review your work gradually, instead of all at once.

## Get Access to the Data
If you don’t have access to the data already, you will need request access. To access the data you need for initiatives, email the DALL data holder and team manager. They will confirm and provide the data from the DALP Oracle database.

If the data is not in DALP or not what you need, you can submit a service request to access to the required data in the DWCP Oracle database. Advice on how to do this and what to say can be found within the DALL OneNote Wiki.

To note, the data stored within DALP is typically static, while it is updated on a regular basis within DWCP. Depending on your use case, you may opt to use the data in DWCP instead, if the work needs to be repeated on a regular basis. Please be careful when using DWCP data. Running SQL queries may slow down production systems.

Finally, on occasion, data may come from additional locations such as internal spreadsheets. Please store the data securely in SharePoint and never access it outside of a virtual machine.

## Initial Research and Look at Previous Iterations
If you have the data, analysing it for insights and limitations will help you understand what is possible for the initiative.
As an aside, look at previous initiatives conducted in the team, these can be identified using JIRA and by asking around within the team. Your critical friend and the DALL team manager may be able to assist here too. This is especially helpful for understanding the business in the area you're focused on and the data you'll be using.

Additionally, online resources may help here such as Stack Overflow, Medium and other websites. It is likely that your initiative has been conducted by another individual or company. For technical projects such as machine learning based initiatives, research papers may assist. These can guide what is possible and what is not, given the data you have available.

If you're trying something new, consider taking a course from Data Camp to learn before starting.

## Initial Meeting with the Customer
It is important to setup a first meeting with the customer once you have an initial understanding of initiative. If you are unsure who to invite to the meeting, you can ask your critical friend, the DALL team manager, or other colleagues. During this meeting, you can identify:

* What they are looking to do within the initiative,
* What outputs they are expecting to see, in which format,
* Any business knowledge or insights they can provide to aid your work,
* Any data limitations and possible solutions,
* If there are any additional data sources to be considered and
* The required timescales if applicable.

This meeting is important, as it can help to inform the problem definition within section 2. If the work is particularly urgent, more colleagues and resource can be assigned to the initiative accordingly.

Note that some customers will have busy schedules so it is important to setup the meeting in advance so the project can progress. It may also be useful to invite your critical friend to the meeting, so they can provide additional insight from prior work and understand the ask.

Following this meeting, it may be useful to setup a reoccurring follow up meeting to keep in touch regularly. If you feel like you have questions unanswered following the meeting, make sure to follow on team or email to ask additional questions.

## Create Initiative Resources
Before beginning to work on your problem definition, you will need to setup all of the initiative resources. Currently, these include:

* A JIRA ticket to track progress on the work,
* SharePoint folder to store documents and data and
* A GitHub repository to store and monitor code.

Before creating these, you will need to identify the DALL number of the initiative. To do this, and for guidance on how to setup the above, please see the DALL OneNote Wiki page here: Project setup  (Web view).

After creating all resources, remember to provide regular updates to the ticket and repository. This allows the DALL team manager to track progress.
