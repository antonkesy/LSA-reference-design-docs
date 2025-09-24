# Risk Assessment

This section provides the risk assessment for low-speed autonomy vehicles. The risk assessments are conducted at two levels. The first one is conducted on the functional level, named Automotive Safety Integrity Level and shortened as ASIL, in order to prevent hazards due to system malfunctions or hardware/software failures. The second one is the system level, named Safety Of The Intended Functionality and shortened as SOTIF, to prevent hazards due to functional insufficiencies or performance limitations.

|           | ASIL HARA  (ISO 26262) | SOTIF HARA  (ISO 21448) |
|-----------|--------------------|-------------------|
| Primary Goal | Prevent hazards due to system malfunctions or hardware/software failures. | Prevent hazards due to functional insufficiencies or performance limitations. |
| Hazard Source | Component failures (e.g., a brake sensor fails). | Limitations of the intended function (e.g., the system fails to detect a pedestrian in a specific environment). |
| Hazardous Event | An event caused by a component or system failure (e.g., unintended braking due to a software bug). | An event caused by a limitation of the ADS's capabilities (e.g., a collision because the ADS couldn't handle a complex traffic scenario). |
| Methodology | Fault Tree Analysis (FTA), Failure Mode and Effects Analysis (FMEA). | Scenario-based analysis, trigger condition analysis. |
| Scope | E/E system failures and their effects on safety. | The ADS's intended function and its performance in various operational contexts (ODD). |
| Output | Safety Goals to avoid unreasonable risk from malfunctions. | Safety Goals to avoid unreasonable risk from functional insufficiencies. |

- [ASIL Assessment](ASIL/index.md): Assessment for ASIL using HARA process. 
- [SOTIF Assessment](SOTIF/index.md): Assessment for SOTIF using HARA process.