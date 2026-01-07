## Release notes

**Release .... (27.2.1)**
<details style="font-size: 0.85em;">
<summary>Trade assistant role centre (click for details)</summary>
<ul>
<li>New role centre created to access all trade assistant documents</li>
</ul></details>

<details style="font-size: 0.85em;">
<summary>DCM: Collection Note Search (click for details)</summary>
<ul>
<li>Ability to search for a document number and view the collection notes on which it appears. </li>

[How do I do this?](../DCM/RunDebtors.md)

</ul></details>

<details style="font-size: 0.85em;">
<summary>DCM: Collection Note Document (click for details)</summary>
<ul>
<li>After creating and updating a collection note, you can now generate a PDF or hard copy of the collection note.</li></ul></details>

<details style="font-size: 0.85em;">
<summary>DCM: Debtors Admin Customer list (click for details)</summary>
<ul>
<li>New report listing customers per debtors administrator</li>
</ul></details>

<details style="font-size: 0.85em;">
<summary>DCM: Collection Note Search (click for details)</summary>
<ul>
<li></li>
</ul></details>

<details style="font-size: 0.85em;">
<summary>DCM: Collection Note Search (click for details)</summary>
<ul>
<li></li>
</ul></details>

<details style="font-size: 0.85em;">
<summary>VRS: Disable actions on archived document (click for details)</summary>
<ul>
<li></li>
</ul></details>

<details style="font-size: 0.85em;">
<summary>VRS: Supplier Performance Report (click for details)</summary>
<ul>
<li>New report showing supplier reliability on purchase orders</li>
</ul></details>

<details style="font-size: 0.85em;">
<summary>VRS: Unmatched GRV's (click for details)</summary>
<ul>
<li>New report showing purchase orders not delivered, or delivered and not invoiced.</li>
</ul></details>

**Release 26.0.20251212.2 (27.1.1)**
<details style="font-size: 0.85em;">
<summary>VRS: Search for a vendor document number (click for details)</summary>
<ul>
<li>From the vendor ledger page, or vendor recon list, select 'Find Vendor Reconciliation, enter a document number or external document number. All recons on which the document appears will be listed. Click on the recon number to open the recon.</li>
</ul>
</details>

**Release 26.0.20251212.2 (27.1)**
<details style="font-size: 0.85em;">
<summary>VRS: Report layout - Payment authorisation (click for details)</summary>
<ul>
<li>Font in detail changed to Calibri 7pt.</li>
<li>Document columns changed to allow wrap.</li>
</ul>
</details>

**Release 26.0.20251126.1 (26.6)**
<details style="font-size: 0.85em;">
<summary>VRS: When suggesting lines, system requires response to prompt for discount (click for details)</summary>
<ul>
<li>Message is suppressed if discount value on vendor ledger entry is the same as discount available on recon line.</li>
</ul>
</details>

**Release 26.0.20251124.3 (26.5)**
<details style="font-size: 0.85em;">
<summary>1. VRS: Error message: Amount to pay does not equal matched amount" when clicking on 'Request Approval' (click for details)</summary>
<ul>
<li>Modified filter before calculating totals</li>
</ul>
</details>

<!-- next issue -->
<details style="font-size: 0.85em;">
<summary>2. VRS: The Remittance Advice also does not show the actual net payment correctly when discount is taken (click for details)</summary>
<ul>
<li>Report layout adjusted to include new columns for Discount Claimed and Other deductions.</li>
<li>Font reduced to 7pt to accommodate new columns</li>
<li>Calculation of nett payment adjusted to deduct discount and Other Deductions</li>
</ul>
</details>

<!-- next issue -->
<details style="font-size: 0.85em;">
<summary>3. VRS: On 'Request Approval', when matched amount and payment amount don't match, clicking No on the confirmation dialog has no effect (click for details)</summary>
<ul>
<li>Click on No now results in operation being cancelled.</li>
</ul>
</details>

**Release 26.0.20251121.1 (26.4)**

<details style="font-size: 0.85em;">
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
<details style="font-size: 0.85em;"> 
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
