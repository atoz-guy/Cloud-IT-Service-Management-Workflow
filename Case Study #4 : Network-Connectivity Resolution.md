**Case #4: Network Connectivity Troubleshooting**

## Incident Details
* **Category:** Network and Infrastructure
* **Priority:** High
* **Status:** Resolved

## Issue
User reported an inability to access the internal "Finance" file server. Internet connectivity was confirmed active, suggesting a localized network or DNS issue.

## Diagnostic Steps
1. **Verification:** Confirmed user had active internet access.
2. **Isolation:** Performed a ping test to the file server IP. Test failed.
3. **Trace:** Ran `tracert` which revealed a timeout at the local switch gateway.
4. **Physical Inspection:** Inspected workstation cabling. Found a faulty network patch cable at the wall jack.

## Resolution
Replaced the faulty patch cable and verified network link. Confirmed with the user that the "Finance" file server was accessible.

## Lessons Learned
* **Layer 1 First:** Always check physical connectivity (cables/ports) before assuming complex software or DNS issues.
* **Testing:** Proactive testing of local resources confirms resolution before closing tickets.
