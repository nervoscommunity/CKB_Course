# CKB Experience Course

[分组情况](groups.md)|[结业大作业](last_homework.md)

## 课程表

|课程|时间|
|---|---|
|第一讲|2020.4.20|
|第二讲|2020.4.24|
|第三讲|2020.4.20|
|第四讲|2020.4.20|

## 课程内容

### 第一讲：CKB Studio 介绍篇（4/20周一）

目的：介绍 CKB Studio，了解基本功能和使用

1. CKB Studio 是什么；解决了什么问题；集成了那些环境
2. 安装
    1. 环境要求
    2. 安装步骤
3. 启动
    1. 本地开发链
    2. 测试网
    3. 主网
4. 编写CKB Script
    1. 创建CKB项目
    2. 编译
    3. 使用debugger
5. 构造交易
    1. CKB的交易结构
    2. 转账
    3. 部署合约
    4. 调用合约

 
### 第二讲：CKB Script 开发篇1：UDT（4/24周五）

目的：介绍 sUDT 并完成发币和转账，了解 type script 基础概念和功能
合约要求：Simple UDT 

具体课程内容：

1. 准备工作
    1. 部署sUDT合约
    2. type script讲解
    3. 使用Cell manifest和UDT manifest
2. sUDT 的发行
    1. 构造发币交易
    2. 交易结构讲解
3. sUDT 的转账
    1. 构造转账交易
    2. 交易结构讲解
4. sUDT 合约
    1. owner模式（发币）
    2. 普通模式（转账）
5. 小作业（TBD）


### 第三讲：CKB Script 开发篇2：anyone-can-pay（4/29周五）

目的：介绍 anyone-can-pay 合约
 
具体课程内容：

1. 上述智能合约的实现与讲解
2. debug 功能使用和教学
3. anyone-can-pay 合约的讲解和使用
4. 小作业（TBD）


### 第四讲：CKB Script 开发篇3：使用 JavaScript 编写CKB Script（58周五）

目的：介绍如何使用 JavaScript 进行合约编写，使用 JavaScript debugger，Molecule，构造交易
 
1. Duktape
    1. 创建Duktape项目
    2. 编译
    3. 部署
2. Minimal JavaScript
    1. 创建JavaScript项目
    2. 使用debugger
    3. 构造交易
3. Molecule
    1. Molecule简述
    2. 基于Molecule的JavaScript项目结构
    3. .mol, schema, moleculec-es
4. HTLC

