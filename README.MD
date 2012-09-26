###############################################
ecommerce group pricing
Pre 0.2 proof of concept
###############################################

This module is a must for e-commerce applications
where the product prices go beyond a straight price
for each product. For example, if you want to provide
discounts based on security group of purchaser
(e.g. staff discounts) or customer country of origin.

It also provides a price list page.

Developers
-----------------------------------------------
Nicolaas Francken [at] sunnysideup.co.nz
hans [at] hdrlab.org.nz


Requirements
-----------------------------------------------
Ecommerce 1.0+ / SSU Branch
SilverStripe 2.4+

Project Home
-----------------------------------------------
See http://code.google.com/p/silverstripe-ecommerce

Demo
-----------------------------------------------
See http://www.silverstripe-ecommerce.com

Installation Instructions
-----------------------------------------------
1. Find out how to add modules to SS and add module as per usual.
2. copy configurations from this module's _config.php file
into mysite/_config.php file and edit settings as required.
NB. the idea is not to edit the module at all, but instead customise
it from your mysite folder, so that you can upgrade the module without redoing the settings.

If you just want one or two things from this module
then of course you are free to copy them to your
mysite folder and delete the rest of this module.

History
-----------------------------------------------

0.2 - 2012/09/25
- Added the ability to name discounts, and to display the name and other details 
  via templates
- Removed the dependency on the ecommerce coupon discount module
- Fixed some bugs

0.1 - Initial Version

