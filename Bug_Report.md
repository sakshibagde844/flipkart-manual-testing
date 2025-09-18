* Flipkart Manual Testing - Bug Report

| Bug ID  | Title                         | Module    | Severity  | Steps to Reproduce                                  | Expected Result                     | Actual Result                     | Status     |
|---------|-------------------------------|-----------|-----------|---------------------------------------------------|-----------------------------------|---------------------------------|------------|
| BUG_001 | "Remove" button not working    | Cart      | Major     | 1. Add item to cart  2. Go to cart  3. Click Remove | Item should be removed from cart  | Nothing happens when clicked     | Open       |
| BUG_002 | Payment fails on Chrome browser | Checkout  | Critical  | 1. Add item  2. Checkout  3. Enter card details  4. Click Pay | Payment should be processed       | Page freezes and payment fails   | In Progress|
| BUG_003 | Search crashes with special chars | Search    | Critical  | 1. Enter "%%%$$$" in search bar  2. Click Search   | Show "No Results Found" message   | Application crashes              | Open       |
| BUG_004 | Wishlist not saving after login | Wishlist  | Medium    | 1. Add item to wishlist  2. Logout  3. Login again  | Wishlist items remain saved       | Wishlist is empty                | Open       |
| BUG_005 | Mobile UI broken on cart page   | UI        | Minor     | 1. Open site on mobile  2. Add item  3. Go to cart | Responsive layout maintained      | Layout broken and overlaps       | Open       |
