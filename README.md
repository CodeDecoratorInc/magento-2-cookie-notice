# Magento 2 Cookie Notice Extension

## Introduction
The **Magento 2 Cookie Notice** extension helps store owners comply with global privacy laws by displaying a cookie consent banner on their websites. This extension allows you to inform visitors about the usage of cookies and obtain their consent seamlessly, ensuring transparency and legal compliance.

## How It Works
The **Magento 2 Cookie Notice** extension displays a fully customizable cookie consent banner on your store. Store owners can modify the banner text, colors, and button styles to match their branding. Customers can either accept the cookies or learn more about the website's cookie policies. The extension also provides options to manage cookie preferences and comply with GDPR, CCPA, and other data protection regulations.

## Key Features
- Display a customizable cookie consent banner
- Support for GDPR and CCPA compliance
- Enable/Disable cookie notice from the admin panel
- Multi-language support for global stores

## Advanced Customization
### Customizable Banner Text & Style
Modify the cookie banner message, button text, and styling to match your store’s branding.

### GDPR & CCPA Compliance
Ensure legal compliance by informing visitors about cookie usage and obtaining their consent before tracking begins.

### Easy Enable/Disable Option
Enable or disable the cookie notice extension from the Magento admin panel with just a few clicks.

### Multi-Language Support
Supports multiple languages to cater to global audiences and improve user experience.

## Extension Installation

### Step 1: Install the extension using Composer
```sh
composer require codedecorator/magento2-cookie-notice
```
For a specific version:
```sh
composer require codedecorator/magento2-cookie-notice:<version>
```
*Note: You may need authentication keys from the vendor or Magento Marketplace.*

### Step 2: Run Magento Commands
```sh
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
```

## How to Configure Magento 2 Cookie Notice Extension

### Step 1: Navigate to the Admin Panel
Go to **Stores** > **Configuration** > **CodeDecorator** > **Cookie Notice**.

### Step 2: Enable the Extension
Set **Enable Cookie Notice** to **Yes**.

### Step 3: Customize the Cookie Notice Banner
- Edit the **Banner Text**
- Modify **Button Labels**
- Choose **Colors & Styling**

### Step 4: Save Configuration
Click **Save Config** and clear the cache using:
```sh
php bin/magento cache:flush
```

## Download Our [Magento 2 Cookie Notice](https://codedecorator.com/magento-2-cookie-notice.html) Extension
