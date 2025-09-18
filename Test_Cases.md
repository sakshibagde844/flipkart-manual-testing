* Flipkart Manual Testing - Test Cases

| Test Case ID | Scenario                    | Module      | Steps                                                    | Test Data                              | Expected Result                         | Status |
|--------------|-----------------------------|-------------|----------------------------------------------------------|---------------------------------------|---------------------------------------|--------|
| TC_001       | Login with valid credentials | Login       | 1. Open site  2. Enter email/password  3. Click Login    | Email: test@site.com  Password: pass123 | User redirected to homepage            | Pass   |
| TC_002       | Login with invalid credentials | Login       | 1. Open site  2. Enter email/password  3. Click Login    | Email: test@site.com  Password: wrong  | Error message "Invalid credentials"    | Pass   |
| TC_003       | Register new user            | Signup      | 1. Click Sign Up  2. Fill mandatory fields  3. Submit    | Valid name, email, phone               | Account creation success message       | Pass   |
| TC_004       | Search for product          | Search      | 1. Enter “Shoes” in search bar  2. Click Search          | Keyword: Shoes                        | List of shoe products displayed        | Pass   |
| TC_005       | Apply price filter          | Filters     | 1. Search product  2. Apply price filter ₹1000–₹2000      | Price Range: 1000–2000                 | Products within price range displayed  | Pass   |
| TC_006       | View product details page   | Product Page| 1. Click on product name                                  | Any product                          | Full product details shown              | Pass   |
| TC_007       | Add item to cart            | Cart        | 1. Click "Add to Cart" on product page                    | Any product                          | Item successfully added to cart         | Pass   |
| TC_008       | Remove item from cart       | Cart        | 1. Go to cart  2. Click remove item                       | Product present in cart               | Item removed from cart                   | Pass   |
| TC_009       | Proceed to checkout         | Checkout    | 1. Add item to cart  2. Click "Checkout"  3. Enter address  4. Confirm payment | Valid address and payment details      | Order confirmation page displayed       | Pass   |
| TC_010       | Search with special chars (Negative Test) | Search | 1. Enter "###@@@" in search bar  2. Click Search          | Input: ###@@                        | Show "No results found" or appropriate error | Pass   |
| TC_011       | Add item to wishlist        | Wishlist    | 1. Click "Add to Wishlist" on product                      | Any product                          | Item added to wishlist                   | Pass   |
| TC_012       | Remove item from wishlist   | Wishlist    | 1. Go to wishlist  2. Remove item                          | Product present in wishlist           | Item removed from wishlist               | Pass   |
| TC_013       | Verify user profile update  | Profile     | 1. Go to profile  2. Edit details  3. Save changes        | New phone/email                      | Profile updates saved successfully      | Pass   |
| TC_014       | Verify order history        | Orders      | 1. Login  2. Go to order history                           | Any previous orders                   | List of past orders displayed            | Pass   |
| TC_015       | Logout from the application | Logout      | 1. Click logout button                                     | Logged in user                      | User logged out and redirected to login page | Pass   |

