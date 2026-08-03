<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<div align="center">
  <img width="100%" src="./assets/banner.svg" alt="Siddhant Bhattarai — DevSecOps Engineer & Cloud Security Architect" />
</div>


<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3000&pause=800&color=38BDF8&center=true&vCenter=true&width=680&lines=Breaking+things+before+attackers+do.;Writing+security+tooling+in+Rust.;Architecting+cloud+that+survives+contact.;Teaching+engineers+to+do+the+same.)](https://github.com/siddhantbhattarai)

<img src="https://komarev.com/ghpvc/?username=siddhantbhattarai&style=for-the-badge&color=38BDF8&label=PROFILE+VIEWS" />
<img src="https://img.shields.io/github/followers/siddhantbhattarai?style=for-the-badge&color=38BDF8&labelColor=0D1117&logo=github" />
<img src="https://img.shields.io/badge/Experience-5%2B%20Years-38BDF8?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Kathmandu-Nepal-38BDF8?style=for-the-badge&labelColor=0D1117&logo=googlemaps&logoColor=white" />

</div>

<br>

<!-- ═══════════════════════════ ABOUT ═══════════════════════════ -->
## &nbsp;`~/whoami`

```yaml
name:        Siddhant Bhattarai
role:        DevSecOps Engineer & Cloud Security Architect
credentials: Accredited Educator @ AWS Academy & Red Hat Academy
philosophy:  "Prove the vulnerability. Don't guess at it."

building:    ANVIL — Rust web-app scanner covering 8 of the OWASP Top 10
architects:  AWS & Azure environments with security inside the pipeline
teaches:     Siddhant Academy — cloud, DevOps & security curriculum
writes:      72 long-form posts on DevSecOps, AWS and CI/CD
open_to:     Consulting · Security architecture · Tooling collaboration
```

> I spend my time on two things: writing tools that find real vulnerabilities with a low
> false-positive rate, and designing infrastructure where security is a build-time gate
> rather than a post-incident meeting.

<div align="center">
  <img src="https://trophygithubreadmelang.cybee.dpdns.org/?username=siddhantbhattarai&theme=algolia&no-frame=true&no-bg=true&margin-w=6&column=7&title=Stars,Followers,Commits,Repositories,PullRequest,MultipleLang,Experience" />
</div>

---

<!-- ═══════════════════════ FLAGSHIP PROJECT ═══════════════════════ -->
<h2 align="center">⚒️ &nbsp;ANVIL — Adversarial Security Testing Framework</h2>

<div align="center">

<img src="https://img.shields.io/badge/Written_in-Rust-000000?style=for-the-badge&logo=rust&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/OWASP_Top_10-8_of_10_covered-DC2626?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Detections-11_active_·_5_passive-38BDF8?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/MCP_Server-native-9333EA?style=for-the-badge&labelColor=0D1117" />

</div>

A scanner built on one principle: **every finding ships with evidence.** ANVIL detects and safely
proves SQL injection across seven techniques, plus XSS, SSRF, command injection, SSTI, XXE, path
traversal, NoSQL injection, CORS misconfiguration, open redirect and CRLF — backed by passive
audits for security headers, JWT weaknesses, exposed secrets, outdated components and SRI.

```bash
# One-shot OWASP sweep, gated for CI — exit 2 if anything High or worse lands
anvil -t "https://target.com" --owasp --crawl --fail-on high --format json

# Run as an MCP server so AI agents can call it as a native tool
anvil --mcp
```

<table align="center">
<tr>
<td width="33%" align="center">
<h3>🎯 Evidence-driven</h3>
Findings are <b>proven</b>, not flagged.<br>Low false-positive rate by design.
</td>
<td width="33%" align="center">
<h3>🤖 Agent-native</h3>
Built-in <b>MCP server</b> exposing<br><code>anvil_scan</code> to AI agents.
</td>
<td width="33%" align="center">
<h3>🚦 CI-ready</h3>
Deterministic <code>--fail-on</code> exit codes.<br>Stable JSON schema for triage.
</td>
</tr>
</table>

<div align="center">
<a href="https://github.com/siddhantbhattarai/anvil">
<img src="https://img.shields.io/badge/Explore_the_source-→-38BDF8?style=for-the-badge&labelColor=0D1117&logo=github" />
</a>
</div>

---

<!-- ═══════════════════════ SELECTED WORK ═══════════════════════ -->
<h2 align="center">📦 &nbsp;Selected Work</h2>

<table>
<tr>
<td width="50%" valign="top">

### ⚒️ [ANVIL](https://github.com/siddhantbhattarai/anvil)

Evidence-driven web application security scanner. 11 active detection classes, 5 passive audits, native MCP server for AI agents.

<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
<img src="https://img.shields.io/badge/Security-DC2626?style=flat-square" />
<img src="https://img.shields.io/badge/OWASP-38BDF8?style=flat-square" />

</td>
<td width="50%" valign="top">

### 🐳 [Fullstack PHP on Docker](https://github.com/siddhantbhattarai/Fullstack-PHP-Application-Docker)

Containerized multi-service application demonstrating orchestration patterns for full-stack deployments. One of my most-forked references.

<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" />
<img src="https://img.shields.io/badge/20_forks-38BDF8?style=flat-square" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ☁️ [AWS Cloud Foundational Lab](https://github.com/siddhantbhattarai/AWS-Cloud-Foundational-Lab)

Hands-on lab environment covering core AWS services and architecture patterns. Built as teaching material for engineers entering cloud roles.

<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
<img src="https://img.shields.io/badge/Architecture-38BDF8?style=flat-square" />

</td>
<td width="50%" valign="top">

### ⚡ [Azure Function Demo](https://github.com/siddhantbhattarai/Azure-Function-Demo)

Serverless implementation patterns on Azure Functions — a working reference for event-driven architecture.

<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Serverless-38BDF8?style=flat-square" />
<img src="https://img.shields.io/badge/19_forks-38BDF8?style=flat-square" />

</td>
</tr>
</table>

<div align="center">
<a href="https://github.com/siddhantbhattarai?tab=repositories">
<img src="https://img.shields.io/badge/Browse_all_111_repositories-→-38BDF8?style=for-the-badge&labelColor=0D1117&logo=github" />
</a>
</div>

---

<!-- ═══════════════════════ CREDENTIALS ═══════════════════════ -->
<h2 align="center">🎓 &nbsp;Credentials</h2>

<div align="center">

<img src="https://img.shields.io/badge/AWS_Academy-Accredited_Educator-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Red_Hat_Academy-Accredited_Educator-EE0000?style=for-the-badge&logo=redhat&logoColor=white&labelColor=0D1117" />

<br><br>

<img src="https://img.shields.io/badge/AWS_Academy-Cloud_Architecting-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/AWS_Academy-Cloud_Developing-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/AWS_Academy-Data_Engineering-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Fortinet-Network_Security-EE3124?style=flat-square&logo=fortinet&logoColor=white&labelColor=0D1117" />

</div>

---

<!-- ═══════════════════════ ARSENAL ═══════════════════════ -->
<h2 align="center">🧰 &nbsp;Arsenal</h2>

<table align="center">
<tr>
<td align="right" width="30%"><b>Security &amp; Offensive</b></td>
<td><img src="https://skillicons.dev/icons?i=rust,kali,linux,bash&theme=dark" height="42" /></td>
</tr>
<tr>
<td align="right"><b>Cloud</b></td>
<td><img src="https://skillicons.dev/icons?i=aws,azure,gcp&theme=dark" height="42" /></td>
</tr>
<tr>
<td align="right"><b>Infrastructure as Code</b></td>
<td><img src="https://skillicons.dev/icons?i=terraform,ansible,docker,kubernetes&theme=dark" height="42" /></td>
</tr>
<tr>
<td align="right"><b>CI/CD</b></td>
<td><img src="https://skillicons.dev/icons?i=githubactions,jenkins,gitlab,git&theme=dark" height="42" /></td>
</tr>
<tr>
<td align="right"><b>Languages</b></td>
<td><img src="https://skillicons.dev/icons?i=python,c,cpp,r&theme=dark" height="42" /></td>
</tr>
<tr>
<td align="right"><b>Data &amp; ML</b></td>
<td><img src="https://skillicons.dev/icons?i=postgres,mysql,pytorch,tensorflow,sklearn&theme=dark" height="42" /></td>
</tr>
<tr>
<td align="right"><b>Backend</b></td>
<td><img src="https://skillicons.dev/icons?i=fastapi,flask,django&theme=dark" height="42" /></td>
</tr>
</table>

---

<!-- ═══════════════════════ METRICS ═══════════════════════ -->
<h2 align="center">📊 &nbsp;The Numbers</h2>

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=siddhantbhattarai&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&border_radius=10&bg_color=0D1117&title_color=38BDF8&icon_color=38BDF8&text_color=C9D1D9" />
<img width="42%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=siddhantbhattarai&layout=compact&langs_count=8&hide_border=true&border_radius=10&bg_color=0D1117&title_color=38BDF8&text_color=C9D1D9&hide=php,scss,css,html,batchfile,gherkin,freemarker,xslt,tsql,ruby" />

<img width="92%" src="https://streak-stats.demolab.com?user=siddhantbhattarai&hide_border=true&border_radius=10&background=0D1117&ring=38BDF8&fire=38BDF8&currStreakLabel=38BDF8&sideLabels=C9D1D9&dates=8B949E&stroke=30363D&sideNums=C9D1D9&currStreakNum=E0F2FE" />

<img width="92%" src="https://github-readme-activity-graph.vercel.app/graph?username=siddhantbhattarai&hide_border=true&radius=10&bg_color=0D1117&color=38BDF8&line=38BDF8&point=E0F2FE&area=true&area_color=1E3A8A&title_color=38BDF8" />

</div>

<!-- Contribution snake — regenerated daily by .github/workflows/snake.yml -->
<div align="center">
  <img width="95%" src="https://raw.githubusercontent.com/siddhantbhattarai/siddhantbhattarai/output/snake-dark.svg" alt="Contribution snake" />
</div>

---

<!-- ═══════════════════════ WRITING ═══════════════════════ -->
<h2 align="center">✍️ &nbsp;Writing &amp; Teaching</h2>

<div align="center">

Long-form breakdowns of DevSecOps pipelines, AWS architecture and CI/CD — plus free curriculum
for engineers moving into cloud and security roles.

<a href="https://siddhantbhattarai.hashnode.dev"><img src="https://img.shields.io/badge/Hashnode-72_posts-2962FF?style=for-the-badge&logo=hashnode&logoColor=white&labelColor=0D1117" /></a>
<a href="https://www.youtube.com/@siddhantacademy101"><img src="https://img.shields.io/badge/Siddhant_Academy-Courses-FF0000?style=for-the-badge&logo=youtube&logoColor=white&labelColor=0D1117" /></a>

</div>

<!-- BLOG-POST-LIST:START -->
<!-- Latest posts appear here automatically — see .github/workflows/blog-posts.yml -->
<!-- BLOG-POST-LIST:END -->

---

<!-- ═══════════════════════ CURRENTLY ═══════════════════════ -->
<h2 align="center">🛰️ &nbsp;Currently</h2>

<div align="center">

`Extending ANVIL's detection coverage` &nbsp;·&nbsp; `Deepening agent / MCP integration`
&nbsp;·&nbsp; `Publishing cloud security curriculum`

</div>

---

<!-- ═══════════════════════ CONNECT ═══════════════════════ -->
<h2 align="center">🤝 &nbsp;Let's Build Something Secure</h2>

<div align="center">

<a href="https://www.linkedin.com/in/siddhant-bhattarai-3853ab238"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://siddhantbhattarai.hashnode.dev"><img src="https://img.shields.io/badge/Hashnode-2962FF?style=for-the-badge&logo=hashnode&logoColor=white" /></a>
<a href="https://www.youtube.com/@siddhantacademy101"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" /></a>
<a href="https://www.instagram.com/siddhantacademy101"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>

<br><br>

<i>Open to DevSecOps consulting, cloud security architecture, and security tooling collaboration.</i>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1E3A8A,55:2C1810,100:0D1117&height=130&section=footer" />
