Help Desk Ticket #001 – Unable to Access Websites

Lab Type: Independent Home Lab
Operating System: Windows 11
Category: Network Troubleshooting
Difficulty: Beginner
Status: Investigation in Progress


1. Problem Description

A client reports that their computer successfully connects to Wi-Fi but cannot access websites such as Google.

The client states that internet access was working the previous day.

2. Initial Troubleshooting Questions

Before making changes, I asked:

Is the issue affecting one particular website or all websites?
Is the issue occurring on one computer or multiple devices?
Was internet access working previously?
Purpose: Identify whether the issue is isolated to one website, one device, or the entire network.

3. Troubleshooting Steps

Step 1 – Check IP Configuration

Command:

ipconfig /all
Purpose:

Check IPv4 address.
Verify subnet mask.
Identify default gateway.
Identify configured DNS server.
Step 2 – Test Default Gateway

Command:

ping [default gateway]
Purpose:

Verify communication between the computer and local network gateway.
Identify potential local network connectivity issues.
Step 3 – Test External Connectivity

Command:

ping 8.8.8.8
Purpose:

Test connectivity to an external IP address without relying on DNS name resolution.
Step 4 – Investigate DNS

Command:

nslookup google.com
Purpose:

Determine whether DNS can resolve a domain name into an IP address.
Identify potential DNS resolution problems.
Step 5 – Test Website Access

Website:
https://google.com

Purpose:

Verify whether the browser can successfully access the website.
4. Diagnosis

The investigation is intended to determine whether the problem involves:

Incorrect IP configuration.
Default gateway connectivity.
Internet connectivity.
DNS resolution.
Browser or website access.
Final Root Cause: Not yet confirmed. Additional test results are required.

5. Resolution

Pending diagnosis.

Once the root cause is identified, apply the appropriate corrective action and document the change.

6. Verification

After applying the fix:

Repeat the failed connectivity test.
Confirm DNS resolution if applicable.
Open the affected website.
Confirm the client can access the internet.
Document the successful result.
7. Skills Practiced

Windows Command Prompt
IP configuration
Default gateway troubleshooting
Ping testing
DNS troubleshooting
Network connectivity diagnosis
Help Desk ticket documentation

Lab Outcome: Practiced a structured Tier 1 troubleshooting process using Windows 11.

Environment: Personal Windows 11 home lab.

Documentation Status: Investigation in progress.

