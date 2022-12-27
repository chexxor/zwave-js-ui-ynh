Full featured Z-Wave Control Panel and MQTT Gateway.

### Features

- Control Panel UI: Directly control your nodes and their values from the UI, including:
-- Nodes management: Add, remove, and configure all nodes in your Z-Wave network
-- Firmware updates: Update device firmware using manufacturer-supplied firmware files
-- Groups associations: Add, edit, and remove direct node associations
-- Z-Wave JS Exposed: Provides full-access to Z-Wave JS's APIs
- Full-Featured Z-Wave to MQTT Gateway: Expose Z-Wave devices to an MQTT broker in a fully configurable manner
- Secured: Supports HTTPS and user authentication
- Scene Management: Create scenes and trigger them by using MQTT apis (with timeout support)
- Debug Logs in the UI: See debug logs directly from the UI
- Access Store Files in the UI: Access the files are stored in the persistent store folder directly from the UI
- Network Graph: Provides a beautiful map showing how nodes are communicating with the controller
- Supports the Official Home Assistant Integration: Can act as the backend driver for the official Home Assistant integration, using the same driver and socket server as the official addon
- Supports Home Assistant Discovery via MQTT: In lieu of the official integation, can be used to expose Z-Wave devices to Home Assistant via MQTT discovery.
- Supported by Domoticz (beta 2021.1) using MQTT Autodiscovery.
- Automatic/Scheduled backups: Scheduled backup of NVM and store directory. It's also possible to enable automatic backups of NVM before every node inclusion/exclusion/replace, this ensures to create a safe restore point before any operation that can cause a network corruption.
