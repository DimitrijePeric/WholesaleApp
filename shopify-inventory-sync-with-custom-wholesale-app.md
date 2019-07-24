# shopify-wholesale-app-with-inventory-sync

#
## Intro - Sync your warehouse data to your store via Shopify RestAPI

This is a »NON-opensource« private app for Shopify which enables you to pull in data from an external server and use it in the shop's UI.

We're yet to pack it up for Shopify's app store, but it works as intended already, so if you'd like to try it out right away, contact us at <dimitrije.peric@hotmail.com>.

#
#### Practical Details

The script is highly configurable and basically allows what Shopify doesn't natively - pulling in data from an FTP server or similar, and showing/using it on-site.

Having the .CSV table in such a location (which you can generate by hardware trackers, or manually via Excel, Libre Office, Google Sheets, whatever), the script parses it, converts into a data format Shopify finds acceptable, and pulls it into .liquid for manipulation.

In this case, the script is configured for wholesale use (gets displayed for customers logged in with 'wholesale' tag), but can be used on retail shops as well. 

Current configuration is set to parse the CSV for 4 fields (retail price, wholesale price, two price points for volume discounts), pull in that data to .liquid and use it to display in UI or calculate discount prices and so on, and repeat the sync every 30 minutes.

#
#### What the Script Does
  - Takes data from a .CSV or similar stored on your local server
  - Pulls it into your Shopify store for manipulation via Shopify API
  - Allows using that data in .liquid files and displaying it client-side, in the UI
  - And keeps it synced automatically, at desired intervals

#
#### How It Works

Installation is a one-time setup (for as long as addresses remain unchanged), and gets down to this:

• Installs to your Shopify store as a private app
• Data input/output addresses get configured between your store and server
• And finally, .liquid files get edited to use that data and display it to your users - wholesale, retail or both (it includes a custom written wholesale app/portal)

After that, you just basically update the input CSV file (or similar, other formats can be used as well), and the sync is automatic.

#
#### Contact

To get a free live test and custom installation quote (additional features available), contact us at <dimitrije.peric@hotmail.com>. Works as intended guaranteed.
