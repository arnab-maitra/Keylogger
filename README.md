# Keylogger

## Overview
Keyloggers serve the purpose of capturing and logging keystrokes on a target system. While they can be a tool in a hacker's arsenal, it's crucial to note that keyloggers have applications beyond malicious intent, finding use in both legitimate and illegitimate scenarios.

Legitimate uses of keyloggers encompass:

1. **Employee Monitoring:** Employers may deploy keyloggers to track employee activities on company-owned devices, ensuring compliance with organizational policies.

2. **Parental Control:** Keyloggers can be utilized by parents to monitor their children's online activities, ensuring their safety and responsible internet usage.

3. **System Administration:** System administrators might employ keyloggers for troubleshooting or monitoring purposes, aiding in the detection of unauthorized access or unusual behavior.

However, in the hands of malicious actors, keyloggers can present severe security threats. Cybercriminals may leverage keyloggers for:

1. **Credential Theft:** Illegitimate capture of login credentials for various accounts (e.g., email, social media, banking) by logging keystrokes.

2. **Espionage:** Spying on individuals, companies, or government entities to gather sensitive information.

3. **Identity Theft:** Illicit collection of personal information, such as credit card details or social security numbers, for fraudulent activities.

4. **Surveillance:** Covert monitoring and recording of user activities without their knowledge for malicious purposes.

To safeguard against keyloggers, individuals and organizations should adopt robust cybersecurity practices. This includes using reliable security software, maintaining up-to-date software and systems, exercising caution regarding phishing attempts, employing secure password practices, and regularly monitoring and auditing system logs to detect any suspicious activities.

## Concept

The keylogger works by creating an instance of a Listener from the pynput library. The listener is set up to call a function whenever a key is pressed. The function then logs the pressed key into the specified log file.

## Prerequisites
Before running the script, make sure to install the required libraries:

1. pynput: Used for reading keystrokes.
   
2. logging: Used for logging keystrokes into a file.

## Usage

1. Run the script: python keylogger.py

2. 

3. The script will start recording keystrokes and logging them into the keylog.txt file.

4. To stop the keylogger, manually terminate the script.
