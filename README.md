# phishing-url-analysis-beginner
Beginner cybersecurity project analyzing phishing URLs using domain and server concepts
# Beginner Phishing Detection Using URL Analysis

## Introduction
Phishing is a common cyber attack where attackers trick users into revealing sensitive information.
This beginner project explains how phishing works by analyzing URLs and identifying technical indicators
that reveal fake websites.

## How URLs Work
A URL tells the browser:
- HOW to connect (HTTP or HTTPS)
- WHO to connect to (domain / server owner)
- WHAT page to request (path)

The most important part for security is the domain because it shows who owns the server.

## HTTP vs HTTPS
- HTTP sends data openly
- HTTPS encrypts the connection
- HTTPS does NOT guarantee a website is legitimate

## Domain, Subdomain, and Path
- Domain: The owner of the website (example: socialmedia.com)
- Subdomain: A section of the same website (example: login.socialmedia.com)
- Path: The page or resource being requested (example: /account/verify)

Attackers often place trusted brand names in the path to trick users.

## Phishing URL Case Studies

### Case 1
URL: http://login-security.net/socialmedia/verify

Analysis:
- The domain is login-security.net
- socialmedia appears only in the path
- The server belongs to an attacker
- This is a phishing attempt
### Case 2
URL: https://paypal-login.net/account/verify

Analysis:
- The domain is paypal-login.net
- The real PayPal domain is paypal.com
- Extra words indicate a fake domain
- This is phishing
### Case 3
URL: https://accounts.google.com

Analysis:
- The domain is google.com
- accounts.google.com is a valid subdomain
- This is legitimate
### Case 4
URL: http://banking-secure.info/chase/login

Analysis:
- The domain is banking-secure.info
- chase appears only in the path
- This is phishing
### Case 5
URL: https://appleid.apple.com

Analysis:
- The domain is apple.com
- appleid.apple.com is a valid Apple subdomain
- This is legitimate
  
## Defensive Checklist
- Always check the domain name
- Read URLs from right to left
- Do not trust HTTPS alone
- Avoid clicking urgent login links
  
## Conclusion
This beginner project helped me understand how phishing attacks work at a technical level.
Learning how URLs, domains, and servers work is a foundational cybersecurity skill.

