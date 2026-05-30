# Linux Autommation Labs: Shell Scripting

A collection of shell scripts for system administration and automation tasks. <br>
Assignment File: [PDF Link](https://drive.google.com/file/d/1ap2JMbnO2hp-IgQR5QM9P3j2S3Tv-t3K/view?usp=sharing)

---

## Overview

This project contains Bash scripts designed to automate common system administration workflows, including process monitoring, log management, user management, and scheduled maintenance tasks. Built as part of a shell scripting assignment, each script follows POSIX-compliant practices and is intended for use on Linux/Unix environments.

---

## Prerequisites

Before running any scripts, ensure the following are available on your system:

| Requirement | Version | Notes |
|-------------|---------|-------|
| Bash | 4.0+ | Check with `bash --version` |
| coreutils | any | `grep`, `awk`, `sed`, `cut` |
| sudo / root access | — | Required for system-level operations |
| cron | any | For scheduled automation tasks |

> **Tested on:** Ubuntu 22.04 LTS, Debian 11, CentOS 7

---

## Installation
 
Place all `.sh` script files into a directory of your choice, then follow the steps below.
 
**1. Navigate to the scripts directory**
 
```bash
cd path/to/scripts/
```
 
**2. Make all scripts executable**
 
```bash
chmod +x *.sh
```
 
To make a single script executable:
 
```bash
chmod +x q01_prime_range.sh
```
 
**3. Verify permissions**
 
```bash
ls -l *.sh
```
 
You should see `-rwxr-xr-x` before each script name.
 
---
 
## How to Run
 
Shell scripts do not need to be compiled. They are interpreted directly by Bash.
 
**General syntax:**
 
```bash
bash <script-name>.sh [ARGUMENTS]
```
 
Or using the direct path after making it executable:
 
```bash
./<script-name>.sh [ARGUMENTS]
```
 
---
 
## Usage Examples
 
Below are run examples for each category of scripts.
 
**Scripts that take a numeric range as argument**
 
```bash
bash q01_prime_range.sh 1 50          # Primes between 1 and 50
bash q10_fibonacci.sh 10              # Fibonacci up to range 10
```

## Scripts
 
This project includes **33 shell scripts** organized across the following categories. Run `ls scripts/` to view all files.
 
| Category | Count | Topics Covered |
|----------|-------|----------------|
| **Number & Math** | 10 | Prime numbers, Fibonacci, factorial, GCD, quadratic roots, palindrome check, second highest, prime factors, reverse string |
| **Sorting & Searching** | 5 | Bubble sort (ascending/descending), selection sort, binary search, sequential search |
| **String & File Processing** | 9 | Word frequency, duplicate line removal, vowel filter, case conversion, `wc` simulation, line range print, vowel exclusion copy |
| **Patterns** | 2 | Pascal's triangle, diamond/pyramid star pattern |
| **File & Directory Utilities** | 4 | File/directory checker with line count, empty subfolder finder, delete lines by keyword, word frequency in file |
| **Menu-Driven & Interactive** | 3 | Calculator, case converter, employee record system |
| **System / Login** | 1 | Login greeting based on time of day |
 
---

## Project Structure

```
Linus Automation Labs: Shell Scripting/
├── Algorithm/
│   ├── one.tex
│   ├── two.tex
│   ├── ...
├── Assets/
│   ├── one.png
│   ├── two.png
│   ├── ...
├── codes/    ## you can copy the code from here and put them into .sh file 
│   ├── one.tex          
│   ├── two.tex
│   ├── ...
├── Acknowledgement.tex
├── conclusion.tex
├── introduction.tex
├── main.tex
├── objective.tex
└── questions.tex
```

---

## Notes

- Always review a script before running it with elevated privileges.
- Scripts log output to the `logs/` directory by default.
- Modify configuration variables at the top of each script to suit your environment.

---

<table>
<tr>
<td>

## Author

**Arijit Chowdhury**  
Course: OS / Shell Scripting — 2025  
Institution: University of Calcutta

</td>
<td align="right">

<img src="https://drive.google.com/uc?export=view&id=1-7qUwyzp-jHOv7cHwXfg-b2a3KupdfZ_" width="500">

</td>
</tr>
</table>
