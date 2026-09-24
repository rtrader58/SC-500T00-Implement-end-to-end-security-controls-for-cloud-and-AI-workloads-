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

# Note there is no labs for Modules 8 and 9

# Module 10 Lab: Microsoft Foundry (formerly Azure AI Studio) and AI Gateway Security​​

## Lab 7 - Configure AI Gateway and Foundry Security Controls ~60 Minutes

### Lab Setup

Step 3: Choose your subscription - select apply <br>
Step 11: Before selecting Review + create, paste the lab instance from the note above <br>

### Exercise 1: Review the unsecured state

Step 9: Verify the checkbox is cleared <br>

### Exercise 2: Review the Foundry model endpoint

Step 2: Sign-in with User 1 if required / click continue without feedback<br>
Step 3: Scroll to the top to see the project <br>
Skip step 4 <br>
Skip step 7 <br>

### Exercise 3: Apply the AI Gateway token rate limit policy

No errata <br>

### Exercise 4: Require subscription key authentication

No errata <br>

### Exercise 5: Test the configured gateway

Completed in the Azure portal <br>

Step 7: Also remove the Request Body - The response will be 400 bad request<br> 

Step 9: Paste into notepad first make changes then paste into the Cloudshell <br>

### Exercise 6: Create a content safety guardrail in Azure AI Foundry

Step 3: Select Go to project in the left menu <br>

### Exercise 7: Enable Defender for AI Services

No errata <br>

### Clean up

After step 2: Click on Edit <br>
Step 3: After choosing default click Submit changes <br>

# Module 11: AI Security Monitoring with Defender for Cloud​ ~30 Minutes

## Lab 8 - Monitor AI Security with Defender for Cloud ~30 Minutes

### Skip Lab 8 as there is no data to view 

 # Day 4 Errata

# Module 12 Lab: Security for Application Platform Services​

## Lab 9 - Secure Container Workloads with AKS and Defender for Containers ~45 Minutes

### Lab Setup

### Note: Do not close the CloudShell until directed to

Step 3: Choose your subscription - select apply <br>
Step 5: Paste into Notepad first, repace the values then paste into Clouddhell
Step 10: Before selecting Review + create, paste the information from the note above <br>
Step 12: The ACR Registry will be 3 or 4 lines above the word Result <br>

### Exercise 1: Review the Preconfigured State

No errata <br>

### Exercise 2: Enable Defender for Containers

No errata <br>

### Exercise 3: Verify Container and Registry Monitoring

Step 1: Will only say 2 Kubernetes cores are protected <br>
Step 5: Browse to the Resource Group <br>

### Exercise 4: Apply ACR Access Controls

Step 2: remove the checkbox <br>
Step 11: Only do if you cannot find User2 or User3 in the Step 7 or 10

### Exercise 5: Restrict ACR Network Access

No errata <br>

## Lab 10 - Secure Azure App Services and API Management ~45 Minutes

### Lab Setup

Step 6: Before selecting Review + create, paste the lab instance from the note above <br>

### Exercise 1: Review the Preconfigured State

Step 3: Expand Settings > Click Web application firewall > Click sc500-lab4c-waf <br>

### Exercise 2: Validate WAF Detection Mode

### Note: Do not close the CloudShell until directed to do so 

Step 2: Search for Application gateway
Step 3: Expand Settings > Click Web application firewall > Click sc500-lab4c-waf <br>
Step 3: to verivy Rule set - Click on Managed Rules under settings <br>
Step 4: Choose your subscription - select apply <br>
Step 5: Paste into Notepad > Replace the <agw-public-ip> with tne public IP address of you Application Gateway > paste into the CloudShell<br>

Step 6: Search for Log Analytics workspace - click logs - If an agent opens cllose it with the slider bar - choose KQL mode <br>
Step 7: Remove the first | in line 2 before running<br>

### Exercise 3: Switch WAF to Prevention Mode and Re-test

Step 1: Search Application gateway > Select the sc500-labc-agw > Under Settings Select Web application firewall > Select the Associated WAF <br>

Step 2: Click Switch to prevention mode at the top of the screen <br>
Step 3: Not requires <br>

### Exercise 4: Enable App Service Authentication

Step 1 Search for App Serives <br>
Step 2: Under Settings <br>
Step 4: Select 90 days for Client secret  <br>
Step 6: Skip if step 5 succeeded <br>

### Exercise 5: Apply Network Restrictions to App Service and Function App

Step 1: Under Settings > Under Inbound traffic select Enable with no access restrictions <br>
Step 2: Select Enable from select virtual networks and IP addresses > Use the Following settings <br>
Name: Give it a name <br>
Priority: 100 <br>
Type: Virtual network <br>
Virtual network: sc500-lab4c-vnet <br>
Subnet: agw-subnet <br>
Leave the rest of the default settings <br>
Step 5: Browse back to App Services <br>
Step 6: Under Settings > Under Inbound traffic select Enable with no access restrictions <br>
Step 7: Select Enable from select virtual networks and IP addresses > Use the Following settings <br>
Name: Give it a name <br>
Priority: 100 <br>
Type: Virtual network <br>
Virtual network: sc500-lab4c-vnet <br>
Subnet: func-allowed-subnet <br>
Leave the rest of the default settings <br>
Step 7: Set unmatched rull action to Deny not the Function rule <br>

### Exercise 6: Enforce Subscription Key Protection in API Management

Step 1: Searrch for API Management Services <br>
Step 3: Click Lab 4C API > Settings > Check Subscription required

# Module 13: AI Security Monitoring with Defender for Cloud​ ~30 Minutes

## Lab 11 - Explore Defender for Cloud Security Posture and CSPM ~75 Minutes

### Lab Setup

### Note: Skip Lab 11 does not work as written
