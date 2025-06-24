# Bug Report – Login Page (Mobile UI)

**ID**: BUG-LOGIN-001  
**Summary**: Error message is cut off on small screens  
**Environment**: iPhone SE, Safari browser  
**Steps to Reproduce**:
1. Open login page on iPhone SE
2. Enter invalid credentials
3. Tap "Login"

**Expected Result**: Full error message ("Invalid credentials") displays below input  
**Actual Result**: Message is partially cut off, text runs off screen  
**Severity**: Medium  
**Priority**: High  
**Suggested Fix**: Apply text-wrap or resize error box  
**Automation Note**: Add visual regression test for error messages on small breakpoints
