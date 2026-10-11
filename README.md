BankSim — Blue-Team AI Firewall

Tagline: Secure the request. Protect the bank.

Overview
BankSim is a browser-based cybersecurity prototype demonstrating how basic security rules can inspect simulated banking requests, identify selected prompt-injection patterns, and block unsupported or potentially unsafe actions.

Live Demo
https://banksim-firewall.netlify.app/

Features
- Interactive banking request analysis
- Basic prompt-injection pattern detection
- Risk scores and threat categories
- Structured security decisions: APPROVED or BLOCKED
- Fail-closed handling for unsupported requests
- Responsive dashboard interface

Technology Stack
- HTML
- CSS
- JavaScript
- Netlify for deployment

How to Run
1. Clone or download this repository.
2. Open `index.html` in a web browser.
3. Enter a sample request or select one of the example buttons.

No installation or API key is required.

Security Approach
The prototype checks requests against predefined patterns and supports a limited set of demo intents. Transfers are blocked pending further validation.

Limitations
This is a rule-based educational prototype, not a production-grade AI firewall. It does not use a live AI model, authenticate bank customers, access real accounts, or execute transactions. Pattern matching may miss attacks or incorrectly flag legitimate requests.

Future Improvements
- Integrate a hosted language model for request classification.
- Add a Python backend with deterministic policy enforcement.
- Develop automated security tests.
- Add audit logging and stronger authorization checks.

Project Type
AI Security & FinTech — simulated banking security demonstration.
