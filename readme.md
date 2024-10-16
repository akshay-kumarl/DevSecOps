## DevSecOps 
<br/>


![devopstools](https://github.com/user-attachments/assets/fa144312-0386-4dea-9bc9-db819165efcf)


---

1. Version Control Systems (VCS)

   •	**Git:** Popular version control system for tracking changes in code and collaborating with teams. Tools like GitHub, GitLab, and Bitbucket are built on Git.

2. Continuous Integration (CI) / Continuous Delivery (CD)

	•	**Jenkins:** Widely used for automating CI/CD pipelines. Allows integration with various other tools.<br/>
	•	**GitLab CI:** Built-in CI/CD pipeline within GitLab for seamless DevOps processes.<br/>
	•	**CircleCI:** Cloud-based CI/CD service that integrates well with GitHub and Bitbucket.<br/>
	•	**Travis CI:** Another cloud-based CI tool, often used in open-source projects.<br/>
	•	**Azure DevOps:** Microsoft’s cloud platform providing CI/CD pipelines, repos, and more.

3. Configuration Management

	•	**Ansible:** Agentless configuration management tool that uses simple YAML files.<br/>
	•	**Chef:** Automates server provisioning using “recipes” to define configurations.<br/>
	•	**Puppet:** Another tool for configuration management with a focus on system configurations.<br/>
	•	**SaltStack:** For event-driven IT automation and configuration management.

4. Containerization & Orchestration

	•	**Docker:** Most popular containerization tool, enables creating, managing, and running containers.<br/>
	•	**Kubernetes:** Leading container orchestration platform for deploying, scaling, and managing containerized applications.<br/>
	•	**OpenShift:** Red Hat’s Kubernetes-based container platform.<br/>
	•	**Helm:** Kubernetes package manager to manage Kubernetes applications.

5. Infrastructure as Code (IaC)

	•	**Terraform:** Open-source tool by HashiCorp for building, changing, and versioning infrastructure efficiently.<br/>
	•	**CloudFormation:** AWS-specific tool to provision infrastructure using JSON/YAML templates.<br/>
	•	**Pulumi:** An IaC tool that allows infrastructure definitions in general-purpose programming languages.

6. Monitoring & Logging

	•	**Prometheus:** Open-source tool for monitoring and alerting, commonly used with Kubernetes.<br/>
	•	**Grafana:** Visualization tool for metrics from Prometheus, InfluxDB, etc.<br/>
	•	**ELK Stack** (Elasticsearch, Logstash, Kibana): Popular for logging and data visualization.<br/>
	•	**Datadog:** Cloud-based monitoring and analytics platform for infrastructure and applications.<br/>
	•	**Splunk:** Comprehensive tool for searching, monitoring, and analyzing machine-generated data.

7. Security and Compliance (DevSecOps)

	•	**SonarQube:** Continuous inspection of code quality to detect bugs, vulnerabilities, and code smells.<br/>
	•	**Aqua Security:** Secures containerized applications.<br/>
	•	**Snyk:** Finds and fixes vulnerabilities in open-source libraries and container images.<br/>
	•	**HashiCorp Vault:** Manages secrets and protects sensitive data.

8. Collaboration and Communication

	•	**Slack:** For team communication, often integrated with various DevOps tools for alerts and updates.<br/>
	•	**Microsoft Teams:** Another popular communication tool, integrated with CI/CD pipelines.

9. Cloud Platforms

	•	**AWS:** Amazon Web Services, widely used for cloud infrastructure.<br/>
	•	**Azure:** Microsoft’s cloud platform, popular for hybrid cloud environments.<br/>
	•	**Google Cloud Platform (GCP):** Google’s cloud offering, strong in big data and machine learning.

10. Build Automation

	•	**Maven:** Apache tool primarily for building Java projects.<br/>
	•	**Gradle:** Another build automation tool that integrates with popular IDEs and platforms.<br/>
	•	**Ant:** Tool for automating build processes, also popular in Java ecosystems.

11. Artifact Management

	•	**Nexus:** Universal artifact repository manager for storing binaries and build artifacts.<br/>
	•	**Artifactory:** Another widely used repository manager that supports multiple package types.

12. Testing Automation

	•	**Selenium:** Open-source tool for automating web browser interactions.<br/>
	•	**JUnit:** Framework for unit testing in Java.<br/>
	•	**Postman:** For testing APIs in development and CI/CD workflows.

13. Feature Flag Management

	•	**LaunchDarkly:** For feature flagging and managing feature rollouts in production.<br/>
	•	**Flagsmith:** Open-source alternative to manage feature toggles.


---


Vulnerability **IMAGE** Scanner Tool For DevSecOps

Trivy<br/>
Anchore<br/>
DependencyCheck

---

### to check which port is occupied 
```
sudo netstat -tulnp | grep 80
```
