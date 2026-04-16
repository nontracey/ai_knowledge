# 第五章 RAG 检索增强生成

本章将详细介绍 RAG（Retrieval-Augmented Generation，检索增强生成）技术，包括其原理、实现方式以及与 LangChain、Semantic Kernel 的结合使用。

## 本章内容概览

| 小节 | 主题 | 核心知识点 |
|------|------|----------|
| 5.1 | RAG 是什么 | RAG 定义、工作原理、应用场景 |
| 5.2 | LangChain RAG 核心流程 | LangChain 的 RAG 架构 |
| 5.3 | 文档加载与文本分割 | 各类文档加载器、分割策略 |
| 5.4 | 文本嵌入与向量存储 | 嵌入模型、向量数据库 |
| 5.5 | 检索策略与完整 RAG 链 | 检索类型、链的构建 |
| 5.6 | 对话式 RAG 与 LangGraph | 多轮对话、RAG 系统实现 |
| 5.7 | Semantic Kernel RAG | SK 的 RAG 实现方式 |

## 学习目标

- 理解 RAG 的基本原理和应用价值
- 掌握使用 LangChain 构建 RAG 应用
- 了解向量数据库的选型和使用
- 能够实现对话式 RAG 系统
