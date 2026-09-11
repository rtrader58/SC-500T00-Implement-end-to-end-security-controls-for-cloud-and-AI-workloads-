# SC-500 Implement end‑to‑end security controls for cloud and AI workloads - All Learning Paths Errata

# Day 1 Errata

# Module 1 Lab: Identity Governance​ and Access Control

## Lab 01 – Configure Privileged Identity Management (45 Minutes)

## Note - Exercise 2: Configure activation settings must be accomplished before Exercise 1: Assign a PIM-eligible role

### Exercise 1 – Assign a PIM-eligible role

Skip to Exercise 2: Configure activation settings - once exercise 2 is completed return to step 2 <br>

### Exercise 2 - Configure activation settings

Do step 1 of Exercise 1 before doing step 1 - Step 1: Requires MFA with use of an Authenticaton App on phone<br><br>

### Exercise 3 - Request role activation

Step 2 Requires MFA with use of an Authenticaton App on phone<br>
Step 7: Paste the Justification in the Reaso box <br>

### Exercise 4 - Approve the activation request

Step 8: Paste into the Enter the reson box <br>

### Exercise 5 - Test the activation in Conditional Access

No Errate

### Exercise 6 - Deactivate the role

Step 3: A minimum of 5 minutes must pass before you can deactivate - you may have to wait <br>

### Clean up

No Errata

# Module 2 Lab: Securing Azure Key Vault​

## Lab 02 - Deploy and secure Azure Key Vault (60 Minutes)

### Lab Setup
 
Step 1: Credentials are at the top of the screen <br>
Step 2: Choose your subscription <br>
Step 4: Do not type registered, it will be in the output - az frouRegistered

### Exercise 1 - Deploy and Secure Azure Key Vault

Step 4: Paste the Key vault name as is - you do not have to add your initials <br>

### Exercise 2 - Configure access using Azure RBAC

Step 5: Paste from the resources tab your user1 in the search pane <br>
Step 10: Paste from the resources tab your user1 in the search pane <br>
Step 21: Paste from the resources tab your user2 in the search pane <br>

### Exercise 3 - Store secrets and keys

No Errata <br>

### Exercise 4 - Verify access control enforcement

Step 2: User2 credentials are under the Resources tab <br>

### exercise 5 - Retrieve a secret using the managed identity

Step 4: The status should return True <br>
Step 6: Paste into notepad first, replace key valut name then paste <br>

### Exercise 6 - Restrict network access

No Errata <br>

### Exercise 7 - Enable Defender for Key Vault

No Errata <br>

# Module 3 Lab: Security Governance and Role Management​

## Lab 03 - Configure Azure Policy and Role-Based Access Control (~ 60 Minutes)

### Lab Setup
 
Step 1: Credentials are at the top of the screen <br>
Step 2: Choose your subscription, click Apply <br>
Step 3: Paste into notepad first, replace key valut name then paste <br>
Step 5: Do not paste Register <br>
Step 9: The object ID is the value you saved in Step 3 <br>

### Exercise 1 - Assign a built-in compliance policy

No Errata <br>

### Exercise 2 - Deploy a custom policy using Infrastructure as Code

If still running, wait for the previous task to finish <br>

### Exercise 3 - Create a custom security reviewer role

Step 6: The permissions will be populated with a JSON in step 10 <br>

### Exercise 4: Evaluate and remediate overprivileged access

Step 8: There is currently no Access Review, you will create one in the next exercise <br>

### Exercise 5 - Create and complete the access review

Step 2: You may not be able to change the Duration <br>
Step 7: Search for user2 that is located in the resources tab <br>
Step 14: Select Azure resources to see the Access review <br>

### Skip Exercise 6 - Fallback: remove the assignment directly

### Exercise 7 - Verify the remediation

No Errata <br>

### Exercise 8 - Apply a resource lock

No Errata <br>

# Day 2 Errata

# Module 4 Lab: Security for Azure Storage Accounts​

## Lab 4 - Secure Azure Storage ~60 Minutes

### Lab Setup

No Errata <br>

### Exercise 1 - Create a stored access policy and generate a SAS token

Step 12: Set the Start time to the current date and time  <br>
Step 18: Open Notepad and store the SAS token <br>

### Exercise 2 - Verify access before applying network restrictions

Step 1: Select your subscription and Apply <br>
Step 2: Paste into Notepad - replace the token <br>

### Exercise 3 - Restrict network access to the authorized virtual network

No errata <br>

### Exercise 4 - Confirm the firewall blocks unauthorized access

No errata <br>

### Exercise 5 - Enable Defender for Storage

No errata <br>

### Exercise 6 - Confirm diagnostic logging

# Module 5 Lab: Security for Azure Databases​

## Lab 5 - Secure Azure SQL Database ~60 Minutes

### Lab Setup

Step 1: Credentials are at the top of the screen <br>
Step 2: Choose your subscription, click Apply <br>
Step 9: Ensure you set both region and location to westus3 and the the lab instance from the note <br>

### Exercise 2 - Configure Entra ID authentication

Step 6: Search User2 that is located in the resources tab <br>

### Exercise 3 - Restrict network access and configure a Private Endpoint

No errata <br>

### Exercise 4 - Enable SQL auditing and generate an auditable event

No errata <br>

### Exercise 5 - Verify audit logs in Log Analytics

Step 7: If you get a syntax error enrure there is not an etra | in line 2 <br>
Step 8: There may be no data to return, Wait a few minutes and run again <br>

### Exercise 6 - Enable Defender for Databases

# Module 6 Lab: Security for Azure Networking​ 

## Lab 6 - Configure Network Security Controls ~60 Minutes

### Lab Setup

Step 5: Ensure you set both region and location to westus3 and the the lab instance from the note. Use User1 password <br>

### Exercise 1 - Start Azure Firewall deployment

Step 4: When creating the Firewall Policy choose westus3 <br>

### Exercise 3 - Create Application Security Groups and NSG rules

No errata <br>

### Exercise 4 - Associate the VM with the ASG

No errata <br>

### Exercise 5 - Create the NSG

No errata <br>

### Exercise 6 - Add inbound security rules

No errata <br>

### Exercise 7 - Apply the NSG to the workload subnet

No errata <br>

### Exercise 8 - Configure a Private Endpoint for storage

No errata <br>

### Exercise 9 - Complete Azure Firewall configuration

No errata <br>

### Exercise 10 - Validate network security controls with Network Watcher

No errata <br>
