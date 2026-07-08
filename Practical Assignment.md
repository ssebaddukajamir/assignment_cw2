# Practical Assignment: Collaborative Software Evolution Using GitHub, DevOps, and CI/CD

### Course

Software Evolution

### Assignment Title

Developing and Evolving a University Student Management System Using Collaborative Software Engineering Practices

## Background

Modern software systems continually evolve to satisfy changing user requirements, technological advances, security demands, and organizational needs. Unlike software developed once and left unchanged, real-world software requires continuous enhancement, maintenance, testing, integration, deployment, and documentation throughout its lifetime. According to Lehman's Software Evolution principles, software that supports real-world activities must continuously adapt to remain useful. Therefore, successful software evolution depends on effective collaboration, version control, software architecture, configuration management, documentation, testing, and automated deployment.

This assignment provides practical experience in collaborative software development and software evolution by requiring students to develop, integrate, maintain, and deploy a complete software system using modern software engineering and DevOps practices.

## Scenario

A software company has awarded your class a contract to develop Version 1.0 of a University Student Management System.

The software must be developed collaboratively by 12 students working as one software development team.

To improve maintainability, scalability, and teamwork, the application will be divided into six software modules.

Each module will be developed by one development team consisting of two students.

Although each team develops a specific module, all twelve students are collectively responsible for delivering one fully integrated software application.

After completing Version 1.0, the software must evolve through enhancements, maintenance, testing, documentation updates, and deployment to produce Version 1.1 (or later), demonstrating real-world software evolution practices.

## Development Teams

The project group consists of 12 students divided into 6 development teams, with 2 students per team.

| Team | Members | Module |
| --- | --- | --- |
| Team 1 | Student 1 & Student 2 | User Authentication and User Management |
| Team 2 | Student 3 & Student 4 | Student Management |
| Team 3 | Student 5 & Student 6 | Course and Department Management |
| Team 4 | Student 7 & Student 8 | Results and Academic Records |
| Team 5 | Student 9 & Student 10 | Reports, Dashboard and Analytics |
| Team 6 | Student 11 & Student 12 | Notifications, Settings, Application Configuration, Integration and Deployment |

## Project Requirements

The complete system shall include:

- User Authentication
- Student Registration
- Course Management
- Academic Records
- Reports and Dashboard
- Notifications
- Database Integration
- REST APIs (where applicable)
- Responsive User Interface
- Security and Validation
- Audit Logs
- Error Handling

## Practical Tasks

### Part A: Software Planning and Architecture (10 Marks)

As one development team of 12 students, perform the following:

- Gather functional and non-functional requirements.
- Design the overall software architecture.
- Identify software modules and their dependencies.
- Produce use case, class, sequence, and deployment diagrams.
- Assign responsibilities to each two-member development team.
- Create one shared GitHub repository.
- Prepare the project README and coding standards.

**Deliverables**

- Software Requirements Specification (SRS)
- Software Architecture Document
- GitHub Repository
- README
- Branching Strategy

This task reinforces software architecture and modular design to support software evolution.

### Part B: Collaborative Module Development (30 Marks)

Each team of two students shall:

- Develop its assigned module independently.
- Create a dedicated Git feature branch.
- Implement frontend, backend, and database functionality.
- Perform unit testing.
- Commit code frequently using meaningful commit messages.
- Push commits to GitHub.
- Submit Pull Requests.
- Participate in peer code reviews.
- Resolve merge conflicts when necessary.

Each module should include:

- User Interface
- Business Logic
- Database Operations
- Validation
- Error Handling
- Unit Tests
- Inline code documentation

This task demonstrates software configuration management and collaborative version control.

### Part C: Configuration Management and Source Control (10 Marks)

Throughout development, students shall apply software configuration management practices by:

- Using Git for version control.
- Maintaining separate feature branches.
- Creating Pull Requests before merging.
- Reviewing code from other teams.
- Managing merge conflicts.
- Tagging software releases.
- Maintaining release history.

Evidence should include:

- Commit history
- Pull Requests
- Branch structure
- Release tags
- Merge history

Students should follow professional branching and merging practices while avoiding common branching anti-patterns.

### Part D: Integration and Software Evolution (15 Marks)

After completing all six modules, the entire group of 12 students shall integrate the modules into one complete application.

Activities include:

- Merge all feature branches into the main branch.
- Perform integration testing.
- Resolve integration issues.
- Release Version 1.0.

After Version 1.0, evolve the software by implementing at least six improvements, such as:

- New functionality
- User interface improvements
- Bug fixes
- Security enhancements
- Performance optimization
- Database improvements
- Code refactoring
- Additional reports
- Improved validation

Each enhancement must be committed, reviewed, tested, documented, and released as Version 1.1 (or later).

This activity demonstrates corrective, adaptive, perfective, and preventive software maintenance while applying Lehman's Software Evolution principles.

### Part E: Continuous Integration, DevOps and Deployment (15 Marks)

The complete application shall be deployed using a CI/CD pipeline.

The deployment workflow should follow:

```
Visual Studio Code
│
▼
Git Repository
│
▼
GitHub Repository
│
▼
Pull Request & Code Review
│
▼
GitHub Actions (Continuous Integration)
│
▼
Automatic Build
│
▼
Automated Unit Tests
│
▼
Integration Tests
│
▼
Continuous Deployment
│
▼
Cloud Deployment Server
(Render / Railway / Azure / AWS / GCP / DigitalOcean)
│
▼
Live Production Application
```

Students must configure GitHub Actions to:

- Build the application automatically.
- Execute automated tests.
- Deploy successfully after passing all tests.
- Maintain deployment logs.

Evidence required:

- GitHub Actions workflow
- Build logs
- Test reports
- Deployment URL
- Screenshots

This task demonstrates DevOps practices, Continuous Integration, Continuous Deployment, and automated software delivery.

### Part F: Software Quality Improvement (5 Marks)

Evaluate the software and improve maintainability by:

- Refactoring duplicated code.
- Reducing complexity.
- Improving modularity.
- Applying coding standards.
- Measuring software quality using appropriate metrics (e.g., complexity, cohesion, coupling).
- Updating documentation where necessary.

Prepare a short report describing the improvements made and their impact.

This activity reinforces software quality, refactoring, code smells, and maintainability.

### Part G: Documentation (10 Marks)

Prepare comprehensive documentation containing:

- Introduction
- Objectives
- Software Requirements
- Architecture Design
- Module Descriptions
- Database Design
- GitHub Workflow
- Branching Strategy
- Configuration Management
- Testing Strategy
- Software Evolution Activities
- Refactoring Activities
- CI/CD Pipeline
- Deployment Process
- Challenges Encountered
- Lessons Learned
- Conclusion

Documentation should be updated throughout the project to support future maintenance and evolution.

### Part H: Team Module Presentations (5 Marks)

Presentations will be conducted by the six development teams, not by individual students.

Each team of two students shall present:

- Module objectives
- Module architecture
- Features implemented
- GitHub branch
- Commit history
- Pull Requests
- Challenges encountered
- Demonstration of the module
- Integration with the overall application

Presentation Time: 10–15 minutes per team.

### Part I: Final Integrated System Demonstration (5 Marks)

After all module presentations, all 12 students shall jointly demonstrate the complete integrated system.

The final presentation should include:

- Complete application walkthrough
- Successful integration of all six modules
- GitHub collaboration workflow
- Branching and merging strategy
- Code review process
- Software evolution from Version 1.0 to Version 1.1 (or later)
- CI/CD pipeline execution
- Live cloud deployment
- Lessons learned from collaborative software evolution

Presentation Time: 20–30 minutes.

## Deliverables

Each group shall submit:

1. GitHub Repository Link
2. Complete Source Code
3. Software Requirements Specification (SRS)
4. Software Architecture Document
5. Database Script
6. Technical Documentation (PDF)
7. GitHub Actions Workflow Files
8. Live Deployment URL
9. Presentation Slides
10. Demonstration Video (5–10 minutes)
11. Screenshots of CI/CD Pipeline Execution
12. Version History (Version 1.0 and Version 1.1 or later)

## Marking Guide (100 Marks)

| Assessment Item | Marks |
| --- | --- |
| Project planning, requirements, and software architecture | 10 |
| Module development (6 teams × 2 students) | 30 |
| Configuration management using Git/GitHub | 10 |
| Integration and software evolution | 15 |
| CI/CD implementation and cloud deployment | 15 |
| Software quality improvement (refactoring and metrics) | 5 |
| Technical documentation | 10 |
| Team module presentation | 5 |
| Final integrated application demonstration | 5 |
| Total | 100 |

### Learning Outcomes

Upon successful completion of this assignment, students should be able to:

1. Explain and apply software evolution concepts and Lehman's Laws in a practical software project.
2. Design and develop a modular software system collaboratively using Git and GitHub.
3. Apply software architecture and configuration management principles to support maintainability and scalability.
4. Integrate independently developed modules into a single functional application.
5. Implement professional Git workflows, including branching, pull requests, code reviews, tagging, and merge conflict resolution.
6. Apply DevOps practices by configuring Continuous Integration and Continuous Deployment pipelines using GitHub Actions.
7. Improve software quality through testing, refactoring, documentation, and maintenance.
8. Deploy a production-ready application to a cloud server and manage its evolution through iterative releases.
