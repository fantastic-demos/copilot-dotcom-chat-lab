# Kubernetes Codebase Analysis Challenge
This is a challenge exercise and hands-on laboratory to help you get familiar with the Copilot Chat on the GitHub.com UI.

<img src="https://github.com/kubernetes/kubernetes/raw/master/logo/logo.png" width="100">

## Overview

Welcome to the **Kubernetes Codebase Analysis Challenge**! In this challenge, you will explore and analyze the structure of the Kubernetes codebase, with a particular focus on its key modules and the **CSI (Container Storage Interface) Plugin**. You will also have the opportunity to examine a real-world issue, propose a solution, and visualize parts of the code using **Mermaid JS**.

You can find the Kubernetes codebase [here](https://github.com/kubernetes/kubernetes).

## Before You Begin
Perform the following steps before you start the challenge:
1. Visit the [Kubernetes codebase](https://github.com/kubernetes/kubernetes) _(open in a new tab)_.
2. Launch the GitHub Copilot Chat at the top-right corner of the interface _(Look for the ![copilot](https://github.com/user-attachments/assets/027fc880-2a7a-497d-8ed5-f5aade9a1753) icon)_.

> [!Note] 
> At the end of this exercise, you will be asked to copy and paste your chat conversation and commit it in your repo.

## Challenge Tasks
Here are the tasks you need to complete. You are expected to prompt Copilot to perform the tasks. Remember to be creative with your prompts.

### 1. Summarise functionality and code analysis of Kubernetes

Craft your prompt to understabnd below points 

- **Main features of the codebase**
- **high-level understanding of the Kubernetes’s workflow & architecture**
- **Identify the tech stack (Technologies used in the codebase) of Kubernetes**
- **Gain a general understanding of the code quality by checking if industry best practices are used**

### 2. Identify Kubernetes Modules
Review the key modules or components and their responsibilities in the Kubernetes codebase, such as:
- **API Server**
- **Scheduler**
- **Controller Manager**
- **Kubelet**

## Bonus
For the `Scheduler` module, provide answers to the following:
- **Primary Responsibility:** What is the module responsible for in Kubernetes' architecture?
- **Interaction with Other Modules:** How does it interact with other components within the system?
- **Role in Kubernetes:** What role does it play in Kubernetes' overall functionality (e.g., scheduling, state management, networking)?

### 3. Explore the CSI Plugin
Dive into the **CSI (Container Storage Interface) Plugin** and describe:
- **Primary Functionality:** What is the CSI Plugin's role in Kubernetes? How does it enable Kubernetes to manage storage in a flexible, extensible manner?
- **Interaction with Other Modules:** How does the CSI Plugin interact with other Kubernetes components, such as the **Kubelet**, **API Server**, and **Controller Manager**? 

### 4. Explain and Solve Kubernetes Issue #128071
Investigate **Kubernetes Issue #128071**:
- Provide a detailed explanation of the issue.
- **Generate the required code** to resolve the issue or suggest a potential solution.

### 5. Generate a Mermaid JS Diagram
Visualise Kubernetes codebase by creating a **Mermaid JS diagram**. Your diagram should depict:
- Overall structure and components of Kubernetes
- Overall flow of Kubernetes 

### Conclusion
- Highlight and copy your entire conversation
- Within the challenge lab repo you created, create a conversation.md file and commit this text to the file (be sure to paste markdown styles as markdown).
