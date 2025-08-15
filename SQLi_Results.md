# SQL Injection Test Report
## Test 1: ' OR 1=1 --
- *Date*: 15/08/2025
- *Page*: /login
- *Result*: Success (Admin access)
- *Time Taken*: 5 minutes
- *Screenshot*: ![SQLi1](screenshots/screenshots/Capture d'écran 2025-08-15 115303.png)

## Test 2: ' OR 'a'='a' --
- *Date*: 15/08/2025
- *Page*: /login
- *Result*: Success (Same result)
- *Difference*: 
  - Both payloads worked identically
  - No noticeable speed difference
  - ' OR 1=1 -- is more commonly used in documentation
  - ' OR 'a'='a' -- might bypass some basic filters
