<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ana Stojkova-Bonaventura | Cybersecurity Portfolio</title>
    <style>
        :root {
            --bg-color: #0d1117;
            --card-bg: #161b22;
            --text-main: #c9d1d9;
            --accent-green: #238636;
            --accent-blue: #58a6ff;
            --border: #30363d;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        header {
            background: linear-gradient(135deg, #010409 0%, #161b22 100%);
            padding: 3rem 1rem;
            text-align: center;
            border-bottom: 1px solid var(--border);
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 2rem;
        }

        h1 { margin: 0; color: #fff; font-size: 2.5rem; }
        .subtitle { color: var(--accent-blue); font-size: 1.2rem; margin-top: 0.5rem; font-weight: bold; }
        .contact-info { margin-top: 1rem; font-size: 0.9rem; }
        .contact-info a { color: var(--text-main); text-decoration: none; margin: 0 10px; border-bottom: 1px solid var(--accent-green); }

        .project-card {
            background-color: var(--card-bg);
            border: 1px solid var(--border);
            border-radius: 8px;
            padding: 1.5rem;
            margin-bottom: 2rem;
            transition: transform 0.2s;
        }

        .project-card:hover { transform: translateY(-3px); border-color: var(--accent-blue); }

        h2 { border-left: 4px solid var(--accent-green); padding-left: 15px; color: #fff; }
        h3 { color: var(--accent-blue); margin-top: 0; }

        .tag {
            display: inline-block;
            background: #21262d;
            border: 1px solid var(--border);
            padding: 2px 8px;
            border-radius: 4px;
            font-size: 0.8rem;
            margin-right: 5px;
            color: #8b949e;
        }

        .cysa-badge {
            float: right;
            background: rgba(35, 134, 54, 0.1);
            color: var(--accent-green);
            border: 1px solid var(--accent-green);
            padding: 2px 10px;
            border-radius: 20px;
            font-weight: bold;
            font-size: 0.85rem;
        }

        ul { padding-left: 20px; }
        li { margin-bottom: 8px; }

        footer { text-align: center; padding: 2rem; font-size: 0.8rem; border-top: 1px solid var(--border); color: #8b949e; }
    </style>
</head>
<body>

<header>
    <h1>Ana Stojkova-Bonaventura [cite: 2]</h1>
    <div class="subtitle">Cybersecurity | IT Support | Security Operations [cite: 3]</div>
    <div class="contact-info">
        📍 Jersey City, NJ [cite: 4] | 
        📧 <a href="mailto:Anastojkova913@yahoo.com">Anastojkova913@yahoo.com</a> [cite: 5] | 
        🔗 <a href="https://linkedin.com/in/ana-stojkova-bonaventura">LinkedIn</a> [cite: 6]
    </div>
</header>

<div class="container">

    <section class="project-card">
        <span class="cysa-badge">CySA+ 1.1, 2.5</span> [cite: 22, 23]
        <h3>1. Cloud-Hosted Cyber Lab [cite: 8]</h3>
        <p>Explored a cloud-hosted enterprise lab environment featuring multiple Windows and Linux virtual machines to understand system roles and network segmentation[cite: 10, 11].</p>
        <ul>
            <li>Identified Domain Controllers, servers, and client workstations[cite: 14].</li>
            <li>Navigated mixed OS environments and reviewed network access paths[cite: 13, 15].</li>
            <li>Prepared systems for security analysis[cite: 16].</li>
        </ul>
        <div>
            <span class="tag">Enterprise Architecture</span>
            <span class="tag">Linux/Windows Navigation</span> [cite: 18, 19]
        </div>
    </section>

    <section class="project-card">
        <span class="cysa-badge">CySA+ 1.1, 2.5</span> [cite: 37, 38]
        <h3>2. Security Control Configuration [cite: 24]</h3>
        <p>Configured and validated preventive, detective, directive, and corrective controls to improve organizational security[cite: 26].</p>
        <ul>
            <li>Implemented firewall rules and Group Policy security settings[cite: 28, 30].</li>
            <li>Controlled service behavior and permissions[cite: 31].</li>
            <li>Validated control effectiveness through testing[cite: 32].</li>
        </ul>
    </section>

    <section class="project-card">
        <span class="cysa-badge">CySA+ 1.1, 1.4, 1.5, 2.5</span> [cite: 52, 53]
        <h3>3. IoC & Threat Intelligence [cite: 39]</h3>
        <p>Researched and applied threat intelligence to strengthen detection capabilities[cite: 41].</p>
        <ul>
            <li>Reviewed IP, domain, and hash-based Indicators of Compromise[cite: 43].</li>
            <li>Analyzed MITRE ATT&CK techniques and CVE repositories[cite: 45, 46].</li>
            <li>Compared tactical, operational, and strategic intelligence[cite: 47].</li>
        </ul>
    </section>

    <section class="project-card">
        <span class="cysa-badge">CySA+ 1.2, 1.3, 1.4, 3.2</span> [cite: 65, 66]
        <h3>4. Threat Hunting [cite: 54]</h3>
        <p>Conducted proactive threat hunting using logs, network analysis, and DNS investigation[cite: 56].</p>
        <ul>
            <li>Identified suspicious IP traffic from firewall logs[cite: 58].</li>
            <li>Used netstat to detect abnormal connections and DNS anomalies[cite: 59, 60].</li>
            <li>Performed cross-system investigative triage[cite: 60].</li>
        </ul>
    </section>

    <section class="project-card">
        <span class="cysa-badge">CySA+ 1.1, 2.5</span> [cite: 80, 81]
        <h3>5. System Hardening [cite: 67]</h3>
        <p>Hardened systems by removing unnecessary components and securing essential services[cite: 69].</p>
        <ul>
            <li>Managed Windows device drivers and host name resolution[cite: 71, 72].</li>
            <li>Removed unnecessary software and configured restrictive firewall rules[cite: 73, 74].</li>
            <li>Managed Linux file permissions to reduce attack surface[cite: 75, 78].</li>
        </ul>
    </section>

    <section class="project-card">
        <span class="cysa-badge">CySA+ 1.1, 2.1, 2.5</span> [cite: 95, 96]
        <h3>6. Security Operations Automation [cite: 82]</h3>
        <p>Integrated threat intelligence feeds with automated controls to improve response speed[cite: 84].</p>
        <ul>
            <li>Automated firewall updates and scripted malware removal via hash-based intel[cite: 86, 87].</li>
            <li>Implemented DNS blocking for malicious domains[cite: 89].</li>
            <li>Scheduled automated remediation tasks[cite: 90].</li>
        </ul>
    </section>

    <section class="project-card">
        <span class="cysa-badge">CySA+ 1.1, 2.5</span> [cite: 127, 128]
        <h3>7. Vulnerability Assessment (OpenVAS) [cite: 97]</h3>
        <p>Performed a network vulnerability assessment using Greenbone Vulnerability Manager to identify security weaknesses[cite: 99].</p>
        
        <ul>
            <li>Initialized OpenVAS vulnerability feeds on Kali Linux[cite: 101, 105].</li>
            <li>Created and executed comprehensive network scans[cite: 107, 108].</li>
            <li>Identified misconfigurations and outdated services[cite: 112].</li>
            <li>Recommended system patches and network segmentation[cite: 117, 119].</li>
        </ul>
    </section>

</div>

<footer>
    &copy; 2026 Ana Stojkova-Bonaventura | Cybersecurity Portfolio
</footer>

</body>
</html>
