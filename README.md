# USB Isolator

The title says it all: it isolates an USB port.

It will be useful to break ground loops, or to protect your laptop when working on high voltage devices such as an AC motor controller.
Commercially-available offerings either lacked proper isolation for working with mains voltage (only 1kV isolation rating), full USB 2.0 speed (limited to 12Mbps), partial USB3.0 support, or a high price point (onwards to 1000€ range).


The ADUM1366 is the main chip that isolates USB2.0 LS, FS and HS (1.5, 12 and 480Mbps respectively). It's tested at 3750V for 1 minute.
5V @1A of output power is provided through the onboard REC5A DC/DC converter, which is tested at 2kV for 1 min. If higher insulation is required, other DC/DC converters with similar package and 3 kV or more rating exist.
