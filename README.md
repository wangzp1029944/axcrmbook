## 爱旭CRM帮助手册

该手册主要目标为指导爱旭太阳能科技营销机构、市场机构及后勤机构人员可以快速学习和使用CRM系统，包括PC版、苹果及安卓客户端。

### CRM系统登陆方式:![](/assets/20200203-4-IOS.png)

* PC端：[http://crm.aikosolar.net](http://crm.aikosolar.net)

> 推荐使用Chrome谷歌浏览器或360浏览器极速模式

* 移动客户端：请扫描或微信中识别下方二维码
* 软件内测密码：123456

| 苹果客户端 | 安卓客户端 |
| :--- | :--- |
| ![](/assets/20200203-5-IOS.png) | ![](/assets/2020-04-02-02-anzhuo.png) |

> 苹果版需要在完成安装后，点击设置-&gt;通用-&gt;设备管理-&gt;信任  Guangdong Aiko Solar Energy Technology Co., Ltd.
>
> 注：仅第一次安装需要信任设置

### 概念解释

| 术语 | 解释 |
| :--- | :--- |
| SAP | 目前爱旭正在用的ERP软件品牌 |
| OA | 目前爱旭正在用的OA系统，日常工作流审批都在这里 |
| CRM | 本次项目实施的系统名称，”客户关系管理系统“-CRM |
| MES | 生产制造执行系统 |
| CRM-PC端 | 爱旭CRM在电脑上使用的软件 |
| CRM-APP端 | 爱旭CRM在手机上使用的客户端，有安卓端、苹果端 |
| CC3 | 铁三角服务团队简称 |
| AR | 铁三角中的AR角色--客户经理角色 |
| SR | 铁三角中的SR角色--客户解决方案经理角色 |
| FR | 铁三角中的FR角色--客服经理角色 |

### 爱旭CRM模块清单

1. 客户管理（客户、供应商、终端、竞争对手、双经销类型客户资料、情报、铁三角分配等业务）
2. 市场管理（情报、市场活动、销售预测）
3. 商机跟进（线索、商机、报价、样品） 
4. 合同中心（合同创建、审批、变更）
5. 订单管理（订单同步与跟踪）
6. 发货管理（发货同步与物流跟踪）
7. 发票管理（发票及邮寄跟踪）
8. 收款管理（收款、保证金录入与合同收款分解、客户对账业务）
9. 商务活动（客户拜访与接待）
10. 售后管理（客户投诉、退换货）
11. 用款管理（用款申请创建）
12. 信用证管理（信用证录入、变更、审批）
13. 产品中心（产品清单与产品360卡片、产品信息同步）
14. 客户评价管理（从财务、技术、战略协同、关键指标等多维度对客户进行评价）
15. 日报管理（CC3日报）
16. 任务协作与通讯录（任务指派与提醒、通讯录人员查询与设置）
17. 流程中心（流程待办、我的流程）
18. 报表中心（库存、市场、销售、资金等相关报表）
19. 报价管理（产品报价信息）
20. 知识管理（知识库、爱旭1000问、机构报价大全、历史合同条款查询、小包批次查询）
21. 系统管理（组织人员与权限管理、应用大全管理、字典管理、文章与公告管理、流程审批支持等）

## CRM常见问题（持续更新中）

##### 1.合同提交后看不到下一审批人怎么办？

> 这种情况应该是合同没有提交上去，请检查合同的整体状态是不是仍处于草稿状态，如果是，应该是合同没有通过ERP数据检查，请检查如下地方：
>
> 1）行项目上的价格是不是小数点超过了3位，如果超过3位，请调整价格单位（这种情况一般发生在海外用户身上）
>
> 2）合同的客户对应的销售组织是否都填写正确

##### 2.合同CRM导入SAP后能否修改？

> * 合同在导入SAP前如果要修改，需要审批人员退回给创建人，创建人可以直接在电脑端修改；
>
> * 合同导入SAP后如果要修改，只能通过销售支持在SAP中手动修改，之后在CRM中手工输入SAP合同号+CRM合同号将该合同从SAP中同步到CRM中，并和CRM合同产生关联（因CRM合同会对应多个SAP合同）
>
> * 注：合同在SAP中删除后必须在CRM点击同步，保证CRM合同状态调整为已取消

##### 3.CRM合同都有哪些状态，分别代表什么含义？

> 合同目前状态有
>
> | 状态 | 说明 | 可操作按钮 |
> | :--- | :--- | :--- |
> | 草稿 | 还没有提交审批或审核被退回 | 编辑、取消、复制合同 |
> | 草稿编辑状态 | 草稿状态下，编辑合同界面 | 保存并提交审批 |
> | 审核中 | 相关人员审核中 | 审批按钮\(退货或通过）、强制撤回\(只有本人可见）、重新提交\(只有本人可见）、复制合同 |
> | 待提交 | 合同审核通过，尚未提交SAP或提交SAP失败 | 再次提交SAP（只有本人可见）、复制合同 |
> | 待发货 | 合同已提交到SAP且尚未创建发货单，或发货单已创建CRM还没有收到（一般有5分钟左右延迟） | 终止合同、复制合同 |
> | 发货中 | SAP中已发货或部分发货 | 终止合同、复制合同、完成合同 |
> | 已完成 | 合同评价流程结束后 | 复制合同 |
> | 已取消 | 合同被撤回/退回到草稿状态，销售支持可以点击取消 | 复制合同 |
> | 已终止 | 合同被另一个合同覆盖，不再执行；或合同被直接终止 | 复制合同 |
>
> ##### 已完成状态说明：合同发货后，由销售支持点击完成，触发合同评价流程。评价结束后状态变更为已完成
>
> **已取消状态说明：合同被退回后可手工取消，或者SAP中删除合同后，CRM同步合同自动将状态设置为已取消**
>
> ##### 强制撤回说明：强制撤回后，进入草稿状态，在草稿状态可以编辑或者直接取消
>
> ##### 合同状态统计说明：
>
> （1）终止后，状态变成已终止，已终止合同需要参与合同统计
>
> （2）草稿、审核中和已取消状态不参与合同统计

##### 4.合同提交SAP报错怎么办？

> 目前合同在提交审批前都会做SAP测试，如果有问题系统会预先告知问题原因，便于提交人修改，有效避免了后续审批完成后写入不了SAP的情况。
>
> 对于零星的提交失败问题，可以找IT协助解决。
>
> 目前常见的报错原因是
>
> * 销售组织、渠道选择错误或客户没有扩充视图，该问题请联系IT部门SD内部顾问处理
> * 物料没有扩充销售视图，该问题请联系IT部门SD内部顾问处理
> * 鲁迅更新中

##### 5.合同审核通过后提交到SAP要多久？

> 目前审批通过的合同会排队进入SAP，排队时间大概5s-30s左右，如果提交SAP出错会发给销售支持、AR客户经理发送消息

##### 6.订单、发货过账今后也在CRM中操作码？

> 目前CRM合同审批后会自动创建SAP合同，订单、发货过账、开票仍在ERP中操作，ERP做完后会自动将订单、发货、发票同步到CRM系统中
>
> 同步间隔如下：
>
> * 订单：1小时同步一次
> * 发货：5分钟同步一次
> * 发票：1小时同步一次

##### 7.收款未来在哪里做？

> 未来财务相关人员收到银行到账信息后，需要在CRM中录入收款单，之后在SAP中过账，过账后需要在CRM中将CRM收款单状态设置为已过账

##### 8.为什么CRM待办详情点击不进去？

> 由于部分用户使用的浏览器比较老，当在CRM系统中打开的TAB页面太多的时候，内存不够会导致该问题发生。请
>
> 1）按下F5或者手工刷新一下浏览器页面即可
>
> 2）更换内存较大的电脑
>
> 浏览器兼容：目前仅支持谷歌浏览器、360浏览器极速模式、苹果safari浏览器及IE10+浏览器、EDGE浏览器，旧版的IE浏览器暂不支持

##### 9.建了情报会给哪些人发消息？

> 如果情报跟客户有关，则发消息给该客户的AR，根据客户国别区分出来的国内或海外销售总监，该客户关联的销售支持，销售副总，总经理
>
> 如果情报跟客户无关，则发消息给副总经理和总经理

##### 10.手机端如何上传附件

> 手机端目前仅支持图片上传；
>
> 如果要上传PDF、Excel、Word等文件，需要到电脑端上传。

##### 11.合同标的跟合同附件中的内容是一致的吗?

> 不一定，合同标的和SAP合同保持一致，合同附件中的标的AR人为做了一些预估，可能会有不一致情况

##### 12.送样申请被退回后可以修改吗？

> 退回状态下的送样申请可以编辑，编辑后可以提交



