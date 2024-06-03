Test 1: push direct to main with branch protection advisory. 
Expect: get a warning
Actual: no warning

Test 2: push direct to main with branch protection required.
Expect: fail
Actual: fail

````remote: Bypassed rule violations for refs/heads/main:
remote: 
remote: - Changes must be made through a pull request.```

