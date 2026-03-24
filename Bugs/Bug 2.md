# Bug Report

## BUG_002
**Title:** Name field accepts invalid characters and allows form submission  

**Module:** Registration Form  

**Environment:**  
- Browser: Chrome  
- OS: Windows 11  

**Preconditions:**  
User is on registration form page  

**Steps to Reproduce:**  
1. Enter a name with numbers and special characters (e.g. "testname123@")  
2. Fill in all other required fields with valid data  
3. Click submit  

**Expected Result:**  
System should validate the name field and reject invalid characters  

**Actual Result:**  
Form accepts invalid name input and submits successfully  

**Severity:** Medium  
**Priority:** Medium  
**Status:** New  
