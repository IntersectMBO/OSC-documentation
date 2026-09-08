# Security Incident Officer Mid-Year Report

### Strengthening the Security Posture of the Cardano Ecosystem

Over the reporting period, Security Officer Mike Hornan focused on proactive threat detection, ecosystem resilience, and structured incident response as part of the Intersect MBO security initiative. He oversaw vulnerability management, real-time network monitoring, and operational preparedness.This report was prepared by the Security Officer and as such will be from their perspective.&#x20;

### Foreword by Intersect - Open Source Committee

The Open Source Committee has analyzed this Security Incident Officer Mid-Year Report and appreciates the output. The sheer volume, quality, and impact of the technical and operational contributions delivered by Mike and the Security Council demonstrate an exceptional standard of proactive ecosystem defense. The validation of over 124 community-submitted vulnerability reports through the Bug Bounty Program has successfully leveraged community expertise as a high-signal security layer, while the construction and real-time Grafana monitoring of 18 Cardano nodes across multiple key networks (including Mainnet, Preprod, Preview, SanchoNet, and the Dijkstra Network), have significantly elevated early issue detection and network visibility.&#x20;

Furthermore, the execution of vital resilience testing, such as the second fire drill exercise on SanchoNet aligned with CIP-0135, ensures our ecosystem's readiness under simulated failure conditions. Equally critical is the behind-the-scenes collaboration with the Security Council and development teams, alongside active coordination with emerging implementations like the Amaru and Dingo Node teams to support node diversity. This mature alignment on sensitive security topics and responsible disclosure practices plays a vital role in protecting the ecosystem.&#x20;

On behalf of the Open Source Committee, we extend our sincere thanks to Mike, the Security Council, and the Cardano Technology Team for their diligent work in establishing incident response playbooks, real-time alerting channels, and disaster recovery protocols. Your unwavering commitment provides the Cardano community with great confidence and profoundly strengthens the resilience and security posture of the Cardano ecosystem.&#x20;

The following is the report provided by Mike Hornan, Intersect Security Officer:

### Bug Bounty Program Impact (Since January)

From January on to April, through the Intersect Bug Bounty Program, I have conducted end-to-end validation and testing of 124 vulnerability reports submitted by the community.

* 91 reports were triaged and determined to be non-impactful, invalid, or out of scope
* 33 reports were validated as legitimate security findings, with 25 qualifying for rewards. The remaining were submitted by contributors who are unable to accept compensation.&#x20;

These validated reports led to the identification of meaningful weaknesses and directly contributed to remediation efforts, strengthening the reliability and security of the ecosystem. The program continues to act as a high-signal external security layer, leveraging community expertise to uncover issues that may otherwise go undetected.

### Multi-Network Monitoring & Coverage

I actively monitor the health and behavior of key Cardano networks, including:

* Cardano Mainnet
* Preprod
* Preview
* SanchoNet
* Dijkstra Network

I have built 18 Cardano nodes, monitored via Grafana, running the same versions used by block-producing operators across these networks.&#x20;

This approach allows me to:

* Detect version-specific bugs or regressions in real conditions
* Identify potential chain divergence between node versions
* Mirror production behavior to improve early issue detection and validation

By aligning my infrastructure with production-used versions, I increase confidence in identifying issues before they propagate at the network level.

![](<../../../.gitbook/assets/unknown (11).png>)

### Real-Time Alerting & Incident Awareness

I have implemented a dedicated channel, that alerts Intersect professional staff, to provide real-time visibility into critical network events, including:

* Network partitions
* Chain halts
* Node desynchronization

This enables rapid detection, coordination, and response, reducing reaction time and limiting potential impact on the network.

### Security Procedures & Incident Response Framework

In collaboration with the Security Council, there is now established, a clear and actionable security framework, overseen by the Open Source Office and Cardano Technology Team (Intersect). This framework includes:

* Logging procedures, standardized methods for capturing and preserving critical data
* Active incident response playbooks, defined processes for coordinated handling of live incidents
* Disaster recovery protocols, structured steps to restore operations and ensure continuity

This framework ensures consistency, preparedness, and effective coordination across all involved parties.

### Fire Drill & Resilience Testing

I successfully executed the second fire drill exercise on SanchoNet, aligned with Scenario 3 of CIP-0135.

This exercise stress-tested incident response coordination, validated operational procedures under simulated failure conditions, and provided actionable insights to further strengthen ecosystem resilience.

**Link to full report:** [SanchoNet Disaster Recovery – Second Round Findings](https://committees.docs.intersectmbo.org/intersect-technical-steering-committee/about/security-council/sanchonet-fire-drill)

### Confidential Coordination & Security Collaboration

In addition to the work outlined above, I have been actively engaged in ongoing security discussions and coordination efforts with the Security Council and development teams.

These interactions include sensitive security topics, vulnerability discussions, and coordination on potential or active issues, which cannot be disclosed publicly for security reasons. However, this work plays a critical role in:

* Supporting responsible disclosure practices
* Aligning response strategies across stakeholders
* Contributing to the resolution of sensitive security matters

I also maintain active coordination with the Amaru and Dingo Node teams to support node diversity efforts, as these implementations are expected to become part of the ecosystem. I am currently monitoring the Dingo Node on Preview, contributing to early visibility and validation ahead of broader adoption.

While not all contributions can be detailed in this report, the details shared represent a significant portion of the overall security effort and impact.

### Conclusion

My security efforts focus on proactive defense, real-time detection, and coordinated response. By combining community-driven vulnerability discovery, production-aligned monitoring, and tested operational procedures, I am actively contributing to strengthening the resilience and security of the Cardano ecosystem.

<br>
