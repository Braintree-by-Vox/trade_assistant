# Release notes

- [Vendor Reconciliation](#vendor-reconcliation)
- [Debtors Collections](#debtors-collections)
- [FEC](#fec)

# Vendor Reconcliation

<details>
<summary><strong>Release 26.0.20251119.1</strong></summary>

- Manage settlement discount
  - Requirement: Handle settlement discounts on invoices being settled.
  - Changes:
    - field added to Vendor Recon subpage to display discount available from vendor ledger
    - when Suggest Lines is run, IF payment date is less than Discount date on vendor ledger, AND discount is avalalbe, the remaining discount will be populated.
    - discount is provided for info only - will show on reports
    - discount will be applied to vendor payment when the payment journal is posted, using standard BC settlement discount function

</details>

# Debtors Collections

# FEC