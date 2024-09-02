# Splunk SIEM Analysis

## Objective
The Splunk analysis project aimed to explore the capabilities of Splunk as a powerful tool for data analysis and security monitoring. The focus was on ingesting various data sources, constructing dashboards, and utilizing Splunk’s search and reporting features to enhance incident response and threat detection.

### Skills Learned
- In-depth understanding of Splunk architecture and data ingestion processes.
- Proficiency in creating dynamic dashboards for real-time data visualization.
- Ability to write complex search queries using the Splunk Search Processing Language (SPL).
- Knowledge of log management and event correlation for cybersecurity analysis.
- Development of analytical skills for interpreting data patterns and anomalies.

### Tools Used
- **Splunk Enterprise** for log ingestion, indexing, and analysis.
- **Splunk Dashboard Studio** for creating interactive visualizations.
- **SPL (Search Processing Language)** for querying and reporting on data.

## Steps

### 1. **Data Ingestion**
   - Screenshots showing the data ingestion process in Splunk.
     
![Screenshot 2024-08-26 at 3 57 15 PM](https://github.com/user-attachments/assets/92935f20-3822-4cb2-8f7b-3926963a75c1)

*Ref 1: Data injestion using the "Add Data" task button followed by the upload option since my data was in a compressed file format on my computer.*

![Screenshot 2024-08-26 at 4 06 04 PM](https://github.com/user-attachments/assets/a08d8ca9-2f5f-42e6-a849-d17bdeb46f2b)

*Ref 2: Select the compressed file on my computer followed by the Next button*

![Screenshot 2024-08-26 at 4 06 45 PM](https://github.com/user-attachments/assets/a9528c47-8fda-4cd8-a9e0-4a30ed27d637)

*Ref 3: Created a new index called "gamestore", saved, and clicked the Review button*

![Screenshot 2024-08-26 at 4 07 12 PM](https://github.com/user-attachments/assets/c8f602b8-4aca-466d-aa63-5dcb39778510)

*Ref 4: Reviewed the information and clicked the Submit button*

![Screenshot 2024-08-26 at 4 07 41 PM](https://github.com/user-attachments/assets/09ec2775-05c6-422b-914c-b47200a5e222)

   *Ref 5: Finished the data uploaded process and ready to start searching*

### 2. **Creating Dashboards**
   - A screenshot of a dashboard created in Splunk illustrating bucket and event metrics.
     
![Screenshot 2024-08-26 at 4 18 42 PM](https://github.com/user-attachments/assets/e2d06111-900f-4123-ac97-73e95e000f5b)

   *Ref 6: Dashboard Metrics* 

### 3. **Search Queries**
   - A screenshot showcasing a complex SPL query used for data analysis to find the ip address of the client with the highest count using an iPad.
     
![Screenshot 2024-08-26 at 4 22 34 PM](https://github.com/user-attachments/assets/64d2b318-cd4d-44c9-a568-405a2ce78f41)

   *Ref 7: Example SPL Query*

### 4. **Event Correlation**
   - A screenshot demonstrating event correlation results in Splunk.
     
![Screenshot 2024-08-26 at 4 29 55 PM](https://github.com/user-attachments/assets/92d9b325-a435-4fb7-834e-96c262aafe5f)

   *Ref 8: Event Correlation Results*


## Proactive Security Implementations

### Overview
In addition to data analysis and incident response, implementing proactive security measures is crucial for organizations. This section explores strategies for detecting past, current, and future threats.

### Threat Detection and Analysis
- Historical Data Analysis: Utilize Splunk to analyze historical logs to identify patterns in past security incidents. This helps organizations understand attacker tactics and improve defenses.

- Current Threat Monitoring: Implement real-time monitoring dashboards in Splunk that display current security events, enabling quick identification of potential threats.

   ![Real-time monitoring dashboard](https://www.splunk.com/content/dam/splunk2/en_us/images/solutions/security-monitoring/extensive-detections-dashboard-embelishment.jpg)

### Predictive Analytics
- Machine Learning Models: Splunk integrates with machine learning tools for sophisticated predictive analytics. It is difficult to detect unknown threats like Advanced Persistent Threats (APTs) and insider threats, which traditional methods often overlook. Splunk User Behavior Analytics (UBA) utilizes unsupervised machine learning to identify unusual behavior patterns that help detect these threats effectively, allowing SOC analysts to focus on critical risks.

   Key Points

   - High Volume of Events: SOCs struggle with a large number of benign security events, overwhelming limited staff.
   - Unknown Threats: Traditional detection methods are inadequate for evolving threats like APTs and insider threats.
   - Splunk UBA: Employs unsupervised machine learning to profile normal user behavior and identify anomalies indicative of potential threats.
   - Anomaly Detection: Splunk UBA generates actionable insights from anomalies, facilitating the identification of threats through various models.
   - Personalized Security Context: The system provides customizable detection rules and watchlists, enhancing the precision of threat detection.

   - Link: [[Machine learning in cybersecurity with Splunk](https://www.splunk.com/en_us/blog/security/elevating-security-intelligence-with-splunk-uba-s-machine-learning-models.html)]

- Anomaly Detection: Utilize Splunk’s capabilities for anomaly detection to identify deviations from normal behavior, which can indicate emerging threats.

   ![UBA Content Overview](https://www.splunk.com/content/dam/splunk-blogs/images/en_us/2024/03/uba-content-overview-1.png)

### Continuous Improvement
- Feedback Loop: Establish a feedback loop based on findings from incident analysis. Use insights gained from past incidents to update security policies and procedures.

- Regular Audits: It is recommended to perform regular audits of security logs and systems to ensure compliance and identify any vulnerabilities that may have been overlooked. Knowing what is happening in your system is vital to keeping it secure.

   - Link: [How to use audit logs and use cases](https://www.splunk.com/en_us/blog/learn/audit-logs.html)

### Case Study
- Gatwick Airport: Operational Insights with Splunk
   -    Challenges: Gatwick Airport needed to make sense of huge amounts of uncorrelated data from disparate sources, which required a full, live overview of airport operations.
   -    Results: By giving more teams at Gatwick access to data, Splunk has improved efficiency and lowered costs while empowering the team.
  
   - Link: [Gatwick Airport: Operational Insights with Splunk](https://www.splunk.com/en_us/customers/success-stories/gatwick-airport.html)

## Conclusion
The Splunk analysis project provided an invaluable opportunity to engage with one of the leading platforms in cybersecurity data analysis. Throughout this project, I gained practical experience in data ingestion, dashboard creation, and advanced querying using SPL. 

By simulating real-world scenarios and analyzing logs, I developed a comprehensive understanding of how to leverage data for effective threat detection and incident response. This hands-on experience has not only enhanced my technical skills but also reinforced the importance of data-driven decision-making in cybersecurity.

Overall, this project has significantly contributed to my ability to think critically about security incidents, recognize patterns in data, and communicate findings through visual dashboards. I am now better equipped to tackle cybersecurity challenges and contribute to organizational security efforts.
