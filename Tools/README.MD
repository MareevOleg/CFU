# Tools related to Component Firware Update
# Contents
This folder contains 
- A sample CFU protocol based Host Stand-alone tool

# CFU Standalone tool sample

The CFU tool sample sends firmware image file(s) to a device in need of an update. Before sending the firmware image, the tool sends several commands to the device with firmware offers. Only if the device accepts, the tool sends the firmware payload. The communication between the tool and the device is in accordance with the [CFU protocol](https://github.com/Microsoft/CFU/tree/master/Documentation/CFU-Protocol), an open source specification (included with CFU) based on the HID protocol.

# See also
[CFU Tool Sample Readme](https://github.com/Microsoft/CFU/blob/master/Tools/ComponentFirmwareUpdateStandAloneToolSample/README.md)
