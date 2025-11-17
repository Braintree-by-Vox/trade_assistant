# Configure Vendor Reconciliation

## Geting Started
- [Installing from Appsource](#installing-from-appsource)
- [How to request a licence registration key](#how-to-request-a-licence-registration-key)
- [Number Series](#number-series)
- [Setups](#setups)

## Installing from Appsource
Open your Microsoft Dynamics Business Central tenant.
Search for Extension Management.
From the extension management page, select 'AppSource Gallery'. This may take a minute or two to open.
Search for Braintree.
Select 'Braintree Trade Assistant'.
Click on Install App:

![alt text](InstallApp.png)

After the app has installed, the setup page will open. The first thing you need to do is request a licence key.

## How to request a licence registration key
From the Trade Assistant Setup page.
From the menu bar, select 'Register App':

![alt text](RegisterApp.png)

From the list of apps, select 'BCP-TRADEASSIST-VRS', then select 'Request Subscription / Trial licence' from the menu bar:

![alt text](RequestSubscription.png)

An email will be sent to the Braintree service desk.

## Number Series

On installation, the system will create a new number series and insert it in the setup table. You can edit this if required.

![alt text](NoSeries.png)

## Workflow setups
The Trade Assistant model has two versions of workflow: a simple line management model, and a full workflow based on standard Business Central workflow templates.

## User Setups
Users who will be running vendor reconciliations need some basic setups.
From the Trade Assistant setup page, select the menu option: 'User Setups':
![alt text](image.png)

For each recon administrator, fill in the fields:

| Column | Content|
|----------|----------|
| Vendor Recon Approver   | The name of the administrator's immediate supervisor   |
| Default payment Jnl Template   | Select a payment journal batch template from the list   |
| Default Payment Jnl Batch| Select a journal batch name from the list.|

Note: it is a good idea to create separate payment batches for each administrator.
