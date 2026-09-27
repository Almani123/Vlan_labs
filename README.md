# Cisco Packet Tracer – VLAN Labs 🖧

Two Cisco Packet Tracer lab files covering VLAN configuration and network segmentation, built for practicing switching fundamentals (CCNA-level).

## 📁 Repository Structure

```
.
├── labs/
│   ├── LAB5.pkt                        # Lab 5 – VLAN configuration exercise
│   └── VLANsbyCiscoPacketTracer.pkt    # VLAN topology & inter-VLAN setup
├── docs/                               # (add topology diagrams / notes here)
├── screenshots/                        # (add PT screenshots here)
├── LICENSE
└── README.md
```

## 🧰 Requirements

- [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) **v8.0+** (free with a Cisco Networking Academy / NetAcad account)
- Basic understanding of switching, VLANs, and trunking

## 🚀 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>/labs
   ```
2. Open a `.pkt` file directly in Cisco Packet Tracer (double-click, or `File > Open`).
3. Click through the topology, check device configs (`enable` → `show running-config`), and explore the VLAN assignments.

## 📚 Lab Contents

### `LAB5.pkt`
A hands-on exercise covering:
- Creating and naming VLANs on a switch
- Assigning access ports to VLANs
- Verifying VLAN membership (`show vlan brief`)
- Basic connectivity testing between hosts in the same/different VLANs

### `VLANsbyCiscoPacketTracer.pkt`
A topology-focused lab covering:
- Multi-switch VLAN setup
- Trunk port configuration (`switchport mode trunk`)
- Inter-VLAN routing (router-on-a-stick or L3 switch, depending on topology)
- End-to-end connectivity verification with `ping`/`traceroute`

> ℹ️ Both files are Packet Tracer's proprietary binary format, so exact device configs can't be diffed/viewed on GitHub — open them in Packet Tracer to inspect.

## 🖼️ Screenshots

_Add topology screenshots to `screenshots/` and reference them here, e.g.:_
```markdown
![Topology](screenshots/topology.png)
```

## 🎯 Learning Objectives

- Understand VLAN segmentation and its role in reducing broadcast domains
- Configure access & trunk ports on Cisco switches
- Set up inter-VLAN routing
- Verify and troubleshoot VLAN connectivity

## 🤝 Contributing

Pull requests for additional labs, improved documentation, or topology diagrams are welcome.

## 📄 License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.
