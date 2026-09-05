---
layout: page
title: Home
permalink: /
---

<div class="page-wrap">

<div class="hero">
  <h1>Abdiaziz Maalim</h1>
  <div class="hero-title">Cybersecurity Analyst</div>
  <div class="hero-tags"> SOC Operations • Threat Detection • Incident Response • Threat Intelligence • SIEM Engineering</div>
  <div class="hero-buttons">
    <a href="https://github.com/Amaalim1">GitHub</a>
    <a href="https://www.linkedin.com/in/YOUR-LINKEDIN">LinkedIn</a>
    <a href="mailto:you@example.com">Email</a>
  </div>
</div>

<nav class="custom-nav">
  <a href="#" class="tab-link active" data-tab="about">About</a>
  <a href="#" class="tab-link" data-tab="work">Work Experience</a>
  <a href="#" class="tab-link" data-tab="education">Education</a>
  <a href="#" class="tab-link" data-tab="skills">Skills</a>
  <a href="/projects/">Projects</a>
</nav>

<div class="profile-layout">
  <div class="profile-sidebar">
    <img src="/assets/img-01.jpg" alt="Abdiaziz Maalim">
    <ul>
      <li>📍 Canada </li>
      <li>💻 <a href="https://github.com/Amaalim1">GitHub</a></li>
      <li>🔗 <a href="https://www.linkedin.com/in/https://www.linkedin.com/in/abdiaziz-maalim/">LinkedIn</a></li>
    </ul>
  </div>

  <div class="profile-main">

<div class="tab-panel" id="panel-about" markdown="1">

<h3>About me</h3>

I am a cybersecurity professional focusing on Security Operations, Incident
Response, detection engineering, threat intelligence, and blue team
operations, with a growing interest in purple teaming. I hold an Honours
Bachelor of Information Technology in Cybersecurity from Seneca
Polytechnic, and I bring hands-on experience across SIEM platforms, threat
detection workflows, and security frameworks including MITRE ATT&CK, NIST
CSF, ISO 27001, and CIS Controls. I'm always working on side projects
to keep my skills sharp. you can find
those on my <a href="https://github.com/Amaalim1">GitHub</a>, where I post
about side projects and educational content.

Beyond traditional Security Operations, I'm increasingly interested in cybercrime, fraud investigations, financial crime detection, and risk analysis. I enjoy the investigative side of cybersecurity and the process of identifying patterns, analyzing suspicious activity, and turning data into actionable findings.
</div>

<div class="tab-panel" id="panel-work" style="display:none;" markdown="1">

<h3>Work Experience</h3>

<p><strong>Cyber Threat Detection Analyst (Co-op)</strong> — TD Bank<br>
<em>Jan–Apr 2026</em></p>

<p><strong>Enterprise Security Support</strong> — Dream Unlimited<br>
<em>Jul 2024–Mar 2025</em></p>

<p><strong>IT Security Support</strong> — Canadian Appliance Source<br>
<em>Mar 2020–Aug 2023</em></p>

</div>

<div class="tab-panel" id="panel-education" style="display:none;" markdown="1">

<h3>Education</h3>

Honours Bachelor of Information Technology (Cybersecurity)

**Seneca Polytechnic**

</div>

<div class="tab-panel" id="panel-skills" style="display:none;">
<h3>Skills</h3>
<div class="skill-grid">
<div class="skill-card">
<h4>Security Tools</h4>
<ul>
<li>Microsoft Sentinel</li>
<li>Microsoft Defender XDR</li>
<li>Microsoft Defender for Endpoint</li>
<li>Splunk</li>
<li>Wazuh</li>
<li>ServiceNow</li>
<li>Burp Suite</li>
<li>Ffuf</li>
<li>Wfuzz</li>
<li>Metasploit</li>
<li>Wireshark</li>
<li>Nmap</li>
<li>Qualys</li>
</ul>
</div>
<div class="skill-card">
<h4>Programming & Query Languages</h4>
<ul>
<li>Python</li>
<li>PowerShell</li>
<li>KQL</li>
<li>SQL</li>
<li>Bash</li>
</ul>
</div>
<div class="skill-card">
<h4>Cloud & Identity</h4>
<ul>
<li>Microsoft Azure</li>
<li>Microsoft Entra ID</li>
<li>Active Directory</li>
<li>Microsoft Intune</li>
</ul>
</div>
<div class="skill-card">
<h4>Networking</h4>
<ul>
<li>TCP/IP</li>
<li>DNS</li>
<li>DHCP</li>
<li>VPN</li>
<li>Wireshark</li>
</ul>
</div>
<div class="skill-card">
<h4>Security Concepts</h4>
<ul>
<li>Threat Detection</li>
<li>Incident Response</li>
<li>Detection Engineering</li>
<li>Threat Intelligence</li>
<li>Security Monitoring</li>
<li>Log Analysis</li>
</ul>
</div>
<div class="skill-card">
<h4>Frameworks</h4>
<ul>
<li>MITRE ATT&amp;CK</li>
<li>NIST CSF</li>
<li>CIS Controls</li>
<li>OWASP Top 10</li>
</ul>
</div>
</div>
</div>

<div class="contact-section" markdown="1">

### Let's Connect

<a href="mailto:you@example.com">📧 Email</a>
<a href="https://www.linkedin.com/in/https://www.linkedin.com/in/abdiaziz-maalim/">💼 LinkedIn</a>
<a href="https://github.com/Amaalim1">💻 GitHub</a>

</div>

</div>

<script>
document.querySelectorAll('.tab-link[data-tab]').forEach(function(tab) {
  tab.addEventListener('click', function(e) {
    e.preventDefault();
    document.querySelectorAll('.tab-link[data-tab]').forEach(function(t) {
      t.classList.remove('active');
    });
    this.classList.add('active');
    document.querySelectorAll('.tab-panel').forEach(function(panel) {
      panel.style.display = 'none';
    });
    document.getElementById('panel-' + this.dataset.tab).style.display = 'block';
  });
});
</script>
