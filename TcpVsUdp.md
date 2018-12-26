## TCP vs UDP

| TCP | UDP |
| ------ | ------ |
| Transmission Control Protocol | User Datagram Protocol |
| Connection-oriented protocol (with built in error recovery and re-transmission)| Connectionless protocol (not correct or recover errors in the message) |
| Slower (Heavy-weight) | Faster (Light-weight, Best effort protocol)|
| Header size is 20 Bytes  | Header size is 8 Bytes |
| Packets are ordered | No guarentee for the packets order (it must handled by app layer)|
| There are 3 levels handshaking (SYN, SYN-ACK, ACK) | No handshaking|
| Used mostly in applications that require high reliability, and transmission time is relatively less critical. | Mostly used for live broadcasts and online games|