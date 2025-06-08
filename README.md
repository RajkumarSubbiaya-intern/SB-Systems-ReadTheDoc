# Nexus Book: The Systems Team Process

Welcome to the **Systems Team Handbook**!  
This repository provides a comprehensive guide for the Systems Team, detailing our processes, tools, and best practices. It is designed to help both new and existing team members understand our workflows and contribute effectively to our mission of delivering high-quality systems solutions.

---

## Who Should Use This Handbook?

- **Fresher to Systems Team:** New team members starting their journey with us.
- **Existing Team Members:** Current members refreshing knowledge or learning new processes.
- **Stakeholders:** Anyone interested in how the Systems Team operates and collaborates.

---

## 📚 Table of Contents

- **Getting Started**
  - Introduction
  - SB - Systems Architecture Overview

- **L2 to Dev Team Process Guide**
  - Issue/Cases Identification & Categorization
  - Issue/Cases Analysis Guide Docs
  - Issue/Case Routing & Documentation

- **Dev Team Perspective: Execution & Responsibility**
  - Task Assignment & Planning
  - Developer’s Responsibilities
  - Collaboration & Escalation

- **Release Management & Deployment**
  - Bugs Lifecycle & Continuous Improvement

- **Development Process**
  - Handling Bugs Efficiently
  - Handling Features

- **DI Development Process**
  - Motivation
  - Setup (Installation Tools & Libraries, Tech Stack, Permissions, Cloning, Repositories, Installations)
  - Useful Tools (Aliases, CLI Highlighting, Dev Containers)
  - Development Process (RCA, Bugs, Features, PRs, QA, Merging)

- **UI Development Process (Frontend)**
  - Requirements for Setup (Installation Tools, Permissions, Cloning, Repositories)
  - Workflow (Tickets, Documentation, Design Review, Implementation, Unit Testing, PRs, QA, Merging)
  - Bug Fix Workflow

- **Revision History**

---

## 🛠️ How to Use

Run Locally
-----------

1. Git clone the repo.
2. cd to ``docs``.
3. Run the below command to install the dependencies:

   ``pip install -r requirements.txt``

4. Run to install autobuild:

    ``sudo apt install python3-sphinx-autobuild``

5. Run the below command to clean and build the ``index.html`` locally:

   ``make clean html``

   You can also auto-build the documentation on changes with live-reload in the browser using the below command:

   ``sphinx-autobuild . ./build/html --port <any-port-number>``
---

## 📝 Contributing

Contributions are welcome!  
Please submit issues or pull requests to help us improve this handbook.

---

## 📅 Revision History

| Rev | Date         | Description     | Author           | Reviewers         |
|-----|--------------|----------------|------------------|-------------------|
| 1   | 03-Mar-2025  | First draft    | Dinesh Kumar V   | Pierre Buechler   |
| 2   | 02-Jun-2025  | ReadTheDocs    | Rajkumar S       | Dinesh Kumar V    |

---

**Start exploring the Systems Team Handbook and help us build robust, high-quality systems!**
