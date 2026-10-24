# QDG lab status

Live status of the Quantum Devices Group cryostats and Angstrom evaporator at UC Berkeley:
https://quantumdevicesgroup.github.io/lab-status/

The lab monitoring PC regenerates `data/status.json` every 10 minutes from its logging database
and pushes it here, so the page runs 10–15 minutes behind. Each update replaces the previous one;
this repository keeps no history.

Everything here is generated automatically. Changes to the page belong in
`FridgeStatus/templates/index.html` of the group's MonitorBear repository.
