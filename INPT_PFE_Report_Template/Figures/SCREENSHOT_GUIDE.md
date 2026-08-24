# Screenshot Capture Guide

Place each image at the exact path below. The LaTeX placeholder is automatically replaced by the image on the next compile. Use PNG, crop empty desktop space, keep text legible, and hide usernames, tokens, serial numbers, and confidential paths.

| Destination path | Capture from | What must be visible |
|---|---|---|
| `Figures/footprint-tool/screenshots/main-analysis-window.png` | MCU Workflow Studio | Completed comparison, project summary, footprint chart, tabs, mapping status |
| `Figures/footprint-tool/screenshots/mapping-review-queue.png` | MCU Workflow Studio review queue | Candidate pairs, confidence, acceptance state, selected pair's signal explanation |
| `Figures/footprint-tool/screenshots/exported-results.png` | Excel, LibreOffice, or generated PDF | Global flash/RAM result, per-layer result, verdict or quality summary |
| `Figures/benchmark-agent/screenshots/copilot-campaign.png` | VS Code Copilot Chat | Real request, selected custom agent, delegated action, tool or build outcome |
| `Figures/benchmark-agent/screenshots/iar-build-output.png` | IAR EWARM | Project and configuration identity plus successful Build Output summary |
| `Figures/benchmark-agent/screenshots/campaign-dossier.png` | VS Code Explorer and editor | Completed campaign files and one populated manifest or fairness record |
| `Figures/benchmark-agent/screenshots/workspace-configuration.png` | VS Code Explorer and editor | Agent folders and one populated board or toolchain YAML entry |
| `Figures/gd32/screenshots/board-and-project-setup.png` | Camera and/or IAR EWARM | Both boards or both device/project configurations, including the 160 MHz setting |
| `Figures/gd32/screenshots/usb-runtime-capture.png` | UART terminal, debugger, or USB host tool | ST/GD32 identity, scenario, enumeration, initialisation and transfer values |
| `Figures/gd32/screenshots/freertos-uart-results.png` | UART terminal or debugger | ST/GD32 identity, same scenario, 30-second counters, repetition identifier |
| `Figures/ti-static/screenshots/analysis-reports.png` | Static-analysis output or terminal | SDK versions and representative cloc, Lizard, Cppcheck, and jscpd results |
| `Figures/ti-functional/screenshots/functional-build-and-map.png` | IAR EWARM and map viewer | Matched scenario names, successful builds, RO code/data and RW data totals |
| `Figures/ti-freertos/screenshots/project-configuration.png` | IAR project options or config files | Device, optimisation, clock, kernel version, heap, tick and scheduler options |
| `Figures/ti-freertos/screenshots/uart-runtime-windows.png` | UART terminal | Side-by-side ST/TI identities, raw counters, repeated 30-second windows |

## Capture Rules

1. Use actual project evidence, not a recreated mock-up.
2. Prefer 1600 px or more in width and a 16:9 or 16:10 crop.
3. Increase the editor or terminal font size before capture so labels remain readable in print.
4. For side-by-side evidence, use one combined PNG and label the ST and competitor halves.
5. Do not include API keys, access tokens, email addresses, unrelated chats, or confidential source paths.
6. Keep the filenames unchanged; no LaTeX edit is needed after adding the PNG files.