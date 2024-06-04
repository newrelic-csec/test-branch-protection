Test 1: push direct to main with branch protection advisory. 
Expect: get a warning
Actual: no warning

Test 2: push direct to main with branch protection required.
Expect: fail
Actual: fail

````remote: Bypassed rule violations for refs/heads/main:
remote: 
remote: - Changes must be made through a pull request.```

Test 3: an outside developer forks and submits a pull request. This is a precondition to other tests that rely on having an account that is not an owner or an admin.
