
# **GitHub Actions Workshop: Automating Workflows for Beginners**

Welcome to the repository for the **"Automating Workflows with GitHub Actions"** workshop! This repository contains all the materials and examples to help you get started with GitHub Actions, including the workflows we'll create and additional resources for you to practice.

---

## **Workshop Overview**

In this workshop, you'll learn how to:
- Understand the basics of GitHub Actions.
- Set up and run workflows to automate tasks.
- Create an automated test workflow for C programs.
- Complete a task to implement a coding style checker as a workflow.

---

### **1. Examples**
- `compile.yml`: An example GitHub Actions workflow for compiling with a make file

---

## **Getting Started**

### **Prerequisites**
- A GitHub account.
- Basic knowledge of Git, C programming and bash
- A repository to practice creating workflows.

---

### **Setup Instructions**
1. **Create the following structure `.github/workflows`:**
   This is where GitHub Actions workflows are stored.

2. **Start adding your .yml files:**

3. **Push Changes to Your Repository:**

---

## **Your Task: Valgrind memory leak Workflow**

Create a workflow that checks for memory leak issues in your C programs:
1. Set up a new workflow file in `.github/workflows`, e.g., `memory-leak.yml`.
2. Use a tool like `valgrind` to check the memory leaks.
3. Ensure the workflow runs on `pull_request` events.
4. Use grep to get the valgrind output

---

## **Resources**
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [GitHub Actions Workflow Syntax](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions)
