![leap-max](https://i.imgur.com/asehULC.png)

# Leap-Motion-Max-MSP
A patch to use the Leap Motion controller inside Max/MSP with the help of [Reach, an open source Leap Motion OSC Sender](https://github.com/NiccoloGranieri/Reach) made by [Niccolo Granieri](https://github.com/NiccoloGranieri) and [Jefferson Bledsoe](https://github.com/JeffersonBledsoe).

***Currently for Windows only.*** 

## To use in your patch:
- Open Reach
- Set the baud rate speed (by default is in 200 but lower values get better and smoother results)
- Open Max and create a new patch
- Create a bpatcher and set the patcher file
- Use the values from the outlets of the bpatcher

*Palm position values don't work with the latest Leap Motion SDK (Orion v4). If you want to use this values try with the v3.2.1 or the v2.3.1 of the SDK. ([Reach issue](https://github.com/NiccoloGranieri/Reach/issues/8))*
