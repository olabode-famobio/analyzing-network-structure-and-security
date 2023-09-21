# Analyzing Network Structure and Security
### Scenario
You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved. During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

* A new firewall rule to limit the rate of incoming ICMP packets

* Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

* Network monitoring software to detect abnormal traffic patterns

* An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity incident and integrate your analysis into a general security strategy:

* Identify security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 

* Protect internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 

* Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 

* Respond to contain, neutralize, and analyze security incidents; implement improvements to the security process. 

* Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident.


### Summary
The company faced a security incident when all network services suddenly went offline. The cybersecurity team identified the cause as a distributed denial of service (DDoS) attack, with a flood of incoming ICMP packets triggering the disruption. In response, the team swiftly took action by blocking the attack and temporarily suspending non-essential network services to prioritize the restoration of critical network functions.

### Identify
The company fell victim to a malicious actor or group who launched an ICMP flood attack, impacting the entire internal network. It became imperative to safeguard and recover all vital network resources, ensuring they were back in full operation.

### Protect
The cybersecurity team put a new plan into action: they introduced a firewall rule to control the influx of ICMP packets and deployed an IDS/IPS system to scrutinize and filter out specific ICMP traffic exhibiting suspicious traits.

### Detect
The cybersecurity team set up source IP address verification on the firewall to validate incoming ICMP packets and detect any spoofed IP addresses. Additionally, they deployed network monitoring software to spot unusual traffic patterns and act accordingly.

### Respond
For future security events, the cybersecurity team will isolate affected systems to prevent further disruption to the network. They will attempt to restore any critical systems and services that were disrupted by the event. Then, the team will analyze network logs to check for suspicious and abnormal activity. The team will also report all incidents to upper management and appropriate legal authorities, if applicable.

### Recover
To recover from a DDoS attack by ICMP flooding, access to network services need to be restored to a normal functioning state. In the future, external ICMP flood attacks can be blocked at the firewall. Then, all non-critical network services should be stopped to reduce internal network traffic. Next, critical network services should be restored first. Finally, once the flood of ICMP packets have timed out, all non-critical network systems and services can be brought back online.
