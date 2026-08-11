# PortSwigger Web Security Academy - Solved Labs

![Total Labs](https://img.shields.io/badge/Total%20Labs%20Solved-84-blue) ![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--08--11-yellow) ![Level](https://img.shields.io/badge/Level-NEWBIE-green) ![Vulnerability labs](https://img.shields.io/badge/Completed-30%25-purple)

This file tracks my progress through [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs. I focus on web app pentesting, documenting key labs as full writeups (linked below) and logging all solves here for reference. Full writeups are reserved for first-time techniques, complex exploits, or custom tools.

## Level progress
- **Apprentice**: 26 of 61
- **Practitioner**: 52 of 174
- **Expert**: 6 of 39

## Categories Covered

- **Authentication vulnerabilities**: 14/14 lab
- **SQL injection**: 18/18 lab
- **Access control**: 13/13 lab
- **Cross-site scripting**: 1/30 lab
- **Path traversal**: 6/6 lab
- **Command injection**: 5/5 lab
- **File upload vulnerabilities**: 7/7 lab
- **Race conditions**: 1/6 lab
- **Server-side request forgery (SSRF)**: 7/7 lab
- **Business logic vulnerabilities**: 3/11 lab 
- **API testing**: 5/5 lab
- **GraphQL API vulnerabilities**: 4/5 lab
 
## Notes
- **Full Writeups**: Only for significant labs (e.g., chained exploits or scripted solutions). See `platforms/portswigger/` for details.
- **Tools Used**: Burp Suite

## How to Read
- **Columns**: 
  - `No`: Sequential lab number.
  - `Date`: When I solved it (YYYY-MM-DD).
  - `Topic`: Vulnerability category (e.g., API Testing, XSS).
  - `Lab Title`: Exact name from PortSwigger.
  - `Difficulty`: Apprentice, Practitioner, or Expert.
  - `Writeup Link`: Links to full writeup (if exists) or "N/A" for quick solves.

---

## Solved Labs

| No | Date       | Topic          | Lab Title                                   | Difficulty  | Writeup Link |
|----|------------|----------------|---------------------------------------------|-------------|--------------|
| 1  | 2026-06-16 |  SQL injection  | SQL injection vulnerability in WHERE clause allowing retrieval of hidden data | APPRENTICE | N/A |
| 2  | 2026-06-16 |  SQL injection | SQL injection vulnerability allowing login bypass | APPRENTICE  | N/A |
| 3  | 2026-06-16 |  Cross-site scripting  | Reflected XSS into HTML context with nothing encoded | APPRENTICE  | N/A |
| 4  | 2026-06-16 |  Access control vulnerabilities   | Insecure direct object references | APPRENTICE  | N/A |
| 5  | 2026-06-21 |  SQL injection   | SQL injection with filter bypass via XML encoding | PRACTITIONER | N/A |
| 6  | 2026-06-21 |  SQL injection   | SQL injection UNION attack, determining the number of columns returned by the query | PRACTITIONER | N/A |
| 7  | 2026-06-21 |  SQL injection   | SQL injection UNION attack, finding a column containing text | PRACTITIONER | N/A |
| 8  | 2026-06-21 |  SQL injection   | SQL injection UNION attack, retrieving data from other tables | PRACTITIONER | N/A |
| 9  | 2026-06-21 |  SQL injection   | SQL injection attack, querying the database type and version on Oracle | PRACTITIONER | N/A |
| 10  | 2026-06-21 |  SQL injection    | SQL injection attack, querying the database type and version on MySQL and Microsoft | PRACTITIONER | N/A |
| 11  | 2026-06-24 |  Authentication vulnerabilities   | Username enumeration via different responses | APPRENTICE | N/A |
| 12  | 2026-06-27 |  Authentication vulnerabilities   | Username enumeration via subtly different responses | PRACTITIONER | N/A |
| 13  | 2026-06-27 |  Authentication vulnerabilities   | Username enumeration via response timing | PRACTITIONER | N/A |
| 14  | 2026-06-27 |  Authentication vulnerabilities   | Broken brute-force protection, IP block | PRACTITIONER | N/A |
| 15  | 2026-06-27 |  Authentication vulnerabilities   | Username enumeration via account lock | PRACTITIONER | N/A |
| 16  | 2026-06-27 |  Authentication vulnerabilities   | 2FA simple bypass | APPRENTICE | N/A |
| 17  | 2026-06-27 |  Authentication vulnerabilities   | 2FA broken logic | PRACTITIONER | N/A |
| 18  | 2026-07-01 |  SQL injection   | SQL injection attack, listing the database contents on non-Oracle databases | PRACTITIONER | N/A |
| 19  | 2026-07-01 |  SQL injection   | SQL injection attack, listing the database contents on Oracle | PRACTITIONER | N/A |
| 20  | 2026-07-05 |  Path traversal   | File path traversal, simple case | APPRENTICE | N/A |
| 21  | 2026-07-05 |  Path traversal   | File path traversal, traversal sequences blocked with absolute path bypass | PRACTITIONER | N/A |
| 22  | 2026-07-05 |  Path traversal   | File path traversal, traversal sequences stripped non-recursively | PRACTITIONER | N/A |
| 23  | 2026-07-05 |  Path traversal   | File path traversal, traversal sequences stripped with superfluous URL-decode | PRACTITIONER  | N/A |
| 24  | 2026-07-05 |  Path traversal   | File path traversal, validation of file extension with null byte bypass | PRACTITIONER  | N/A |
| 25  | 2026-07-05 |  Path traversal   | File path traversal, validation of start of path | PRACTITIONER  | N/A |
| 26  | 2026-07-05 |  Command injection   | OS command injection, simple case   |  APPRENTICE  | N/A |
| 27  | 2026-07-05 |  Command injection   | Blind OS command injection with time delays |  PRACTITIONER  | N/A |
| 28  | 2026-07-05 |  Command injection   | Blind OS command injection with output redirection    |  PRACTITIONER  | N/A |
| 29  | 2026-07-05 |  Command injection   | Blind OS command injection with out-of-band interaction    |  PRACTITIONER  | N/A |
| 30  | 2026-07-12 |  Access control   |  Unprotected admin functionality  |  APPRENTICE   | N/A |
| 31  | 2026-07-12 |  Access control   |  Unprotected admin functionality with unpredictable URL   |  APPRENTICE   | N/A |
| 32  | 2026-07-12 |  Access control   |  User role controlled by request parameter   |  APPRENTICE   | N/A |
| 33  | 2026-07-12 |  Access control   |  User role can be modified in user profile   |  APPRENTICE   | N/A |
| 34  | 2026-07-12 |  Access control   |  URL-based access control can be circumvented   |  PRACTITIONER   | N/A |
| 35  | 2026-07-18 |  File upload vulnerabilities   |  Remote code execution via web shell upload   |  APPRENTICE   | N/A |
| 36  | 2026-07-18 |  File upload vulnerabilities   |  Web shell upload via Content-Type restriction bypass   |  APPRENTICE   | N/A |
| 37  | 2026-07-18 |  File upload vulnerabilities   |  Web shell upload via path traversal   |  PRACTITIONER   | N/A |
| 38  | 2026-07-18 |  File upload vulnerabilities   |  Web shell upload via extension blacklist bypass   |  PRACTITIONER   | N/A |######
| 39  | 2026-07-26 |  Race conditions   |  Limit overrun race conditions   |  APPRENTICE   | N/A |
| 40  | 2026-07-28 |  SQL injection   |  SQL injection UNION attack, retrieving multiple values in a single column   |  PRACTITIONER   | N/A |
| 41  | 2026-07-29 |  SQL injection   |  Blind SQL injection with conditional responses   |  PRACTITIONER   | [Medium Writeup](https://medium.com/@yabsr23/portswigger-lab-blind-sql-injection-with-conditional-responses-5d37b5f042f9) |
| 42  | 2026-07-30 |  SQL injection   |  Blind SQL injection with conditional errors   |  PRACTITIONER   | N/A |
| 43  | 2026-07-30 |  SQL injection   |  Visible error-based SQL injection   |  PRACTITIONER   | N/A |
| 44  | 2026-07-30 |  SQL injection   |  Blind SQL injection with time delays   |  PRACTITIONER   | N/A |
| 45  | 2026-07-30 |  SQL injection   |  Blind SQL injection with time delays and information retrieval   |  PRACTITIONER   | N/A |
| 46  | 2026-07-31 |  SQL injection   |  Blind SQL injection with out-of-band interaction   |  PRACTITIONER   | N/A |
| 47  | 2026-07-31 |  SQL injection   |  Blind SQL injection with out-of-band data exfiltration   |  PRACTITIONER   | N/A |
| 48  | 2026-07-31 |  Authentication vulnerabilities   |  Broken brute-force protection, multiple credentials per request   |  EXPERT   | N/A |
| 49  | 2026-08-01 |  Server-side request forgery (SSRF)   |  Basic SSRF against the local server   |  APPRENTICE   | N/A |S
| 50  | 2026-08-01 |  Server-side request forgery (SSRF)   |  Basic SSRF against another back-end system   |  APPRENTICE   | N/A |
| 51  | 2026-08-01 |  Server-side request forgery (SSRF)   |  SSRF with blacklist-based input filter   |  PRACTITIONER     | N/A |
| 52  | 2026-08-01 |  Server-side request forgery (SSRF)   |  SSRF with whitelist-based input filter   |  EXPERT   | N/A |
| 53  | 2026-08-02 |  Server-side request forgery (SSRF)   |  SSRF with filter bypass via open redirection vulnerability   |  PRACTITIONER   | N/A |
| 54  | 2026-08-02 |  Server-side request forgery (SSRF)   |  Blind SSRF with out-of-band detection   |  PRACTITIONER   | N/A |
| 55  | 2026-08-02 |  Server-side request forgery (SSRF)   |  Blind SSRF with Shellshock exploitation   |  EXPERT   | N/A |
| 56  | 2026-08-02 |  Access control   |  Method-based access control can be circumvented   |  PRACTITIONER   | N/A |
| 57  | 2026-08-02 |  Access control   |  User ID controlled by request parameter   |  APPRENTICE   | N/A |
| 58  | 2026-08-02 |  Access control   |  User ID controlled by request parameter, with unpredictable user IDs    |  APPRENTICE   | N/A |
| 59  | 2026-08-02 |  Access control   |  User ID controlled by request parameter with data leakage in redirect   |  APPRENTICE   | N/A |
| 60  | 2026-08-02 |  Access control   |  User ID controlled by request parameter with password disclosure   |  APPRENTICE   | N/A |
| 61  | 2026-08-03 |  Access control   |  Multi-step process with no access control on one step   |  PRACTITIONER   | N/A |
| 62  | 2026-08-03 |  Access control   |  Referer-based access control    |  PRACTITIONER   | N/A |
| 63  | 2026-08-03 |  Authentication vulnerabilities   |  2FA bypass using a brute-force attack   |  EXPERT   | N/A |
| 64  | 2026-08-04 |  Authentication vulnerabilities   |  Brute-forcing a stay-logged-in cookie   |  PRACTITIONER   | N/A |
| 65  | 2026-08-04 |  Authentication vulnerabilities   |  Offline password cracking   |  PRACTITIONER   | N/A |
| 66  | 2026-08-04 |  Authentication vulnerabilities   |  Password reset broken logic   |  APPRENTICE   | N/A |
| 67  | 2026-08-04 |  Authentication vulnerabilities   |  Password reset poisoning via middleware   |  PRACTITIONER   | N/A |
| 68  | 2026-08-05 |  Authentication vulnerabilities   |  Password brute-force via password change   |  PRACTITIONER   | N/A |
| 69  | 2026-08-05 |  Command injection   |  Blind OS command injection with out-of-band data exfiltration   |  PRACTITIONER   | N/A |
| 70  | 2026-08-06 |  Business logic vulnerabilities   |  Excessive trust in client-side controls   |  APPRENTICE   | N/A |
| 71  | 2026-08-06 |  Business logic vulnerabilities   |  High-level logic vulnerability   |  APPRENTICE   | N/A |
| 72  | 2026-08-06 |  Business logic vulnerabilities   |  Low-level logic flaw   |  PRACTITIONER   | N/A |
| 73  | 2026-08-07 |  API testing   |  Exploiting an API endpoint using documentation   |  APPRENTICE   | N/A |
| 74  | 2026-08-07 |  API testing   |  Finding and exploiting an unused API endpoint   |  PRACTITIONER   | N/A |
| 75  | 2026-08-07 |  API testing   |  Exploiting a mass assignment vulnerability   |  PRACTITIONER   | N/A |
| 76  | 2026-08-07 |  API testing   |  Exploiting server-side parameter pollution in a query string   |  PRACTITIONER   | N/A |
| 77  | 2026-08-07 |  API testing   |  Exploiting server-side parameter pollution in a REST URL   |  EXPERT   | N/A |
| 78  | 2026-08-08 |  GraphQL API vulnerabilities   |  Accessing private GraphQL posts   |  APPRENTICE   | N/A |
| 79  | 2026-08-08 |  GraphQL API vulnerabilities   |  Accidental exposure of private GraphQL fields   |  PRACTITIONER   | N/A |
| 80  | 2026-08-08 |  GraphQL API vulnerabilities   |  Finding a hidden GraphQL endpoint   |  PRACTITIONER   | N/A |
| 81  | 2026-08-08 |  GraphQL API vulnerabilities   |  Bypassing GraphQL brute force protections   |  PRACTITIONER   | N/A |
| 82  | 2026-08-10 |  File upload vulnerabilities   |  Web shell upload via obfuscated file extension   |  PRACTITIONER   | N/A |
| 83  | 2026-08-11 |  File upload vulnerabilities   |  Remote code execution via polyglot web shell upload   |  PRACTITIONER   | N/A |
| 84  | 2026-08-11 |  File upload vulnerabilities   |  Web shell upload via race condition   |  EXPERT   | N/A |
| 00  | 0000-00-00 |     |     |     | N/A |





