# Cybersecurity Lab 1 — Network Traffic Analysis


**Moumouni OUEDRAOGO**


## Part 1: Password Security

### Weak Passwords

Examples:

* 123456
* password
* admin

These passwords are insecure because:

* They are easy to guess
* They are included in hacker dictionaries
* They can be cracked in seconds

### Strong Passwords (Examples)

* M0m0@Cyber2026!
* Secure#Lab1_Wifi!
* Wireshark$Analysis99


## Part 2 : captures


## Part 3: Packet Analysis

### DNS Traffic


Observed domain name resolution (e.g., google.com)


### HTTP Traffic


http

Observed:

* URLs
* Request headers
* Unencrypted data

HTTP traffic is NOT secure.


### TLS Traffic (HTTPS)

tls


Observed encrypted communication

TLS ensures:

* Data confidentiality
* Protection of sensitive information



## Results

* Approximate packets captured: **1500+** (depends on test)
* Protocols observed:

  * DNS
  * HTTP
  * TLS


## Analysis Questions

### 1. Why is encryption important?

Encryption protects sensitive data from being intercepted by attackers.



### 2. What information can be exposed without encryption?

* Login credentials
* Personal data
* Browsing activity
* Cookies



### 3. Key Observation

Unencrypted traffic (HTTP) can be easily read, while encrypted traffic (TLS) protects user data.



## Conclusion

This lab demonstrated that:

* Weak passwords are a major security risk
* Network traffic can be captured and analyzed easily
* Unencrypted communication exposes sensitive data
* HTTPS (TLS) is essential for secure communication



