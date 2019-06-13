# CAN-Gateway-Custom-Device

The **CAN Gateway Custom Device** allows to block frames, change DLC of frames and apply real-time faults on signals inside a frame in a CAN Network. If the message contains a CRC in J1950 format the addon is capable to recalculate the correct CRC after a signal fault insertion. The output frames are Echoed directly by the Custom Device to allow logging.

## LabVIEW Version

LabVIEW 2018

### Quality, Limitations ###

IP has been tested by developer. It meets VeriStand addon coding best practices.

Protocol support for CAN-FD is partially implemented.

### Source Dependencies ###

NI XNET 18.0 or later

## License

The CAN Gateway Custom Device is licensed under an MIT-style license (see LICENSE). Other incorporated projects may be licensed under different licenses. All licenses allow for non-commercial and commercial use.

