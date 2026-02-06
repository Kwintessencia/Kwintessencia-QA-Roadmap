# SauceDemo Login Test Cases

**Website:** https://www.saucedemo.com/
**Date Created:** February 6, 2026
**Total Test Cases:** 8

## Positive Tests

| ID | Title | Steps | Expected Result |
|----|-------|-------|-----------------|
| TC-LOGIN-001 | Valid credentials | 1. Enter "standard_user" 2. Enter "secret_sauce" 3. Click LOGIN | Redirected to inventory page |
| TC-LOGIN-008 | Capitalized username | 1. Enter "Standard_user" 2. Enter valid password 3. Click LOGIN | [To be determined] |

## Negative Tests

| ID | Title | Steps | Expected Result |
|----|-------|-------|-----------------|
| TC-LOGIN-002 | Invalid username | 1. Enter "invalid_user" 2. Enter valid password 3. Click LOGIN | Error message |
| TC-LOGIN-003 | Invalid password | 1. Enter valid username 2. Enter wrong password 3. Click LOGIN | Error message |
| TC-LOGIN-004 | Empty username | 1. Leave username empty 2. Enter password 3. Click LOGIN | Error message |
| TC-LOGIN-005 | Trailing space in username | 1. Enter "standard_user " 2. Enter valid password 3. Click LOGIN | Error message |
| TC-LOGIN-006 | ALL CAPS username | 1. Enter "STANDARD_USER" 2. Enter valid password 3. Click LOGIN | Error message |
| TC-LOGIN-007 | Special characters | 1. Enter "standard@user" 2. Enter valid password 3. Click LOGIN | Error message |

## Notes
- Edge cases reveal how robust the login system is
- Boundary testing includes: empty values, spaces, case sensitivity, special chars
