# 📋 JIRA – Complete Guide for Beginners & DevOps Engineers

![Jira](https://img.shields.io/badge/Jira-Project%20Management-blue)
![Agile](https://img.shields.io/badge/Agile-Scrum%20%7C%20Kanban-green)
![DevOps](https://img.shields.io/badge/DevOps-Learning-orange)
![Status](https://img.shields.io/badge/Status-Learning%20Project-success)

A complete beginner-friendly guide to Jira, covering project management, Agile methodology, Scrum, Kanban, Sprint Management, Bug Tracking, JQL Queries, Workflows and DevOps Integration.

---

# 📌 1. What is Jira?

Jira is a project management and issue-tracking tool developed by Atlassian.

It is mainly used by software development teams to plan, track, manage and complete their work.

### Why do we use Jira?

* To manage software development projects.
* To create and assign tasks.
* To track bugs and issues.
* To manage development sprints.
* To monitor team performance.
* To track project progress.
* To collaborate with team members.
* To manage Agile projects.

### Simple Example

Imagine a company is developing a website.

The team has different tasks:

1. Developer creates the login page.
2. Tester checks the login functionality.
3. Tester finds a bug.
4. Developer fixes the bug.
5. Tester verifies the fix.
6. Project manager tracks the progress.

The team can manage all these activities using Jira.

---

# 📌 2. Important Jira Terminology

| Term       | Explanation                           |
| ---------- | ------------------------------------- |
| Project    | Collection of related tasks           |
| Issue      | Any task, bug or story                |
| Epic       | Large feature or requirement          |
| Story      | A feature from the user's perspective |
| Task       | Work that needs to be completed       |
| Bug        | Error in software                     |
| Sub-task   | Smaller part of a task                |
| Sprint     | Fixed development period              |
| Backlog    | List of pending work                  |
| Board      | Visual display of project tasks       |
| Workflow   | Steps followed by an issue            |
| Assignee   | Person responsible for the task       |
| Reporter   | Person who creates the issue          |
| Priority   | Importance of an issue                |
| Status     | Current condition of an issue         |
| Resolution | Final outcome of an issue             |
| Label      | Tag used to organize issues           |
| Component  | Part of a project                     |
| Version    | Software release information          |
| Dashboard  | Displays project information          |

---

# 📌 3. Jira Issue Types

Jira provides different issue types to organize work.

### 1. Epic

An Epic is a large feature that contains multiple stories or tasks.

Example:

* User Authentication System
* Payment Gateway
* E-commerce Website

### 2. Story

A Story describes a feature from the user's perspective.

Example:

* As a user, I want to log in using my email.

### 3. Task

A Task represents general work.

Example:

* Configure AWS EC2 server.
* Create Docker image.
* Configure Jenkins pipeline.

### 4. Bug

A Bug represents an error or problem.

Example:

* Login button is not working.
* Application crashes during deployment.

### 5. Sub-task

A Sub-task represents a smaller part of a larger task.

Example:

Main Task: Deploy Application

Sub-tasks:

* Configure EC2.
* Install Docker.
* Build Docker image.
* Deploy application.

---

# 📌 4. Jira Issue Status

An issue moves through different statuses during development.

| Status      | Meaning                     |
| ----------- | --------------------------- |
| To Do       | Work not started            |
| In Progress | Work is ongoing             |
| In Review   | Work is being reviewed      |
| Testing     | Application is being tested |
| Done        | Work completed              |
| Blocked     | Work cannot continue        |

### Example Workflow

```text
TO DO
  |
  v
IN PROGRESS
  |
  v
IN REVIEW
  |
  v
TESTING
  |
  v
DONE
```

Note: Actual workflow statuses depend on project configuration.

---

# 📌 5. How to Create a Jira Project

Steps:

1. Open Jira.
2. Login to your account.
3. Go to Projects.
4. Click Create Project.
5. Select Scrum or Kanban.
6. Enter Project Name.
7. Select Project Key.
8. Click Create.

Example:

Project Name: DevOps Learning

Project Key: DEV

Now your Jira project is ready.

---

# 📌 6. How to Create an Issue

Steps:

1. Open your Jira project.
2. Click Create.
3. Select Issue Type.
4. Enter Summary.
5. Add Description.
6. Select Priority.
7. Assign the issue to a team member.
8. Click Create.

Example:

Issue Type: Task

Summary: Configure Docker Environment

Description:
Install Docker and configure the environment for application deployment.

Priority: High

---

# 📌 7. Agile Methodology

Agile is a software development methodology in which work is completed in smaller parts.

Instead of developing the entire application at once, teams work in smaller iterations.

### Benefits of Agile

* Faster development.
* Better teamwork.
* Continuous feedback.
* Easy bug tracking.
* Flexible project management.
* Continuous improvement.

### Agile Process

```text
Planning
   |
   v
Development
   |
   v
Testing
   |
   v
Review
   |
   v
Release
   |
   v
Feedback
```

---

# 📌 8. Scrum in Jira

Scrum is an Agile framework where teams work in fixed periods called Sprints.

### Important Scrum Terms

| Term                 | Meaning                      |
| -------------------- | ---------------------------- |
| Product Owner        | Manages product requirements |
| Scrum Master         | Helps the team follow Scrum  |
| Development Team     | Builds the product           |
| Product Backlog      | All planned product work     |
| Sprint Backlog       | Work selected for a Sprint   |
| Sprint               | Fixed development period     |
| Sprint Planning      | Meeting to plan Sprint work  |
| Daily Scrum          | Daily team meeting           |
| Sprint Review        | Demonstrates completed work  |
| Sprint Retrospective | Discusses improvements       |

### Scrum Workflow

```text
Product Backlog
       |
       v
Sprint Planning
       |
       v
Sprint Backlog
       |
       v
Development
       |
       v
Daily Scrum
       |
       v
Sprint Review
       |
       v
Retrospective
```

---

# 📌 9. Sprint Management

A Sprint is a fixed time period during which the team completes selected work.

Usually, a Sprint lasts 1–4 weeks.

### How to Create a Sprint

1. Open your Scrum Board.
2. Go to Backlog.
3. Click Create Sprint.
4. Add issues to the Sprint.
5. Click Start Sprint.
6. Select Sprint duration.
7. Complete the assigned tasks.
8. Click Complete Sprint when finished.

### Example Sprint

Sprint Name: Sprint 1

Duration: 2 Weeks

Tasks:

* Create Login Page.
* Configure Database.
* Fix Login Bug.
* Test Application.

### Sprint Commands / Operations

| Operation       | Use                      |
| --------------- | ------------------------ |
| Create Sprint   | Create a new Sprint      |
| Start Sprint    | Start development        |
| Add Issues      | Add tasks to Sprint      |
| Complete Sprint | Finish Sprint            |
| Sprint Report   | Check Sprint performance |
| Burndown Chart  | Track remaining work     |

---

# 📌 10. Kanban in Jira

Kanban is an Agile method used to visualize and manage continuous work.

Unlike Scrum, Kanban does not require fixed-length Sprints.

### Kanban Board

```text
+------------+-------------+-------------+
|   TO DO    | IN PROGRESS |    DONE     |
+------------+-------------+-------------+
| Task 1     | Task 3      | Task 5      |
| Task 2     | Task 4      | Task 6      |
+------------+-------------+-------------+
```

### Important Kanban Concepts

| Concept    | Meaning                            |
| ---------- | ---------------------------------- |
| Board      | Visual task management             |
| Column     | Work stage                         |
| WIP Limit  | Maximum work allowed in progress   |
| Work Item  | Individual task                    |
| Cycle Time | Time from work start to completion |
| Flow       | Movement of work across columns    |

### Scrum vs Kanban

| Scrum                 | Kanban                     |
| --------------------- | -------------------------- |
| Uses Sprints          | Continuous workflow        |
| Fixed Sprint duration | No fixed Sprint required   |
| Sprint planning       | Continuous planning        |
| Sprint review         | Continuous delivery/review |
| Scrum Master role     | No mandatory Scrum Master  |

---

# 📌 11. Jira Query Language (JQL)

JQL stands for Jira Query Language.

It is used to search, filter and find specific issues in Jira.

JQL is not a terminal command. It is written inside Jira issue search.

### Basic JQL Queries

| Query                      | Explanation               |
| -------------------------- | ------------------------- |
| `project = DEV`            | Find DEV project issues   |
| `status = "To Do"`         | Find pending issues       |
| `status = "In Progress"`   | Find active issues        |
| `status = Done`            | Find completed issues     |
| `priority = High`          | Find high-priority issues |
| `issuetype = Bug`          | Find bugs                 |
| `issuetype = Task`         | Find tasks                |
| `issuetype = Story`        | Find stories              |
| `assignee = currentUser()` | Find my assigned issues   |
| `reporter = currentUser()` | Find issues created by me |
| `assignee IS EMPTY`        | Find unassigned issues    |
| `resolution IS EMPTY`      | Find unresolved issues    |

### Advanced JQL Queries

Find all incomplete bugs:

```jql
issuetype = Bug AND status != Done
```

Find high-priority bugs:

```jql
issuetype = Bug AND priority = High
```

Find my pending tasks:

```jql
assignee = currentUser() AND status = "To Do"
```

Find issues created in the last 7 days:

```jql
created >= -7d
```

Find issues updated in the last 24 hours:

```jql
updated >= -1d
```

Find unassigned issues:

```jql
assignee IS EMPTY
```

Find issues in a particular Sprint:

```jql
sprint = 12
```

Find issues in open Sprints:

```jql
sprint in openSprints()
```

Sort issues by latest creation date:

```jql
ORDER BY created DESC
```

Find high-priority bugs in DEV project:

```jql
project = DEV AND issuetype = Bug AND priority = High
```

---

# 📌 12. Bug Tracking in Jira

Bug Tracking is the process of identifying, reporting, assigning and fixing software problems.

### Bug Tracking Process

```text
Bug Found
    |
    v
Create Bug in Jira
    |
    v
Assign to Developer
    |
    v
Developer Fixes Bug
    |
    v
Testing
    |
    v
Bug Fixed?
   / \
 No   Yes
 |     |
 v     v
Reopen Done
```

### Example Bug Report

| Field       | Value                    |
| ----------- | ------------------------ |
| Issue Type  | Bug                      |
| Summary     | Login button not working |
| Priority    | High                     |
| Environment | Chrome Browser           |
| Status      | To Do                    |
| Assignee    | Developer                |

### Important Bug Fields

* Bug ID
* Bug Summary
* Description
* Steps to Reproduce
* Expected Result
* Actual Result
* Priority
* Severity
* Environment
* Assignee

---

# 📌 13. Jira Workflow

A Workflow defines how an issue moves from creation to completion.

### Example DevOps Workflow

```text
Task Created
     |
     v
To Do
     |
     v
In Progress
     |
     v
Code Review
     |
     v
Testing
     |
     v
Deployment
     |
     v
Done
```

Different projects can have different workflows.

---

# 📌 14. Jira Reports and Charts

Jira provides reports to understand project progress.

| Report                  | Explanation                          |
| ----------------------- | ------------------------------------ |
| Burndown Chart          | Shows remaining Sprint work          |
| Velocity Chart          | Shows completed work across Sprints  |
| Sprint Report           | Shows Sprint results                 |
| Control Chart           | Shows issue cycle and lead times     |
| Cumulative Flow Diagram | Shows work distribution              |
| Created vs Resolved     | Compares created and resolved issues |

### Why are reports important?

* Track team performance.
* Find project delays.
* Monitor Sprint progress.
* Identify bottlenecks.
* Improve future planning.

---

# 📌 15. Jira Automation

Jira Automation helps perform repetitive tasks automatically.

### Examples

1. Automatically assign new bugs.
2. Send notifications when issues change.
3. Update issue status.
4. Notify team members about deadlines.
5. Automatically close eligible issues.

### Example Automation Workflow

```text
Issue Created
     |
     v
Automation Rule
     |
     v
Check Issue Type
     |
     v
Assign Developer
     |
     v
Send Notification
```

---

# 📌 16. Jira + DevOps Integration

Jira is useful in DevOps because it helps track development and deployment activities.

### Example DevOps Pipeline

```text
       JIRA
         |
         v
    Task Created
         |
         v
      GitHub
         |
         v
    Code Commit
         |
         v
      Jenkins
         |
         v
    CI/CD Pipeline
         |
         v
       Docker
         |
         v
    Kubernetes
         |
         v
     Deployment
         |
         v
   Update Jira Issue
```

### Real-World DevOps Example

Task: Deploy Application on AWS EC2.

Sub-tasks:

1. Create EC2 Instance.
2. Install Docker.
3. Build Docker Image.
4. Push Image to Docker Hub.
5. Configure Jenkins Pipeline.
6. Deploy Application.
7. Test Application.
8. Update Jira Task Status.

---

# 📌 17. Important Jira Keyboard Shortcuts

| Shortcut     | Use                     |
| ------------ | ----------------------- |
| `c`          | Create issue            |
| `/`          | Search                  |
| `.`          | Open available actions  |
| `g` then `g` | Go to dashboard         |
| `?`          | Show keyboard shortcuts |

Note: Shortcuts can vary by Jira version and configuration.

---

# 📌 18. Important Jira Interview Questions

**Q1. What is Jira?**

Jira is a project management and issue-tracking tool developed by Atlassian.

**Q2. What is JQL?**

JQL stands for Jira Query Language. It is used to search and filter issues.

**Q3. What is an Epic?**

An Epic is a large feature that can contain multiple stories and tasks.

**Q4. What is a Sprint?**

A Sprint is a fixed development period in Scrum.

**Q5. What is a Backlog?**

A Backlog is a list of pending tasks and requirements.

**Q6. What is Scrum?**

Scrum is an Agile framework where teams work in fixed-length Sprints.

**Q7. What is Kanban?**

Kanban is a visual method of managing continuous work.

**Q8. What is a Workflow?**

A Workflow defines the steps an issue follows from creation to completion.

**Q9. What is the difference between Story and Task?**

A Story describes a user requirement, while a Task represents general work.

**Q10. What is Bug Tracking?**

Bug Tracking is the process of identifying, reporting and fixing software issues.

**Q11. What is an Assignee?**

An Assignee is the person responsible for completing an issue.

**Q12. What is a Reporter?**

A Reporter is the person who creates an issue.

**Q13. What is a Burndown Chart?**

It shows how much work remains in a Sprint.

**Q14. What is Velocity?**

Velocity measures the amount of work completed by a team during a Sprint.

**Q15. How is Jira useful in DevOps?**

Jira helps DevOps teams manage tasks, track bugs, monitor deployment work and coordinate activities.

---

# 📌 19. Practical Jira Tasks for Beginners

Practice these tasks in your Jira account:

* Create a new Jira project.
* Create an Epic.
* Create a Story.
* Create a Task.
* Create a Bug.
* Assign a task to a team member.
* Change issue priority.
* Add comments to an issue.
* Create a Sprint.
* Start a Sprint.
* Move an issue to In Progress.
* Complete a Sprint.
* Create a Kanban board.
* Search issues using JQL.
* Generate a Sprint Report.
* Create a Jira Automation Rule.

---

# 📌 20. Useful Learning Resources

* Official Jira Website: https://www.atlassian.com/software/jira
* Jira Documentation: https://support.atlassian.com/jira-software-cloud/
* JQL Documentation: https://support.atlassian.com/jira-software-cloud/docs/what-is-advanced-search-in-jira-cloud/

---

# 👨‍💻 Author

**Yash Pawar**

Cloud & DevOps Engineer | AWS | Linux | Docker | Kubernetes | Jira

* GitHub: https://github.com/CodewithYash77
* LinkedIn: https://linkedin.com/in/yashpawar11092005
* Portfolio: https://my-portfolio-nine-woad-73.vercel.app

---

⭐ If this repository helps you learn Jira, don't forget to Star this repository!

**Keep Learning | Keep Practicing | Keep Building 🚀**
