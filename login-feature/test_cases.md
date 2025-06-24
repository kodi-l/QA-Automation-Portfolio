# Login Feature – Automation Ready Test Cases

| ID    | Title                       | Preconditions         | Steps                                                                 | Expected Result                        | Notes for Automation |
|-------|-----------------------------|------------------------|------------------------------------------------------------------------|----------------------------------------|----------------------|
| TC001 | Valid Login                 | Valid user credentials | 1. Navigate to login page<br>2. Enter valid email/password<br>3. Click Login | User is redirected to dashboard         | Core smoke test       |
| TC002 | Invalid Password            | Registered email       | 1. Enter valid email<br>2. Enter wrong password<br>3. Click Login       | Error message: "Invalid credentials"    | Negative test case    |
| TC003 | Empty Fields                | None                   | 1. Leave all fields blank<br>2. Click Login                            | Error message prompts for input         | Validation test       |
| TC004 | SQL Injection Attempt       | None                   | 1. Enter `' OR 1=1 --` as email<br>2. Enter random password<br>3. Click Login | Generic error message, no DB access     | Security placeholder  |
| TC005 | Case Sensitivity Check      | Valid credentials      | 1. Enter correct email/password in all caps<br>2. Click Login          | Login fails (if case-sensitive) or passes if not | Edge case            |
