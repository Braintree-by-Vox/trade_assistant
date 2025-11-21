# Release notes

- [Vendor Reconciliation](#vendor-reconcliation)
- [Debtors Collections](#debtors-collections)
- [FEC](#fec)

# Vendor Reconcliation

### Release 26.0.20251120.1 (26.4)

<details>
<summary>Allow selected users to override payment discounts from Vendor Recon page (click for details)</summary>
<p>- Trade assistant user setup: new field "Allow Discount Modify" </p>
<p>- If turned on, user can edit Discount Available on recon lines</p>
<p>- When discount is edited, user will be prompted to confirm.</p>
<p>- Discount amount will be transferred to vendor ledger entry</p>
<p>- Pmt Discount date on vendor ledger entry will be set to Recon payment date + 1 day</p>

</details>
    
### Release 26.0.20251119.1
- Manage settlement discount
  - Requirement: Handle settlement discounts on invoices being settled.
  - Changes:
    - field added to Vendor Recon subpage to display discount available from vendor ledger
    - when Suggest Lines is run, IF payment date is less than Discount date on vendor ledger, AND discount is avalalbe, the remaining discount will be populated.
    - discount is provided for info only - will show on reports
    - discount will be applied to vendor payment when the payment journal is posted, using standard BC settlement discount function


# Debtors Collections

# FEC