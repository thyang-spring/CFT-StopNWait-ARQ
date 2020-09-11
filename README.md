# Chatting and File Transfer: Stop and Wait ARQ
- The communication of CFT is based on Ethernet protocol in Data Link Layer.
- And this adopt the stop and wait ARQ as a transmission mechanism.
- Thus, a transmission speed is very low.
- CFT is suitable for a transmission for small data.
- This mechanism operates with two rules as follows:
  1) the sender transmits a DATA message after receiving the ACK message.
  2) the receiver transmits a ACK message after receiving a DATA message.
- Hence, this mechanism is one of reliable communications.

# Environment
- Development Tool: Microsoft Visual Studio 2010
- Language: C++, MFC

# Summary
- This is applied a mechanism, the stop and wait ARQ.
- This project is extended from IPC project.
