# Cascade Edition Change Log

## Output isolation

- Added `main_cascade.tex`, which compiles to `main_cascade.pdf` and separate auxiliary files.
- Preserved the original `main.tex`, chapter sources, and `main.pdf`.

## Revised chronology

1. General introduction and project requirements.
2. Standalone STM32 board-equivalence assignment.
3. Pilot USB optimisation and ST-versus-Renesas/NXP measurements.
4. MCU Workflow Studio and MCU Benchmark Copilot Agent.
5. Extended GD32 and TI campaigns.
6. General conclusion and perspectives.

The existing tool, GD32, and TI chapters were copied under `Cascade/` so their opening
transitions could be revised without changing the original report.

## Internal evidence used

- `board equivalence.pdf`: result of the independent assignment to map a host-provided list
  of competitor boards to their nearest STM32 counterparts. It did not select or influence
  the boards used in the benchmark chapters.
- Workbook `Summary`: primary source for the Renesas pilot tables and NXP aggregate gaps.
- Workbook `Renesas`: detailed Renesas footprint and cycle-level cross-checks.
- Workbook `Initialization Execution time `: STM32 cycle-level traceability.
- Presentation `ST Competitors MW Benchmark`, slides 23--25: authoritative NXP footprint,
  timing, clock-configuration, and scenario-boundary evidence. Displayed image values take
  precedence over conflicting workbook cells.
- Workbook `Nxp vs StM32U5` and `ST vs NXP`: supporting cross-checks only.

## Resolved workbook conflicts

- Presentation slide 23 confirms STM32 HID ROM as 16,377 bytes.
- Presentation slide 23 confirms MCX-N9 CDC ROM as 13,549 bytes.
- Presentation slide 24 confirms MSC RAM with RCC as 13,556 bytes for STM32U575 and
  11,859 bytes for MCX-N9; without RCC it shows 13,556 and 11,747 bytes.
- Presentation slides 23--24 replace the conflicting workbook timing rows with displayed
  initialisation times: HID 10/5 ms, CDC 9.993/8.159 ms, and MSC 112/100.03 ms for
  STM32U575/MCX-N9.
- Presentation slide 24 identifies the MSC measurement as an MSC host initialisation path
  covering clock, USB, and FATFS setup before the media-insertion check.

## Resolved review items

- The official ST product page confirms `STM32H735G-DK`, resolving the source typo
  `SM32H735G-DK`.
- Inconsistent TI parameter-distribution rows were removed because their source population
  did not match the reported public-function totals.
- No unresolved value is used to derive a new percentage or universal vendor conclusion.