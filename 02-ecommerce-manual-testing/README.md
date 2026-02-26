# 🛒 Level 2 - E-Commerce Manual Testing

## Project Overview
Manual functional testing of the **Automation Exercise** e-commerce website covering seven key functional areas including user registration, login, product browsing, cart management and contact form validation.

**Website:** https://automationexercise.com  
**Test Type:** Manual Functional Testing  
**Tester:** Hajarat Busola Akande  
**Date:** 26 February 2026  
**Browser:** Google Chrome  
**OS:** Windows  

---

## 📊 Test Results Summary

| Feature | Total | Pass | Fail |
|---------|-------|------|------|
| User Registration | 6 | 3 | 3 |
| User Login | 5 | 5 | 0 |
| User Logout | 3 | 3 | 0 |
| Product Search | 2 | 2 | 0 |
| Product Browsing | 3 | 2 | 1 |
| Add to Cart | 7 | 4 | 3 |
| Contact Us | 10 | 7 | 3 |
| **TOTAL** | **36** | **26** | **10** |

**Pass Rate: 72% ✅**

---

## 🐛 Bug Summary

| Severity | Count |
|----------|-------|
| High | 8 |
| Medium | 7 |
| Low | 4 |
| **Total** | **19** |

### Key Bugs Found
- 🔴 Cart missing reduce quantity button
- 🔴 Cart missing remove button
- 🔴 Cart final total not displayed
- 🔴 Contact form accepts invalid email
- 🟡 Orange overlay covers product images on hover
- 🟡 Invalid email accepted on signup
- 🟡 No back button on any page
- 🟡 Search bar only on Products page

---

## 📁 Project Structure


02-ecommerce-manual-testing/
├── README.md
├── Level2_Manual_Test_Plan.docx
├── Level2_Test_Cases_Results.docx
├── Level2_Bug_Report.docx
├── Level2_Test_Summary.docx
└── screenshots/

---

## 📄 Documents

| Document | Description |
|----------|-------------|
| Test Plan | Scope, objectives, approach and test strategy |
| Test Cases | 36 test cases with Pass/Fail results |
| Bug Report | 19 bugs with steps to reproduce and severity |
| Test Summary | Overall results, findings and recommendations |

---

## 🔍 Testing Approach
- Functional Testing
- Negative Testing
- UI/UX Testing
- Security Testing — SQL injection
- Exploratory Testing

---

## ✅ Positive Findings
- Login and logout working correctly and securely
- SQL injection attempt correctly rejected
- Product browsing and category filtering working
- Duplicate email registration correctly blocked

---

## 🛠️ Tools Used
- Google Chrome
- Chrome DevTools
- Windows Snipping Tool
- GitHub

---

## 🔗 Related Projects
- [Level 1 - Login Page Testing](../01-login-page-testing)