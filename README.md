# Redact-Sensitive-Information Userscript

This userscript automatically redacts predefined sensitive information from webpages, enhancing your online privacy. It is designed to be compatible with Tampermonkey and other userscript managers.

## Installation

To use this script, follow these detailed steps:

1. **Install a Userscript Manager:** If you haven't already, install a userscript manager like [Tampermonkey](https://www.tampermonkey.net/) for your browser. This is necessary for the script to run.

2. **Add the Script:** Navigate to the Tampermonkey dashboard in your browser, and select the option to create a new script.

3. **Copy the Script:** Copy the contents of the `Redact-Sensitive-Information` script from this GitHub repository.

4. **Paste and Save:** Paste the copied script into the new script template in Tampermonkey. Save the script by clicking File > Save in the Tampermonkey editor.

5. **Enable the Script:** Ensure the script is enabled in Tampermonkey's dashboard. Once enabled, it will run automatically on all webpages.

## Features

- **Privacy Protection:** Automatically replaces specific, predefined text with a redaction label.
- **Universal Compatibility:** Functions on any website, ensuring broad protection.
- **Customizable:** Users can easily adjust redaction rules to fit their privacy needs.
- **Continuous Monitoring:** Actively scans and redacts information in the background for optimal privacy.

## How to Use

After installation, the script operates automatically, applying your predefined redaction rules to any webpage you visit. To customize these rules:

```javascript
const redactionRules = [
    { target: "SensitiveInfo1", replacement: "REDACTED" },
    // Add more rules as needed
];
