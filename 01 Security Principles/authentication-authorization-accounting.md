# Authentication, Authorization, and Accounting (AAA)

AAA is a set of security concepts used to control and track access to systems and information.

## Authentication

### What it means

Authentication is the process of **proving who you are**.

The system checks your identity before allowing you to continue.

### Examples

* Username and password
* Fingerprint
* Face recognition
* Security token
* Multi-factor authentication (MFA)

### Example

You enter your username and password to log into your school account.

The system checks your credentials to determine whether you really are the person associated with that account.

### Remember

**Authentication = Who are you?**

---

## Authorization

### What it means

Authorization determines **what an authenticated user is allowed to access or do**.

Authentication comes first. Authorization comes after.

### Example

You successfully log into a school's computer system.

You are authorized to:

* View your own grades
* Submit assignments

But you may not be authorized to:

* Change your grades
* View another student's private records
* Change school system settings

### Remember

**Authorization = What are you allowed to do?**

---

## Accounting

### What it means

Accounting keeps track of a user's activity and system usage.

It can help organizations determine:

* Who accessed something
* When they accessed it
* What they did
* Which resources they used

### Example

A company records that an employee:

> Logged into a server at 9:15 AM and accessed a particular file.

This record can help with auditing and investigating security incidents.

### Remember

**Accounting = What did you do?**

---

# Authentication vs. Authorization

These two are easy to mix up.

### Authentication

**Proves your identity.**

> "I am KB."

### Authorization

**Determines your permissions.**

> "KB is allowed to access this file."

### Easy memory trick

**AuthenTICATION = identity**

**AuthorIZATION = permissions**

---

# AAA Summary

| Concept        | Main Question    | Example          |
| -------------- | ---------------- | ---------------- |
| Authentication | Who are you?     | Password/MFA     |
| Authorization  | What can you do? | File permissions |
| Accounting     | What did you do? | Activity logs    |

---

# Real-World Example

Imagine logging into a company's file server.

### 1. Authentication

You enter your username and password.

The system verifies your identity.

### 2. Authorization

The system checks your permissions.

You can access the files assigned to your job, but not restricted HR files.

### 3. Accounting

The system records your activity.

It may record when you logged in and which files you accessed.

---

# CC Exam Tip

If a question asks about:

**Proving identity** → Authentication

**Determining permissions** → Authorization

**Tracking activity** → Accounting

---

# What I Learned

AAA can be remembered as three questions:

1. **Authentication:** Who are you?
2. **Authorization:** What are you allowed to do?
3. **Accounting:** What did you do?

Authentication establishes identity, authorization controls permissions, and accounting records activity.
