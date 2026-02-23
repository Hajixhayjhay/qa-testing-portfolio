# Test Summary Report — Login Feature Testing

## Project Details
- **Application:** Practice Test Automation
- **Feature Tested:** Login Functionality
- **Tester:** Hajarat Akande
- **Date:** 23/02/2026
- **Browser:** Chrome

## Test Execution Summary

| Total Test Cases | Passed | Failed | Blocked |
|-----------------|--------|--------|---------|
| 10 | 6 | 4 | 0 |

## Pass Rate: 60%

## Bugs Summary

| Bug ID | Title | Severity | Status |
|--------|-------|----------|--------|
| BUG-001 | Remember Me missing | Medium | Open |
| BUG-002 | Forgot Password missing | High | Open |
| BUG-003 | Case sensitive username | Low | Open |
| BUG-004 | Poor UI design | Low | Open |
| BUG-005 | Generic error messages | Low | Open |
| BUG-006 | Username clears after failed login | Medium | Open |

## Conclusion
Basic login functionality works correctly 
for standard scenarios. However several 
usability and security concerns were 
identified that should be addressed 
before production release.

## Recommendations
1. Add Forgot Password functionality — High priority
2. Fix username field retention after failed login
3. Improve error message specificity
4. Add Remember Me functionality
5. Redesign login page UI for better UX
6. Make username field case insensitive