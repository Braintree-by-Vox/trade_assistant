# Release notes

- [Vendor Reconciliation](#vendor-reconcliation)
- [Debtors Collections](#debtors-collections)
- [FEC](#fec)

# Vendor Reconcliation

### Release 26.0.20251120.1 (26.4)

<details>
<summary>Allow selected users to override payment discounts from Vendor Recon page (click for details)</summary>
<ul>
<li>Trade assistant user setup: new field "Allow Discount Modify"</li>
<li>If turned on, user can edit Discount Available on recon lines</li>
<li>When discount is edited, user will be prompted to confirm.</li>
<li>Discount amount will be transferred to vendor ledger entry</li>
<li>Pmt Discount date on vendor ledger entry will be set to Recon payment date + 1 day</li>
</ul>
</details>

### Release 26.0.20251119.1
<details> 
<summary>Manage settlement discount</summary>
<ul>
<li>Requirement: Handle settlement discounts on invoices being settled.</li>
<li>Changes:
  <ul>
  <li>field added to Vendor Recon subpage to display discount available from vendor ledger</li>
  <li>when Suggest Lines is run, IF payment date is less than Discount date on vendor ledger, AND discount is avalalbe, the remaining discount will be populated.</li>
  <li>discount is provided for info only - will show on reports</li>
  <li>discount will be applied to vendor payment when the payment journal is posted, using standard BC settlement discount function</li>
  </ul>
</li>
</ul>
</details>

# Debtors Collections

# FEC