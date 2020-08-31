# PayDollar/SaimPay/PesoPay Payment plugin for Drupal
Use PayDollar/SaimPay/PesoPays plugin for Drupal to offer ALL payments option.

## Download
Please download the latest plugin version. [Download](https://github.com/asiapay-lib/asiapay-Drupal/releases/latest)

## Integration
The plugin integrates Drupal with PayDollar/SaimPay/PesoPay payment gateway with All payment method.

## Requirements
This plugin supports Drupal Commerce (Kickstart 2.x) 7.x and higher.

## Installation
1.	Go to Modules the click **'Install new module'**. Browse the module and click the 'Install' button
2.	After successful installation, click the **'Enable newly added modules'** to go to the 
3.	Search for **'Commerce AsiaPay'** module and enable it then click 'Save Configuration' on the left sidebar.
4.	Then go to Go to ***Store > Configuration > Payment Methods***. Look for 'AsiaPay' and click 'enable'
5.	Once enabled, click **'edit'**.
6.  Find AsiaPay on the **'Actions section'** and click **'edit'**
7.  Setup the AsiaPay module correctly and click the **'Save'** button.

## Setup the Datafeed URL on PayDollar/PesoPay/SiamPay
 1. Login to your PayDollar/PesoPay/SiamPay account.
 2. After login, Go to left sidebar on Profile > Profile Settings > Payment Options.
 3. Click the “Enable” radio and set the datafeed URL on “Return Value Link” and click the “Update” button. The datafeed URL should be like this: http://www.yourdrupalcommercesite.com/commerce_asiapay/datafeed
 4. On the confirmation page, review your changes then click the “Confirm button”.

 ## Documentation
[Drupal documentation](https://github.com/asiapay-lib/asiapay-Drupal/raw/master/Drupal%20Commerce%20Module%20Integration%20Guide%2020140917.doc)

## Support
If you have a feature request, or spotted a bug or a technical problem, create a GitHub issue. For other questions, contact our [Customer Service](https://www.paydollar.com/en/contactus.html).

## License
MIT license. For more information, see the LICENSE file.
