# Windows 11 Help Desk Troubleshooting Lab

Hands-on Windows 11 support portfolio demonstrating a structured Tier 1 troubleshooting workflow in a VirtualBox lab environment.

## Project Objective

Practice the same workflow used in entry-level Help Desk and Service Desk work:

1. Identify the user's symptom and impact.
2. Form a theory before making changes.
3. Gather evidence with low-risk diagnostics.
4. Apply a safe, reversible fix.
5. Verify the original issue is resolved.
6. Document findings, actions, and next steps.

## Skills Demonstrated

- Windows 11 troubleshooting
- TCP/IP, DHCP, DNS, gateway and ping testing
- Network adapter diagnosis
- NTFS permissions and standard-user access
- Windows Services
- Task Manager and application recovery
- Windows Update and storage review
- Event Viewer analysis
- Device Manager and audio troubleshooting
- Technical documentation and user-focused verification

## Troubleshooting Cases

| # | Case | Primary Tools | Result |
|---|---|---|---|
| 1 | DNS failure | `ipconfig`, `ping` | Connectivity/name resolution restored |
| 2 | Disabled/disconnected network adapter | Settings, network adapter tools, `ping` | Adapter and connectivity restored |
| 3 | Incorrect static IP | `ipconfig`, adapter settings | DHCP configuration restored |
| 4 | NTFS permission issue | File Explorer, Security, Advanced Security | Employee read access restored |
| 5 | Windows Search service | `services.msc` | Search service restored |
| 6 | Frozen application | Task Manager | Application recovered without rebooting PC |
| 7 | Performance / unexpected shutdown | Task Manager, Windows Update, Event Viewer | Evidence documented; Event 41 and 6008 correlated |
| 8 | Disabled audio device | Sound Settings, Device Manager | Disabled device identified and enabled |

## Evidence

See [`screenshots/`](screenshots/) for sanitized lab evidence. Screenshots are used to support the troubleshooting narrative, not as a substitute for explaining the diagnostic reasoning.

## Documentation

The full case-study document is included as:

- `Windows_11_Help_Desk_Troubleshooting_Portfolio.docx`
- `Windows_11_Help_Desk_Troubleshooting_Portfolio.pdf`

## Key Takeaway

The goal of this lab was not simply to click through Windows settings. It was to practice isolating a problem, explaining why each diagnostic step was chosen, making the least disruptive change, and verifying the result - the same reasoning expected in Tier 1 IT support.
