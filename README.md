### RC2
- Remove a caching dependence on warehouse availability
- Clear global cart and associated selection after checkout
- Changes to attention/tag passing to reference field
- Catalog fetch performance improvments
- Additional bug fixes and improvements

### RC1
- Updates to saved carts (hyperlinks, images, updated recall messaging)
- Various cart editing fixes
- Various cart update fixes
- Added attention tag for all non-will call packages
- Corrected subtotal calculations in confirmed orders
- Resolved issues when adding high-quantity items
- Set cookie expiration and graceful handling expired tokens
- Changed “Search for part” to “Search by description”
- Updated hero copy; re-added category/subcategory search options
- Fixed UI/UX states when changing quantities and switching manufacturers
- Reference number passes from top line item
- Reintroduced a red warning message for zero list price
- Limited search results display to categories
- Fixed issues adding over-available-quantity items to cart
- Ensured “Add to Cart” updates correctly when navigating via footer links
- Unify “attention” tag on all applicable shipments
- Show correct messages for unavailable “Approved” products
- Fixed address resubmission and related UI inconsistencies
- Additional bug fixes and improvements

### Build 17
- Prevent creating source map files to avoid endpoints in source code.
- Improved handling for shipping terms selection in carts under various scenarios.
- Add phone number to addresses.
- Disable order submission if cart is inactive and show error message.
- Change copy to “PO Line # is required.”
- Update sold-out UI to recommend contacting Allied.
- Handle items with no list price to recommend contacting Allied.
- Require “Attention To / Tag” if UPS carrier is selected and pass on checkout.
- Bug fix for PO numbers not populating.
- Prevent users from selecting weekends for custom dates.
- Reverting back from Fastly endpoints.
- Additional bug and UI fixes.

### Build 16
* No release *

### Build 15
- Updated all image URLs to use new Fastly path.
- Updated UI copy to display "Include PO Line #s" in relevant sections.
- Added detailed line item data to the checkout confirmation screen.
- Improved cart design by repositioning elements, updating text, and refining layout for clarity.
- Added specific error messages for missing shipping terms or PO Line #s during checkout.
- Updated banner design to move buttons and adjust font size.
- Resolved issue where items from multiple warehouses were not consolidating correctly due to API response latencies.
- Restricted weight values to one decimal point in the cart.
- Corrected saved cart image URLs pointing to placeholder locations.
- Restored the homepage to its original layout.
- Added a new footer link to "Technical Information".
- Updated size filter logic to sort values numerically instead of alphabetically.
- Implemented logic to auto-fill freight account numbers based on carrier and customer IDs.


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
