# 合成输入材料

这里的记录均为合成数据，不对应真实住户、项目或城市。每个文件表示一个来源数据表，不包含分析结论；解释记录时应保留来源标识和修订关系。

- `funds.csv`：CSV 表格，字段为 `fund_id, fiscal_year, category, limit`。日期字段使用 ISO 8601 格式；空单元格表示未知或未提供，不代表数值零。
- `contracts.csv`：CSV 表格，字段为 `contract_id, work_package, scope_version, category, approved_amount, valid_from`。日期字段使用 ISO 8601 格式；空单元格表示未知或未提供，不代表数值零。
- `payments.csv`：CSV 表格，字段为 `voucher_id, contract_id, work_package, fund_id, amount, status, revision_of`。日期字段使用 ISO 8601 格式；空单元格表示未知或未提供，不代表数值零。
- `work-quantities.csv`：CSV 表格，字段为 `quantity_id, work_package, period, value, unit, review_status`。日期字段使用 ISO 8601 格式；空单元格表示未知或未提供，不代表数值零。
