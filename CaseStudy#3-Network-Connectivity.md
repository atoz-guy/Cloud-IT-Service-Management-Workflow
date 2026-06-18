**# Case Study #3 : Network-Connectivity Resolution**
# Case Study: Network Connectivity Troubleshooting

## Incident Details
* **Category:** Network / Infrastructure
* **Priority:** High
* **Status:** In Progress

## Issue
User reported an inability to access the internal "Finance" file server. Internet connectivity is confirmed active, suggesting a localized network or DNS issue.

## Diagnostic Steps
1. **Verification:** Confirmed the user has active internet access.
2. **Isolation:** Attempted to ping the file server IP address from the user's machine.
3. **DNS Check:** Verified if the hostname resolves correctly.
4. **Result:** Ping test to file server IP failed. Tracert revealed a timeout at the local switch gateway.
5. **Resolution:** Identified a faulty network patch cable at the user's workstation wall jack. Replaced the cable and re-tested. Connection to the "Finance" server was restored.
6. **Verification:** Confirmed file server access with the user.
