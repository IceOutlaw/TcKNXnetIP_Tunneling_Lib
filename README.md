# TcKNXnetIP_Tunneling_Lib

TwinCAT 3 library implementing KNXnet/IP Tunneling communication over TCP
The library allows sending and receiving KNX telegrams via a KNXnet/IP interface.

The implementation has been tested with the following device:
- **ABB IPS/S3.1.1 KNXnet/IP Interface (TCP/UDP Connection)**
- **MDT SCN-IP000.03 KNXnet/IP Interface (TCP/UDP Connection)**

Other KNXnet/IP devices may work but have not yet been tested.

---

## Features

- KNXnet/IP Tunneling communication
- UDP transport support
- Sending KNX telegrams
- Receiving and decoding KNX telegrams
- Designed as a reusable TwinCAT library
- Structured and extensible architecture (IEC 61131-3, Structured Text)

---

## Limitations

- Currently tested only with **ABB IPS/S3.1.1**
- Other KNXnet/IP interfaces are not officially supported yet
- No guarantee for compatibility with all KNXnet/IP devices
- No ETS integration (raw KNX telegram handling)

---

## Requirements

To use this library, the following requirements must be met:

### TwinCAT Software
- TwinCAT 3 Build Verison 4026.19 or higher
- **TwinCAT TCP/IP license** (must be enabled in the project)
- TwinCAT TCP/IP Communication package installed on the IPC

### Hardware / Network
- Beckhoff IPC or Industrial PC with TwinCAT runtime
- KNXnet/IP interface (tested with ABB IPS/S3.1.1)
- Proper KNX network configuration

---

## Usage Notes

- The TwinCAT TCP/IP license must be activated, otherwise communication will not work.
- Ensure that the TCP/IP communication package is installed on the target system.
- Network ports required by KNXnet/IP must be accessible (firewall configuration).

---

## Disclaimer

This project is provided "as is", without warranty of any kind.
The author assumes no responsibility for any damages or malfunctions caused by the use of this software.
Use at your own risk.

---

## License

This project is licensed under the **MIT License**.
See the LICENSE file for details.
