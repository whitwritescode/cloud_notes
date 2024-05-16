# AWS Identity and Access Management (IAM)

## Date: [05/15/2024]

---

### What is AWS IAM?

- A service that secures control to other AWS services by managing how reources are accessed and which actions can be performed.
- Consider *Who can access which AWS services?* and *What is the user or system allowed to do with the service?*.
- IAM reduces sharing passwords or access keys when granting access rights, also easily turning on and off a user's account.
- IAM is offered as a feature of an AWS account at no charge.
 

### Features of AWS IAM:

- Orgs can manage authentication and access to AWS services from one place.
- Create users, groups and role and attach policies to them to control their access to AWS services. 
- Users gain access through the CLI using access keys or GUI using ID, username and password (MFA for extra protection) in the Management console.  

### AWS IAM Best Practices:

- Avoid using the account root user credentials for daily administration. 
- Delegate administrative functions by following the principle of least privilege.
- Use IAM roles to provide cross-account access.
- MFA is a good practice to implement for security purposes. 

---

## Key Takeaways

- A **principal** is a person or application that can make a request for an action or operation on an AWS resource. 
- An IAM policy is a JSON document that defines permissions. These permissions are applied to users, groups, and roles.
- By using roles, users can temporarily assume certain permissions that are defined by the role.

---

## Questions

- Question 1
- Question 2

---

## Next Steps

- Next step 1
- Next step 2

---

## Action Items

- [ ] Task 1
- [ ] Task 2
- [ ] Task 3


