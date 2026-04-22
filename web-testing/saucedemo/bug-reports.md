# Bug Reports - SauceDemo

---

## [BUG-1] Unable to add more than two products to cart for problem_user

**Environment:**
- Browser: Chrome
- Platform: Web
- User: problem_user

**Preconditions:**
User is logged in as problem_user

**Steps to reproduce:**
1. Open https://www.saucedemo.com/
2. Log in as problem_user
3. Add first product to cart
4. Add second product to cart
5. Try to add a third product

**Actual result:**
The third product is not added to the cart. Cart badge does not update.

**Expected result:**
User should be able to add multiple products to the cart.

**Severity:** Medium  
**Priority:** Medium  

**Note:**
Issue is reproducible only for problem_user. Works correctly for standard_user.

---

## [BUG-2] Remove button does not work on inventory page for problem_user

**Environment:**
- Browser: Chrome
- Platform: Web
- User: problem_user

**Preconditions:**
User is logged in and has items in cart

**Steps to reproduce:**
1. Log in as problem_user
2. Add any products to cart
3. Click "Remove" button on inventory page

**Actual result:**
Products are not removed from cart on inventory page.

**Expected result:**
Products should be removed from cart when clicking "Remove".

**Severity:** Medium  
**Priority:** Medium  

**Note:**
Issue is reproducible only for problem_user. Works correctly for standard_user.

---

## [BUG-3] Product data is displayed incorrectly for problem_user

**Environment:**
- Browser: Chrome
- Platform: Web
- User: problem_user

**Preconditions:**
User is logged in as problem_user

**Steps to reproduce:**
1. Open https://www.saucedemo.com/
2. Log in as problem_user
3. Observe product list on inventory page

**Actual result:**
- All product images are identical
- Product descriptions do not match the products
- Some product names do not correspond to displayed items

**Expected result:**
Each product should display correct image, name, and description.

**Severity:** High  
**Priority:** High  

**Note:**
Issue is reproducible only for problem_user. Works correctly for standard_user.
