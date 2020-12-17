# 01. Comparing Common Vulnerabilities

## Software Bugs & Buffer Overflow

An attacker can write over data and can also obtain unauthorised data.

### Software Bug

Flaw in computer program that causes the program to behave in a way that was not intended.

### Buffer Overflow

A Buffer is a reservation of memory for a specific size.
An Overflow is when the size of data is greater than the reservation.

## Weak Passwords & Hard Coded Passwords

### Strong Passwords

* Complex and long
* 12 to 16 character minimum
* A-Z, a-z, 0-9, !@#$%

Also:

* No dictionary words
* Replacing letters with special characters or numbers doesn't provide much security
* Change passwords

### Hard Coded Passwords

Passwords embedded in software code. Once attacker knows the password, they can compromise any system that uses the program.

**Mitigations:**
* Store passwords outside of application in encrypted file
* Could prompt for initial password
* Match against hashes, not the actual password

**Inbound HCP:** Credentials used for access to program

**Outbound HCP:** Application uses password to access other application

## Missing Encryption

### Encryption

* Provides confidentiality and integrity
* VPNs are used for data in transit
* Makes it difficult
  * to gain access
  * to manipulate data

If data is missing encryption, it leaves the data exposed

## Path Traversal

Allows attacker to navigate outside of original directory (www.test.com/../../etc/password.file). Attacker can use error messages to figure out the structure.

**Mitigations:**
* Work without user input if possible
* Blacklist special characters
* Mask the structure by using indexes
  * Enter ID 10
  * Back end will navigate to Nebraska directory

## SQL Injection

* Use a tool to inject malicious code into legitimate code.
* Easy to discover - Internet search can provide a lot of info
* Prevalence is common
* Easy to exploit
* Impacts can be severe

**Impact:**
* Successful attack can reveal usernames and passwords, PII, and sensitive corporate info.
* Can modify data
  * Create additional accounts
  * Create fake, damaging information
* Can bring down the system
  * Attacker can remove necessary files

## Cross Site Scripting & Cross Site Forgery Request
