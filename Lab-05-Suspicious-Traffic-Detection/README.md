Lab 05: Suspicious Traffic Detection

Objective
To identify unusual or suspicious network behavior using packet analysis.

Tool Used
- Wireshark

Steps Performed
- Captured network traffic
- Filtered SYN packets
- Analyzed connection patterns
- Looked for abnormal behavior

Filters Used
- tcp.flags.syn == 1 && tcp.flags.ack == 0
- !(tcp.srcport==80) && !(tcp.srcport==443) && !(udp.srcport==53) && !(udp.srcport==443) && !(tcp.dstport==80) && !(tcp.dstport==443) && !(udp.dstport==53) && !(udp.dstport==443) &&
- dns && !(dns.qry.name contains "google") && !(dns.qry.name contains "youtube") && !(dns.qry.name contains "whatsapp") && !(dns.qry.name contains "tiktok") && !(dns.qry.name contains "instagram")

Observations
- Multiple SYN packets may indicate scanning behavior.
- Normal traffic has balanced request-response patterns.
- Abnormal traffic can indicate probing or scanning activity.

Key Learnings
- Understanding SYN packets
- Detecting abnormal network behavior
- Basic intrusion detection concepts
