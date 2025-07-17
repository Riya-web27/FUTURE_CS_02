# FUTURE_CS_02
🛡️ Task 2: Security Alert Monitoring & Incident Response
🔍 Overview
This internship task involved analyzing simulated HTTP log data using ELK Stack (Elasticsearch, Logstash, Kibana) and Splunk to detect unauthorized access attempts, visualize alert patterns, and assess potential privilege escalation behaviors.

🛠️ Tools Used
Elastic Stack (Elasticsearch, Logstash/Filebeat, Kibana)
Splunk Free Trial
Burp Suite
jwt.io
Windows Snipping ToolI

📁 Repository Contents
task-2-security-alert-monitoring.docx – Final incident response report
/screenshots/ – Evidence figures used in the report
/queries/ – KQL filters applied in Kibana for endpoint triage
README.md – Project summary and metadata

✅ Summary of Findings

Repeated 403 Forbidden responses observed for /admin endpoint
IP 192.168.0.1 identified as a consistent actor attempting unauthorized access
Response payload analysis revealed consistent body sizes (~512 bytes)
Visual dashboards showed scanning behavior and potential escalation attempts
Mitigation strategies include response normalization and rate limiting 📘 Developed as part of my cybersecurity internship at Future Interns.
Feel free to explore or reach out for collaboration!
