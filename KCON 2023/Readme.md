# vSphere 攻防技法分享 - KCON 2023



Our slides in chinese for KCON 2023. It's about attacking Vmware vSphere.


VMware vSphere（简称 vSphere）是 VMware 旗下的一整套云计算基础架构虚拟化平台，自发布更新以来在全球已经拥有超过 250000 客户。vSphere 包括了 ESXi、vSphere client、vCeneter 等多个组件。



作为业界领先的虚拟化平台，vSphere 备受客户喜爱的同时，也是攻防对抗的重要战场。如针对 vSphere 勒索的相关活动在今年更是备受关注。然而 vSphere 攻防在业内的讨论并不多见。本议题将介绍多个 vSphere 中的攻防技术，主要内容包括：



1. 介绍 ESXi 中多个关键漏洞的稳定利用手法

2. vSphere 集群中横向移动技术

3. vSphere 中实现隐蔽后门的技术原理


VMware vSphere is a comprehensive cloud computing infrastructure virtualization platform under the VMware umbrella, with over 250,000 global customers. It encompasses various components, including ESXi, vSphere client, and vCenter. While vSphere is highly favored by customers, it is also a critical battleground in the realm of cybersecurity, with notable attention on vSphere ransomware activities this year. However, discussions about vSphere attack and defense are relatively limited within the industry. This topic will introduce several attack and defense techniques within vSphere, focusing on the following:

1. Introduction to stable exploitation methods of critical vulnerabilities in ESXi.

2. Lateral movement techniques within vSphere clusters.

3. Techniques for creating covert backdoors within vSphere.
