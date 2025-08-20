Raspberry Pi + Salesforce Demo

Overview

This project demonstrates a conceptual integration between a Raspberry Pi and Salesforce. The goal is to simulate a car rental company where physical actions (e.g., button presses) could trigger Salesforce automations such as creating Cases or updating records. Responses from Salesforce could be reflected back on the Raspberry Pi (e.g., LED notifications).

Features (Planned)
	•	Simulate car rental operations: reservations, returns, fuel check, car washing, and damage reporting.
	•	Create Salesforce Cases automatically for reported damages.
	•	Track cars, customers, and contracts in Salesforce custom objects.
	•	LED/physical indicators on Raspberry Pi respond to Salesforce updates.
	•	End-to-end integration concept between a local device and Salesforce automation.

Tech Stack
	•	Raspberry Pi 4 Model B (8GB)
	•	Python (for GPIO scripting)
	•	Salesforce (custom objects, Flows, automation rules)
	•	Salesforce CLI (sf CLI)

Status
	•	Project conceptualized and setup environment ready.
	•	Next steps: implement GPIO interactions, connect to Salesforce org, create triggers/Flows.

License

MIT License (planned)