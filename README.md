# Large-Model-Driven Agents for Recovery Decision-Making of Critical Infrastructure Networks

## 🚨 重要申明 | Important Notice

由于本文目前正在评审中，本仓库中所有内容暂时不允许任何人以任何形式复用，直至本公告移除。感谢您的理解与配合！As the paper is under review, all contents in this repository are currently not permitted for reuse by anyone until this announcement is removed. Thank you for your understanding!

## 0. 智能体操作演示视频 | Videos of Agent Operations

### 0.1 自主开发原型的运行 | Operation of the Developed Prototype

在开发的TS-ReAct智能体原型上进行CIN-RDM工具箱更新:

https://github.com/user-attachments/assets/0e40b326-c7a1-40a1-87a8-467a318b6105

### 0.2 基于ReAct架构的智能体运行 | Agents Based on ReAct Framework

基于ReAct架构，由GPT-4o、GPT-4驱动的智能体运行片段

https://github.com/user-attachments/assets/e18fd36c-745d-4c9f-8300-1b541b5b4082

基于ReAct架构，由Qwen2.5、Deepseek-V3、Llama-3.1、Mixtral MoE驱动的智能体运行片段

https://github.com/user-attachments/assets/4cc1c327-58fd-49ff-ac4d-e28c887ebd8d

### 0.3 基于TF-ReAct架构的智能体运行 | Agents Based on TF-ReAct Framework

TF智能体进行工具选择运行片段

https://github.com/user-attachments/assets/86d73b6c-09e2-4b21-bb96-01110a4d3061

ReAct智能体进行工具执行运行片段

https://github.com/user-attachments/assets/c0e3da47-cf27-46c2-aef3-1f1fed1fe2aa

## 1. 简介 | Introduction

### 1.1 目的 | Objective

本仓库旨在提供论文《……》所涉及的全部代码与数据，相关研究由中国的XXX大学和美国的XXX大学共同完成。This repository provides codes and data related to the paper entitled “……” developed by XXX University in China and XXX University in US.

### 1.2 致谢 | Acknowledgements

感谢以下开源项目对本研究的支持：Thanks to the contributors of these open-source projects:

LangChain-Agent (https://github.com/LangChain-OpenTutorial/LangChain-OpenTutorial/tree/main/15-Agent)

LangChain-RAG (https://github.com/LangChain-OpenTutorial/LangChain-OpenTutorial/tree/main/12-RAG)

MTEB Leaderboard (https://huggingface.co/spaces/mteb/leaderboard)

LLMs: Gemma-2 (https://huggingface.co/google/gemma-2-27b-it), Llama3.1 (https://huggingface.co/spaces/llamameta/llama3.1-405B), Qwen, etc.

### 1.3 版权声明 | Copyright

请遵循 MIT License 使用本仓库内容。如有疑问，请联系作者。Please refer to the MIT License or contact the authors for any copyright matters.

## 2. 补充材料汇总 | Summary of Supplemental Materials

如下表汇总了所有的补充材料（包括 S1 和 S2 中的所有表格）：The table below lists all supplemental materials, including all sheets in Tables S1 and S2.



## 3. 如何复用本仓库 | How to Reuse This Repository

### 3.1 导入CIN-RDM工具函数 | Import CIN-RDM Tool Functions

请将27个CIN-RDM工具函数定义文件从原目录（{Codes for defining the functions of 27 CIN-RDM tools}）复制至目标运行目录（如：{Codes for running ReAct-based agents} 或 {Codes for running TF-ReAct-based agents}）。

![Image](https://github.com/user-attachments/assets/1ce9f07f-055b-42d6-9f09-a2d1ecb5b6e0)

导入函数示例如下图所示：

![image](https://github.com/user-attachments/assets/92cd0fb9-8077-4440-b7c6-8c0be1cd9a5d)

### 3.2 运行ReAct模式智能体 | Run ReAct-based Agents

以下目录包含运行基于6种LMs的ReAct智能体的代码：

![image](https://github.com/user-attachments/assets/1c355e14-21df-4c29-b776-e4d1f91945dc)

### 3.3 运行TF-ReAct模式智能体 | Run TF-ReAct-based Agents

以下目录包含运行基于6种LMs的TF-ReAct智能体的代码：

![image](https://github.com/user-attachments/assets/6988b845-80ce-4457-8148-283246993a1d)

### 3.4 启动原型与更新工具库 | Operate Prototype & Update Tool Kit

以下目录用于运行TF-ReAct原型及工具箱的更新：

![image](https://github.com/user-attachments/assets/abb3c65a-22ac-4007-898a-bacd2182fb5f)
