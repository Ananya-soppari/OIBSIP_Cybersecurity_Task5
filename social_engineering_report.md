# Social Engineering Attacks

## Research Report – Security Analyst Track

**Task:** Task 5 – Social Engineering Attacks


## Table of Contents

1. Introduction
2. Phishing Attacks
   * 2.1 Overview
   * 2.2 How Phishing Works
   * 2.3 Real-World Example
   * 2.4 Impact
   * 2.5 Mitigation Strategies
3. Spear Phishing
   * 3.1 Overview
   * 3.2 How Spear Phishing Works
   * 3.3 Real-World Example
   * 3.4 Impact
   * 3.5 Mitigation Strategies
4. Whaling
   * 4.1 Overview
   * 4.2 How Whaling Works
   * 4.3 Real-World Example
   * 4.4 Impact
   * 4.5 Mitigation Strategies
5. Vishing and Smishing
   * 5.1 Vishing
   * 5.2 Smishing
   * 5.3 Impact
   * 5.4 Mitigation Strategies
6. Pretexting and Baiting
   * 6.1 Pretexting
   * 6.2 Baiting
7. Comparison of Social Engineering Attacks
   * 7.1 Security Impact and Key Defensive Measures
8. Employee Security Training Checklist
9. Conclusion
   * 9.1 Key Takeaways
10. References

## 1. Introduction

Social engineering is a type of cyberattack that uses human interaction and psychological manipulation to trick people into revealing confidential information, opening malicious links, transferring money, or performing actions that help an attacker. It is considered an effective attack vector because attackers exploit human factors such as trust, curiosity, fear, urgency, authority, and helpfulness instead of relying only on technical vulnerabilities. Social engineering can be carried out through emails, phone calls, text messages, fake websites, social media, and impersonation. Common techniques include phishing, spear phishing, whaling, vishing, smishing, pretexting, and baiting. According to the FBI's Internet Crime Complaint Center (IC3), phishing/spoofing was among the most frequently reported categories of cybercrime in its recent Internet Crime Reports, demonstrating the continuing importance of user awareness and effective security controls. Organizations therefore need both technical protections and regular employee security training to reduce the risk of credential theft, financial fraud, malware infections, and unauthorized access.

## 2. Phishing Attacks

### 2.1 Overview

Phishing is one of the most common forms of social engineering. In a phishing attack, an attacker sends a fraudulent email or message that appears to come from a trusted person, company, bank, or online service. The main purpose is to convince the victim to click a malicious link, open an attachment, provide login credentials, or share other sensitive information. Phishing attacks can target individuals as well as organizations.

Phishing can also be divided into more targeted forms. **Spear phishing** targets specific individuals, **whaling** targets senior or high-value personnel, **vishing** uses voice or telephone communication, and **smishing** uses SMS or text messages.

### 2.2 How Phishing Works

A typical phishing attack begins with the attacker creating a convincing message that looks legitimate. The message may use a trusted company logo, familiar language, or a false warning about an account problem. It may create a sense of urgency by asking the victim to verify an account, reset a password, or make a payment.

The message may contain a link leading to a fake website designed to collect usernames, passwords, banking information, or other personal details. Attackers may also use malicious attachments to install malware. In some campaigns, stolen credentials are later used to access email, cloud services, financial accounts, or internal organizational systems.

### 2.3 Real-World Example

A documented example is the **2014 Dyre banking malware campaign**, which used phishing emails to target victims. According to the U.S. Computer Emergency Readiness Team (US-CERT), attackers distributed malicious emails containing PDF attachments. When victims opened the attachments, the campaign attempted to deliver Dyre malware, which could steal banking credentials and other sensitive information. This incident demonstrates how phishing can combine social engineering with malware delivery to compromise users and financial information.

### 2.4 Impact

Phishing can result in stolen usernames and passwords, unauthorized access to email and cloud accounts, financial fraud, identity theft, and malware infections. When an employee's account is compromised, attackers may also use it to send additional phishing messages or gain access to organizational information. This can increase the damage beyond the original victim.

A successful phishing attack can therefore affect the **confidentiality, integrity, and availability** of organizational information and services.

### 2.5 Mitigation Strategies

1. **Security awareness training:** Employees should be trained to identify suspicious emails, unexpected attachments, unusual requests, misleading links, and signs of impersonation.

2. **Multi-factor authentication (MFA):** MFA provides an additional layer of protection if a password is stolen through phishing.

3. **Email and web security controls:** Organizations should use spam filtering, phishing detection, URL scanning, attachment scanning, and domain protection mechanisms to identify and block malicious messages.

4. **Verify suspicious requests independently:** Employees should confirm unusual requests for payments, credentials, sensitive information, or account changes through a separate trusted communication channel rather than replying directly to the suspicious message.


## 3. Spear Phishing

### 3.1 Overview

Spear phishing is a more targeted form of phishing in which an attacker creates a message specifically for a particular person, employee, department, or organization. Unlike general phishing campaigns that send similar messages to many people, spear phishing uses information about the intended victim to make the communication appear more believable. Attackers may use the victim's name, job role, organization, colleagues, or current activities.

### 3.2 How Spear Phishing Works

The attacker first gathers information about the target from sources such as company websites, social media, or previously exposed information. The attacker then creates a personalized email or message that appears to come from a trusted colleague, manager, customer, or business partner. The message may request confidential information, ask the victim to open a file, click a link, or perform a financial transaction. Because the message is personalized, the victim may be more likely to trust it.

### 3.3 Real-World Example

A documented example of spear phishing involved four Iranian nationals charged by the U.S. Department of Justice for a multi-year cyber campaign. The attackers used spearphishing emails and social engineering, including impersonation, to gain the confidence of targeted individuals. Their campaign was directed at organizations and individuals in the United States and other countries.

### 3.4 Impact

Spear phishing can lead to:
- Theft of usernames, passwords, and other credentials.
- Unauthorized access to organizational systems.
- Malware installation and data theft.
- Financial losses and reputational damage.

### 3.5 Prevention and Mitigation

1. **Verify suspicious requests:** Confirm unexpected requests through a separate trusted communication channel.
2. **Use multi-factor authentication (MFA):** MFA reduces the risk of account compromise even when passwords are stolen.
3. **Security awareness training:** Train employees to identify targeted phishing emails, impersonation attempts, and suspicious links.

## 4. Whaling

### 4.1 Overview

Whaling is a highly targeted form of phishing that focuses on senior or high-value individuals within an organization, such as chief executive officers, directors, managers, or finance executives. Attackers target these individuals because they often have access to sensitive information, financial systems, or authority to approve important transactions.

### 4.2 How Whaling Works

Whaling attacks usually follow these steps:

1. **Target identification:** The attacker identifies a senior executive or other high-value employee in the organization.
2. **Information gathering:** Publicly available information such as the person's name, job title, organization, and business relationships may be collected.
3. **Impersonation:** The attacker creates an email or message that appears to come from the executive or another trusted senior person.
4. **Urgent request:** The message may ask an employee to make a payment, transfer funds, share confidential information, or perform another sensitive action.
5. **Victim response:** Because the request appears to come from a senior authority, the employee may act without performing additional verification.

Whaling is particularly dangerous because it combines targeted information gathering with executive impersonation and social pressure.

### 4.3 Real-World Example

A documented example of whaling is found in Business Email Compromise (BEC) attacks, where criminals impersonate senior executives or other trusted decision-makers. In these attacks, the attacker may send a fraudulent email appearing to come from a CEO, director, or other senior employee and request an urgent payment or transfer of sensitive information. The FBI identifies executive impersonation as a common form of BEC.

### 4.4 Impact

Whaling attacks can lead to:
- Large financial losses through fraudulent payments.
- Theft of confidential business information.
- Compromise of executive or employee accounts.
- Damage to an organization's reputation.

### 4.5 Prevention and Mitigation

1. **Verify financial requests:** Confirm unusual payment or transfer requests using a separate trusted communication method.
2. **Use multi-factor authentication (MFA):** MFA helps protect accounts even if login credentials are compromised.
3. **Employee awareness training:** Train employees to recognize executive impersonation, urgent requests, and suspicious email behavior.
## 5. Vishing and Smishing

### 5.1 Vishing

Vishing, or voice phishing, is a social engineering attack carried out through phone calls or voice communication. The attacker usually pretends to be a bank employee, technical support representative, government official, or another trusted person. The victim may be pressured to provide passwords, one-time passwords (OTPs), banking details, or other confidential information.

### 5.2 Smishing

Smishing is phishing carried out through SMS or text messages. Attackers may send messages claiming that a package delivery failed, a bank account needs verification, or a service subscription requires immediate action. The message may contain a malicious link or a phone number controlled by the attacker. When the victim follows the instructions, sensitive information may be stolen or malware may be installed.

### 5.3 Impact

Vishing and smishing can result in stolen credentials, financial fraud, identity theft, unauthorized account access, and malware infections. These attacks can be particularly effective because people may trust phone calls and text messages more than suspicious-looking emails. Attackers can also create urgency by claiming that immediate action is required.

### 5.4 Mitigation Strategies

1. **Never share confidential information through unexpected calls or messages:** Banks, organizations, and legitimate service providers should be independently contacted using their official contact details.

2. **Avoid suspicious links and attachments:** Users should not click links in unexpected SMS messages or provide information on websites reached through suspicious messages.

3. **Use caller and message verification:** Users should verify the identity of callers and senders before responding to requests involving passwords, OTPs, payments, or other sensitive information.

4. **Enable multi-factor authentication:** MFA provides additional protection if credentials are stolen through vishing or smishing attacks.

## 6. Pretexting and Baiting

### 6.1 Pretexting

Pretexting is a social engineering technique in which an attacker creates a false story or identity, known as a pretext, to obtain information or convince a victim to perform an action. The attacker may pretend to be an employee, customer, IT support technician, bank representative, or another trusted person. The attacker first researches the target and then creates a believable situation that gives a reason for requesting information or access.

**Real-World Case Study:** A documented example involved Iranian attackers who impersonated trusted individuals and organizations to gain the confidence of victims. According to the U.S. Department of Justice, the attackers used social engineering, impersonation, and carefully constructed online identities to deceive victims and obtain sensitive information. This case demonstrates how attackers can create believable identities and situations to manipulate victims.

**Prevention Measures:**

1. **Verify identity independently:** Confirm unusual requests through a trusted phone number, official website, or direct communication instead of relying only on the contact information provided by the requester.
2. **Do not disclose sensitive information:** Never provide passwords, authentication codes, financial information, or confidential data simply because someone claims to be authorized.
3. **Follow verification procedures:** Organizations should require proper approval and identity verification before employees provide sensitive information or perform high-risk actions.

### 6.2 Baiting

Baiting is an attack technique that uses something attractive or interesting to persuade a victim to take an unsafe action. For example, an attacker may leave a USB drive containing malicious software in a location where employees are likely to find it. Digital baiting can also involve fake software, free downloads, media files, or other attractive content that contains malware. When the victim interacts with the bait, the attacker may gain access to the system or information.

**Real-World Case Study:** A documented example of physical baiting involved malicious USB drives being deliberately left in public places. In one reported incident, USB sticks containing malware were left in a London car park, and unsuspecting people picked them up and connected them to their computers. This demonstrates how curiosity and the desire to use a seemingly useful device can be exploited to introduce malware into a system.

**Prevention Measures:**

1. **Do not use unknown USB devices:** Employees should never connect unidentified or found USB drives to organizational computers.
2. **Control removable media:** Organizations should restrict unauthorized USB devices and use endpoint security controls to monitor removable media.
3. **Use trusted software sources:** Employees should download software and files only from approved and trusted sources and report suspicious devices or downloads to the security team.

## 7. Comparison of Social Engineering Attacks

The following table compares common social engineering attacks based on their primary target, psychological technique used, and most effective countermeasure.

| Attack Type    | Primary Target                    | Psychological Lever Exploited          | Best Countermeasure                                                  |
| -------------- | --------------------------------- | -------------------------------------- | -------------------------------------------------------------------- |
| Phishing       | General users and employees       | Urgency, fear, curiosity, and trust    | Email filtering, security awareness training, and MFA                |
| Spear Phishing | Specific individuals or employees | Personalization, trust, and authority  | Verify requests independently and use MFA                            |
| Whaling        | Executives and senior employees   | Authority, urgency, and business trust | Strong approval procedures and verification of financial requests    |
| Vishing        | Individuals and employees         | Trust, fear, and authority             | Verify callers independently and avoid sharing sensitive information |
| Smishing       | Mobile phone users                | Urgency, curiosity, and fear           | Do not open suspicious links and use mobile security controls        |
| Pretexting     | Employees and individuals         | Trust, authority, and helpfulness      | Verify identity and the legitimacy of the request                    |
| Baiting        | Employees and computer users      | Curiosity, greed, and temptation       | Avoid unknown USB devices, downloads, and external media             |

### 7.1 Security Impact and Key Defensive Measures

| Attack Type    | Main Security Property Affected  | Typical Result                                   | Key Defensive Measures                              |
| -------------- | -------------------------------- | ------------------------------------------------ | --------------------------------------------------- |
| Phishing       | Confidentiality and Integrity    | Credential theft or malware infection            | Awareness training, email filtering, MFA            |
| Spear Phishing | Confidentiality and Integrity    | Targeted credential theft or unauthorized access | MFA, verification, and email security               |
| Whaling        | Confidentiality and Integrity    | Financial fraud or sensitive data theft          | Multi-person approval and verification              |
| Vishing        | Confidentiality                  | Disclosure of sensitive information              | Caller verification and employee training           |
| Smishing       | Confidentiality and Integrity    | Malicious link execution or credential theft     | SMS filtering and user awareness                    |
| Pretexting     | Confidentiality and Integrity    | Unauthorized disclosure or access                | Identity verification and security procedures       |
| Baiting        | Confidentiality and Availability | Malware infection or system compromise           | Removable-media controls and safe-download policies |

## 8. Employee Security Training Checklist

Organizations should provide regular security awareness training to help employees recognize and prevent social engineering attacks. Employees should follow these five basic practices:

1. **Verify suspicious requests:** Independently verify unexpected requests for passwords, confidential information, money transfers, or system access.

2. **Identify phishing and impersonation:** Check the sender, links, attachments, phone calls, and messages carefully before responding or taking action.

3. **Never share sensitive information:** Do not disclose passwords, OTPs, MFA codes, financial information, or confidential company data through unverified channels.

4. **Avoid unknown links, files, and devices:** Do not open suspicious attachments, click unknown links, install untrusted software, or connect unknown USB devices.

5. **Report security incidents immediately:** Report suspicious emails, calls, messages, lost devices, or possible security incidents to the organization's IT/security team without delay.


## 9. Conclusion

Social engineering attacks exploit human trust, emotions, and normal workplace behavior rather than relying only on technical vulnerabilities. Phishing, spear phishing, whaling, vishing, smishing, pretexting, and baiting can lead to credential theft, malware infections, financial loss, data exposure, and unauthorized access.

Organizations can reduce these risks by combining employee awareness with technical security controls such as multi-factor authentication, email filtering, access controls, security monitoring, and safe handling of removable media. Employees should remain cautious when receiving unexpected requests and should independently verify suspicious communications before taking action.

### 9.1 Key Takeaways

1. **Verify before trusting:** Employees should independently verify unexpected requests for sensitive information, money transfers, or system access.

2. **Use layered security controls:** MFA, email security, access controls, monitoring, and secure device policies provide additional protection when human mistakes occur.

3. **Report suspicious activity quickly:** Early reporting of phishing emails, suspicious calls, malicious links, or unknown devices can help security teams contain incidents before they cause greater damage.


## 10. References

1. Cybersecurity and Infrastructure Security Agency (CISA). *Avoiding Social Engineering and Phishing Attacks.*
   https://www.cisa.gov/topics/cyber-threats-and-advisories

2. National Institute of Standards and Technology (NIST). *Phishing Guidance and Cybersecurity Resources.*
   https://www.nist.gov/

3. MITRE ATT&CK. *Phishing (T1566).*
   https://attack.mitre.org/techniques/T1566/

4. Cybersecurity and Infrastructure Security Agency (CISA). *More Than a Password: Multi-Factor Authentication.*
   https://www.cisa.gov/topics/cybersecurity-best-practices/multifactor-authentication

5. Federal Bureau of Investigation (FBI). *Business Email Compromise.*
   https://www.ic3.gov/CrimeInfo/BEC

6. U.S. Computer Emergency Readiness Team (US-CERT). *Phishing Campaign Linked with Dyre Banking Malware.*
   https://www.cisa.gov/ncas/alerts/TA14-300A

7. U.S. Department of Justice. *Justice Department Announces Charges Against Four Iranian Nationals for Multi-Year Cyber Campaign Targeting U.S. Companies.*
   https://www.justice.gov/usao-sdny/pr/justice-department-announces-charges-against-four-iranian-nationals-multi-year-cyber

8. WIRED. *Trojan Malware Delivered by Sneakernet.*
   https://www.wired.com/2007/04/trojan-malware-/

9. FBI Internet Crime Complaint Center (IC3). *Internet Crime Reports.*
   https://www.ic3.gov/AnnualReport
10. U.S. Department of Justice. “Iranian Hackers Indicted for Stealing Data from Aerospace and Satellite Tracking Companies.” https://www.justice.gov/usao-edva/pr/iranian-hackers-indicted-stealing-data-aerospace-and-satellite-tracking-companies
