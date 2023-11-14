# Initiative Setup

## Problem Identified
This could be identified by the DALL team, an internal NHSBSA customer, or an external customer.

For NHSBSA and external customers, you should log each initiative request through Nhsbsa.dall@nhs.net before starting the work. The DALL team manager normally assigns these initiatives.

Internal ideas can come from the ideas register, exploratory project, or another source. The customer of these initiatives is the DALL team manager unless a customer is found. If you, your critical friend or the DALL team manager has a potential customer in mind, you should setup a meeting with them to explain your ideas and see if they would be interested.

## Assign Critical Friend
Typical DALL initiatives usually involve 1-2 people working on the project. They also choose a "critical friend" to give an extra review of the coding and/or business understanding. They can also attend meetings, check documents and provide extra support and guidance throughout the initiative.

The data scientist usually chooses a critical friend with input from the DALL team manager. The manager knows who is available and has valuable knowledge about the upcoming project.

It is useful to assign a critical friend **as early as possible**. Ideally, they should have prior experience with similar data or techniques. This will help them offer more insight and review the project. If you are an initiative expert, you can choose a new team member as the critical friend so they can gain experience.

Make sure to include them in the project through regular catch ups. This way, they can review your work gradually, instead of all at once. If you can, make sure to give your critical friend as much as notice as possible of work that you will be sending over, to ensure they can make the time to look at it.

## Get Access to the Data
If you don’t have access to the data already, you will need request access. To access the data you need for initiatives, email the DALL data holder and team manager. They will confirm and provide the data from the DALP Oracle database.

If the data is not in DALP or not what you need, you can submit a service request to access to the required data in the DWCP Oracle database.
Advice on how to request data from both sources can be found within the DALL OneNote Wiki [INSERT LINK]. Additionally, tips on how to connect to and use both sources are included here within the [DALL OneNote Wiki](https://nhsbsauk.sharepoint.com/sites/InsightTeam-DataAnalyticsLearningLabDALL/_layouts/OneNote.aspx?id=%2Fsites%2FInsightTeam-DataAnalyticsLearningLabDALL%2FShared%20Documents%2FData%20Analytics%20Learning%20Lab%20%28DALL%29%2FDALL%2FDALL%20-%20Knowledge%20Share%2FDALL%20Wiki&wd=target%28Coding%20and%20Dashboards%2FDatabases.one%7C25F114EE-BC3E-4011-9D41-E56687950354%2FDatabase%20connections%7CB58CCC12-83F6-4643-896C-206477DC24FC%2F%29
onenote:https://nhsbsauk.sharepoint.com/sites/InsightTeam-DataAnalyticsLearningLabDALL/Shared%20Documents/Data%20Analytics%20Learning%20Lab%20[DALL]/DALL/DALL%20-%20Knowledge%20Share/DALL%20Wiki/Coding%20and%20Dashboards/Databases.one#Database%20connections&section-id={25F114EE-BC3E-4011-9D41-E56687950354}&page-id={B58CCC12-83F6-4643-896C-206477DC24FC}&end).

To note, the data stored within DALP is typically static, while it is updated on a regular basis within DWCP. Depending on your use case, you may opt to use the data in DWCP instead, if the work needs to be repeated on a regular basis. **You must be careful when using DWCP data. Running SQL queries may slow down production systems**.

Finally, on occasion, data may come from additional locations such as internal spreadsheets. **You must store the data securely in SharePoint and never access it on your personal laptop**.

## Initial Research and Look at Previous Iterations
If you have the data, analysing it for insights and limitations will help you understand what is possible for the initiative.
As an aside, look at previous initiatives conducted in the team, these can be identified using JIRA and by asking around within the team. Your critical friend and the DALL team manager may be able to assist here too. This is especially helpful for understanding the business in the area you're focused on and the data you'll be using.

Additionally, online resources may help here such as Stack Overflow, Medium and other websites. There is also the NHS-R and government slack channels that you can use to message other data scientists and statisticians for advice. It is likely that your initiative has been conducted by another individual or company.

For technical projects such as machine learning based initiatives, research papers may assist. These can guide what is possible and what is not, given the data you have available.  If you're trying something new, consider taking a course from Data Camp to learn before starting.

## Initial Meeting with the Customer
It is important to setup a first meeting with the customer once you have an initial understanding of initiative. If you are unsure who to invite to the meeting, you can ask your critical friend, the DALL team manager, or other colleagues. During this meeting, you can identify:

* What they are looking to do within the initiative,
* What outputs they are expecting to see, in which format,
* Any business knowledge or insights they can provide to aid your work,
* Any data limitations and possible solutions,
* If there are any additional data sources to be considered and
* The required timescales if applicable.

This meeting is important, as it can help to inform the problem definition within section 2. If the work is particularly urgent, more colleagues and resource can be assigned to the initiative accordingly.

Note that some customers will have busy schedules so it is important to setup the meeting in advance so the project can progress. You should invite your critical friend to the meeting, so they can provide additional insight from prior work and understand the ask.

Following this meeting, it may be useful to setup a reoccurring follow up meeting to keep in touch regularly. If you feel like you have questions unanswered following the meeting, make sure to follow on team or email to ask additional questions.

## Create Initiative Resources
Before beginning to work on your problem definition, you will need to setup the initiative resources. Currently, these include:

* A JIRA ticket to track progress on the work,
* SharePoint folder to store documents and data and
* A GitHub repository to store and monitor code.

Before creating these, you will need to identify the DALL number of the initiative. To do this, and for guidance on how to setup the above, please see the DALL OneNote Wiki page [here](https://nhsbsauk.sharepoint.com/sites/InsightTeam-DataAnalyticsLearningLabDALL/_layouts/OneNote.aspx?id=%2Fsites%2FInsightTeam-DataAnalyticsLearningLabDALL%2FShared%20Documents%2FData%20Analytics%20Learning%20Lab%20%28DALL%29%2FDALL%2FDALL%20-%20Knowledge%20Share%2FDALL%20Wiki&wd=target%28Project%20setup.one%7CA67782A4-EFB2-4B50-8584-6A2B8101E998%2FSet-up%20Process%7C4462877D-A630-4688-B4BB-22E364E1CC7B%2F%29
onenote:https://nhsbsauk.sharepoint.com/sites/InsightTeam-DataAnalyticsLearningLabDALL/Shared%20Documents/Data%20Analytics%20Learning%20Lab%20[DALL]/DALL/DALL%20-%20Knowledge%20Share/DALL%20Wiki/Project%20setup.one#Set-up%20Process&section-id={A67782A4-EFB2-4B50-8584-6A2B8101E998}&page-id={4462877D-A630-4688-B4BB-22E364E1CC7B}&end).

When setting up a Github repository, remember to set it to private and invite the DALL team to the project so everyone can make changes. You should write your code with the intention of the repo going public in the future. Therefore, you must be careful not to include PII information within your code, such as NHS numbers.

After creating all resources, remember to provide regular updates to the ticket and repository. This allows the DALL team manager to track progress.
