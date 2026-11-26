# Manual Testing Project - Practice Software Testing (Toolshop)

Manual functional testing of an e-commerce demo website.

## Deliverables

| File | Contents |
|---|---|
| `Test-Cases.xlsx` | Test cases for all 7 modules (one sheet each) |
| `Bug-Reports.xlsx` | Bug report with all 15 bugs |
| `Test-Scenarios.xlsx` | Module-wise test scenarios with priority and test case count |


## Test Summary

| Module | Test Cases | Pass | Fail |
|---|---|---|---|
| Login | 10 | 10 | 0 |
| Registration | 11 | 6 | 5 |
| Product search | 10 | 8 | 2 |
| Shopping cart | 10 | 10 | 0 |
| Coupon application | 1 | 0 | 1 |
| Checkout | 10 | 6 | 4 |
| Payment | 10 | 7 | 3 |
| **Total** | **62** | **47** | **15** |

## Bugs Found: 15

| Severity | Count |
|---|---|
| Critical | 2 |
| High | 2 |
| Medium | 9 |
| Low | 2 |

Main issues:
- Registration gives no success or error message after valid details.
- Credit card payment shows "Unknown error".
- No coupon field available.
- Checkout page is blank when the cart is empty.
- Invalid postal code, phone number and name fields are accepted.

## Test Environment

- Browser: Google Chrome (latest)
- Test user: `customer@practicesoftwaretesting.com` / `welcome01`

## Status Values

Pass, Fail
