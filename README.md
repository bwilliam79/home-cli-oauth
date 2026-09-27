# home-cli

home-cli is a small personal command-line tool used by one household to check and adjust its own Google Nest thermostat and other home devices.

It is not a public service, not offered to other users, and not for sale.

- It signs in with Google only to use the Smart Device Management API (scope `https://www.googleapis.com/auth/sdm.service`) for the owner's own thermostat.
- It reads thermostat status (temperature, humidity, mode, setpoints) and, when the owner asks, changes the setpoint or mode.

Privacy policy: [PRIVACY.md](PRIVACY.md)
