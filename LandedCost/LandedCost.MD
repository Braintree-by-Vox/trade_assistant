# Landed Cost
Products which are purchased for resale or for production may attract surcharges such as freight, import duties, inspection fees. Some of these costs may only be finalised weeks or months after the product has been received into the business. This can lead to stock items being incorrectly costed, and to selling prices being too high or too low.

The Landed Cost module of Trade Assistant provides tools to incorporate interim estimates for all supplimentary costs into the purchase cost of goods before the service providers' invoices have been processed, and to accrue for the costs in the general ledger.

## Configuration and Setup

### Item Charges
Supplimentary costs are defined under the Item Charges table. The table allows you to specify a preferred supplier for each defined charge. :

![alt text](image.png)

### Landed Cost Templates
Landed cost templates are used to define groups of item charges that should be applied to when buying certain products. After definition, the template can be attached to an item, or added on a purchase line.

Search for 'Landed Cost Template':

![alt text](image-3.png)

![alt text](image-4.png)

Click on New to create a new template. 

Go to the item list, and open the item card. Enter a code and description, and tick on 'Apply to Purchase'.

![alt text](image-5.png)

For each item charge to be applied, enter a line:

| **Field**          | **Value** |
| Charge Item        | Select an option from the dropdown. |
| Accrue on Receipt  | Tick ON if you want the charge to accrue when primary product is received |
| Calculation Type   | Select: Flat / Percent / Quantity |
| Calculation Amount | The rate to be applied to an order line | 

On the 'Costs and Purchasing' tab, drill down on the field 'Purchase Surcharge':

![alt text](image-1.png)

This will open a list of defined surcharges for the item.

![alt text](image-2.png)

## Attach Landed Cost Templates to Items
If you attach a landed cost template to an item, it will be automatically activated when you use the item on a purchase order.

Go to Items. Open the item card.

On the Costs and Posting tab, select the field 'Landed Cost Template', and select an option from the dropdown:

![alt text](image-6.png)

## Create landed costs on purchase orders
**Create a new order**
Create a new purchase and capture lines for the items to be purchased, as per normal Business Central processing.

If the item you selected is linked to a landed cost template, the code will be inserted on the order line:

![alt text](image-7.png)

You can amend the code, or insert a template code into lines which are not linked to landed costs templates.

**Generate Surcharges for Landed Cost**
After entering all lines and assigning landed cost templates, click on 'Generate Surcharges':

![alt text](image-8.png)

For each purchase order line which has a landed cost template attached, surcharge lines will be created, using the item charges associated with the template:

![alt text](image-9.png)

The calculation type, calculation rate and preferred vendor will be defaulted from the template. You can amend these if required.

Charges can be added manually to the list if desired.

**Generate Surcharge Orders**
For each surcharge, ensure that a vendor has been captured into the 'Sevice Provide' column.  Click on 'Generate Surcharge Orders'.

![alt text](image-10.png)

For each service provider used on the surcharge lines, a purchase order will be created for later use. The order number is inserted into the column 'Surcharge Purchase Order No.". You can view the orders by clicking on the order number:

![alt text](image-11.png)

![alt text](image-12.png)

## Accrue costs on purchase receipts

## Posting landed cost invoices


[**⬆️ Back to Top**](#landed-cost) &nbsp;&nbsp;&nbsp;&nbsp; [**🏠 Home**](/trade_assistant)