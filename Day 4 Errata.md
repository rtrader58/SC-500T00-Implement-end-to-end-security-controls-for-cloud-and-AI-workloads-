# SC-500 Implement end‑to‑end security controls for cloud and AI workloads - Day 4 Errata

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

Step 3: Choose your subscription - select apply <br>
Step 10: Before selecting Review + create, Set the VMAdmin password to the same as User1 > paste the information from the note above <br>

### Exercise 1: Review the Preconfigured State

No errata <br>

### Exercise 2: Review Secure Score and Top Recommendations

### Exercise 3: Assign and Review Regulatory Compliance

### Exercise 4: Investigate CSPM Secret Scanning Findings

### Exercise 5: Review Attack Path Analysis

### Exercise 6: Assign Governance Ownership

### Exercise 7: Optional Task: Review Multicloud Connector Scope


# Note there is no labs for Modules 14 and 15
