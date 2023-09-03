# Password Generator

Password Generator is a simple Python based program to generate random passwords using alpha-numeric and symbolic characters. Random password generators are tools or programs that create complex and unpredictable passwords. 

## Libraries Used

A Python library random is used to randomize the characters to generate new password with every run.

```
import random
```

## Variables Used

1. lower - A tuple storing all lowercase english alphabet characters in string type.
2. upper - A tuple storing all uppercase english alphabet characters in string type.
3. numeric - A tuple storing all numeric characters from 0 to 9 in string type.
4. symbol - A tuple storing only 10 allowed symbolic characters in string type.
5. all - A variable storing the concatenated characters from above variables generated at random.
6. len - A variable defining the maximum size of the password to be generated.
7. pswd - A variable storing the finally generated password.

## Function Used

The ```sample()``` function from the random module is an in-build function that performs random sampling without replacement.

## Usage

They have numerous applications in enhancing security across various domains. Here are some of the key applications:

1. **Online Account Security:** Random password generators help individuals and organizations create strong and unique passwords for online accounts. This helps protect against unauthorized access to email, social media, banking, and other online services.

2. **Network and Server Security:** In the realm of IT and cybersecurity, random password generators are used to create strong passwords for network devices, servers, and databases. These passwords are harder to crack through brute force or dictionary attacks.

3. **Encryption Keys:** Generating random keys for encryption algorithms is crucial for ensuring the security of sensitive data. Strong encryption keys are used to protect confidential information during transmission and storage.

4. **Two-Factor Authentication (2FA):** Some 2FA systems generate one-time passwords (OTPs) as a second layer of authentication. Random password generators can be used to create these temporary codes, adding an extra layer of security to user logins.

5. **Password Managers:** Password managers often include built-in random password generators. They create and store strong, unique passwords for various accounts, making it easier for users to maintain a high level of security without having to remember all their passwords.

6. **Secure File Sharing:** When sharing sensitive files or documents, you can generate passwords to protect them. These passwords add an extra layer of security to ensure that only authorized individuals can access the shared content.

7. **Compliance and Regulations:** Many industries and organizations are subject to regulations and compliance standards that require strong password policies. Random password generators can help ensure compliance with these standards.

8. **User Registration:** Websites and online services often require users to create accounts. To encourage strong password practices, these platforms can include password strength meters and random password generation options during the registration process.

9. **API and Application Access:** In software development, random password generators are used to create access tokens, API keys, and other authentication credentials. This ensures secure access to various services and APIs.

10. **Penetration Testing and Ethical Hacking:** Security professionals use random password generators to test the strength of systems and networks. They simulate attacks by attempting to crack generated passwords, helping identify vulnerabilities.

11. **IoT Device Security:** Internet of Things (IoT) devices often require secure authentication mechanisms. Randomly generated passwords can be used to secure access to IoT devices and prevent unauthorized control.

12. **Cloud Services:** Cloud platforms and hosting providers use random password generators for creating secure login credentials and access keys, safeguarding cloud-based resources.

## Summary

Random password generators are a critical tool in safeguarding digital assets and maintaining online security. They help protect against unauthorized access, data breaches, and other security threats by creating strong and unpredictable passwords.
