# Nessus
Vulnerability scannning


1. **Install a Vulnerability Scanner**  
   Example: Install Nessus Essentials from Tenable's website or OpenVAS (Greenbone Vulnerability Manager) from their official repository.

2. **Set Scan Target**  
   Example: Configure scan target as `localhost` (127.0.0.1) or your local IP (e.g., 192.168.1.x).

3. **Start a Full Scan**  
   Example: Run the full system/network vulnerability scan using default settings.

4. **Wait for Scan Completion**  
   The scan may take 30-60 minutes depending on system and network size.

5. **Review Scan Report**  
   Example: Note vulnerabilities categorized as High or Critical, with details on affected ports, software versions, or configurations.

6. **Research Fixes or Mitigations**  
   Example: For a detected outdated software vulnerability, find and apply patches or update the software.

7. **Document Critical Vulnerabilities**  
   Example: List vulnerabilities like “Open SSH with weak encryption algorithms” or “Unpatched OS kernel” including their CVSS scores and suggested remediation.

   Interview questions:-
   
1. **What is vulnerability scanning?**  
   Vulnerability scanning is an automated process that identifies security weaknesses in systems or networks by comparing system information against a database of known vulnerabilities. For example, a scanner might detect an outdated Apache server version vulnerable to remote code execution.

2. **Difference between vulnerability scanning and penetration testing?**  
   Vulnerability scanning identifies potential security issues broadly and automatically, while penetration testing involves manual exploitation to assess the actual risk and impact. For example, scanning may flag a vulnerable website, but penetration testing tries to exploit it for proof.

3. **Common vulnerabilities in personal computers?**  
   Examples include unpatched software, weak or reused passwords, open network ports, outdated antivirus, and misconfigured firewalls.

4. **How do scanners detect vulnerabilities?**  
   Scanners check system configurations, running services, software versions against known vulnerabilities databases (like CVE) and use signature-based and heuristic detection methods.

5. **What is CVSS?**  
   The Common Vulnerability Scoring System assigns a score (0-10) to vulnerabilities representing their severity, helping prioritize patching. For example, a vulnerability with CVSS 9.8 is critical.

6. **How often should vulnerability scans be performed?**  
   Scans should be performed regularly, such as monthly or quarterly, and immediately after major changes in infrastructure or software deployment.

7. **What is a false positive in vulnerability scanning?**  
   A false positive is when a scanner reports a vulnerability that is actually not present or exploitable, e.g., detecting a patch missing when it is already applied.

8. **How do you prioritize vulnerabilities?**  
   Prioritization is based on CVSS scores, exploit availability, asset criticality, potential impact, and ease of remediation. High CVSS and actively exploited vulnerabilities are fixed it
   
