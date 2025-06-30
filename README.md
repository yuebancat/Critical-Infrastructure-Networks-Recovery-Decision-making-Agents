# Large-Model-Driven Agents for Recovery Decision-Making of Critical Infrastructure Networks

## 🚨 重要申明 | Important Notice

由于本文目前正在评审中，本仓库中所有内容暂时不允许任何人以任何形式复用，直至本公告移除。感谢您的理解与配合！As the paper is under review, all contents in this repository are currently not permitted for reuse by anyone until this announcement is removed. Thank you for your understanding!

## 0. 智能体操作演示视频 | Videos of Agent Operations

### 0.1 自主开发原型的运行 | Operation of the Developed Prototype

开发的TS-ReAct智能体原型运行片段：视频链接（片段）

更新工具库的片段：视频链接（片段）

完整视频：完整视频链接

### 0.2 基于ReAct模式的智能体运行 | Agents Based on ReAct Pattern

由GPT-4o、GPT-4、GPT-3.5 Turbo驱动的ReAct智能体：视频片段完整视频



Qwen2.5、Deepseek-V3、Gemma-2、Llama-3.1、Mixtral MoE驱动的ReAct智能体：视频片段完整视频

https://github.com/user-attachments/assets/4cc1c327-58fd-49ff-ac4d-e28c887ebd8d

### 0.3 基于TS-ReAct模式的智能体运行 | Agents Based on TS-ReAct Pattern

TS agent运行片段：视频片段完整视频

https://github.com/user-attachments/assets/86d73b6c-09e2-4b21-bb96-01110a4d3061

ReAct agent运行片段：视频片段完整视频

https://github.com/user-attachments/assets/c0e3da47-cf27-46c2-aef3-1f1fed1fe2aa

## 1. 简介 | Introduction

### 1.1 研究目的 | Objective

本仓库旨在提供论文《……》所涉及的全部代码与数据，相关研究由中国 XXX 大学开发。This repository provides codes and data related to the paper entitled “……” developed by XXX University in China.

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

### 3.1 导入IIN恢复工具函数 | Import IIN Recovery Tool Functions

请将39个IIN恢复工具函数定义文件从原目录（{Codes for defining the functions of 39 IIN recovery tools}）复制至目标运行目录（如：{Codes for running ReAct-based agents} 或 {Codes for running TS-ReAct-based agents}）。



导入函数示例如下图所示：



### 3.2 运行ReAct模式智能体 | Run ReAct-based Agents

以下目录包含运行基于8种LLMs的ReAct智能体的全部代码：



### 3.3 运行TS-ReAct模式智能体 | Run TS-ReAct-based Agents

以下目录包含运行基于8种LLMs的TS-ReAct智能体的全部代码：



### 3.4 启动原型与更新工具库 | Operate Prototype & Update Tool Kit

以下目录用于运行TS-ReAct原型及工具库的更新：
