# Redact-Sensitive-Information Userscript

Automatically redacts predefined sensitive information from webpages to enhance privacy. Compatible with Tampermonkey and other userscript managers.

## Installation

1. Ensure you have Tampermonkey or a similar userscript manager installed.
2. Install the script from this git-hub

## Features

- Replaces specific text with redaction text.
- Works on all websites.
- Customizable redaction rules.
- constinly checks in the backgrownd for best privisy 
## How to Use

The script runs automatically, applying redaction rules to text on webpages. Edit the script to customize redaction rules:

```javascript
const redactionRules = [
    { target: "SensitiveInfo1", replacement: "REDACTED" },
    // Add more rules as needed
];
