## Release notes
<!-- 
- [Vendor Reconciliation](#vendor-reconcliation)
- [Debtors Collections](#debtors-collections)
- [FEC](#fec)
# Vendor Reconcliation -->
**Release 26.0.20251212.2 (27.1.1)**
<details>
<summary>VRS: Search for a vendor document number (click for details)</summary>
<ul>
<li>From the vendor ledger page, or vendor recon list, select 'Find Vendor Reconciliation, enter a document number or external document number. All recons on which the document appears will be listed. Click on the recon number to open the recon.</li>
</ul>
</details>

**Release 26.0.20251212.2 (27.1)**
<details>
<summary>VRS: Report layout - Payment authorisation (click for details)</summary>
<ul>
<li>Font in deatail changed to Calibri 7pt.</li>
<li>Document columns changed to allow wrap.</li>
</ul>
</details>

**Release 26.0.20251126.1 (26.6)**
<details>
<summary>VRS: When suggesting lines, system requires response to prompt for discount (click for details)</summary>
<ul>
<li>Message is suppressed if discount value on vendor ledger entry is the same as discount available on recon line.</li>
</ul>
</details>

**Release 26.0.20251124.3 (26.5)**
<details>
<summary>1. VRS: Error message: Amount to pay does not equal matched amount" when clicking on 'Request Approval' (click for details)</summary>
<ul>
<li>Modified filter before calculating totals</li>
</ul>
</details>

<!-- next issue -->
<details>
<summary>2. VRS: The Remittance Advice also does not show the actual net payment correctly when discount is taken (click for details)</summary>
<ul>
<li>Report layout adjusted to include new columns for Discount Claimed and Other deductions.</li>
<li>Font reduced to 7pt to accommodate new columns</li>
<li>Calculation of nett payment adjusted to deduct discount and Other Deductions</li>
</ul>
</details>

<!-- next issue -->
<details>
<summary>3. VRS: On 'Request Approval', when matched amount and payment amount don't match, clicking No on the confirmation dialog has no effect (click for details)</summary>
<ul>
<li>Click on No now results in operation being cancelled.</li>
</ul>
</details>

**Release 26.0.20251121.1 (26.4)**

<details>
<summary>VRS: Allow selected users to override payment discounts from Vendor Recon page (click for details)</summary>
<ul>
<li>Trade assistant user setup: new field "Allow Discount Modify"</li>
<li>If turned on, user can edit Discount Available on recon lines</li>
<li>When discount is edited, user will be prompted to confirm.</li>
<li>Discount amount will be transferred to vendor ledger entry</li>
<li>Pmt Discount date on vendor ledger entry will be set to Recon payment date + 1 day</li>
</ul>
</details>

**Release 26.0.20251119.1 (26.3)**
<details> 
<summary>VRS: Manage settlement discount</summary>
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
