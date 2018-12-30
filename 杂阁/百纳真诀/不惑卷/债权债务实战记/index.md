债权债务实战记
=======

### 题记


### 场景
合同和结算相关人员需要统计合同有关债权债务数据，

合同债权债务报表帮助公司各级管理层从组织层级和项目维度分析相关合同收付款情况，
通过各期间未收或未付金额情况，分析并监控合同实际发生的业务情况和涉及收付款计划履约情况；
通过信用金额和信用期情况，分析并监控业务上各合作伙伴（供应商和客户）的信用情况和忠诚度。

### 初战
无论是债权统计数据还是债务统计数据，都是以合同为中心。因此，整体数据的流动都围绕着合同。
立足于合同展开来看，总共涉及了下面*17*张表:
1. 合同(hcm_contracts)
2. 合同分类(hcm_setup_category_b)
3. 快速编码(sys_code_value_b)
4. 项目(hbrm_projects)
5. 合同收款计划(hcm_receipt_schedules)
6. 营收结算单(hscs_ar_settle_orders)
7. 收款单头(hscs_ar_receipt_headers)
8. 收款单行(hscs_ar_receipt_lines)
9. (hscs_ar_receipt_schedules)
10. 合同付款计划(hcm_payment_schedules)
11. 付款单头(hscs_ap_payment_headers)
12. 实际付款信息(hscs_ap_act_payment_inf)
13. 采购结算单(hscs_ap_po_settle_orders)
14. (hscs_pub_apply_results)
15. 营收确认头(hscs_confirm_headers)
16. 合同债权明细(hcm_rpt_claim_statement_details)
17. 合同债务明细(hcm_rpt_debt_statement_details)



### 再战










[目录](../../目录.md)