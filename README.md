### Build 14
- updates to PO Line #
- update to PO number input on checkout
- update to saved cart image paths


### Build 13

- New features
    - **Bulk Shipping Selection**: Update shipping options to allow bulk or individual package assignment.
    - **Pre-populate Manufacturing Type**: Default manufacturing type based on the first item in the cart.
    - **Default Warehouse Location**: Automatically set the default warehouse based on the first cart item.
    - **New Product Images:** Included category and subcategory images paths for Nipples.
    - **Enforcing time zones**: Warehouse selection now accounts for time zone offsets to ensure accurate operations and scheduling.
- Bug fixes
    - **Limit PO Number Length**: Enforce PO numbers to 30 characters on the checkout page.
    - **Navbar Search Reset**: Clear the navbar search field on page redirect or refresh.
    - **Save Cart Without PO Numbers**: Enable the "Save Cart" button even when PO Line Numbers are not entered.
    - **Notes on Confirmation Screen:** If notes are not entered, the Note summary does not appear in the confirmation screen (previously “Empty”).
    - **Fix Package Grouping**: Resolve issue where packages split into multiple packages for the same warehouse.
    - **Rename Billing Address**: Change "Billing Address" to "Third Party Billing Address."
    - **Remove Homepage Categories**: Remove categories from the homepage.
    - **Truncate Long Fields**: Shorten fields longer than 50 characters with ellipsis on the checkout and confirmation page.
    - **Toast After Saving Cart**: Display a green toast notification after saving a cart.
    - **Numeric PO Line Entries**: Restrict the PO Line Number field to accept numeric values only.
    - **Fix Address Creation**: Address issue with missing data (e.g., missing zip code) when creating new addresses.
    - **Disable Edit for Saved Carts**: Prevent edits and deletions to items in saved carts.
    - **Display PO Line on Completed Orders**: Show PO Line Numbers under each item on completed orders.
    - **Show Discounts in Order History**: Ensure discounts are visible in past orders and order history.
    - **Persist PO Line in Saved Carts**: Save PO Line Numbers in saved carts and make them non-editable.
    - **Fix Grayed-Out Calendar Dates**: Address issues with unavailable dates being grayed out during order scheduling.
    - **Correct Search Results**: Ensure filter values in search results are accurate and readable.
    - **Change PLP Sort Order**: Default PLP sort to "Size" ascending instead of "Description” ascending.