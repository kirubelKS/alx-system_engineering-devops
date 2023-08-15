0x19. Postmortem



Incident Summary 


On August 11th  2023 at 12:30AM EAT our internet experienced an unexpected downtime incident that resulted in service disruption for 3:30 hours. During this time, users were unable to access the internet and use the softwares leading to frustration and inconvenience. This postmortem aims to provide a detailed analysis of the incident, its root causes, mitigations, and preventive measures. 




Timeline of Events: 


12:30AM: The incident was first detected as user reports started flooding in about the internet being unreachable. 
12:35AM: The ICT Department team-initiated investigations, checking server logs and monitoring tools for signs of anomalies. 
12:45AM: It was observed that the server response time was significantly slower than usual. 
1:00AM The DevOps team identified a fall in internet speed on the server hosting the network provider. 
1:30AM: After thorough analysis, it was determined that the downtime in the internet speed was from the internet provider. 
1:35AM: The company that was the internet provider was called to find the root of the problem. 
1:37AM: The internet provider stated via call and email there was a downtime, and it will take time for it to come back. 
10:05AM: The internet was back. 











Root Causes: 


The internet provider having a downtime which then caused their whole client to suffer from internet downtime  


Mitigation Steps:
 
Trying to change the internet provider to the backup. The ICT department had to go to the database and change the port that supplies internet from one internet provider to another to make the organization at least try and go back to normal  
 
 
 
Preventive Measures: 


Regular check of the internet provider internet speeds. Implement regular internet speed checks to ensure that such problems can be detected early to best practices and do not introduce performance issues. 
Ensure the backup provider is working and working well. For future procedures routine check of the backup internet provider is to be done to reduce perfomance whenever the main internet provider experiences downtime  


Conclusion 


The unexpected downtime incident served as a valuable learning experience for the team. By addressing the root causes and implementing effective mitigation and preventive measures, we have taken significant strides toward enhancing the stability and reliability of our web application. The incident has reinforced the importance of proactive monitoring, rigorous testing, and continuous improvement in maintaining a robust web stack. 
 

