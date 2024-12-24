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
<p> In simple terms, security controls are protections intended particularly to reduce the risks associated with cyber threats. These controls provide a critical basis for enterprises to protect sensitive data such as financial information, personal data, and healthcare records from cybercrime, identity theft, and social engineering.

<h2><b>The Three Common Types of Security Controls</b></h2>
<p> </p>
<ol type="a">
<li><b>Encryption:</b>
<p> On one hand, to keep data safe from people who should not have access to it, <b><i>encryption</i></b> changes data from a style that can be read (plaintext) to one that cannot (ciphertext). On the otherhand, decryption does the opposite of this to get back to the original info. This protects the privacy and accuracy of private data while it is being stored and sent.
<h3><b>Forms of Encryption and Drawbacks:</b></h3>
<ol type="i">
<li><b>Symmetric Encryption</b>
<p> In symmetric encryption, the key used to encrypt and decode data remains unchanged from one operation to the next. Particularly for protecting massive amounts of data, its speed and efficiency make it a popular choice. The most widely used symmetric encryption algorithm nowadays is Advanced Encryption Standard (AES), although Data Encryption Standard (DES), an earlier algorithm that was mostly discontinued because of security flaws, is another example. <br><br>
It is also nice to mention that symmetric encryption offers many benefits, but it has a major downside: it can be very tough to securely distribute and manage keys, particularly in big networks. The encrypted data becomes susceptible to unauthorized access in the event that the key is intercepted or mishandled.</p>
</li>
<li><b>Asymmetric Encryption</b>
In contrast to symmetric techniques, asymmetric encryption employs a pair of keys: a private key for decryption and a public key for encryption. This method is perfect for applications like digital signatures and secure communication channels because it improves security by doing away with the requirement to share a single key. <br><br>
Reputable for their strong security, RSA (Rivest-Shamir-Adleman) and ECC (Elliptic Curve Cryptography) are common instances of asymmetric encryption. Asymmetric encryption is less appropriate for encrypting big datasets or real-time applications, though, because it requires more computing power and operates far more slowly than symmetric encryption.

</li>
<li><b>End-to-End Encryption</b>
End-to-end encryption ensures that data is encrypted on the sender's device and decoded only on the recipient's device, providing high privacy for conversations. This mechanism is used in popular messaging apps such as WhatsApp and Signal, which use protocols like the Signal Protocol. While end-to-end encryption effectively protects message content from interception, it does not protect metadata (such as sender and recipient information) and cannot prevent assaults on endpoints, leaving some gaps in the communication chain.

</li>
<li><b>Hashing (One-Way Encryption)</b>
Hashing is the process of converting data into a fixed-length hash value that cannot be returned to its original form. This type of encryption is commonly used for data integrity verification, such as password storage and file authentication. Popular hashing methods include SHA-256, which is regarded secure, and MD5, which is no longer recommended due to collision problems. While hashing is useful for validation, it is not suited for instances in which the original data must be recovered, limiting its application to specific use cases.

</li>
</ol>
</li>
<img src="/Images/encryption.jpeg">
</ol>
