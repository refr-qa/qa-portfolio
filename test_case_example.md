# ✅ Test Case Example

**Title:** Verify successful login with valid credentials  
**Test ID:** TC_001  
**Module:** Login Page  
**Priority:** High  
**Type:** Functional Test  

---

### 🧭 Preconditions
- User has a valid registered account  
- Application is accessible via web browser  

---

### 🧪 Test Steps
| Step No. | Action | Expected Result |
|-----------|---------|----------------|
| 1 | Navigate to `https://example.com/login` | Login page is displayed |
| 2 | Enter valid username and password | Input fields accept data |
| 3 | Click **Login** button | User is redirected to dashboard page |
| 4 | Check user name on dashboard | Correct user name is displayed |

---

### ✅ Expected Result
User successfully logs into the application and sees the dashboard page.

---

### ❌ Postconditions (if failed)
If login fails, an error message should appear with reason ("Invalid credentials" or "Server error").

---

### 📎 Notes
Can be combined with negative test cases (e.g., wrong password, empty fields).
