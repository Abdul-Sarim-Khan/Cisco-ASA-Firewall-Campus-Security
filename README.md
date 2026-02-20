This project transitions a flat network into a segmented architecture with a focus on 'Inside' vs 'Outside' security zones. Key features include:

- Edge Defense: Configured a Cisco ASA Firewall with Security Levels (100 for Inside, 0 for Outside) and Modular Policy Framework (MPF) for deep packet inspection.

- Internal Access Control: Deployed Extended ACLs (BLOCK_STUDENT_TO_ADMIN and BLOCK_LAB_TO_ADMIN) to enforce strict internal boundaries.

- Administrative Management: Implemented specific icmp echo-reply permits, allowing administrators to monitor the network while maintaining a one-way block for unauthorized users.

- Centralized Internet Access: Established a point-to-point Layer 3 link to route all internet-bound traffic through the firewall perimeter.
