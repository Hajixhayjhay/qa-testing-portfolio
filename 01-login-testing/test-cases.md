# Test Cases — Login Feature

| TC ID | Title | Precondition | Steps | Expected Result | Actual Result | Status |
|-------|-------|--------------|-------|-----------------|---------------|--------|
| TC001 | Valid login | None | 1. Go to login page 2. Enter student 3. Enter Password123 4. Click Login | User logged in successfully | User logged in and redirected to success page | ✅ Pass |
| TC002 | Invalid username | None | 1. Go to login page 2. Enter wrong username 3. Enter any password 4. Click Login | Error message displayed | Invalid username shown | ✅ Pass |
| TC003 | Invalid password | None | 1. Go to login page 2. Enter student 3. Enter wrong password 4. Click Login | Error message displayed | Invalid password shown | ✅ Pass |
| TC004 | Empty username | None | 1. Go to login page 2. Leave username empty 3. Enter any password 4. Click Login | Validation error shown | Invalid username shown | ✅ Pass |
| TC005 | Empty password | None | 1. Go to login page 2. Enter student 3. Leave password empty 4. Click Login | Validation error shown | Invalid password shown | ✅ Pass |
| TC006 | Remember Me | None | 1. Go to login page 2. Look for Remember Me checkbox | Remember Me checkbox visible | Checkbox missing on page | ❌ Fail |
| TC007 | Forgot Password | None | 1. Go to login page 2. Look for Forgot Password link | Forgot Password link visible | Link missing on page | ❌ Fail |
| TC008 | SQL Injection | None | 1. Enter ' OR '1'='1 in username 2. Enter any password 3. Click Login | Login rejected | Invalid username shown - injection blocked | ✅ Pass |
| TC009 | Case sensitivity | None | 1. Enter STUDENT in capitals 2. Enter Password123 3. Click Login | Login successful | Invalid username - case sensitive | ❌ Fail |
| TC010 | UI Check | None | 1. Open login page 2. Review all elements | All elements visible and aligned | Multiple UI issues found | ❌ Fail |