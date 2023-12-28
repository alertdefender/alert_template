<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Custom Nuclei Templates Repository</title>
<style>
    body { font-family: Arial, sans-serif; }
    .container { width: 80%; margin: auto; }
    header { font-size: 2em; font-weight: bold; margin-top: 20px; }
    section { margin-top: 10px; }
    pre { background-color: #f7f7f7; padding: 10px; border: 1px solid #ddd; }
</style>
</head>
<body>
<div class="container">
    <header>Custom Nuclei Templates Repository</header>
    
    <section>
        <h2>Overview</h2>
        <p>This repository is a curated collection of my personal, custom Nuclei templates designed to enhance and streamline the process of vulnerability scanning. These templates serve as an extension to the already powerful and community-driven project <a href="https://github.com/projectdiscovery/nuclei">Nuclei</a> by <a href="https://projectdiscovery.io/">ProjectDiscovery</a>. Aimed to provide advanced scanning capabilities, the templates in this repository are crafted to target specific vulnerabilities and misconfigurations that are not covered by the standard template set.</p>
    </section>
    
    <section>
        <h2>Templates</h2>
        <p>The templates within cover a range of applications and purposes, some of which are tailored to detect misconfigurations and files that should not be publicly accessible, such as backup files, admin interfaces, and configuration files.</p>
        
        <p>Examples include:</p>
        <ul>
            <li>Detection of exposed <code>wp-config.php</code> and <code>wp-config.php.old</code> files in WordPress installations.</li>
            <li>Scans for deprecated API endpoints that may be vulnerable to unauthorized access.</li>
            <li>Templates to check for common misconfigurations in web server settings.</li>
        </ul>
    </section>
    
    <section>
        <h2>Usage</h2>
        <p>To use these templates:</p>
        <ol>
            <li>Clone this repository to your local machine.</li>
            <li>Point Nuclei to the template(s) you wish to use.</li>
        </ol>
        <p>Example:</p>
        <pre>nuclei -u &lt;target-website&gt; -t &lt;path-to-your-cloned-templates-directory&gt;/&lt;specific-template-file&gt;</pre>
    </section>
    
    <section>
        <h2>Contribution</h2>
        <p>Contributions to this repository are welcome. Feel free to fork the repository, make improvements, and submit a pull request.</p>
    </section>
    
    <section>
        <h2>Disclaimer</h2>
        <p>These templates are provided "as-is" with no warranties of any kind. It is your responsibility to ensure that you have the legal right to perform scanning and testing against any target. Always obtain explicit, authorized consent before conducting scans.</p>
    </section>
    
    <section>
        <h2>License</h2>
        <p>This project is released under the <a href="LICENSE">MIT License</a>.</p>
    </section>
</div>
</body>
</html>    
