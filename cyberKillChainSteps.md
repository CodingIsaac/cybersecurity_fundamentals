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

<h2> Step 1: RECONNAISSANCE </h2>
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

<img src="">

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
