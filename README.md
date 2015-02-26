# PayJunction Gateway Module for WooCommerce
Gateway Module for WooCommerce using PayJunction REST API

Requirements:
  WordPress version >= 4.1
  WooCommerce version >= 2.2
  PHP cURL module
  
Installation Instructions:
  1. Install PHP cURL
    a. 'sudo apt-get install php5-curl' on Linux systems using Apt
    b. For other systems please see this page for manual installation instructions: http://curl.haxx.se/libcurl/php/install.html
  
  2. Copy the wc-payjunction-rest folder into your WordPress plugins folder (wp-content/plugins).
  3. Go to the Plugins page in the WordPress administration panel and activate the 
      PayJunction Gateway Module for WooCommerce.
  4. Go to WooCommerce->Settings page and click the Checkout tab
  5. Make sure Force SSL Checkout is enabled and save the settings
  6. Click the PayJunction REST link to edit the module settings
  7. Make desired changes to the settings of the module here.
    a. REQUIRED: To use live mode, you must save your QuickLink API login and password where indicated.
      1) Use the Test Credentials button to check that your API credentials are valid.
      2) Don't have your API credentials? See this guide: <placeholder>
    b. SUGGESTED: Not familiar with Address Verification Security? Read our guide here: <placeholder>
    c. SUGGESTED: For a full description for each setting see our guide here: <placeholder>
  8. It is recommended to do a test transaction through the shopping cart and verify the transaction shows up in 
      your batch in the PayJunction website.
