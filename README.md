# genai_data_lineage

This repository demonstrates how to use **Generative AI (GPT-4 via Azure OpenAI)** to automatically extract **column-level data lineage** from **Azure Synapse stored procedures** and publish the lineage into **Microsoft Purview** in a compliant format.

---

## 🚀 Overview

Lineage extraction from T-SQL stored procedures is complex due to nested queries, dynamic SQL, and procedural logic. This project uses GPT-4’s deep understanding of language and structure to automate this task with impressive accuracy and minimal effort.

The pipeline handles:
- SQL extraction and cleanup
- Prompting GPT-4 to derive lineage
- Structuring the output into JSON
- Publishing lineage to Microsoft Purview using REST APIs
