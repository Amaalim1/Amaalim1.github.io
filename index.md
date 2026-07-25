---
layout: page
title: Home
permalink: /
---

<div class="page-wrap">

<div class="hero">
  <h1>Abdiaziz Maalim</h1>
  <div class="hero-title">Cybersecurity Analyst</div>
  <div class="hero-tags">Threat Detection • Incident Response • SIEM Engineering • Threat Intelligence</div>
  <div class="hero-buttons">
    <a href="/resume/">Resume</a>
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
  <a href="/writeups/">Writeups</a>
</nav>

<div class="profile-layout">
  <div class="profile-sidebar">
    <img src="/assets/img-01.jpg" alt="Abdiaziz Maalim">
    <ul>
      <li>📍 Toronto, ON</li>
      <li>💻 <a href="https://github.com/Amaalim1">GitHub</a></li>
      <li>🔗 <a href="https://www.linkedin.com/in/YOUR-LINKEDIN">LinkedIn</a></li>
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
related to detection engineering and threat intelligence — you can find
those on my <a href="https://github.com/Amaalim1">GitHub</a>, where I post
about side projects and educational content.

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
      <li>Defender XDR</li>
      <li>Splunk</li>
      <li>Wazuh</li>
    </ul>
  </div>
  <div class="skill-card">
    <h4>Programming</h4>
    <ul>
      <li>Python</li>
      <li>PowerShell</li>
      <li>KQL</li>
      <li>SQL</li>
    </ul>
  </div>
  <div class="skill-card">
    <h4>Cloud & Identity</h4>
    <ul>
      <li>Azure</li>
      <li>Microsoft Entra ID</li>
      <li>Active Directory</li>
    </ul>
  </div>
  <div class="skill-card">
    <h4>Frameworks</h4>
    <ul>
      <li>MITRE ATT&CK</li>
      <li>NIST CSF</li>
      <li>ISO 27001</li>
      <li>CIS Controls</li>
    </ul>
  </div>
</div>

</div>

  </div>
</div>

<div class="contact-section" markdown="1">

### Let's Connect

<a href="mailto:you@example.com">📧 Email</a>
<a href="https://www.linkedin.com/in/YOUR-LINKEDIN">💼 LinkedIn</a>
<a href="https://github.com/Amaalim1">💻 GitHub</a>
<a href="/resume/">📄 Resume</a>

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
