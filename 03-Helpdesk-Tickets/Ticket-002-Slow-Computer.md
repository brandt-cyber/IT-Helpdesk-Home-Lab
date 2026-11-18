Help Desk Ticket #002 – Slow Computer

Project: IT Help Desk Home Lab
Ticket Type: Windows Performance Troubleshooting
Environment: Windows 11
Status: Investigation Completed
Experience Type: Independent Home Lab Exercise

1. Customer Problem

The customer reported that their computer was running slowly, applications took a long time to open, and the system occasionally froze for a few seconds.

2. Initial Troubleshooting

Opened Task Manager using Ctrl + Shift + Esc.

Initial readings:

CPU: 1.6%
Memory: 87%
Disk: 0%
3. Investigation Findings

Memory Usage

Identified the following processes:

Process

Memory

Google Chrome

2,357 MB

Search

173 MB

SupportAssist Agent

223 MB

A later memory check showed:

Memory in use: 7.7 GB
Reported capacity: 16.5 GB
Memory usage: 62%
Startup Applications

Reviewed Task Manager Startup Apps:

Application

Startup Impact

Qbuodate

Medium

IntuitDataProtect

Medium

OneDrive.exe

High

No startup applications were disabled.

Windows Update

Found an Extension Driver Update.
Windows indicated that a restart was required.
Computer was restarted.
4. Diagnosis

The original slowdown could not be reproduced during the final performance test.

High memory usage was observed initially, and several applications were identified as potential contributors. However, no confirmed root cause was established.

5. Resolution

The computer was restarted after the pending driver update.

No applications were uninstalled or disabled, and no additional system changes were made.

6. Verification

After restarting:

Google Chrome opened normally.
Websites loaded normally.
No noticeable freezing or slowdown was observed during testing.
Final Result: Computer operating normally during verification. Original cause remains unconfirmed.

7. Skills Practiced

Windows 11 Task Manager
CPU, memory, and disk monitoring
Identifying high-memory processes
Reviewing startup applications
Windows Update investigation
Basic performance troubleshooting
Diagnosis and verification
Help desk ticket documentation
