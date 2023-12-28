# Custom Nuclei Templates Repository

## Overview
This repository is a curated collection of my personal, custom Nuclei templates designed to enhance and streamline the process of vulnerability scanning. These templates serve as an extension to the already powerful and community-driven project [Nuclei](https://github.com/projectdiscovery/nuclei) by [ProjectDiscovery](https://projectdiscovery.io/). Aimed to provide advanced scanning capabilities, the templates in this repository are crafted to target specific vulnerabilities and misconfigurations that are not covered by the standard template set.

## Templates
The templates within cover a range of applications and purposes, some of which are tailored to detect misconfigurations and files that should not be publicly accessible, such as backup files, admin interfaces, and configuration files.

Examples include:
- Detection of exposed `wp-config.php` and `wp-config.php.old` files in WordPress installations.
- Scans for deprecated API endpoints that may be vulnerable to unauthorized access.
- Templates to check for common misconfigurations in web server settings.

## Usage
To use these templates:
1. Clone this repository to your local machine.
2. Point Nuclei to the template(s) you wish to use.

Example: nuclei -u <target-website> -t <path-to-your-cloned-templates-directory>/<specific-template-file>

## Social Profiles
Find me on:
- [LinkedIn](https://www.linkedin.com/in/alireza-jangjo-a87964214/)
- [Twitter](https://twitter.com/alertdefender)
