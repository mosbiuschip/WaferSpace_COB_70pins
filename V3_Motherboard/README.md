# MV3C_PCB_TEMP
Temporary View Repo for V3 Motherboard PCB (v4a_2026)

Changes from V1 Chip PCB (v3b_2025)

1. Pin bindings changed according to pin bindings .csv and WaferSpace_COB_70pins/V3_COB_Original, COB mounting footprint replaced chip socket
    a. Added Bus 1-5 pins, routed out through 2x3 header pin Breakout
    b. Removed NPAIR_4_BODY, PPAIR_4_BODY, ISINK_32 pins
    c. Changed trace width from standard .25 to .15

Further design considerations and questions

1. SOLVED: LDO - Already have voltage supply protection, is there any reason of convenience to keep LDO for 2.5V or other voltage
2. SOLVED: Power Net Switch - Is it desireable to have an aditional low drop mechanical switch for power net for chip safety
3. Feedback from V1 board - Are there any issues with original V1 design that need to be addressed