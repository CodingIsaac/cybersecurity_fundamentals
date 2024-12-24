<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="Isaac Ijuo">
    <meta name="The Role of Security Controls in Protecting Customer Data">
    <meta name="What are Security Controls.">
    <meta name="Ercyption, Authorization, Authentication">
</head>
<body>

<h1>The Role of Security Controls in Protecting Customer Data</h1>
<h2> Author: Isaac Ijuo</h2>
<p>It will interest you to know that just in 2023, data breaches increased by over 20% when compared to the previous year. The number of people affected by ransomware attacks doubled globally, and by 77% in the Middle East alone. According to a research conducted by Cybersecurity Ventures it was reported that there were more than 2,200 cyberattacks every day, or one every 39 seconds. This alarming acceleration from the 44-second interval in 2022 highlights the growing sophistication of cyber threats and their ability to bypass traditional defenses. And it makes it seem that organization are helpless in the hands of cyber exploiters.

It then begs the question: what can organizations do to protect themselves and the data users have entrusted to them? While there are many strategies, a foundational approach lies in implementing proper Security Controls.

These malicious trends highlight the necessity for more effecrtive security measures of which security controls is one them. To note, security controls are essential for mitigating risks and preserving sensitive information and businesses must use best practices to implement them. 

In this article addresses the three critical security controls; encryption, authentication, and authorization and their significance in safeguarding customer data.<br><br>
<img src="/Images/securityGarden.jpeg">

<h2><b> What are Security Controls</b></h2>
<p> In simple terms, security controls are protections intended particularly to reduce the risks associated with cyber threats. These controls provide a critical basis for enterprises to protect sensitive data such as financial information, personal data, communication, and healthcare records from cybercrime, identity theft, and social engineering.


<h2><b>The Three Common Types of Security Controls</b></h2>
<p> </p>
<ol type="a">
<li><b>Encryption:</b>
<p> On one hand, to keep data safe from people who should not have access to it, <b><i>encryption</i></b> changes data from a style that can be read (plaintext) to one that cannot (ciphertext). On the otherhand, decryption does the opposite of this to get back to the original info. This protects the privacy and accuracy of private data while it is being stored and sent.
<h3><b>Forms of Encryption and Drawbacks:</b></h3>
<ol type="i">
<li><b>Symmetric Encryption:</b>
<p> In symmetric encryption, the key used to encrypt and decode data remains unchanged from one operation to the next. Particularly for protecting massive amounts of data, its speed and efficiency make it a popular choice. The most widely used symmetric encryption algorithm nowadays is Advanced Encryption Standard (AES), although Data Encryption Standard (DES), an earlier algorithm that was mostly discontinued because of security flaws, is another example. <br>
It is also nice to mention that symmetric encryption offers many benefits, but it has a major downside: it can be very tough to securely distribute and manage keys, particularly in big networks. The encrypted data becomes susceptible to unauthorized access in the event that the key is intercepted or mishandled.</p>
</li>
<li><b>Asymmetric Encryption:</b>
<p>In contrast to symmetric techniques, asymmetric encryption employs a pair of keys: a private key for decryption and a public key for encryption. This method is perfect for applications like digital signatures and secure communication channels because it improves security by doing away with the requirement to share a single key. <br>
Reputable for their strong security, RSA (Rivest-Shamir-Adleman) and ECC (Elliptic Curve Cryptography) are common instances of asymmetric encryption. Asymmetric encryption is less appropriate for encrypting big datasets or real-time applications, though, because it requires more computing power and operates far more slowly than symmetric encryption.</p>

</li>
<li><b>End-to-End Encryption:</b>
<p>End-to-end encryption ensures that data is encrypted on the sender's device and decoded only on the recipient's device, providing high privacy for conversations. This mechanism is used in popular messaging apps such as WhatsApp and Signal, which use protocols like the Signal Protocol. While end-to-end encryption effectively protects message content from interception, it does not protect metadata (such as sender and recipient information) and cannot prevent assaults on endpoints, leaving some gaps in the communication chain.</p>

</li>
<li><b>Hashing (One-Way Encryption):</b>
<p>Hashing is the process of converting data into a fixed-length hash value that cannot be returned to its original form. This type of encryption is commonly used for data integrity verification, such as password storage and file authentication. Popular hashing methods include SHA-256, which is regarded secure, and MD5, which is no longer recommended due to collision problems. While hashing is useful for validation, it is not suited for instances in which the original data must be recovered, limiting its application to specific use cases.</p>

</li>
</ol>

<h3> Best Practices: </h3>

- Make use of current industry standards with adequate key lengths, such as AES-256 or RSA.
- Controlled access, key rotation procedures, and secure key storage should be put into place.
- Ensure that sensitive data is encrypted at every stage, from transmission to storage.
- It is necessary to maintain up-to-date cryptographic libraries is essential for reducing security risks.
- Carry out audits of encryption on a regular basis to check for compliance and fix vulnerabilities.

</li>
<img src="/Images/encryption.jpeg"><br>

<li><b>Authentication:</b>
<p>
Prior to allowing access to resources, authentication ensures that people or systems are who they claim to be.
</p>
<h3> <b> Multiple Forms of Authentication</b></h3>
<p>It is worth mentioning that, authentication procedures can range from simple ways like combining a username and password to more complicated options like Multi-Factor Authentication (MFA). MFA improves security by requiring three types of verification: something you know (password or PIN), something you have (security tokens or one-time codes), and something you are (biometric data such as fingerprints, facial recognition, or iris scans). And other advanced authentication mechanism which will be discussed briefly. These layers provide a strong protection against unwanted access.
</p>
<ol type="i">
<li><b> Something you Know</b> </li>
<p>This type of authentication uses knowledge-based credentials, such as passwords or PINs. It is among the oldest and most widely used authentication mechanisms. For example, while login onto a website, a person must provide a password to prove their identity. While effective as an initial layer of defense, this strategy is vulnerable to phishing and brute force attacks, particularly if users choose weak or easily guessable passwords.
 </p>
<li>Something you Are</li>
<p>Biometric authentication uses unique physical or behavioral characteristics to validate identification. This usually includes Fingerprint scanning, face recognition, and iris scanning. For example, many current smartphones include fingerprint sensors that enable users to unlock their devices. While biometrics are handy and difficult to copy, they are not perfect and might be vulnerable to social engineering attacks like vishing (voice phishing).
</p>
<li>Something you Have</li>
<p>In this category, authentication involves the ownership of a real or digital device or item. Examples include hardware tokens, one-time passcodes (OTPs), and authentication software such as Google Authenticator. For example, while using online banking, consumers may be asked to input a code received to their mobile device. While this strategy increases security, it is vulnerable if the token is lost or stolen, or if SIM-swapping attacks occur.
</p>
</ol>
<h3> <b>Additional Types of Authentication </b></h3>

1. MultiFactor Authentication (MFA):<br>
To increase security, MFA uses two or more authentication elements, such as a password and a fingerprint. For instance, a business network may demand a PIN plus an app-generated security code. Multiple verification methods decreases the risk of illegal data access. 

2. Logic Conditional Access: <br>
Before allowing access, this technique considers location, device type, and user behavior. For instance, a company's system may reject a login from an unidentified device or location. Logical access is useful in preventing remote access, but it requires sophisticated monitoring systems to understand access patterns.

3. Adaptive Authentication:<br>
This approach dynamically modifies authentication requirements by risk. A low-risk login from a trusted device may merely require a password, whereas a high-risk attempt from a foreign IP address may require OTPs or biometric scans. 

4. Behavioral Biometrics:<br>
This subclass of biometric authentication evaluates user behavior including typing speed, mouse movements, and walking patterns. For instance, Financial organizations may monitor user behavior to detect fraud. Despite being novel, behavioral biometrics create privacy problems and need large computing resources.

5. Passwordless Authentication: <br>
Biometrics, cryptographic keys, or device-based authentication replace passwords in this growing method. Users can authenticate by scanning a pre-registered QR code with their smartphone. Passwordless solutions are convenient and eliminate password repetition, but they need widespread use of suitable technologies. An Example of Passwordless Authentication is Microsoft's Windows Hello, FIDO2 keys.

Best Practices:
- At the Organizational level, activate Multi-Factor Authentication (MFA) policy to provide additional levels of security.
- Enforce users to generate strong, unique passwords and avoid using them across several sites.
- Adopt passwordless authentication techniques, such as biometrics or hardware security keys for defence indept.
- Implement logical access restrictions that consider elements such as location and device before giving access.
- To address developing security vulnerabilities, keep authentication systems up to date and patched on a regular basis.
- To prevent credential theft, teach users how to recognize and avoid phishing attacks.
- Regularly monitor authentication records for questionable login attempts and respond accordingly.

</ol>
