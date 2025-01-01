<h1>Cyber Kill Chain Steps</h1>
<h2> Author: Isaac Ijuo </h2>
<p>The Cyber Kill Chain is a framework that outlines the steps adversaries typically follow to execute a successful cyber attack. It was developed by Lockheed Martin, this model breaks down the attack process into seven distinct phases, each representing a critical stage in the lifecycle of a cyber intrusion.

<img src="/Images/cyberchain.jpeg"><br>
By understanding the sequential nature of these steps, organizations can identify and disrupt an attack at any stage, preventing further progression. The Cyber Kill Chain serves as a guide for security teams to recognize adversary behavior, implement countermeasures, and fortify defenses.</p>

The seven Cyber Kill Chain steps are: 
<ol type ="a">
<li>Reconnaissance</li>
<li>Weaponization</li>
<li>Delivery</li>
<li>Exploitation</li>
<li>Installation</li>
<li>Command & Control (C2)</li>
<li>Actions on Objectives</li>
</ol>

<h2> Step 1: Reconnaissance </h2>
<p>Reconnaissance is the initial phase of the Cyber Kill Chain, where attackers gather information about their target to better understand the attack surface. This step is crucial as it lays the groundwork for subsequent actions in the attack sequence.

During reconnaissance, the attacker seeks to find out details using social engineering, phishing or whatever heps them find out about the target's systems, infrastructure, and personnel. The more information obtained, the more effectively the attacker can plan the attack.</p>

<h3><b>Types of Reconnaissance:</b></h3>
<p>The techniques employed at this stage may be divided into two subcategories:</p>
<ol type="i">
<li><b>Passive Reconnaissance:</b></li>

<p> Using this style, threat actors collect information
 indirectly without interacting with the target system. Examples include using web archives, 
public records, or online databases to retrieve outdated or 
publicly accessible information.</p>

<li><b>Active Reconnaissance:</b></li>

<p>The attacker directly interacts with the target system to gather data.
Examples include sending requests to a web server to uncover version details 
or probing for vulnerabilities.</p>

<h3><b>Activities Performed by the Adversary:</b></h3>
<p>The attacker can gather information from a variety of 
sources using a variety of approaches during the 
"Reconnaissance" process. At this phase, the attacker can 
perform the following operations:</p>

- Identifying server and software versions.
- Gathering open-source information about the organization.
- Harvesting employee email addresses or personal data from social media.
- Detecting internet-connected devices and their vulnerabilities.
- Mapping IP address blocks and identifying vendor relationships.

<h3><b>Defensive Measures:</b></h3>
<p>Organizations can mitigate the risk during this phase by 
limiting the information available to potential attackers. 
Defensive actions include:</p>

- Conducting external penetration tests to identify information leaks.
- Monitoring for organizational data breaches using threat intelligence tools.
- Removing sensitive documents from public access.
- Employing armor/firewalls and security solutions to protect internet-facing assets.
- Promptly applying updates and patches to eliminate vulnerabilities.

<img src="/Images/cyberchains.jpeg">

<h2> Step2: Weaponization</h2>
<p>The Weaponization stage is the second critical step in the 
Cyber Kill Chain. At this point, the attacker utilizes the 
information gathered during the reconnaissance phase to craft 
or acquire the tools necessary for the intended attack. 
Whether leveraging existing tools or developing custom 
exploits, the preparation at this stage is tailored to the 
specific attack type. For instance, in a phishing attack, 
the attacker might exploit a known vulnerability or create
 malicious email content to deceive the target. 
 Despite the intricate preparations, the victim often remains 
 unaware of any malicious activity during this stage, 
 as the attack has not yet been initiated.</p>

 <h3><b>Activities of the Adversary:</b></h3>
 <p>During the weaponization process, attackers work meticulously to build or refine their attack strategies. Common activities include:</p>

- Crafting malware specific to the target system. For example in the Bangladesh $1 Billion attack.
- Developing exploits to take advantage of identified vulnerabilities.
- Designing malicious content for phishing attempts, such as a convincing email template or an infected attachment.
- Selecting and configuring the most effective tools for the attack.

<h3><b>Defensive Measures:</b></h3>
<p>

- Periodically scanning systems for known vulnerabilities to address weak points promptly.
- Ensuring systems are updated with the latest security patches to close exploitable gaps.
- Studying the behavior of newly developed or identified attack tools to prepare defenses and quickly detect their use.</p>

<h2> Step 3: Delivery </h2>
<p>The Delivery phase is the third step in the Cyber Kill Chain. At this stage, the attacker initiates the cyber attack, executing the plans laid out in the preceding phases. This step involves the first direct interaction with the victim systems, as malicious content or tools are delivered to the target environment. For example, malware might be hosted on a server, and the victim unknowingly downloads it onto their system. The delivery methods can vary widely based on the nature of the attack, ranging from email-based phishing to more sophisticated tactics like direct server uploads. Or even a system hyjacking like the Bangladesh heist.</p>

<h3><b>Activities of the Adversary:</b></h3>
<p> In this stage, attackers employ diverse strategies to deliver their payload to the victim. Common tactics include:

- Embedding a malicious URL in an email and enticing the victim to click it.
- Sending malware as a file attachment in an email.
- Hosting malware on a website and tricking the victim into downloading it.
- Distributing malicious links or files through social media platforms.
- Directly uploading malware to a target server, if the server is accessible.
- Physically planting malware using a USB device or similar tools at the work premises using trailing or other techniques.

The choice of delivery method often hinges on the attack’s complexity, the level of access already achieved, and the attacker’s understanding of the victim’s behavior and systems.</p>

<h3><b>Defensive Measures:</b></h3>
<p>Organizations and individuals can adopt these strategies:

- Encourage users to critically evaluate URLs in emails and test them in sandbox environments before clicking.
- Utilize robust antivirus tools to scan email attachments for malicious content.
- Implement advanced email security systems to filter potential threats.
- Provide regular information security training to employees to raise awareness of common delivery tactics like phishing.
- Continuously monitor server access logs for unusual activity.
- Ensure firewalls are effectively configured and actively managed.
- Conduct detailed analyses of suspicious activities and trace the root causes.
- Maintain a clear protocol for handling detected threats to minimize potential damage.</p>

<img src="/Images/securenetwork.jpeg">

<h2> Step 4: Exploitation</h2>
<p>The Exploitation stage is the fourth critical step in the Cyber Kill Chain. This phase marks the activation of the malicious content delivered to the target in the previous step. The attacker attempts to exploit vulnerabilities in the victim’s system, executing malware or exploiting weaknesses in software, hardware, or operating systems. Success at this stage is a extremely necessary for advancing to the later phases of the attack. If the exploitation fails, the attacker’s entire operation is effectively thwarted, halting their progress.

This step represents a pivotal moment where the attacker transitions from preparation to action. The exploit serves as the gateway to deeper access, laying the foundation for subsequent malicious activities.</p>

<h3><b>Activities of the Adversary:</b></h3>
<p>At this stage, attackers utilize their understanding of the target's environment and execute their carefully crafted tools. Common adversary actions include:</p>

- Executing exploits targeting hardware vulnerabilities.
- Exploiting software or operating system vulnerabilities.
- Running malware to establish control or further compromise the system.

Often, the attacker’s success depends heavily on the precision and compatibility of their tools with the victim’s system. Failure here forces the attacker back to earlier stages, seeking alternative methods or targets. And that's also dependent on the security network of the organization.

<h3><b>Defensive Measures:</b></h3>
<p>Defending against exploitation is a complex and resource-intensive endeavor for security teams, particularly when facing previously unknown (zero-day) exploits. However, organizations and individuals can adopt these strategies:

- Train employees to recognize and handle potentially dangerous files, emphasizing caution when opening unfamiliar attachments or links.
- Employ monitoring systems to detect unusual activity or anomalies in real time.
- Track and address known vulnerabilities by implementing monitoring rules and patching systems as updates become available.
- Utilize Endpoint Detection and Response (EDR) solutions to monitor and respond to endpoint activity.
- Provide software developers with secure practices and coding training to minimize vulnerabilities in applications.
- Conduct frequent penetration tests to identify weaknesses and assess the effectiveness of current defenses.
- Use automated tools to regularly scan for vulnerabilities and review reports for security insights.
- Enforce strict access controls, granting each account only the minimum privileges necessary for their role.

<h2>Step 5: Installation </h2>
<p>The Installation phase is the fifth step in the Cyber Kill Chain. At this stage, the attacker aims to secure persistent access to the compromised system by installing backdoors, malware, or other tools. Recognizing that the exploited vulnerability may eventually be patched, the attacker establishes alternate methods to maintain control, such as leveraging privilege escalation to access high-level user accounts. This step is critical in preparing the groundwork for achieving the attacker’s ultimate objectives.</p>

<h3><b>Activities of the Adversary:</b></h3>
<p>In the Installation phase, attackers focus on actions that ensure ongoing access while minimizing detection. Common activities include:

- Installing malware or backdoors on the victim’s device.
- Placing web shells on compromised servers.
- Adding services, firewall rules, or scheduled tasks to sustain persistence.
- Executing privilege escalation techniques to gain higher levels of system access.

By remaining private and invisible, attackers aim to extend their presence and operate without interruption, positioning themselves for later stages of the attack.</p>

<h3><b>Defensive Measures:</b></h3>
<p>At this stage, Blueteams must shift to a Threat Hunting mindset, assuming attackers are already present and actively working within the system. Effective defensive strategies include:

- Continuously monitor all organizational assets for suspicious activity.
- Track configuration changes and detect anomalies on endpoints.
- Have setups that ensure certain data are stored offline.
- Limit access to critical files and paths, monitoring for unauthorized access attempts.
- Allow admin privileges only when absolutely necessary, enforcing strict access controls.
- Identify and block unauthorized processes or unsigned executables.
- Investigate unusual system activities and determine their root cause </p>

<h2> Step 6: Command and Control (C2)</h2>
<p>The Command and Control (C2) stage is the sixth step in the Cyber Kill Chain. At this point, the attacker has established a communication channel between the compromised system and a remote C2 server. This connection enables the attacker to send commands to the target system, laying the groundwork for executing their malicious objectives in subsequent stages.</p>

<h3><b>Activities of the Adversary:</b></h3>
<p>In this phase, the attacker focuses on enabling and maintaining communication with the C2 server. Actions include:</p>

- Configuring the C2 server to interact with the victim’s system.
- Modifying the victim’s device to ensure successful communication with the C2 infrastructure.

<h3><b>Defensive Measures:</b></h3>
<p>While direct actions to stop C2 communication at this stage can be challenging, Blueteams can adopt proactive monitoring and detection practices to mitigate the risk. Key strategies include:</p>

- Scan systems for known C2 tools and suspicious software and identify the vulnerabilities.
- The security team can use Cyber Threat Intelligence to identify and block C2 server IPs via security systems like firewalls.
- Continuously monitor network traffic for signs of C2 communication, such as irregular patterns or connections to unknown domains.

<img src="/Images/chainscyber.jpeg">

<h2> Step 7: Actions on Objectives </h2>
<p>The Actions on Objectives phase is the seventh and final step of the Cyber Kill Chain. At this stage, the attacker executes the ultimate goals of their operation, leveraging the groundwork laid during the previous phases. Each preceding step must have been successfully completed for the attacker to reach this point, allowing them to conduct malicious actions with precision and intent.</p>

<h3><b>Activities of the Adversary:</b></h3>
<p>The attacker’s actions during this phase are guided by their motives, whether it’s financial gain, data theft, sabotage, or espionage. Typical activities include:

- Encrypting files on the system using ransomware.
- Exfiltrating sensitive information or documents.
- Deleting or corrupting critical system data to cause damage.
- Expanding the scope of the attack through privilege escalation or lateral movement to other network devices.
- Harvesting credentials for further access.
- Altering or manipulating data within the system.

At this stage, the attacker’s impact is most visible, and their ultimate objectives come into sharp focus.</p>

<h3><b>Defensive Measures:</b></h3>
<p>Defenders must respond swiftly and decisively at this critical stage to mitigate damage and disrupt the attacker’s operations. Essential actions include:

- Detect anomalies that may indicate exfiltration or unauthorized activity.
- Limit and monitor access to critical files, folders, and databases to prevent unauthorized actions.
- Deploy Data Loss Prevention (DLP) tools/API to block sensitive information from leaving the organization.
- Regularly monitor user activities for unauthorized access or suspicious behavior.
- Tighten controls on network access to external resources and scrutinize all outgoing traffic.

Timely detection and intervention are vital at this stage to limit the attacker’s impact and secure the organization’s assets. </p>

<h2> Conclusion</h2>
<p>The Cyber Kill Chain provides a structured way to understand and combat cyber attacks, breaking them down into distinct phases that attackers follow to achieve their objectives. By addressing each step proactively, defenders can disrupt an attack at any point, minimizing damage and safeguarding critical assets.</p>


