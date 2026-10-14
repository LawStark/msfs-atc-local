# MSFS ATC Local

A planned free Windows desktop companion for Microsoft Flight Simulator 2024, providing simulated air traffic control through contextual buttons and locally generated speech.

## Project status

This project is currently at the requirements and technical planning stage. No working application or download is available yet.

MSFS ATC Local is an independent, non-commercial project.

## Intended experience

Users will select context-sensitive actions instead of speaking into a microphone. The application will generate the pilot's transmission and the controller's response based on the flight plan, aircraft position and current clearances.

The planned scope includes:

- IFR clearances and button-based readbacks.
- Taxi instructions and parking selection.
- Departure, climb, cruise, descent, arrival and approach guidance.
- Radio frequency handoffs.
- Local speech synthesis for pilot and controller voices.
- Flight history and connection diagnostics.

The initial scope focuses on the user's aircraft and a limited set of validated airports and procedures. Traffic observation and coordination are potential later additions.

## Planned ChartFox integration

We are seeking ChartFox API access to evaluate chart integration within the application.

The intended use is to find airports, list available charts and provide convenient chart access for flight briefing and reference. Where available and permitted, georeferencing could support displaying the simulated aircraft position on a chart.

Any integration will depend on ChartFox approval, API capabilities and applicable terms. ChartFox attribution, chart source licences, rate limits and caching restrictions will be respected.

Charts will remain separate from the structured navigation data used by the ATC engine. The core application is intended to remain usable without ChartFox access.

No ChartFox integration, approval or affiliation is claimed at this stage.

## Technical direction

The current plan is to:

- Run locally on Windows.
- Connect to Microsoft Flight Simulator 2024 through SimConnect.
- Use a rule-based ATC engine.
- Start with locally available speech synthesis.
- Avoid mandatory paid APIs or hosted infrastructure.

Technology choices and simulator compatibility remain subject to technical validation.

## Intended benefit

The project aims to make simulated ATC more accessible to virtual pilots who prefer selecting actions on screen, while keeping flight information and chart references convenient to consult.

## Disclaimer

For flight simulation use only. Not intended for real-world navigation, flight planning or air traffic control.

This project is not affiliated with or endorsed by Microsoft, Asobo Studio or ChartFox.
```
