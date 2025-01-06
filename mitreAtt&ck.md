<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Explore the detailed breakdown of MITRE ATT&CK Tactics and Techniques for Enterprise, Mobile, and ICS environments. Understand how adversaries operate and learn effective defensive strategies.">
    <meta name="keywords" content="MITRE ATT&CK, Cybersecurity, Tactics, Techniques, Enterprise Security, Mobile Security, ICS Security, Threat Intelligence, Cyber Defense">
    <meta name="author" content="Isaac Ijuo, Cybersecurity Expext">
    <meta name="Isaac Ijuo" content="Mitre Attack, Isaac Ijuo">
    
<body>
<h1> Understanding and Building Resilient Cyber Defenses with the MITRE ATT&CK Framework.</h1>
<h2> Author: Isaac Ijuo </h2>
<p>The MITRE ATT&CK framework is short for Adversarial Tactics, Techniques, and Common Knowledge and it is a globally recognized knowledge base that categorizes the behaviors and method hackers use to conduct their heist. The framework was developed by MITRE, a nonprofit organization which specializes in systems engineering and cybersecurity, the framework provides a structured approach to understanding how attacks occurs and where defenses can be strengthened.

Majorly, the framework is divided into two primary components:


- Tactics: The adversary’s goals during different phases of an attack, such as reconnaissance, persistence, or lateral movement.

- Techniques: The specific methods attackers use to achieve their tactical objectives, like phishing, malware deployment, Ransomeware or credential dumping.

<h2>Key Tactics in the Framework</h2>
<p>Each tactic represents a stage in the attack lifecycle, offering insights into how adversaries operate. Some of the critical tactics include:

Reconnaissance: Gathering information about a target, such as IP addresses and employee details.
Persistence: Maintaining access through backdoors or rootkits.
Privilege Escalation: Gaining higher privileges to access critical resources.
Lateral Movement: Expanding access across a network using compromised credentials.
Impact: The ultimate damage caused, including data theft, system sabotage, or financial loss.

<p> Key Tactics </p>
<h2>Enterprise Tactics</h2>
<table>
    <thead>
        <tr>
            <th>ID</th>
            <th>Name</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>TA0043</td>
            <td>Reconnaissance</td>
            <td>Gathering information about the target.</td>
        </tr>
        <tr>
            <td>TA0042</td>
            <td>Resource Development</td>
            <td>Establishing resources for the attack.</td>
        </tr>
        <tr>
            <td>TA0001</td>
            <td>Initial Access</td>
            <td>Gaining initial entry into the target network.</td>
        </tr>
        <tr>
            <td>TA0002</td>
            <td>Execution</td>
            <td>Running malicious code on the target system.</td>
        </tr>
        <tr>
            <td>TA0003</td>
            <td>Persistence</td>
            <td>Maintaining access to the target system.</td>
        </tr>
        <tr>
            <td>TA0004</td>
            <td>Privilege Escalation</td>
            <td>Gaining higher-level permissions on the target system.</td>
        </tr>
        <tr>
            <td>TA0005</td>
            <td>Defense Evasion</td>
            <td>Avoiding detection and bypassing security defenses.</td>
        </tr>
        <tr>
            <td>TA0006</td>
            <td>Credential Access</td>
            <td>Stealing account names and passwords.</td>
        </tr>
        <tr>
            <td>TA0007</td>
            <td>Discovery</td>
            <td>Identifying information about the target network and systems.</td>
        </tr>
        <tr>
            <td>TA0008</td>
            <td>Lateral Movement</td>
            <td>Moving through the target network to other systems.</td>
        </tr>
        <tr>
            <td>TA0009</td>
            <td>Collection</td>
            <td>Gathering data of interest from the target.</td>
        </tr>
        <tr>
            <td>TA0011</td>
            <td>Command and Control</td>
            <td>Communicating with compromised systems to control them.</td>
        </tr>
        <tr>
            <td>TA0010</td>
            <td>Exfiltration</td>
            <td>Removing data from the target network.</td>
        </tr>
        <tr>
            <td>TA0040</td>
            <td>Impact</td>
            <td>Manipulating, interrupting, or destroying systems and data.</td>
        </tr>
    </tbody>
</table>

<h2>Mobile Tactics</h2>
<table>
    <thead>
        <tr>
            <th>ID</th>
            <th>Name</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>TA0027</td>
            <td>Initial Access</td>
            <td>The adversary is trying to get into your device.</td>
        </tr>
        <tr>
            <td>TA0041</td>
            <td>Execution</td>
            <td>The adversary is trying to run malicious code.</td>
        </tr>
        <tr>
            <td>TA0028</td>
            <td>Persistence</td>
            <td>The adversary is trying to maintain their foothold.</td>
        </tr>
        <tr>
            <td>TA0029</td>
            <td>Privilege Escalation</td>
            <td>The adversary is trying to gain higher-level permissions.</td>
        </tr>
        <tr>
            <td>TA0030</td>
            <td>Defense Evasion</td>
            <td>The adversary is trying to avoid being detected.</td>
        </tr>
        <tr>
            <td>TA0031</td>
            <td>Credential Access</td>
            <td>The adversary is trying to steal account names and passwords.</td>
        </tr>
        <tr>
            <td>TA0032</td>
            <td>Discovery</td>
            <td>The adversary is trying to figure out your environment.</td>
        </tr>
        <tr>
            <td>TA0033</td>
            <td>Lateral Movement</td>
            <td>The adversary is trying to move through your environment.</td>
        </tr>
        <tr>
            <td>TA0034</td>
            <td>Collection</td>
            <td>The adversary is trying to gather data of interest to their goal.</td>
        </tr>
        <tr>
            <td>TA0035</td>
            <td>Command and Control</td>
            <td>The adversary is trying to communicate with compromised devices to control them.</td>
        </tr>
        <tr>
            <td>TA0036</td>
            <td>Exfiltration</td>
            <td>The adversary is trying to steal data.</td>
        </tr>
        <tr>
            <td>TA0037</td>
            <td>Impact</td>
            <td>The adversary is trying to manipulate, interrupt, or destroy your systems and data.</td>
        </tr>
    </tbody>
</table>

<h2>ICS Tactics</h2>
<table>
    <thead>
        <tr>
            <th>ID</th>
            <th>Name</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>TA0108</td>
            <td>Initial Access</td>
            <td>The adversary is trying to get into your ICS environment.</td>
        </tr>
        <tr>
            <td>TA0109</td>
            <td>Execution</td>
            <td>The adversary is trying to run malicious code or control ICS equipment.</td>
        </tr>
        <tr>
            <td>TA0110</td>
            <td>Persistence</td>
            <td>The adversary is trying to maintain their foothold in your ICS environment.</td>
        </tr>
        <tr>
            <td>TA0111</td>
            <td>Privilege Escalation</td>
            <td>The adversary is trying to gain higher-level permissions in your ICS environment.</td>
        </tr>
        <tr>
            <td>TA0112</td>
            <td>Defense Evasion</td>
            <td>The adversary is trying to avoid being detected in your ICS environment.</td>
        </tr>
        <tr>
            <td>TA0113</td>
            <td>Credential Access</td>
            <td>The adversary is trying to steal account names and passwords in your ICS environment.</td>
        </tr>
        <tr>
            <td>TA0114</td>
            <td>Discovery</td>
            <td>The adversary is trying to figure out your ICS environment.</td>
        </tr>
        <tr>
            <td>TA0115</td>
            <td>Lateral Movement</td>
            <td>The adversary is trying to move through your ICS environment.</td>
        </tr>
        <tr>
            <td>TA0116</td>
            <td>Collection</td>
            <td>The adversary is trying to gather data of interest in your ICS environment.</td>
        </tr>
        <tr>
            <td>TA0117</td>
            <td>Command and Control</td>
            <td>The adversary is trying to communicate with compromised ICS devices to control them.</td>
        </tr>
        <tr>
            <td>TA0118</td>
            <td>Inhibit Response Function</td>
            <td>The adversary is trying to prevent your ICS from responding to events.</td>
        </tr>
        <tr>
            <tr>
    <td>TA0119</td>
    <td>Impair Process Control</td>
    <td>The adversary is trying to disrupt, damage, or destroy your ICS processes.</td>
</tr>
<tr>
    <td>TA0120</td>
    <td>Impact</td>
    <td>The adversary is trying to manipulate, interrupt, or destroy your ICS systems and data.</td>
</tr>



</body>
</html>