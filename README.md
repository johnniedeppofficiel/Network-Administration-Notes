# Network-Administration-Notes
My notes for network administration 2025 Semester 2 @ Swinburne. Copyright ME
---

# Notes for Week 7 tutorial to be emailed to laptop

#Tutorial #Lab

## Key Concepts(Tutorial notes)
### I
### Global groups
- Group identities (Students, Teachers, Staff)
### Domain local
- permissions
### Universal students 
-Used for bringing two types of ths same group?
### IGDLA/IGGDLA/IGUDLA
***I>G>DL<A***

## Naming Conventions recommended by NA Staff
- G_ for global group
- 

## Further Study
### Access Control & Permissions
### Active Directory Domain Services
I failed Questions 7 and 5 in the Week 7 Revision Quiz. These Questions had to do with the Distinction between Forests, Trees and Domains.

***My Plan to Revise***
- Revise the lecture content
- Read up on the related Microsoft 74x books in the library

### From Accounts to Access: Learning How Groups Secure Windows Resources
I failed Questions 6 and 8 in the Week 7 Revision Quiz. These Questions had to do with determining what objects can be a part of a global group, and what the function of Active Directory scopes are.

***My Plan to Revise***
- take notes on the lecture content

---
## Key Configs

### Run ADDS Users & Computers shorthand
- run the command 'dsa.msc'

### Config 1: Prepare a Domain Controller for ADDS 
- Set up DNS server first with default settings
- In post-deployment configuration window
- add it to a forest
- use the Windows Server 2016 defaults
- 
### Config 2: Connecting a machine to ADDS Domain
- verify DNS is working first (via ping or nslookup)
- System>Change Settings>Change...
- Member of: Domain:______
- Click "OK"
- enter allowed credentials ('Admin' in the lab)
-
### notes 
- when making a domain start with domain controller and then go down. might go without saying but it makes the difference
