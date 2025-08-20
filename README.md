# Atlassian-Intern-Project

# 📊 Playbook Usage Tab – Backend Development

This repository contains the backend implementation of the **Usage Tab** in **Jira Service Management (JSM) Automation Playbooks**, developed during my internship at Atlassian.

The Usage Tab provides administrators with insights into how playbooks are being used, enabling them to:

* Identify unused playbooks and deprecate them.
* Enhance frequently used playbooks.
* Improve overall orchestration adoption across tenants.

---

## 🚀 Project Overview

The **Usage Tab** directly supports Atlassian’s broader objective of **increasing JSM Automation adoption**.
By surfacing usage insights, the feature helps administrators make informed decisions, thereby driving engagement and efficiency.

---

## 🎯 Deliverables

* ✅ Designed and implemented **GraphQL queries** for the Usage Tab.
* ✅ Developed backend services to support the Playbook Admin View.
* ✅ Added **filters** in APIs for targeted insights.
* ✅ Wrote **unit and integration tests** to ensure reliability.
* ✅ Collaborated with frontend & product teams for UI visualization.

---

## ⚙️ Implementation Details

1. **Feasibility Study** – Worked with frontend & product teams to finalize feasible filters.
2. **GraphQL Schema Design** – Defined aggregations, response variables, and data formats.
3. **Backend Code Development** – Implemented scalable, maintainable, and peer-reviewed code.
4. **Testing** – Added comprehensive unit and integration tests (following Arrange–Act–Assert).

---

## 📚 Learnings

* Efficient **in-memory aggregations** due to ERS property limitations.
* Designed a **new Playbook Step ARI** for unique identification of playbook steps.
* Importance of **readable, maintainable, and well-documented code**.
* Value of **cross-team collaboration** for resolving blockers and iterating faster.

---

## 🛠 Obstacles & Solutions

* **Local Debugging Issues** → Resolved using Byte-Buddy agent in VM options.
* **GraphQL Schema Conflicts** → Overcame by collaborating on AGG pipeline fixes.
* **Integration & Staging Errors** → Improved debugging strategies for robust solutions.

---

## 🔮 What’s Next

* Add **Issue Type Filter** to highlight effective playbooks per issue type.
* Display **Top 5 Unique Agents** in Usage Tab.
* Extend backend with endpoints for **graphical insights** (trends, usage stats, bar graphs).

---

## 🙌 Acknowledgements

A huge thanks to my mentor, buddy, and teammates in **Team Phantom (ITOps)** for their constant support, feedback, and collaboration throughout this project. 💙

---

