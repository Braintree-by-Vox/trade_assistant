# Release notes
<!-- 
- [Vendor Reconciliation](#vendor-reconcliation)
- [Debtors Collections](#debtors-collections)
- [FEC](#fec)
# Vendor Reconcliation -->

**Release 26.0.20251124.1 (26.5)**
<details>
<summary>1. Error message: Amount to pay does not equal matched amount" when clicking on 'Request Approval' (click for details)</summary>
<ul>
<li>Modified filter before calculating totals</li>
</ul>
</details>

<!-- next issue -->
<details>
<summary>2. The Remittance Advice also does not show the actual net payment correctly when discount is taken (click for details)</summary>
<ul>
<li>Report layout adjusted to include new columns for Discount Claimed and Other deductions.</li>
<li>Font reduced to 7pt to accommodate new columns</li>
<li>Calculation of nett payment adjusted to deduct discount and Other Deductions</li>
</ul>
</details>

<!-- next issue -->
<details>
<summary>3. On 'Request Approval', when matched amount and payment amount don't match, clicking No on the confirmation dialog has no effect (click for details)</summary>
<ul>
<li>Click on No now results in operation being cancelled.</li>
</ul>
</details>

**Release 26.0.20251121.1 (26.4)**

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

## Release 26.0.20251119.1
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