
# Summarizing Fundamental Security Concepts

    Confidentiality: Ensures sensitive information remains shielded and access is granted only to authorized users.

    Integrity: Ensures data remains unaltered and trustworthy.

    Availability: Guarantees that digital assets and services are accessible when needed.

    Non-repudiation: Ensures that actions cannot be denied.

    Authentication, Authorization, and Accounting (AAA): Key principles for managing user access.

 A process that companies use to confirm that only the right people, services, and apps with the right permissions can get organizational resources. Take the iPhone, for example. Unlocking the early versions required a multi-digit passcode. Then Apple introduced Touch ID, which would unlock the phone with a fingerprint reader. The latest version, just out, is the iPhone X, which can use its camera to perform facial recognition to authenticate a user.
  
### Password-based authentication

     Password-based authentication is the most common form of authentication. Many apps and services require people to create passwords that use a combination of numbers, letters, and symbols to reduce the risk that a bad actor will guess them. However, passwords also create security and usability challenges. It’s difficult for people to come up with and memorize a unique password for each of their online accounts, which is why they often reuse passwords. And attackers use many tactics to guess or steal passwords or lure people into sharing them unwillingly. For this reason, organizations are moving away from passwords to other more secure forms of authentication.

### Certificate-based authentication

 Certificate-based authentication is an encrypted method that enables devices and people to identify themselves to other devices and systems. Two common examples are a smart card or when an employee’s device sends a digital certificate to a network or server.

 ### Biometric authentication

    In biometric authentication, people verify their identity using biological features. For example, many people use their finger or thumb to sign in to their phones, and some computers scan a person’s face or retina to verify their identity. This type of authentication is increasingly popular because it’s easy for people—they don’t have to memorize anything—and it’s difficult for bad actors to steal, making it more secure than passwords.
 
 ### Token-based authentication

   In token-based authentication both a device and the system generate a new unique number called a time-based one-time PIN (TOTP) every 30 seconds. If the numbers match, the system verifies that the user has the device.

### One-time password
   
      One-time passwords (OTP) are codes generated for a specific sign-in event that expire shortly after they’re issued. They are delivered via SMS messages, email, or a hardware token.

### Multifactor authentication

     One of the best ways to cut down on account compromise is to require two or more authentication methods, which may include any of the previously listed methods. An effective best practice is to require any two of the following:

  * Something the user knows, typically a password.
  * Something they have, such as a trusted device that is not easily duplicated, like a phone or hardware token.
  * Something the user is, like a fingerprint or face scan.

## Gap analysis: Identifies security weaknesses

</table> A security vulnerability is an unintended characteristic of a computing component or system configuration that multiplies the risk of an adverse event or a loss occurring either due to accidental exposure, deliberate attack, or conflict with new system components. A vulnerability can be fixed using a software patch, reconfiguration, user training, firmware update, or hardware replacement.

* Code vulnerabilities creep in right at the time of software development. There might be logical errors that lead to security flaws.
* The software might inadvertently transfer sensitive data without encryption, or even if it uses randomized encryption strings, they aren’t random enough.
* Ideally, all of these vulnerabilities should be picked up and patched during testing. But if not, could lead to potential data breaches.

### Misconfigured system components

</table> Misconfigurations are another common error when setting up enterprise IT systems. At the very basic level, for example, the administrator might forget to switch from a software’s default configurations, thereby leaving the system open to vulnerabilities. Incorrectly configured cloud systems, network misconfigurations, hurriedly set up Wi-Fi environments, and even the failure to restrict non-work device usage could exponentially multiply your risk exposure. Fortunately, these vulnerabilities are relatively easy to fix – they are typically the result of an overburdened IT team, requiring the intervention of extra hands, preferably a managed services provider. 

### Trust configurations

</table> Trust configurations refer to the allowances you make for data exchange to and from software and hardware systems. For example, a mounted hard disk might be able to read sensitive data from a computing client without necessitating any extra privileges. Trust relationships may exist between active directories and account records, leading to unmitigated data flow between sources that aren’t constantly monitored.

* Once an attacker gains access to a compromised system, they can exploit these trust configuration vulnerabilities to spread the infection from the original system and bring down your entire IT environment. 

## Zero Trust: A security model that assumes no trust by default.

</table> Zero Trust is a security concept that assumes no trust by default, whether access attempts come from within or outside a network's perimeters. It requires every user and device to be verified and authorized before gaining access to network resources. This strict verification helps prevent data breaches by ensuring that trust is never assumed, regardless of the origin of the access attempt. By not assuming trust and requiring continuous verification, Zero Trust minimizes unauthorized access and potential internal and external threats. Organizations benefit through enhanced security, compliance with regulatory requirements, and reduced risk of data breaches.

* Zero Trust means no trust is assumed by default and verification is required from everyone.
* It enhances security by requiring stringent verification for every access attempt.
* This approach helps prevent breaches by ensuring no implicit trust is given.
* Zero Trust is technology-agnostic and applies to all network resources.

</table> Zero Trust operates on the principle that both internal and external threats exist at all times, making it essential to verify everything trying to connect to the system before granting access. Here's a deeper dive into the workings and benefits of Zero Trust:

### Principles of Zero Trust

* No implicit trust: Trust is not assumed based on location (inside or outside the network).
* Least privilege access: Users are granted the minimum access necessary for their tasks.
* Microsegmentation: The network is divided into secure zones, and users must be authorized to access each zone.
* Multi-factor authentication (MFA): MFA is mandatory, enhancing security by adding multiple layers of verification.

### Benefits of Zero Trust

* Enhanced security: By verifying every access attempt, Zero Trust minimizes the potential for unauthorized access and breaches.
* Reduced attack surface: Microsegmentation and least privilege access reduce the number of vulnerable points.
* Compliance: Zero Trust helps organizations meet stringent regulatory requirements by providing robust security controls.

## Physical security: Protects against physical threats.

</table> A physical threat is a potential cause of an incident that can result in loss or physical harm to the computer systems. Physical security is represented as the security of personnel, hardware, programs, networks, and data from physical situations and events that can support severe losses or harm to an enterprise, departments, or organization.Physical threat to a computer system can be as an outcome of loss of the entire computer system, damage of hardware, damage to the computer software, theft of the computer system, vandalism, natural disaster including flood, fire, war, earthquakes etc.

### Unauthorized Access

</table> One of the most common security risks regarding computerized information systems is the hazard of unauthorized access to confidential information .The main concern appears from unwanted intruders, or hackers, who use the current technology and their skills to divide into supposedly secure computers or to exhaust them. A person who gains access to data system for malicious reason is often termed of cracker instead of a hacker.

### Computer Viruses

</table> Computer virus is a type of nasty application written deliberately to enter a computer without the user’s permission or knowledge, with an ability to duplicate itself, therefore continuing to spread. Some viruses do small but duplicate others can cause severe harm or adversely influence program and implementation of the system.

## Vandalism

</table> Deliberate damage cause to hardware, software and data is treated as serious threat to information system security. The threat from destruction lies in the fact that the organization is temporarily refused access to someone of its resources. Even relatively minor damage to an element of a system can have an essential effect on the organization as a whole.

## Accidents

</table> Accidental misuse or damage will be influenced over time by the attitude and disposition of the staff in addition to the environment. Human errors have a higher impact on information system security than do manmade threats caused by purposeful attacks. But most accidents that are serious threats to the security of information systems can be diminished.

## Deceptive and disruption technology: Techniques to mislead or disrupt attackers.

</table> Deception technology is a strategy to attract cyber criminals away from an enterprise's true assets and divert them to a decoy or trap. Deception technology enables defenders to identify a wide variety of attack methods without relying on known signatures or pattern matching. Deception technology is available as a full deception fabric or platform, as features within a broader platform and as independent solutions. Advanced deception platforms use machine learning for fast and accurate deployment and operations without disrupting other network functions (Honeynet, Honeypot, Honeyfile, and Honeytoken)

### Honeypots

</table> Honeypots are computer systems designed as decoys to trick threat actors into believing they’re infiltrating a legitimate target. These strategically crafted traps play an important role in cybersecurity research, enabling experts to gain valuable insights into cyberattacks and the tactics employed by threat actors. By enticing and luring threat actors, honeypots allow organizations to proactively identify, evaluate, and deflect attempts to breach their actual systems.

### Honeynets

</table> Honeynets are decoy networks comprised of interconnected honeypots and seemingly authentic systems and data. Cybersecurity teams use honeynets to study how threat actors operate on a larger scale. Organizations can strengthen their defenses and proactively safeguard their assets by analyzing exploits that threat actors leverage against entire networks. 

#### How do Honeynets Work?

</table> Honeypots deliberately incorporate security vulnerabilities like weak passwords and software flaws. Mirroring authentic systems, honeypots mimic organizations’ billing systems, operating systems holding seemingly sensitive data, web applications, and other common targets. Gathering substantial evidence of attacks, honeypots reveal tactical insights, such as indicators of compromise, intrusion techniques, lateral movement sequences, details of attacker tools, and more. This information’s comprehensive analysis enables organizations to enhance their security defenses proactively. There are three types of honeypots:

   1. Email Honeypot
Email honeypots are decoy email addresses created to attract spam and phishing attempts. Emails received at these fake email addresses can be analyzed to understand spam trends and behaviors and identify potential threats.

   2. Malware Honeypot
These are systems designed to capture various types of malware, such as worms, trojans, viruses, and more. Malware honeypots mimic vulnerable systems to entice threat actors into targeting them, providing cybersecurity experts with insights on attack executions and new malware variants.

   3. Database Honeypot
Database honeypots are crafted databases made to appear as valuable targets to potential malicious actors. They contain seemingly authentic data and resources to lure attackers, which enables organizations to detect and study data breaches and infiltration attempts.

### Benefits

</table> Cyber deception complements existing security controls by detecting discovery, lateral movement, privilege escalation and collection activities that other tools are not designed to address. The technology is highly scalable, which allows it to protect an ever-evolving attack surface. Many of the attack activities that deception provides visibility to are traditionally challenging to detect. The ability to deceive, direct, and guide the adversary away from critical assets denies them their goals and reveals how they want to move through the networks. It also holds the benefit of increasing the attacker’s cost, because they must now decipher what is real from what is fake and forces them to restart their attacks.