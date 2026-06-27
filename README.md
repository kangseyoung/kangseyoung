# kangseyoung

[Korean README](./README.ko.md)

## Aspiring DevOps Engineer with an SRE Foundation

Building reliable systems through Linux operations, monitoring, troubleshooting, and automation.

I started in Visual Communication / Animation at Hongik University Sejong Campus and later added Computer Science as a double major. That background led me to practical pipeline problems: render jobs, shared storage, user-facing tools, Linux-based automation, and infrastructure that real students could use.

My long-term goal is DevOps Engineering. I want to build that path through SRE-style experience first: monitoring, logs, worker/service status, network/security configuration, incident troubleshooting, and operational automation.

## What I'm Focusing On

- DevOps fundamentals: Linux, networking, deployment flow, automation, and operational reliability
- SRE foundations: monitoring, logs, alert thinking, failure analysis, and runbook writing
- Observability: CloudWatch, job/worker status, queued/running/failed states, error codes, and operational logs
- Linux operations: shell scripting, process/log inspection, service setup, and troubleshooting
- AWS infrastructure basics: VPC, EC2, ALB, Security Group, IAM, CloudWatch
- DevOps tools: Docker, Nginx, GitHub workflow, deployment structure
- Infrastructure operations: network/security configuration, deployment flow, and operational checks
- Long-term interest: semiconductor IT / FAB system monitoring, server and equipment status tracking, log analysis, incident response, and operation automation

## Featured Experience / Projects

### [AWS Thinkbox Deadline Render Farm Infrastructure](https://github.com/kangseyoung/deadline-renderfarm-automation)

Built and operated an on-premise render farm infrastructure based on AWS Thinkbox Deadline for a university lab environment.

- Used about 20 lab PCs, a server PC, NAS shared storage, and DCC rendering licenses to support render job submission and management.
- Built a PySide-based UI so students could submit and check render jobs more easily.
- Monitored job status, Worker status, queued/running/failed states, error codes, logs, and job data connected to MongoDB.
- Troubleshot operational issues such as Worker connection failures, NAS shared path problems, port/firewall settings, and license-related failures.
- The system was used by about 40 students during the final graduation project period.
- Also tested Ansible for multi-PC configuration management and Docker for CPU-core-based container separation / Ubuntu runtime experiments. These remained as exploration and future expansion ideas, not the final core architecture.

> This was not an AWS cloud production deployment. It was an on-premise render farm operation project using AWS Thinkbox Deadline.

### AWS Infrastructure / DevOps-SRE Practice Project

Currently studying AWS infrastructure with a DevOps/SRE-oriented focus: how services are deployed, connected, monitored, secured, and troubleshot.

- VPC, public/private subnet structure, routing, Security Groups
- EC2, Docker, Nginx, ALB
- IAM permissions and basic security boundaries
- CloudWatch-based monitoring and log inspection
- Manual infrastructure setup practice with an emphasis on understanding each component and its operational role

### Pipeline Automation Tools with Python / PySide

From the Netflix Academy bootcamp and university pipeline projects, I worked on Linux-based pipeline automation using Python, Shell, and PySide.

- Built tools around DCC workflows, render submission, reservation/login data, shared paths, and job metadata.
- Led a team project and focused on making tools usable in a real production-style environment.
- Connected UI, filesystem paths, database records, and render job states into a practical workflow.

### [Phoenix Pipeline Tool](https://github.com/carlton368/phoenix_pipeline_tool)

Worked on a Python / PySide-based VFX pipeline tool focused on connecting artist-facing UI, DCC environments, and production data flow.

- Built and organized PySide UI modules for login, loader, publisher, and saver workflows.
- Worked with Maya/Nuke environment setup, Linux `.desktop` launch flow, and path/configuration handling.
- Explored ShotGrid API integration patterns for project and production data access.
- Focused on practical pipeline operations: repeatable launch setup, user workflow, error/log inspection, and maintainable tool structure.

### AI / Web Automation Side Projects

I have also built AI-assisted tools and web UI experiments, but they are side projects rather than my main career direction.

- [Lecture Companion Agent](https://github.com/kangseyoung/Lecture-Companion-Agent): PDF-based study note generation workflow
- [Landing Agent Harness](https://github.com/kangseyoung/landing-agent-harness): agent-based landing page workflow prototype
- [Capstone Repo Polisher](https://github.com/kangseyoung/capstone-repo-polisher): repository cleanup and public documentation workflow

## Tech Stack

**DevOps / Operations**  
Linux, Shell Script, Docker, Nginx, Git, GitHub, deployment flow, operational automation

**Infrastructure / Cloud**  
AWS, VPC, EC2, ALB, Security Group, IAM

**SRE / Observability Foundation**  
Monitoring, log inspection, troubleshooting, runbook thinking, CloudWatch, job/worker status tracking

**Programming / Automation**  
Python, PySide6 / PySide2, JavaScript / TypeScript

**Render Farm / Pipeline**  
AWS Thinkbox Deadline, MongoDB, NAS-based workflow, Maya, Blender, Arnold, DCC render licenses

## Career Direction

I want to grow as an engineer who can understand and operate the full path from server and network configuration to monitoring, logs, failure analysis, and automation.

My near-term focus is building SRE-style operational experience: observability, Linux operations, AWS infrastructure basics, incident troubleshooting, and runbook-based automation. My long-term goal is to grow into DevOps engineering, connecting infrastructure, deployment, monitoring, and automation into reliable operating workflows.

I am also interested in applying this direction to semiconductor IT / FAB environments, especially monitoring, log analysis, incident response, and operation automation for servers and equipment-facing systems.
