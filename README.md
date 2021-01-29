# Cardinity Payment Gateway for WHMCS
This module will enable Commerce Cardinity payments system in your WHHMCS shop. 

### Table of Contents  
[<b>How to install? →</b>](#how-to-install)<br>
      [Using extension installer](#using-exension-installer)  
       [Using FTP](#using-ftp)   
 [<b>Changelog →</b>](#changelog)<br>
 [<b>FAQ →</b>](#faq)<br>
 [<b>About us →</b>](#-aboutus)<br>     
<a name="headers"/>  

## How to install?

### Requirements
• Cardinity account  
• Drupal version 7.x
<br>

### Installation

#### Using "Extension installer"
0) Download the Cardinity Payment Module .zip file that matches your Drupal version from here: https://github.com/cardinity/cardinity-drupal/releases
1) In Drupal base directory, navigate to "modules" folder (usually it's "/sites/all/modules/"
2) Extract the Cardinity module .zip file to "modules" folder
3) Open the terminal, go to base directory of Drupal and enter the command:  
```$ composer require 'drupal/commerce_cardinity:^1.0'```
4) Go to Drupal admin panel and enable the module under "Administration -> Extend" (the module will be in the group "Commerce - Payment"). Choose Commerce Cardinity and click "Install"
5) Configure the payment rule. Go back to Drupal admin panel and navigate to "commerce/config/payment-methods". Under "Plugin" chooce the Cardinity module and insert your Cardinity account API keys.

#### Using composer
0) Download the Cardinity Payment Module .zip file that matches your Drupal version from here: https://github.com/cardinity/cardinity-drupal/releases   
<b>or</b>  
go to https://www.drupal.org/project/commerce_cardinity , scroll down to "Downloads", right click tar.gz (xx.xx KB) or zip (xx.xx KB) and click "Copy link address" of the Cardinity module version of your choice.
1) Open the terminal and go to the base directory of your Drupal site
2) Enter the command:
```$ composer require 'drupal/commerce_cardinity:^1.0'```
3) Then go to Drupal admin panel and navigate to Extend and click "Install new module".
4) Paste the copied URL or upload the Commerce Cardinity module .zip file and press install
5) After installation is complete, under "Next steps" go to "Administration pages". Find and check the box of "Commerce cardinity" module under "Commerce - Payment" and click "Install"
6) Configure the payment rule. Go back to Drupal admin panel and navigate to "commerce/config/payment-methods". Under "Plugin" chooce the Cardinity module and insert your Cardinity account API keys.
### Downloads
Find the latest version of this extension here: https://github.com/cardinity/cardinity-drupal/releases

<details show>
  <summary>For Drupal 7.x</summary>
  
| Version       | Description                                         |Link        |
| ------------- |-----------------------------------------------------|------------|
| 1.0.0         | Cardinity Payment Module for Drupal 7.x.            | <a href="https://github.com/cardinity/cardinity-drupal/releases/tag/1.0.0">Download</a> |
</details>

### FAQ
<details>
  <summary>Question 1 →</summary>
  Answer1
  </details>
  <details>
  <summary>Question2 →</summary>
  Answer2
  </details>
  <details>
<summary>Question2 →</summary>
  Answer2
  </details>

<br>

-----

### ► About us
Cardinity is a licensed payment institution, active in the European Union, registered on VISA Europe and MasterCard International associations to provide <b>e-commerce credit card processing services</b> for online merchants. We operate not only as a <u>payment gateway</u> but also as an <u>acquiring Bank</u>. With over 10 years of experience in providing reliable online payment services, we continue to grow and improve as a perfect payment service solution for your businesses. Cardinity is certified as PCI-DSS level 1 payment service provider and always assures a secure environment for transactions. We assure a safe and cost-effective, all-in-one online payment solution for e-commerce businesses and sole proprietorships.<br>
#### Our features
• Fast application and boarding procedure.   
• Global payments - accept payments in major currencies with credit and debit cards from customers all around the world.   
• Recurring billing for subscription or membership based sales.  
• One-click payments - let your customers purchase with a single click.   
• Mobile payments. Purchases made anywhere on any mobile device.   
• Payment gateway and free merchant account.   
• PCI DSS level 1 compliance and assured security with our enhanced protection measures.   
• Simple and transparent pricing model. Only pay per transaction and receive all the features for free.
### Get started
<a href="https://cardinity.com/sign-up">Click here</a> to sign-up and start accepting credit and debit card payments on your website or <a href="https://cardinity.com/company/contact-us">here</a> to contact us 
#### Keywords
payment gateway, credit card payment, online payment, credit card processing, online payment gateway, cardinity for Drupal.     

  
 [▲ back to top](#Cardinity-Payment-Gateway-for-PrestaShop)
<!--
**fjundzer/fjundzer** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

