# Domain 3 Review — Identity and Access Management

## Identity Lifecycle

Remember:

**Define → Provision → Review → Deprovision**

---

## Authentication

**Who are you?**

Authentication verifies identity.

---

## Authorization

**What can you do?**

Authorization determines permissions.

---

## Provisioning

**Give access.**

Create an identity and provide appropriate permissions.

---

## Deprovisioning

**Remove access.**

Remove permissions when access is no longer needed.

---

## Least Privilege

**Only necessary permissions.**

Give users, systems, and processes only the access they require.

---

## Separation of Duties

**Split responsibilities.**

Do not give one person complete control over a sensitive process.

---

# Access Control Models

| Model | Remember |
|---|---|
| DAC | Owner decides |
| MAC | Mandatory security rules decide |
| RBAC | Role decides |

---

# MFA Factors

| Factor | Example |
|---|---|
| Something you know | Password/PIN |
| Something you have | Token/device |
| Something you are | Fingerprint |

### Remember

**Know + Have + Are**

Two passwords are generally still the same factor category.

---

# Important IAM Problems

## Privilege Creep

Permissions accumulate over time because old access is not removed.

**Memory trick: Old access piles up.**

## Orphaned Account

An account remains active even though its authorized owner is no longer supposed to use it.

## Excessive Privileges

A user has more access than their job requires.

## Poor Deprovisioning

Access is not removed when authorization ends.

---

# Key Comparisons

## Authentication vs. Authorization

Authentication → **Who?**

Authorization → **What?**

---

## Provisioning vs. Deprovisioning

Provisioning → **Give access**

Deprovisioning → **Remove access**

---

## Least Privilege vs. Separation of Duties

Least Privilege → **Limit permissions**

Separation of Duties → **Split responsibilities**

---

## DAC vs. MAC vs. RBAC

DAC → **Owner**

MAC → **Mandatory rules**

RBAC → **Role**

---

## Logical vs. Physical

Logical → **Digital access**

Physical → **Physical access**

---

# Practice Questions

## 1. What does authentication verify?

A. What a user can access  
B. A user's identity  
C. A user's job role  
D. A user's physical location  

**Answer: B**

---

## 2. What does authorization determine?

A. Who the user is  
B. Whether a password is strong  
C. What the user is allowed to access  
D. Whether a building has cameras  

**Answer: C**

---

## 3. Which principle gives users only the permissions they need?

A. Separation of duties  
B. Least privilege  
C. Non-repudiation  
D. Availability  

**Answer: B**

---

## 4. An employee changes departments but keeps permissions from their old department. What is this?

A. Privilege creep  
B. Authentication  
C. MFA  
D. Deprovisioning  

**Answer: A**

---

## 5. Which access control model is based on job roles?

A. DAC  
B. MAC  
C. RBAC  
D. MFA  

**Answer: C**

---

## 6. Which model gives the resource owner discretion over access?

A. DAC  
B. MAC  
C. RBAC  
D. MFA  

**Answer: A**

---

## 7. Which model relies on centrally enforced security rules?

A. DAC  
B. MAC  
C. RBAC  
D. SoD  

**Answer: B**

---

## 8. Which is an example of "something you have"?

A. Password  
B. Fingerprint  
C. Security token  
D. PIN  

**Answer: C**

---

## 9. What should happen when an employee leaves an organization?

A. Their permissions should increase  
B. Their account should remain active indefinitely  
C. Their access should be removed through deprovisioning  
D. Their account should become an administrator account  

**Answer: C**

---

## 10. Why are access reviews important?

A. They increase everyone's permissions  
B. They verify that access is still appropriate  
C. They eliminate the need for authentication  
D. They replace MFA  

**Answer: B**

---

# Domain 3 Exam Memory Sheet

**IAM**
→ Manage identities and access.

**Authentication**
→ Who are you?

**Authorization**
→ What can you do?

**Provisioning**
→ Give access.

**Deprovisioning**
→ Remove access.

**Least Privilege**
→ Only necessary permissions.

**Separation of Duties**
→ Split sensitive responsibilities.

**DAC**
→ Owner decides.

**MAC**
→ Mandatory rules decide.

**RBAC**
→ Role decides.

**MFA**
→ Multiple authentication factor categories.

**Privilege Creep**
→ Unnecessary permissions accumulate.

**Orphaned Account**
→ Active account with no authorized current owner.