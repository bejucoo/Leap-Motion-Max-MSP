# Leap-Motion-Max-MSP
A patch to control the Leap Motion controller inside Max/MSP with the help of [Reach, an open source Leap Motion OSC Sender](https://github.com/NiccoloGranieri/Reach) made by Niccolò Granieri & Jefferson Bledsoe.

To use in your patch:
- Open Reach
- Set the baud rate speed (by default is in 200 but lower values get better and smoother results)
- Open Max and create a new patch
- Create a bpatcher and set the patcher file
- Use the values from the outlets of the bpatcher

*Palm position values don't work with the latest Leap Motion SDK (Orion v4). If yoy want to use this values try with the v3.2.1 of the SDK. ([Reach issue](https://github.com/NiccoloGranieri/Reach/issues/8))*

To do:
- Better and more compact presentation mode (UI)
