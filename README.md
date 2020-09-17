# netnsavd
bash scripts to launch anonymous android emulators

Run Android Virtual Devices in network namespaces, or runs Android Studio launcher also in a network namespace. I think that it is better to isolate android and make an external firewall security, to use mobile apps fully anonymous.

x0netns - Base script, that creates network namespaces, reading parameters from environment variables
netns-avd1 - Example script to run TOR-AVD, sorry, Android Virtual Device emulator in a linux network namespace.
