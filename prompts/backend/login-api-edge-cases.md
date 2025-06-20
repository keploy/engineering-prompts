# 🧪 API Testing Prompt: Login Endpoint Edge Cases

**Instruction**:  
Generate test cases for a typical login endpoint (`POST /login`) that validate both functional correctness and security edge cases.

**Context**:  
This endpoint accepts a JSON body with `email` and `password`, and returns a session token if valid.

**Scenarios to cover**:
- ✅ Valid credentials
- ❌ Incorrect password
- 🕵️ Non-existent email
- 🧨 SQL injection attempt in email field
- 🚫 Empty payload
- 🧼 Leading/trailing whitespaces
- 🧪 Special characters in password
- 🔄 Rate-limiting scenario (multiple login attempts)

**Expected Output**:
- Keploy-generated `.yaml` or `.json` test cases simulating each of these edge scenarios
- Response validations (status code, message content, error type)

**Use case**:  
Can be used to test login robustness, session creation, and API security in production or staging.
