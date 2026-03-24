## TC_REGISTRATION_001

**Title:** Verify user can submit form with valid data  

**Execution Date:** 24 March 2026  

**Preconditions:**  
User is on the registration form page  

**Test Data:**  
Name: Hamza Test  
Email: testuser123@test.com  
Mobile: 0744825562  

**Steps:**  
1. Open registration page  
2. Enter valid first name  
3. Enter valid last name  
4. Enter valid email  
5. Select gender  
6. Enter valid mobile number  
7. Enter valid date of birth  
8. Enter subject  
9. Select hobbies  
10. Enter address  
11. Select state  
12. Select city  
13. Click submit  

**Expected Result:**  
Form is successfully submitted and confirmation message is displayed  

**Actual Result:**  
Form is successfully submitted and confirmation message is displayed  

**Status:**  
Pass  

**Tested By:** Hamza Sattar  

## TC_REGISTRATION_002
**Title:** Verify form validation for invalid email  

**Execution Date:** 24 March 2026  

**Preconditions:**  
User is on the registration form page  

**Test Data:**  
Email: invalidemail  

**Steps:**  
1. Open registration page  
2. Enter valid first name  
3. Enter valid last name  
4. Enter invalid email  
5. Fill remaining required fields  
6. Click submit  

**Expected Result:**  
Validation message is displayed for invalid email and form submission is blocked  

**Actual Result:**  
Validation message is displayed for invalid email and form submission is blocked  

**Status:**  
Pass  

**Tested By:** Hamza Sattar  


## TC_REGISTRATION_003
**Title:** Verify validation when required fields are empty  

**Execution Date:** 24 March 2026  

**Preconditions:**  
User is on the registration form page  

**Test Data:**  
All fields empty  

**Steps:**  
1. Open registration page  
2. Leave required fields blank  
3. Click submit  

**Expected Result:**  
Validation messages are displayed for required fields and form submission is blocked  

**Actual Result:**  
Validation messages are displayed for required fields and form submission is blocked  

**Status:**  
Pass  

**Tested By:** Hamza Sattar  

## TC_REGISTRATION_004
**Title:** Verify validation for invalid phone number  

**Execution Date:** 24 March 2026  

**Preconditions:**  
User is on the registration form page  

**Test Data:**  
Mobile: 074859985  

**Steps:**  
1. Open registration page  
2. Enter valid first name  
3. Enter valid last name  
4. Enter valid email  
5. Enter invalid mobile number  
6. Fill remaining required fields  
7. Click submit  

**Expected Result:**  
Validation message is displayed for invalid mobile number and form submission is blocked  

**Actual Result:**  
Validation message is displayed for invalid mobile number and form submission is blocked  

**Status:**  
Pass  

**Tested By:** Hamza Sattar  
