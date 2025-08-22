# Authentication

**Authentication** = the process of verifying a user’s identity before granting access to a system, app, or resource.


**Example:** Entering username + password before accessing Gmail.

## Authentication Factors

Authentication factors are categories of methods used to verify identity.

**Factor Type	Description	Example**

Something you know	Knowledge-based	Password, PIN, security questions
Something you have	Possession-based	Smart card, mobile phone, OTP token
Something you are	Inherence-based	Biometric (fingerprint, face, iris)
Somewhere you are	Location-based	GPS location, IP address
Something you do	Behavior-based	Typing speed, mouse movement

**Multi-Factor Authentication (MFA) = using 2 or more factors together (e.g., password + OTP).**

## NIST Password Guidelines (NIST SP 800-63B)

NIST (National Institute of Standards and Technology) provides modern password rules:

Length over complexity → Minimum 8 characters, encourage long passphrases (16–64 chars).

No frequent forced changes unless compromised.

Ban weak/known passwords (like "123456").

Allow copy-paste and password managers.

Encourage MFA instead of only passwords.

## Password Vault (Password Manager)

A secure encrypted storage for passwords.

Auto-fills credentials and helps create strong unique passwords.

**Examples: LastPass, 1Password, Bitwarden, KeePass.**

**Benefit:** Users don’t need to remember multiple complex passwords.

## OTP (One-Time Password)

A password valid for only one login session or transaction.

Delivered via SMS, email, or authenticator apps (Google Authenticator, Authy).

**Types:**

**TOTP (Time-based OTP)** → Expires after a short time window (30s).

**HOTP (HMAC-based OTP)** → Based on a counter, valid until used.

## Smart Card Authentication

A physical card with embedded chip that stores digital certificates or keys.

Used with PIN to authenticate user (2FA).

Common in enterprises, banking, and government.

## Biometric Authentication

Authentication based on unique biological traits.

**Types of Biometric Authentication:**

## Type--------------------------------------------------------	Example

Fingerprint Recognition --------------------------------	Mobile phone unlock, attendance systems

Facial Recognition----------------------------------	Apple Face ID, airport security

Iris Recognition----------------------------------	High-security labs, border control

Retina Scan ------------------------------------	Rare, highly secure (analyzes eye blood vessels)

Voice Recognition---------------------------------	Phone banking, smart assistants

Hand Geometry-------------------------------------	Some physical access systems

Behavioral Biometrics -------------------------	Typing speed, walking style, touchscreen pattern

## Summary:

**Authentication** = verifying identity.

**Factors** = knowledge, possession, inherence, location, behavior.

**NIST says:** longer passwords, allow managers, no forced frequent changes.

**Vaults** = encrypted password storage.

**OTP** = short-lived passwords.

**Smart Card** = physical chip-based login.

**Biometric** = fingerprints, face, iris, etc.
