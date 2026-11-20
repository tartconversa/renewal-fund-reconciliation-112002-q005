# Input material

All records are synthetic and refer to no real household, project, or city. A file is a source extract, not a precomputed answer. Preserve source identifiers and revisions when interpreting it.

- `funds.csv`: CSV; columns `fund_id, fiscal_year, category, limit`. Dates use ISO 8601 where present; blank cells mean unknown or not supplied, not numeric zero.
- `contracts.csv`: CSV; columns `contract_id, work_package, scope_version, category, approved_amount, valid_from`. Dates use ISO 8601 where present; blank cells mean unknown or not supplied, not numeric zero.
- `payments.csv`: CSV; columns `voucher_id, contract_id, work_package, fund_id, amount, status, revision_of`. Dates use ISO 8601 where present; blank cells mean unknown or not supplied, not numeric zero.
- `work-quantities.csv`: CSV; columns `quantity_id, work_package, period, value, unit, review_status`. Dates use ISO 8601 where present; blank cells mean unknown or not supplied, not numeric zero.
