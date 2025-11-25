# Forward Exchange Contracts

The Forward Exchange Contracts module is a tool to assist importers to manage their foreign currency exposures on purchases. It provides options to reduce the risk posed by undpredictable exchange rates, improve cash flow forecasting and provide more accurate costing on imported inventory.

It is suitable for businesses that rely heavily on imported inventory

## Configuration and Setups
Go to Trade Assistant Setup.

On installation, the system will have created 
- a number series for FEC contracts.
- a default FEC duration of 6 months
- a payment journal template and batch.

![alt text](FECSetup.png)

## Creating contracts
**Capture the Contract Details**
Search for FEC Contracts, and click on the link to open the list.
From the list, click on New to create a new contract.

![alt text](image.png)

Select a bank account from the drop down. The system will allocate a contract number.
Complete the required information in the header:

| Field Name | Content |
|---|---|
| FEC Contract No. | The document number issued by the bank |
| Purchase Date | The date on which the contract was purchased|
| Settlement date|    | Will be set by adding the default expiry period to the purchase date, amend if required|
| Currency code| Defaults to the bank's currency; amend if necessary |
| Rate of Exchange | Defaults to system exchange rate. Change to the rate of the contract|
| Forex Amount Purchased | The value of foreign exchange purchased, in the currency of the contract |

The system will calculate the value of the contract in local currency, as per the following example:

![alt text](image-1.png)

**Release and Post the Contract**
Click on 'Release' in the menu bar.

![alt text](image.png)

The FEC header will no longer be editable. You can re-open the contract at this point, if you need to change anything. If you are happy with the contract, click on 'Post'. This will create an entry in the FEC ledger, recording the exact value of the contract. The entries can be viewed under 'Ledger Entries'.

**Load Purchase Documents from Contract**
To load multiple purchase orders, invoices or credit memos from the contract, click on 'Load Documents'. (This option will not be available until the contract has been posted.)

![alt text](image-2.png)

From the dialog, select the document types that need to be included. (By default, orders and invoices will be included.) Click OK.

![alt text](image-3.png)

A list of available documents in the currency of the contract will be presented. To appear on the list, the document must have been released, and must have a due date on or before the expiry date of the contract.
Highlight the documents you want to load onto the contract, and click OK.

![alt text](image-4.png)

The documents will be connected to the contract, and appear in the lines of the contract card. The balance of the contract will be updated:

![alt text](image-5.png)

You can review the documents by clicking on the Source Document No. The document page will open.
The field 'FEC Contract' shows the value covered by FEC contracts.

![alt text](image-6.png)

**Post a receipt for a FEC-linked purchase order**

**Post an invoice for a FEC-linked purchase order**

**Post an invoice linked to FEC**

**Link a posted invoice to FEC**

