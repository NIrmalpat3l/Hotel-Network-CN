# Hotel Network Configuration (4 Floors)

This network setup is designed to manage the operations of a hotel with specific VLAN configurations across four floors, providing isolated and secure communication for each department and service.

This hotel network uses VLANs to separate departments across four floors, ensuring secure communication. Four routers, using OSPF for routing, connect the floors, while DHCP services dynamically assign IP addresses to devices for efficient network management.
----
## ScreenShot

![](/Screenshot/All.png)

----
## 1st Floor: Reception, Security, and Guest Wi-Fi

![1st Floor Network Screenshot](/Screenshot/Floor1-img.png)

- **VLAN 10: Reception**
  - Manages guest check-ins, room booking systems, and inquiries.
  - Ensures seamless communication with the reservation system, guest services, and front desk staff.

- **VLAN 20: Security**
  - Handles hotel surveillance, access control, and alarm systems.
  - Ensures that security devices (cameras, motion sensors, etc.) are isolated for safety and efficient monitoring.

- **VLAN 30: Guest Wi-Fi**
  - Provides secure Wi-Fi access for hotel guests without interfering with internal systems.
  - Ensures the privacy of guest data while maintaining high-speed internet access.

## 2nd Floor: HR, Finance, and IT

![2nd Floor Network Screenshot](/Screenshot/Floor2-img.png)

- **VLAN 40: HR**
  - Manages employee records, recruitment, and payroll.
  - Keeps sensitive employee data secure while ensuring efficient HR management.

- **VLAN 50: Finance**
  - Handles hotel billing, room rates, and financial data.
  - Ensures the confidentiality and integrity of financial transactions and records.

- **VLAN 60: IT**
  - Manages hotel networks, internal systems, and support services.
  - Responsible for troubleshooting and maintaining the hotel’s technology infrastructure.

## 3rd Floor: Housekeeping, Room Service, and Inventory

![3rd Floor Network Screenshot](/Screenshot/Floor3-img.png)

- **VLAN 70: Housekeeping**
  - Manages cleaning schedules, room assignments, and staff communication.
  - Enables smooth coordination between the housekeeping staff and other hotel departments.

- **VLAN 80: Room Service**
  - Manages guest orders, deliveries, and room service logistics.
  - Ensures quick and efficient delivery of services to guests' rooms.

- **VLAN 90: Inventory**
  - Tracks hotel supplies, linens, and food stock.
  - Manages inventory levels and ensures that necessary items are always available.

## 4th Floor: Conference Rooms, Event Management, and Executive Offices

![4th Floor Network Screenshot](/Screenshot/Floor4-img.png)

- **VLAN 100: Conference Rooms**
  - Smart projectors, video conferencing, and room booking systems.
  - Facilitates business meetings and conferences with secure and reliable equipment.

- **VLAN 110: Event Management**
  - Handles event planning, scheduling, and client communication.
  - Coordinates with external clients for event-related services.

- **VLAN 120: Executive Offices**
  - Manages high-level decision-making, budgeting, and staff management.
  - Ensures secure access to confidential business and executive information.

## Router Connectivity and OSPF Configuration

All four floors are connected through four routers, each assigned to a specific floor. The routers use **OSPF (Open Shortest Path First)** as the routing algorithm to ensure efficient and reliable communication between the floors.

Additionally, all routers are configured to provide **DHCP (Dynamic Host Configuration Protocol)** services to automatically assign IP addresses to devices connected to the network, ensuring smooth and dynamic address management across the hotel network.
