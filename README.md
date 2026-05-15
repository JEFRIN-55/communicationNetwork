# Hybrid Topology with ED-06
## Network Topology Report

---

# 1. Introduction
A Hybrid Topology is a network configuration that combines two or more different types of network topologies such as Star, Bus, Ring, or Mesh into a single unified network. This approach combines the advantages of multiple topologies while reducing their individual limitations.

Hybrid topology is commonly used in large organizations, educational institutions, hospitals, and enterprises because it provides better scalability, flexibility, reliability, and fault tolerance.

In this experiment, a Star-Bus Hybrid Topology is implemented using Cisco Packet Tracer with 6 end devices (ED-06).

---

# 2. Concept of Hybrid Topology
In a hybrid topology, different network segments use different topologies according to their requirements. These segments are interconnected using networking devices such as switches, hubs, and routers.

## Common Types of Hybrid Topologies
1. Star-Bus Hybrid
2. Star-Ring Hybrid
3. Star-Mesh Hybrid

In this experiment, a Star-Bus Hybrid Topology is used.

---

# 3. Network Design for 6 End Devices (ED-06)

## Structure Used
### Star-Bus Hybrid Topology

### Configuration
- PC0 and PC1 are connected to Hub0 forming the Star segment.
- PC2, PC3, PC4, and PC5 are connected directly to Switch0 forming the backbone segment.
- Hub0 is connected to Switch0 using an uplink connection.
- ICMP Ping is used to verify communication.

---

# 4. Diagram Representation

## Hybrid Network – Star-Bus Combination

### Explanation
- PC0 and PC1 connect to Hub0.
- PC2, PC3, PC4, and PC5 connect to Switch0.
- Hub0 connects to Switch0.
- Data travels through both segments during communication.

### Data Flow
PC0 → Hub0 → Switch0 → PC5

---

# 5. Cisco Packet Tracer Simulation

## Simulation Screenshot 1 – Packet Initiated
- ICMP packet initiated from PC0.
- Simulation starts at t = 0.000s.
- Packet enters Hub0 and moves toward Switch0.

## Simulation Screenshot 2 – Packet Traversing
- Packet moves through Hub0 and Switch0.
- Event list shows forwarding sequence.

## Simulation Screenshot 3 – Successful Delivery
- Packet successfully reaches PC5.
- Status shows Successful.
- Packet loss is 0%.

---

# 6. Components Required

| Component | Quantity | Purpose |
|---|---|---|
| PCs | 6 | End devices |
| Hub (Hub-PT) | 1 | Star segment |
| Switch (2950-24) | 1 | Backbone segment |
| Ethernet Cables | 7+ | Connections |
| IP Addresses | 6 | Unique device addressing |

---

# 7. Working Principle

1. PC0 sends data to PC5.
2. Data first reaches Hub0.
3. Hub0 broadcasts the frame to all ports.
4. Switch0 receives the frame through uplink.
5. Switch0 checks destination MAC/IP address.
6. Packet forwarded to PC5.
7. Communication completes successfully.

## Example Scenario
### Source Device:
PC0

### Destination Device:
PC5

### Path:
PC0 → Hub0 → Switch0 → PC5

### Result:
- Successful transmission
- 0% packet loss

---

# 8. Real-Time Scenario

## College Campus Network
Different departments in a college may use different topologies:
- Administrative Block uses Star topology.
- Computer Labs use Switch backbone.
- All departments connect through a central network.

### Benefits
- Easy expansion
- Better fault isolation
- Reliable communication
- Flexible design

---

# 9. Advantages of Hybrid Topology

1. High scalability
2. Better fault tolerance
3. Flexible design
4. Improved reliability
5. Efficient communication
6. Supports large networks
7. Easy to expand

---

# 10. Disadvantages of Hybrid Topology

1. Complex design
2. Higher installation cost
3. Difficult troubleshooting
4. Requires more hardware
5. Large cabling requirement

---

# 11. Applications

1. Enterprise Networks
2. Educational Institutions
3. Hospital Networks
4. ISP Networks
5. Data Centers
6. Banking Systems

---

# 12. Comparison with Other Topologies

| Feature | Star | Bus | Ring | Hybrid |
|---|---|---|---|---|
| Reliability | Medium | Low | Medium | High |
| Cost | Medium | Low | Medium | Medium-High |
| Scalability | High | Low | Low | Very High |
| Complexity | Low | Low | Medium | High |
| Fault Tolerance | High | Low | Medium | High |
| Flexibility | Low | Low | Low | Very High |

---

# 13. Conclusion
The 6 end devices (PC0, PC1, PC2, PC3, PC4, and PC5) were successfully connected using a Star-Bus Hybrid Topology in Cisco Packet Tracer. Hub0 was used for the Star segment and Switch0 acted as the backbone network device.

ICMP Ping tests from PC0 to PC5 confirmed successful communication with 0% packet loss. The experiment demonstrates that hybrid topology provides reliable, scalable, and efficient communication in modern networking environments.

---

# QUESTION BANK – HYBRID TOPOLOGY

# PART A – Fill in the Blanks

1. Hybrid topology combines ________ or more different types of topologies.
2. In this experiment, the Star segment uses a ________.
3. The network was implemented using ________ Packet Tracer.
4. The backbone device is Cisco ________.
5. ICMP ping showed ________% packet loss.
6. The 6-device network is called ________.
7. Hub0 connects to Switch0 using a ________ cable.
8. Failure in one segment ________ affect the entire network.
9. Source device is ________ and destination device is ________.
10. Hybrid topology provides high ________.

---

# PART B – Match the Following

| Column A | Column B |
|---|---|
| Hub0 | Star segment device |
| ICMP | Ping protocol |
| PC0 | Source device |
| Switch0 | Backbone device |
| Hybrid Topology | Combination of topologies |

### Answer Key
1-b, 2-c, 3-a, 4-d, 5-e

---

# PART C – True or False

1. Hybrid topology uses only one topology. – False
2. ICMP tests connectivity. – True
3. Hub broadcasts data to all ports. – True
4. Hybrid topology is less scalable. – False
5. Ping from PC0 to PC5 was successful. – True

---

# PART D – Multiple Choice Questions

## 1. Hybrid topology combines:
a) Only star topologies  
b) Two or more topologies  
c) Only bus topology  
d) Only mesh topology  

### Answer:
b) Two or more topologies

---

## 2. Which protocol tests connectivity?
a) HTTP  
b) FTP  
c) ICMP  
d) SMTP  

### Answer:
c) ICMP

---

## 3. Result of the ping test:
a) Failed  
b) 50% packet loss  
c) Successful with 0% packet loss  
d) Timeout  

### Answer:
c) Successful with 0% packet loss

---

## 4. Which device forms the Star segment?
a) Switch0  
b) Router0  
c) Hub0  
d) Modem0  

### Answer:
c) Hub0

---

## 5. Which switch was used?
a) Cisco 3560  
b) Cisco 2950-24  
c) Cisco 4500  
d) Cisco 7200  

### Answer:
b) Cisco 2950-24

---

# PART E – Short Answer Questions

## 1. Define Hybrid Topology.
Hybrid topology is a network formed by combining two or more different topologies into a single network.

## 2. Components used in the experiment.
- PCs
- Hub
- Switch
- Ethernet cables
- IP addresses

## 3. Explain data flow from PC0 to PC5.
Data travels from PC0 to Hub0, then to Switch0, and finally reaches PC5.

## 4. Advantages of Hybrid Topology.
- Scalability
- Reliability
- Flexibility
- Fault tolerance

## 5. Real-time application.
College campus networks commonly use hybrid topology.

---

# PART F – Long Answer Questions

## 1. Explain Hybrid Topology with diagram.
Hybrid topology combines multiple network topologies into a single network. In this experiment, Star and Bus topologies are combined using a hub and switch.

## 2. Working principle of Hybrid Topology.
Data from source PC travels through Hub0, then through Switch0, and reaches the destination device successfully.

## 3. Compare Hybrid with Star, Bus, and Ring.
Hybrid topology provides better scalability, reliability, and flexibility than individual topologies.

## 4. Advantages and disadvantages.
Advantages include flexibility and fault tolerance, while disadvantages include complexity and higher cost.

## 5. Real-time scenario.
Enterprise and college networks use hybrid topology for efficient communication and scalability.

---

# FINAL CONCLUSION
The Hybrid Topology experiment using 6 end devices was successfully implemented and tested in Cisco Packet Tracer. The Star-Bus combination provided reliable communication between all devices with 0% packet loss. The experiment proves that hybrid topology is suitable for large and scalable networking environments.
