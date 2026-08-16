# AI Knowledge Management System for Renewable Energy Regulations

## 📌 Project Overview

This project demonstrates an end-to-end **Business Analysis and AI Solution Design** process for developing an AI-powered Knowledge Management System for renewable energy regulations in Indonesia.

The project focuses on analyzing the challenges of manually searching and interpreting regulatory documents, defining business and system requirements, modeling current and future business processes, and designing an AI-based solution to support regulatory information retrieval and question answering.

The proposed solution applies a **Retrieval-Augmented Generation (RAG)** approach to help users retrieve relevant regulatory information and generate answers based on a centralized knowledge base of renewable energy regulations.

---

## 🎯 Business Objective

The objective of this project is to design a centralized AI-powered knowledge management solution that can:

* Improve the efficiency of searching renewable energy regulations
* Reduce the effort required to identify relevant regulatory information
* Support users in understanding regulatory documents
* Provide AI-assisted answers to regulatory questions
* Improve access to a centralized regulatory knowledge base
* Support more efficient regulatory research and decision-making

---

## 💼 Business Problem

Renewable energy regulatory information is distributed across multiple regulatory documents and can be difficult to search and interpret efficiently.

The existing process relies heavily on manual keyword-based searching, where users need to:

1. Identify the required regulatory information
2. Search regulatory documents using keywords
3. Review search results
4. Open and read relevant documents
5. Identify relevant regulatory passages
6. Interpret the information manually
7. Formulate an answer based on the retrieved information

This process can become time-consuming, especially when users need to search across a large collection of regulatory documents.

The proposed solution introduces an AI-powered knowledge management system that combines **semantic retrieval and generative AI** to support regulatory information discovery and question answering.

---

## 📂 Project Documentation

| No. | Document                                                                     | Description                                                                                                 |
| --- | ---------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| 01  | [Business Problem Analysis](./01-Business-Problem-Analysis/)                 | Defines the business background, problems, objectives, and project scope                                    |
| 02  | [Stakeholder Analysis](./02-Stakeholder-Analysis/)                           | Identifies stakeholders and analyzes their roles and interests                                              |
| 03  | [As-Is BPMN](./03-As-Is-BPMN/)                                               | Models the existing regulatory information search process                                                   |
| 04  | [Process Gap Analysis](./04-Process-Gap-Analysis/)                           | Identifies gaps, impacts, and improvement opportunities in the current process                              |
| 05  | [To-Be BPMN](./05-To-Be-BPMN/)                                               | Models the proposed future-state business processes                                                         |
| 06  | [Functional Requirements](./06-Functional-Requirements/)                     | Defines the functional capabilities required by the system                                                  |
| 07  | [Non-Functional Requirements](./07-Non-Functional-Requirements/)             | Defines quality attributes such as performance, accuracy, reliability, scalability, security, and usability |
| 08  | [User Stories & Acceptance Criteria](./08-User-Stories-Acceptance-Criteria/) | Translates system requirements into user-oriented requirements and validation criteria                      |
| 09  | [Use Case Analysis](./09-Use-Case-Analysis/)                                 | Defines system actors, use cases, and detailed use case specifications                                      |
| 10  | [Activity Diagrams](./10-Activity-Diagrams/)                                 | Models detailed system workflows for key use cases                                                          |
| 11  | [System Architecture](./11-System-Architecture/)                             | Describes the proposed technical architecture of the AI solution                                            |
| 12  | [Prototype](./12-Prototype/)                                                 | Presents the proposed user interface and system interaction design                                          |

---

## 🤖 AI Solution

The proposed system uses a **Retrieval-Augmented Generation (RAG)** architecture.

At a high level, the solution consists of:

```text
Regulatory Documents
        ↓
Document Processing
        ↓
Text Chunking
        ↓
Embedding Generation
        ↓
Vector Database
        ↓
Semantic Retrieval
        ↓
Relevant Regulatory Context
        ↓
Large Language Model
        ↓
AI-Generated Response
```

The RAG approach allows the system to retrieve relevant regulatory information before generating an answer, helping ground the response in the available regulatory knowledge base.

---

## 🛠 Tools & Technologies

| Category                  | Tools / Technologies                 |
| ------------------------- | ------------------------------------ |
| Business Process Modeling | BPMN.io / Draw.io                    |
| System Modeling           | UML                                  |
| Documentation             | Microsoft Office                     |
| AI Architecture           | Retrieval-Augmented Generation (RAG) |
| Embedding                 | Sentence Transformer Models          |
| Vector Database           | Milvus                               |
| LLM                       | Large Language Model                 |
| Programming               | Python                               |
| Version Control           | GitHub                               |

---

## 🎓 Project Context

This project is based on my Final Year Project and was adapted into a **Business Analysis & AI Solution Design portfolio project**.

The original project focused on analyzing chunking, embedding, and similarity search strategies within a Retrieval-Augmented Generation pipeline for processing renewable energy regulatory documents in Indonesia.

The portfolio version emphasizes the **business analysis, requirements engineering, process modeling, and solution design aspects** of the project.

---

## 🌐 Portfolio & Learning Resources

| Resource              | Link                                                  |
| --------------------- | ----------------------------------------------------- |
| Portfolio Website     | [Dewi Maharani Portfolio](https://dwmhr.vercel.app/)  |
| Business Analyst Blog | [Dewi Maharani Blog](https://dewimhr7.wordpress.com/) |
| GitHub Profile        | [github.com/dwmhr12](https://github.com/dwmhr12)      |

---

## 👩‍💻 Author

**Dewi Maharani**

Business Analyst / System Analyst Portfolio

* Portfolio: [dwmhr.vercel.app](https://dwmhr.vercel.app/)
* GitHub: [github.com/dwmhr12](https://github.com/dwmhr12)
* Blog: [dewimhr7.wordpress.com](https://dewimhr7.wordpress.com/)

---

