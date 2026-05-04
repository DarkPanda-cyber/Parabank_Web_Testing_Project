## 📊 Sample Test Cases (Parabank QA Project)

| TC ID | Feature | Description | Steps | Expected Result | Actual Result | Status |
|------|--------|------------|------|----------------|--------------|--------|
| TC-REG-01 | Registration | Register with valid data | 1. Go to registration <br> 2. Enter valid details <br> 3. Submit | Account created and redirected | Account created and redirected | ✅ Pass |
| TC-REG-02 | Registration | Register with empty fields | Leave all fields empty → Submit | Validation messages should be shown | Validation messages shown | ✅ Pass |
| TC-REG-03 | Registration | Password mismatch validation | Enter mismatched passwords → Submit | Error message should be shown | Error message shown | ✅ Pass |
| TC-LGN-01 | Login | Login with valid credentials | Enter valid username & password → Login | User logged in successfully | User logged in | ✅ Pass |
| TC-LGN-02 | Login | Login with invalid credentials | Enter invalid credentials → Login | Error message should be shown | User logged in without error | ❌ Fail |
| TC-NEW-01 | New Account | Open new checking account | Select checking → Submit | New account created | Account created successfully | ✅ Pass |
| TC-TRF-01 | Transfer Funds | Verify fund transfers between account | 1. Go to transfer funds <br> 2. Enter amount <br> 3. Select from and to account | Successful funds transfer | Transfer successful | ✅ Pass |
| TC-BILL-02 | Bill Pay | Bill payment with invalid amount | Enter 0 or negative → Submit | Should show validation error | Payment processed successfully | ❌ Fail |
| TC-TRN-01 | Transactions | Search transaction by ID | Enter valid ID → Search | Transaction details displayed | Details displayed | ✅ Pass |
| TC-LON-04 | Loan Request | Loan with invalid down payment | Enter negative down payment → Submit | Should reject request | Loan approved incorrectly | ❌ Fail |
| TC-LON-01 | Loan Request | Loan with valid data | Enter valid amount & down payment → Submit | Loan approved | Loan approved | ✅ Pass |
| TC-CUST-02 | Customer Care | Invalid email validation | Enter invalid email → Submit | Error message should be shown | Form submitted successfully | ❌ Fail |
