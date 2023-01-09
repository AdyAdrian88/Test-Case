# Test Case Samples

.......................................................................................................................................................................

**Description**
Check if the login works when a person uses a correct user/pass

**Steps to reproduce**
1. Go to https://www.emag.ro/
2. Add correct user/pass
3. Press Login button

**Expected Result**
User should be able to login and is taken to his profile page

**Test Data**
User: test
Pass: 123


.......................................................................................................................................................................

**Description** 
Check if forgot password functionality works as expected and an email withe reset password link is sent

**Steps to reproduce**
1. Go to https://www.emag.ro/
2. Press "Forgot Password" button
3. Add an email address
4. Press "Recover" button

**Expected Result**
User should receive an email with a reset password link. That link should allow the user to create a new password

**Test Data**
User: test@email.com

**Note**
Please check the login again after running this test case
