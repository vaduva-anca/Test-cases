#Test Case Samples#
Below are some Test Case samples that I wrote while working on previous projects.
----------------------------------------------------
## Test Case for Login
**Description:** Check if the login works when a person uses a correct user/pass.
**Steps to Reproduce:**
  1.	Go to www.website.com/login
  2.	Add a correct user / pass
  3.	Press Login button
**Expected result:** User should be able to login and is taken to his profile page.
**Test Data:** User: anca & Pass: 1234

----------------------------------------------------------
## Test Case for Password Recovery
**Description**: Verify the password recovery functionality
**Steps to Reproduce:**
  1.	Go to www.website.com/login
  2.	Click on the "Forgot Password" link.
  3.	Enter the email address associated with the account.
  4.	Click the "Recover Password" button.
  5.	Check the email for the password reset link.
  6.	Click the link received in the email.
  7.	Enter and confirm the new password.
  8.	Click the "Reset Password" button.
**Expected result:** The password is successfully reset, and the user can use the new password to log in.
**Test Data:** User: anca@email.com
**Note:** Please check the login again after running this test case.



----------------------------------------------------
## Test Case for Adding a Product to Cart
**Description:** Verify adding a product to the cart
**Steps to Reproduce:**
  1.	 Go to www.website.com
  2.	Go to the product detail page
  3.	Select the product options (size, color, etc.).
  4.	Click the "Add to Cart" button.
  5.	Navigate to the "Cart" page.
**Expected result:** The selected product is displayed in the cart with all correct details (quantity, price, chosen options).

----------------------------------------------------
## Test Case for Product Filtering
**Description:** Verify filtering products by price
**Steps to Reproduce:**
  1.	Go to www.website.com
  2.	Access the "Filters" section.
  3.	Select the desired price range (e.g., $125-$278).
  4.	Apply the filter.
**Expected result:** Only products that fall within the selected price range are displayed.

----------------------------------------------------
## Test Cases for Invalid Login
**Description:** Verify login with invalid credentials
**Case 1:**
**Steps to Reproduce:**
  1.	Go to www.website.com/login
  2.	Enter an invalid username.
  3.	Enter an valid password.
  4.	Click the "Login" button.
**Case 2:**
**Steps to Reproduce:**
  1.	Go to www.website.com/login
  2.	Enter an valid username.
  3.	Enter an invalid password.
  4.	Click the "Login" button.
**Case 3:**
**Steps to Reproduce:**:
  1.	Go to www.website.com/login
  2.	Enter an invalid username.
  3.	Enter an invalid password.
  4.	Click the "Login" button.
**Expected result:** The system displays an error message indicating that the username or password is incorrect, and the user is not logged in.








