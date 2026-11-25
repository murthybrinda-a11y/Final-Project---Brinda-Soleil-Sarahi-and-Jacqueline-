Brinda :
- EncryptionMethod: AES encryption/decryption and Base64 encoding.
- VirtualTunnel: Packet encapsulation and decapsulation logic.
- VpnConnections: State machine (DISCONNECTED, CONNECTING, CONNECTED) and background Task threads.

Sarahi: 
- Packet: Network packet data fields and getters/setters.
- VpnServer: Server location, IP, and latency properties.

Soleil :
- ClientDevice: Stores the local ISP IP and generates simulated outgoing traffic.
- TrafficLogger: Formats timestamped packet logs for the live inspector console.
- Main: Initializes the backend engine and launches the primary JavaFX Stage.

Jacqueline :
TrafficVisualizer: Custom JavaFX Pane that draws nodes and animates packets.
DashboardController: Connects UI buttons, dropdowns, and status badges to ConnectionManager.

