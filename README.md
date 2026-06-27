# kangseyoung

[Korean README](./README.ko.md)

## DevOps Engineer in Progress

I am studying DevOps with a focus on Linux, infrastructure operations, monitoring, and troubleshooting.

My background started in Visual Communication / Animation at Hongik University Sejong Campus. Later, I added Computer Science as a double major. While working on pipeline and render farm projects, I became more interested in the systems behind the tools: servers, shared storage, logs, worker status, and failure handling.

My long-term goal is to become a DevOps engineer. Right now, I am trying to build that foundation through SRE-style operational experience: checking logs, understanding infrastructure components, monitoring system state, and writing down how to respond when something breaks.

## Current Focus

- Linux operation and shell scripting
- AWS infrastructure basics: VPC, EC2, ALB, Security Group, IAM, CloudWatch
- Docker and Nginx basics
- Monitoring, logs, job/worker status, and troubleshooting
- Deployment flow and operational documentation
- Long-term interest in semiconductor IT / FAB infrastructure operations

## Projects

### [AWS Thinkbox Deadline Render Farm Infrastructure](https://github.com/kangseyoung/deadline-renderfarm-automation)

Built and operated an on-premise render farm environment using AWS Thinkbox Deadline in a university lab.

- Used around 20 lab PCs, a server PC, NAS shared storage, and DCC render licenses.
- Built a PySide UI so students could submit and check render jobs more easily.
- Checked job status, Worker status, failed jobs, error codes, logs, and MongoDB job data.
- Troubleshot Worker connection issues, NAS path issues, port/firewall settings, and license problems.
- The tool was used by around 40 students during the graduation project period.
- Tested Ansible and Docker during the project, but they were not part of the final core setup.

This was not an AWS cloud production deployment. It was an on-premise render farm infrastructure project using AWS Thinkbox Deadline.

### AWS Infrastructure Practice

I am currently practicing AWS infrastructure setup while focusing on how each component works and how to check problems.

- VPC, public/private subnets, routing, Security Groups
- EC2, Docker, Nginx, ALB
- IAM basics
- CloudWatch monitoring and log checking
- Manual setup practice to understand the role of each component

### [Phoenix Pipeline Tool](https://github.com/carlton368/phoenix_pipeline_tool)

A Python / PySide-based VFX pipeline tool project.

- Worked on login, loader, publisher, and saver UI flows.
- Handled Maya/Nuke environment setup and Linux `.desktop` launch flow.
- Looked into ShotGrid API integration patterns.
- Focused on making the tool structure easier to run, inspect, and maintain.

### Pipeline Automation Tools

During the Netflix Academy bootcamp and university projects, I worked on Linux-based pipeline automation using Python, Shell, and PySide.

- Connected DCC workflows, render submission, shared paths, and job metadata.
- Took a team lead role in a project.
- Worked on making the tool usable in an actual student production environment.

### AI / Web Side Projects

I have also worked on AI-assisted tools and web UI experiments, but they are not my main direction now.

- [Lecture Companion Agent](https://github.com/kangseyoung/Lecture-Companion-Agent): PDF-based study note generation workflow
- [Landing Agent Harness](https://github.com/kangseyoung/landing-agent-harness): landing page workflow prototype
- [Capstone Repo Polisher](https://github.com/kangseyoung/capstone-repo-polisher): repository cleanup and documentation workflow

## Tech Stack

**Operations / DevOps**  
Linux, Shell Script, Docker, Nginx, Git, GitHub

**Infrastructure / Cloud**  
AWS, VPC, EC2, ALB, Security Group, IAM, CloudWatch

**Monitoring / Troubleshooting**  
Log inspection, job/worker status tracking, error checking, operational notes

**Programming / Automation**  
Python, PySide6 / PySide2, JavaScript / TypeScript

**Render Farm / Pipeline**  
AWS Thinkbox Deadline, MongoDB, NAS-based workflow, Maya, Blender, Arnold

## Direction

I want to grow toward DevOps engineering by first becoming comfortable with real operation work: Linux servers, infrastructure setup, monitoring, logs, and troubleshooting.

I am also interested in infrastructure operation work in semiconductor IT / FAB environments, especially server and equipment monitoring, log analysis, incident response, and operation automation.
