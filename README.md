# PortSwigger Web Security Academy - Solved Labs

![Total Labs](https://img.shields.io/badge/Total%20Labs%20Solved-33-blue) ![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--07--12-yellow) ![Level](https://img.shields.io/badge/Level-NEWBIE-green) ![Vulnerability labs](https://img.shields.io/badge/Completed-11%25-purple)

This file tracks my progress through [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs. I focus on web app pentesting, documenting key labs as full writeups (linked below) and logging all solves here for reference. Full writeups are reserved for first-time techniques, complex exploits, or custom tools.

## Level progress
- **Apprentice**: 12 of 61
- **Practitioner**: 20 of 174
- **Expert**: 0 of 39

## Categories Covered

- **Authentication vulnerabilities**: 7/14 lab
- **SQL injection**: 10/18 lab
- **Access control**: 5/13 lab
- **Cross-site scripting**: 1/30 lab
- **Path traversal**: 6/6 lab
- **Command injection**: 4/5 lab
 
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
| 34  | 2026-07-05 |  Access control   |     |     | N/A |
| 35  | 2026-07-05 |  Access control   |     |     | N/A |
| 36  | 2026-07-05 |  Access control   |     |     | N/A |
| 37  | 2026-07-05 |     |     |     | N/A |

