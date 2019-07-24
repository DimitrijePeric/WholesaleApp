# shopify-wholesale-app-with-inventory-sync
#
#

## Intro – Sync your warehouse data to your store via Shopify RestAPI

This is a configurable 'private app' for Shopify which enables you to parse data from your external server and use it in the shop's UI. 

#
#### What the Script Does
  - Takes data from a CSV data sheet stored on your local server (FTP or otherwise)
  - Pulls it into your Shopify store for manipulation via Shopify API
  - Allows using that data in .liquid files and displaying it client-side, in the UI
  - And keeps it synced automatically, at desired intervals


#
#### Practical Details

The script is highly configurable and basically allows what Shopify doesn't natively – pulling in data from an FTP server or similar, and showing/using it on-site.

Having the .CSV table in such a location (which you can generate by hardware trackers, or manually via Excel, Libre Office, Google Sheets, whatever), the script parses it, converts into a data format Shopify finds acceptable, and pulls it into .liquid for manipulation.

In this case, the script is configured for wholesale use (gets displayed for customers logged in with 'wholesale' tag), but can be used on retail shops as well. 

Current configuration is set to parse the CSV for 4 fields (retail price, wholesale price, two price points for volume discounts), pull in that data to .liquid and use it to display in UI or calculate discount prices and so on, and repeat the sync every 30 minutes.


#
#### How to Use It

Since this is a by-product of one of Shopify projects for a client, don't expect much documentation any time soon, but the installation process basically gets down to this:

• Install to your Shopify store as a private app
• Configure data input/output adresses
• Customize your .liquid files to suit your needs

Alternatively, if you'd like us to do that for you, you can contact us at <dimitrije.peric@hotmail.com>
