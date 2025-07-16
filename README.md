**hello@shenefelt.org**  
**Automated Active Directory Password Management**  

**Updated on: 07/15/2025**

---

### CASE STUDY REPORT

---

### The Problem

Every Wednesday, this client performs mass password resets for 226 Active Directory accounts. This was previously done manually by their helpdesk team, taking about 4 hours and introducing potential for errors such as:

- Typos when resetting the password  
- Missed accounts during the reset process  
- No audit trail  
- Delays in delivering new passwords to users  

---

### The Solution

To eliminate this bottleneck, I developed a small Java application that:

- Reads in all usernames from the OU containing the accounts  
- Resets each account's password and ensures it is unlocked  
- Assigns new passwords in a sequential, trackable format  
- Logs both successes and failures in a human-readable file  
- Maintains unique passwords by tracking usage across sessions  

---

### The Outcome

- Reduced a 4-hour weekly task to a 30-second automated process  
- Eliminated manual errors in password resets  
- Generated audit-friendly logs for internal compliance reporting  
