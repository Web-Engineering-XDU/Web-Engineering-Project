# 项目概述

这是用Go实现的阉割版[Huginn](https://github.com/huginn/huginn)

# 核心概念

## Agent
执行任务的组件，可以输入输出Event，由某些机制触发运行（timer?Event?）

## Event
Agent间通讯的数据结构

# 用户需求描述

- 用户可以CRUD Agent
- 用户可以方便地查看和管理workflow
- 用户可以查看系统实时运行状态