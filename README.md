# Forte Change log
Forte by [ForteSG, Inc](https://fortesg.com)

## Summer 2026.02
_Released July 15, 2026_
* Our single date selector has been optimized to minimize clicks when changing to a specific date. This impacts the manager log, cash tracking, and a few reports.
* Accounting \ Export - A new preview alert has been added if a Location + Date combination has unmatched debits and credits to help isolate days that need further inspection.
* Reports \ Accounting Ops Statement – The report now will ignore inventory adjustments to Accounts outside of COGS category (e.g. supplies in an op ex account)
* Inventory Counts – added alerts for missing costs and missing accounts
* Account Name standardization across the accounting module and reports when class code and/or class name are in use
* Expanded the rollout of the report cancelation feature so a user can stop long running reports
* When adding a post, changing the Post Category will now clear out the list of users to notify before loading the users for the new category
* Various mobile app layout improvements
* Updates to several underlying web libraries and components to resolve issues and improve performance within those packages
* Config \ Users – Sorting by Default Location Group is now fixed
* Config \ Users – Fixed a workflow issue with the new layout when adding a new user
* Config \ Employee Detail – Deactivate and Restore functionality was not working correctly
* Employee Portal – The current day shift could disappear before completed under certain week and time zone conditions
* Operations \ Post Category – After a recent change, adding a new post category was always disabled due to a logic issue

## Summer 2026.01
_Released July 8, 2026_

* User Management improvements - table/detail view, additional filtering and sorting options
* Employee Management improvements - table/detail view
* Operations \ Recurring improvements - Location Group added to the columns, additional filtering options
* Checklist dialog improvements - layout updates, ability to edit existing checklist items
* Imported Invoice Summary Journals deep link back to source system invoices
* Site-wide cleanup of button positioning, style, and layout
* Enhanced feedback when pushing sales to Intacct via the API
* Account Class Code and Class Name now shown at the invoice summary level
* COGS Management page adds a search field when viewing unmapped sale items
* An Hours column has been added to the Labor Compliance report for certain compliance types
* An inventory item can now be created while setting up the inventory layout without navigating away from the page
* In labor scheduling, employee visibility is based fully on location and job assignments and not recent work
* Bug fix - Private bookmarks can now be used by the report batch system
* Bug fix - Deactivated report batches can now be restored

## Summer 2026
_Released July 1, 2026_

[Forte Summer 2026 Release Brings Inventory, Recipes & COGS to Restaurant Teams](https://fortesg.com/blog/forte-summer-2026-release-brings-inventory-recipes-cogs-to-restaurant-teams)
* Forte COGS module released including Inventory, Recipe and COGS Invoice pages
* Reports \ Operations Recap now includes an optional weekly metrics section
* Layout changes and fine tuning of the schedule builder page
* The Compliance Pay report has been added as a tab to the payroll validation workflow.  This allows a manager to view compliance pay details without leaving the payroll validation page.
* Reset password email improvements
* Bug fix – Deactivated employees showing when linking users to employee accounts
* Bug fix – Deactivated employees showing under certain conditions when selecting an employee for a shift
* Bug fix – Cannot restore a deactivated schedule
