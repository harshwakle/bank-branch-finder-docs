Bank Finder Plugin - Official Documentation
Welcome to the Official Documentation for the Bank Finder plugin, a powerful WordPress plugin designed to help users search for bank branches by IFSC code, branch name, or location. This guide provides detailed instructions to set up, configure, and use the plugin effectively.
________________________________________
Table of Contents
1.	Introduction
2.	Installation
3.	Getting Started
4.	Using the Shortcode
5.	Uploading Bank Data
6.	Customizing the Plugin
7.	Managing Bank Data
8.	Support Resources
9.	Troubleshooting
10.	Version History
________________________________________
Introduction
The Bank Finder plugin allows WordPress site administrators to provide a user-friendly interface for searching bank branches. Key features include:
•	Search by IFSC code, bank name, state, district, or branch.
•	Customizable UI with colors, fonts, and layout options.
•	CSV import/export for managing bank branch data.
•	Responsive design for mobile and desktop users.
•	Support for animations and dynamic search suggestions.
This documentation will guide you through every step of using the plugin, from installation to advanced customization.
________________________________________
Installation
To install the Bank Finder plugin, follow these steps:
1.	Download the Plugin:
o	Go to the WordPress admin dashboard.
o	Navigate to Plugins > Add New.
o	Search for "Bank Finder" or upload the plugin ZIP file if you have it.
2.	Install and Activate:
o	Click Install Now and then Activate to enable the plugin.
3.	Verify Installation:
o	After activation, a new menu item called Bank Finder will appear in the WordPress admin sidebar.
________________________________________
Getting Started
Follow these steps to set up the Bank Finder plugin:
1.	Access the Admin Panel:
o	In the WordPress admin dashboard, click on Bank Finder in the sidebar.
2.	Upload Bank Data:
o	Go to the Upload CSV tab to import bank branch data (see Uploading Bank Data).
3.	Customize the Appearance:
o	Use the Customize tab to adjust colors, fonts, and layout (see Customizing the Plugin).
4.	Add the Search Form:
o	Use the [bank_finder] shortcode to display the search form on any page or post (see Using the Shortcode).
5.	Manage Data:
o	Use the Manage Data tab to view, edit, or delete bank branch records (see Managing Bank Data).
________________________________________
Using the Shortcode
The Bank Finder plugin provides a shortcode to display the search form on your website:
•	Shortcode: [bank_finder]
•	Usage:
o	Create a new page or post in WordPress.
o	Add the [bank_finder] shortcode in the content editor.
o	Publish or update the page/post.
o	Visit the page to see the search form in action.
•	Example:
•	[bank_finder]
The search form allows users to search for bank branches by:
•	IFSC code (with autocomplete suggestions).
•	Bank name, state, district, or branch (via dropdowns).
________________________________________
Uploading Bank Data
The plugin supports importing bank branch data via CSV files:
1.	Prepare the CSV File:
o	Ensure the CSV file has the following columns:
	Bank Name
	State
	District
	Address
	Branch
	IFSC Code
	Branch Code
	MICR Code
	SWIFT Code
	Contact
o	Save the file in UTF-8 encoding to avoid character issues.
2.	Upload the CSV:
o	Go to Bank Finder > Upload CSV in the admin dashboard.
o	Click Choose File to select your CSV file.
o	Click Upload to import the data.
3.	Verify Import:
o	After uploading, check the Manage Data tab to confirm the data has been imported correctly.
4.	Export Data:
o	You can export existing bank data as a CSV file from the Manage Data tab.
________________________________________
Customizing the Plugin
The Customize tab allows you to tailor the plugin's appearance and behavior:
1.	Access Customization:
o	Go to Bank Finder > Customize in the admin dashboard.
2.	Available Options:
o	Colors: Set primary, secondary, hover, and background colors.
o	Fonts: Choose font family (e.g., Poppins), size, and weight.
o	Layout: Adjust container width, padding, margin, and border radius.
o	Animations: Enable/disable loading animations and transitions.
o	Custom CSS: Add custom styles for advanced customization.
o	Logo: Upload a custom logo for the search form.
o	Text: Customize placeholders and button text (e.g., "Search", "Reset").
3.	Save Changes:
o	After making changes, click Save Settings to apply them.
o	Preview the changes on a page with the [bank_finder] shortcode.
________________________________________
Managing Bank Data
The Manage Data tab allows you to view, edit, or delete bank branch records:
1.	View Data:
o	Go to Bank Finder > Manage Data to see a table of all imported bank branches.
o	Use the search and filter options to find specific records.
2.	Edit Records:
o	Click Edit next to a record to modify its details.
o	Save changes to update the record in the database.
3.	Delete Records:
o	Click Delete to remove a record permanently.
o	Bulk delete options are available for multiple records.
4.	Export Data:
o	Click Export as CSV to download all records.
________________________________________
Support Resources
If you need help with the Bank Finder plugin, explore these resources:
•	Official Documentation:
o	Visit https://github.com/harshwakle/bank-branch-finder-docs/blob/main/Official%20Documentation.md for detailed guides and tutorials.
•	Support Forum:
o	Join the community at https://github.com/harshwakle/bank-branch-finder-docs/blob/main/support-forum.md to ask questions and share feedback.
•	Contact Support:
o	Reach out to the plugin author at https://github.com/harshwakle/bank-branch-finder-docs/blob/main/contact-support.md for personalized assistance.
Note: Ensure you have the latest version of the plugin (v1.8) for access to all features and support.
________________________________________
Troubleshooting
Common issues and their solutions:
1.	Search Form Not Displaying:
o	Ensure the [bank_finder] shortcode is added to a page or post.
o	Check if the plugin is activated.
o	Verify that bank data is imported via CSV.
2.	CSV Import Fails:
o	Confirm the CSV file has the correct column headers and UTF-8 encoding.
o	Check for errors in the admin dashboard after uploading.
3.	Styles Not Applying:
o	Clear your browser cache or WordPress cache (if using a caching plugin).
o	Ensure custom CSS is correctly formatted in the Customize tab.
4.	Links Not Working:
o	Verify the URLs for Official Documentation, Support Forum, and Contact Support in the Help tab.
o	Contact support if the issue persists.
If you encounter other issues, refer to the Support Resources section for assistance.
________________________________________
Version History
•	Version 1.8 (Current):
o	Added support for IFSC autocomplete suggestions.
o	Improved responsive design for mobile devices.
o	Enhanced customization options for colors and fonts.
o	Fixed bugs in CSV import/export functionality.
•	Version 1.7:
o	Introduced CSV export feature.
o	Added bulk delete option in Manage Data.
o	Improved performance for large datasets.
•	Version 1.6:
o	Initial release with basic search and CSV import features.
For a complete changelog, visit the Official Documentation.
________________________________________
Bank Finder Plugin is developed by Harsh Wakle. For feedback or feature requests, contact us via the Support Resources.

