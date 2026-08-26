# Screenshot Capture Guide

Place each image at the exact path below. The LaTeX placeholder is automatically replaced
by the image on the next compile; no `.tex` edit is required. Report page numbers are not
listed because adding the screenshots will change pagination.

| No. | Report placement and insertion point | Figure label | Exact PNG destination | Capture from | What must be visible |
|---:|---|---|---|---|---|
| 1 | **Chapter 4 — A Cross-Vendor Firmware Footprint Analysis Tool**, end of **Design and architecture**, after the input/output table | `fig:tool-screenshot-main` | `Figures/footprint-tool/screenshots/main-analysis-window.png` | MCU Workflow Studio | Completed two-map comparison, project summary, footprint chart, analysis tabs, and mapping status |
| 2 | **Chapter 4**, **Implementation → The multi-signal mapping engine**, after the candidate-ranking figure | `fig:tool-screenshot-mapping-review` | `Figures/footprint-tool/screenshots/mapping-review-queue.png` | MCU Workflow Studio review queue | Several candidate pairs, confidence values, acceptance states, and the selected pair's signal explanation |
| 3 | **Chapter 4**, **Usage and outputs**, after the description of generated workbook/PDF outputs | `fig:tool-screenshot-export` | `Figures/footprint-tool/screenshots/exported-results.png` | Excel, LibreOffice, or generated PDF | Global flash/RAM comparison, one per-layer breakdown, and verdict or quality summary |
| 4 | **Chapter 5 — An Autonomous AI Agent for Benchmark Campaigns**, **Deterministic campaign workflow**, immediately after the workflow diagram | `fig:agent-screenshot-campaign` | `Figures/benchmark-agent/screenshots/copilot-campaign.png` | VS Code Copilot Chat | Real request, selected benchmark agent, delegated action, and concise tool or build result |
| 5 | **Chapter 5**, **Deterministic campaign workflow**, immediately after screenshot 4 | `fig:agent-screenshot-iar-build` | `Figures/benchmark-agent/screenshots/iar-build-output.png` | IAR EWARM | Project tree, target and configuration identity, Build Output, warning/error count, and successful build summary |
| 6 | **Chapter 5**, **Campaign artifact model**, after the campaign-dossier file list | `fig:agent-screenshot-dossier` | `Figures/benchmark-agent/screenshots/campaign-dossier.png` | VS Code Explorer and editor | Manifest, execution status, fairness review, semantic-equivalence record, measurement metadata, and one open populated file |
| 7 | **Chapter 5**, **Implementation**, after the implementation-layout table | `fig:agent-screenshot-workspace` | `Figures/benchmark-agent/screenshots/workspace-configuration.png` | VS Code Explorer and editor | Agent, skill, tool, config, prompt, and campaign folders plus one populated board or toolchain YAML entry |
| 8 | **Chapter 6 — Benchmarking ST against GD32**, **Hardware platforms**, after the board-comparison table | `fig:gd32-screenshot-platforms` | `Figures/gd32/screenshots/board-and-project-setup.png` | Camera and/or IAR EWARM | Both powered boards or both project-option windows, board/device names, 160 MHz settings, and active build configurations |
| 9 | **Chapter 6**, **USB device stack → Scenario design**, after the USB-scenario table | `fig:gd32-screenshot-usb-runtime` | `Figures/gd32/screenshots/usb-runtime-capture.png` | UART terminal, debugger, or USB host tool | ST/GD32 identities, HID or CDC scenario, enumeration success, initialisation value, and transfer values |
| 10 | **Chapter 6**, **FreeRTOS integration → Scenario design**, after the FreeRTOS-scenario table | `fig:gd32-screenshot-freertos-runtime` | `Figures/gd32/screenshots/freertos-uart-results.png` | UART terminal or debugger | ST/GD32 identities, same scenario on both targets, 30-second counters, and timestamp or repetition identifier |
| 11 | **Chapter 7 — Benchmarking ST against Texas Instruments**, **Static analysis of the driver layer → Scope and methodology**, after the analysis-tool list | `fig:ti-screenshot-static-analysis` | `Figures/ti-static/screenshots/analysis-reports.png` | Static-analysis report or terminal collage | Pinned SDK versions plus representative cloc, Lizard, Cppcheck MISRA, and jscpd results |
| 12 | **Chapter 7**, **Functional analysis of the driver layer → Benchmark design and observables**, after the matched-scenario table | `fig:ti-screenshot-functional-build` | `Figures/ti-functional/screenshots/functional-build-and-map.png` | IAR EWARM and map viewer | Matched ST/TI scenario names, successful build summaries, and RO code, RO data, and RW data totals |
| 13 | **Chapter 7**, **FreeRTOS middleware benchmark → Scenario design and configuration**, after the scenario-semantics table | `fig:ti-screenshot-freertos-config` | `Figures/ti-freertos/screenshots/project-configuration.png` | IAR project options or configuration files | Both devices, optimisation, clocks, kernel versions, heap size, tick rate, and scheduler options |
| 14 | **Chapter 7**, **FreeRTOS middleware benchmark → Results**, after the normalised-runtime table | `fig:ti-screenshot-freertos-uart` | `Figures/ti-freertos/screenshots/uart-runtime-windows.png` | UART terminal | Side-by-side ST/TI identities, scenario, raw counters, and enough repeated 30-second windows to support the table |

## Capture Rules

1. Use actual project evidence, not a recreated mock-up.
2. Prefer 1600 px or more in width and a 16:9 or 16:10 crop.
3. Increase the editor or terminal font size before capture so labels remain readable in print.
4. For side-by-side evidence, use one combined PNG and label the ST and competitor halves.
5. Do not include API keys, access tokens, email addresses, unrelated chats, or confidential source paths.
6. Keep the filenames unchanged; no LaTeX edit is needed after adding the PNG files.