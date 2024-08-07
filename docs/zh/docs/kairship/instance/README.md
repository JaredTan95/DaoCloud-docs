---
hide:
  - toc
---

# 查看多云实例

1. 在多云实例列表中，点击某个实例的名称，可以进入概览页面。

    支持在搜索栏输入实例名称快速检索，搜索支持模糊匹配。

    ![instance](../images/instance01.png)

2. 实例信息展示

    概览页面显示了当前实例的基本信息、多云工作负载状态、多云实例调度次数、资源信息、工作集群信息、策略信息等。具体包括：

    - 实例名称/别名
    - 实例创建时间
    - 当前实例的 Karmada 版本
    - 实例状态
    - 实例总体的 CPU 使用率 **数据基于当前实例接入的所有工作集群的资源总额**
    - 实例总体的内存使用率
    - 当前实例中状态正常的集群数/集群总数 **支持查看详细信息**
    - 当前实例部署策略数/差异化策略数 **支持查看详细信息**

        ![instance](../images/instance02.png)
