Bank Finder Plugin - Official Documentation
Welcome to the Official Documentation for the Bank Finder plugin, a powerful WordPress plugin designed to help users search for bank branches by IFSC code, branch name, or location. This guide provides detailed instructions to set up, configure, and use the plugin effectively.

Table of Contents

Introduction
Installation
Getting Started
Using the Shortcode 
Uploading Bank Data
Customizing the Plugin
Managing Bank Data
Support Resources  
Troubleshooting
Version History


Introduction
The Bank Finder plugin allows WordPress site administrators to provide a user-friendly interface for searching bank branches. Key features include:

Search by IFSC code, bank name, state, district, or branch.
Customizable UI with colors, fonts, and layout options.
CSV import/export for managing bank branch data.
Responsive design for mobile and desktop users.
Support for animations and dynamic search suggestions.

This documentation will guide you through every step of using the plugin, from installation to advanced customization.

Installation
To install the Bank Finder plugin, follow these steps:

Download the Plugin:

Go to the WordPress admin dashboard.
Navigate to Plugins > Add New.
Search for "Bank Finder" or upload the plugin ZIP file if you have it.


Install and Activate:

Click Install Now and then Activate to enable the plugin.


Verify Installation:

After activation, a new menu item called Bank Finder will appear in the WordPress admin sidebar.




Getting Started
Follow these steps to set up the Bank Finder plugin:

Access the Admin Panel:

In the WordPress admin dashboard, click on Bank Finder in the sidebar.


Upload Bank Data:

Go to the Upload CSV tab to import bank branch data (see Uploading Bank Data).


Customize the Appearance:

Use the Customize tab to adjust colors, fonts, and layout (see Customizing the Plugin).


Add the Search Form:

Use the [bank_finder] shortcode to display the search form on any page or post (see Using the Shortcode).


Manage Data:

Use the Manage Data tab to view, edit, or delete bank branch records (see Managing Bank Data).




Using the Shortcode
The Bank Finder plugin provides a shortcode to display the search form on your website:

Shortcode: [bank_finder]

Usage:

Create a new page or post in WordPress.
Add the [bank_finder] shortcode in the content editor.
Publish or update the page/post.
Visit the page to see the search form in action.


Example:
[bank_finder]



The search form allows users to search for bank branches by:

IFSC code (with autocomplete suggestions).
Bank name, state, district, or branch (via dropdowns).


Uploading Bank Data
The plugin supports importing bank branch data via CSV files:

Prepare the CSV File:

Ensure the CSV file has the following columns:
Bank Name
State
District
Address
Branch
IFSC Code
Branch Code
MICR Code
SWIFT Code
Contact


Save the file in UTF-8 encoding to avoid character issues.


Upload the CSV:

Go to Bank Finder > Upload CSV in the admin dashboard.
Click Choose File to select your CSV file.
Click Upload to import the data.


Verify Import:

After uploading, check the Manage Data tab to confirm the data has been imported correctly.


Export Data:

You can export existing bank data as a CSV file from the Manage Data tab.




Customizing the Plugin
The Customize tab allows you to tailor the plugin's appearance and behavior:

Access Customization:

Go to Bank Finder > Customize in the admin dashboard.


Available Options:

Colors: Set primary, secondary, hover, and background colors.
Fonts: Choose font family (e.g., Poppins), size, and weight.
Layout: Adjust container width, padding, margin, and border radius.
Animations: Enable/disable loading animations and transitions.
Custom CSS: Add custom styles for advanced customization.
Logo: Upload a custom logo for the search form.
Text: Customize placeholders and button text (e.g., "Search", "Reset").


Save Changes:

After making changes, click Save Settings to apply them.
Preview the changes on a page with the [bank_finder] shortcode.




Managing Bank Data
The Manage Data tab allows you to view, edit, or delete bank branch records:

View Data:

Go to Bank Finder > Manage Data to see a table of all imported bank branches.
Use the search and filter options to find specific records.


Edit Records:

Click Edit next to a record to modify its details.
Save changes to update the record in the database.


Delete Records:

Click Delete to remove a record permanently.
Bulk delete options are available for multiple records.


Export Data:

Click Export as CSV to download all records.



Support Resources
If you need help with the Bank Finder plugin, explore these resources:

Official Documentation:

Visit https://harshwakle.github.io/bank-branch-finder-docs/ for detailed guides and tutorials.


Support Forum:

Join the community at https://example.com/support-forum to ask questions and share feedback.


Contact Support:

Reach out to the plugin author at https://example.com/contact-support for personalized assistance.


Note: Ensure you have the latest version of the plugin (v1.8) for access to all features and support.

Troubleshooting
Common issues and their solutions:

Search Form Not Displaying:

Ensure the [bank_finder] shortcode is added to a page or post.
Check if the plugin is activated.
Verify that bank data is imported via CSV.

CSV Import Fails:

Confirm the CSV file has the correct column headers and UTF-8 encoding.
Check for errors in the admin dashboard after uploading.


Styles Not Applying:

Clear your browser cache or WordPress cache (if using a caching plugin).
Ensure custom CSS is correctly formatted in the Customize tab.


Links Not Working:

Verify the URLs for Official Documentation, Support Forum, and Contact Support in the Help tab.
Contact support if the issue persists.


If you encounter other issues, refer to the Support Resources section for assistance.

Version History

Version 1.8 (Current):

Added support for IFSC autocomplete suggestions.
Improved responsive design for mobile devices.
Enhanced customization options for colors and fonts.
Fixed bugs in CSV import/export functionality.


Version 1.7:

Introduced CSV export feature.
Added bulk delete option in Manage Data.
Improved performance for large datasets.


Version 1.6:

Initial release with basic search and CSV import features.


For a complete changelog, visit the Official Documentation.

Bank Finder Plugin is developed by Harsh Wakle. For feedback or feature requests, contact us via the Support Resources.
