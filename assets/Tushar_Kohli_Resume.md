**Tushar Kohli**

(817) 781-4904 		[kohli.tushar18@gmail.com](mailto:kohli.tushar18@gmail.com) 	[https\://linkedin.com/in/tusharkohli](https://linkedin.com/in/tusharkohli)     [https\://github.com/Tushar1729-k](https://github.com/Tushar1729-k)  
---

**OBJECTIVE**  Site reliability-focused software engineer building real-time infrastructure and incident-response tooling at 7,500-cluster scale. Go, Kubernetes, ClickHouse, and LLM agents.

**EXPERIENCE**

* Software Engineer III at **Walmart Global Tech Inc.** MetaLake Team, Reliability Engineering Org (REO) Nov 2025 \- *present*  
  * Designed and shipped WCNP Watcher, a real-time Kubernetes inventory service using informer watch streams (client-go), tracking 10 resource types and 10M+ entities across 7,500+ clusters and 6 cloud providers at sub-second ingest latency, sharded across 18 pods.  
  * Exposed Watcher inventory through a GraphQL API, to which I contributed, serving 28 teams and apps, including Resiliency as a Service.  
  * Built the ClickHouse MCP layer and pod-health tools for Triagent, an autonomous incident-triage agent, surfacing root-cause signals from WishLenz (the multi-PB ClickHouse database) to on-call SREs and cutting triage time from 30-45 min to 5 min.  
  * Built 22 persistent Go ingestion services piping API data into Google Cloud AlloyDB (PostgreSQL-compatible) for data-governance compliance.  
  * Consolidated the ingestion services into a monorepo with selective build and deploy, building only changed services and cutting CI/CD time by 50%.  
  * Built and deployed an LLM-powered PR-review bot that polls Slack for GitHub PR links and posts automated feedback. Used by 2 teams (20 engineers), reviewing \~72 PRs/week.  
  * Partnered with the Incident Management Platform team as a backend engineer, writing the queries behind their application-status views for Walmart’s Online, Pickup, and Delivery business: percentage of application pods per region, traffic (GB), and requests per second across 6 regions (SCUS, WUS, EUS, etc.).  
* Software Engineer II at **Walmart Global Tech Inc.**		Post Purchase SRE 	   	         Aug 2023 \- Oct 2025  
  * Owned the Data Query Service (DQS), a Go API layer (WishLenz-Service) giving approved SQL access to WishLenz (ClickHouse), PostgreSQL, AzureSQL, and GraphQL sources, with authentication, rate limiting, and caching. Serves 16 internal customers and 34K+ analytical queries/day.  
  * Built the backend for Wish AI, a GPT-4 incident-triage chatbot on Azure Cosmos DB. Used by \~500 unique users across Walmart teams.  
* Software Engineer Intern at **Snap Inc.**	Content Moderation & Tools Engg Team			  May \- Aug 2022  
  * Integrated Guard (Snap's company-wide RBAC/IAM service) into Storyteller, the internal tool for monitoring public Stories on Discover and Spotlight, replacing the hard-coded ACL service and cutting authorization API latency from 500 ms to 4 ms (React, Go/gRPC).  
  * Deployed the Guard client as a gRPC auth-sidecar in a Docker container in each Storyteller pod on Snap's Kubernetes service mesh, so every request to the service is authorized.  
* Software Engineer Intern at **The Home Depot**	IT Finance SRE Team			 	  May \- Aug 2021  
  * Built a full-stack application using Angular, Spring Boot REST APIs, MySQL on GCP, and Jenkins CI/CD.  
  * Automated alert-threshold changes for Home Depot's financial systems, replacing a manual, alert-by-alert update process; demoed regularly to senior leadership.

**EDUCATION**  
	**University of Texas at Austin (UT)**		 	 	  	       		       Aug 2019 \- May 2023  
	Bachelor of Science in Computer Science, Concentration in ML & AI, Certificate in Applied Statistical Modeling  
Overall GPA:  3.60

**HONORS**	Excellence Award for Operational Excellence, Walmart Global Tech (January, 2024): recognized for building a Python metrics pipeline that collates metrics from external teams such as Last Mile Delivery.

**SKILLS / TOOLS**

* Proficient:  Go, Java, C, C++, React, Next.js, Nest.js, Azure Cosmos DB, Python, TypeScript, Docker, Kubernetes  
* Familiar with: iOS Swift, HTML, CSS, GCP, Jenkins, Unity, gRPC, AWS, Bazel  
* Tools:  Cursor, VS Code, IntelliJ, Jira, GitHub  
* Software Engineering:  Working knowledge of SCRUM, DevOps/ SRE practices, security principles (IAM access control)