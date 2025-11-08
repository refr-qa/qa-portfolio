# 🧪 Test Cases: Login Functionality – Demoblaze

**Test Environment:**  
- Device: Windows 11  
- Browser: Firefox 144.0  
- Website: https://demoblaze.com/index.html  

---

### ✅ Test Case 1: Login without entering credentials

**Test Case ID:** TC001  
**Title:** Verify behavior when clicking Login with empty fields  

**Steps:**
1. Go to https://demoblaze.com/index.html  
2. Click on “Log in”  
3. Do not enter any data  
4. Click “Log in” button  

**Expected Result:**  
User should see an error message prompting to enter username and password.  

**Actual Result:**  
Alert message appears as expected.  

**Status:** ✅ Pass (error message appears later)

---

### ✅ Test Case 2: Login with username only  

**Test Case ID:** TC002  
**Title:** Verify login behavior when password field is empty  

**Steps:**
1. Click on “Log in”  
2. Enter username: `File01`  
3. Leave password empty  
4. Click “Log in”  

**Expected Result:**  
An alert should appear saying “Please fill out Username and Password.”  

**Actual Result:**  
Alert message appears as expected.  

**Status:** ✅ Pass  

---

### ✅ Test Case 3: Login with valid credentials  

**Test Case ID:** TC003  
**Title:** Verify successful login with correct username and password  

**Steps:**
1. Click on “Log in”  
2. Enter username: `File01`  
3. Enter password: `file01`  
4. Click “Log in”  

**Expected Result:**  
User is logged in and “Welcome File01” is displayed at the top right.  

**Actual Result:**  
Login successful, “Welcome File01” displayed.  

**Status:** ✅ Pass
