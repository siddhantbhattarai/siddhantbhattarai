<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=220&section=header&text=Siddhant%20Bhattarai&fontSize=54&fontColor=ffffff&fontAlignY=32&desc=DevSecOps%20Engineer%20%C2%B7%20Cloud%20Security%20Architect&descAlignY=52&descSize=18&animation=fadeIn" />

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3000&pause=800&color=00D9FF&center=true&vCenter=true&width=680&lines=Breaking+things+before+attackers+do.;Writing+security+tooling+in+Rust.;Architecting+cloud+that+survives+contact.;Teaching+engineers+to+do+the+same.)](https://github.com/siddhantbhattarai)

<img src="https://komarev.com/ghpvc/?username=siddhantbhattarai&style=for-the-badge&color=00D9FF&label=PROFILE+VIEWS" />
<img src="https://img.shields.io/github/followers/siddhantbhattarai?style=for-the-badge&color=00D9FF&labelColor=0F2027&logo=github" />
<img src="https://img.shields.io/badge/Experience-5%2B%20Years-00D9FF?style=for-the-badge&labelColor=0F2027" />
<img src="https://img.shields.io/badge/Kathmandu-Nepal-00D9FF?style=for-the-badge&labelColor=0F2027&logo=googlemaps&logoColor=white" />

</div>

<br>

<!-- ═══════════════════════════ ABOUT ═══════════════════════════ -->
## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="30"> &nbsp;`~/whoami`

```yaml
name:       Siddhant Bhattarai
role:       DevSecOps Engineer & Cloud Security Architect
philosophy: "Prove the vulnerability. Don't guess at it."

building:   ANVIL — Rust web-app scanner covering 8 of the OWASP Top 10
architects: AWS & Azure environments with security inside the pipeline
teaches:    Siddhant Academy — cloud, DevOps & security curriculum
writes:     72 long-form posts on DevSecOps, AWS and CI/CD
open_to:    Consulting · Security architecture · Tooling collaboration
```

> I spend my time on two things: writing tools that find real vulnerabilities with a low
> false-positive rate, and designing infrastructure where security is a build-time gate
> rather than a post-incident meeting.

<div align="center">
  <img src="https://trophygithubreadmelang.cybee.dpdns.org/?username=siddhantbhattarai&theme=darkhub&no-frame=true&no-bg=true&margin-w=6&column=7&title=Stars,Followers,Commits,Repositories,PullRequest,MultipleLang,Experience" />
</div>

---

<!-- ═══════════════════════ FLAGSHIP PROJECT ═══════════════════════ -->
<h2 align="center">⚒️ &nbsp;ANVIL — Adversarial Security Testing Framework</h2>

<div align="center">

<img src="https://img.shields.io/badge/Written_in-Rust-000000?style=for-the-badge&logo=rust&logoColor=white&labelColor=0F2027" />
<img src="https://img.shields.io/badge/OWASP_Top_10-8_of_10_covered-DC382D?style=for-the-badge&labelColor=0F2027" />
<img src="https://img.shields.io/badge/Detections-11_active_·_5_passive-00D9FF?style=for-the-badge&labelColor=0F2027" />
<img src="https://img.shields.io/badge/MCP_Server-native-9B59B6?style=for-the-badge&labelColor=0F2027" />

</div>

A scanner built on one principle: **every finding ships with evidence.** ANVIL detects and safely
proves SQL injection across seven techniques, plus XSS, SSRF, command injection, SSTI, XXE, path
traversal, NoSQL injection, CORS misconfiguration, open redirect and CRLF — then backs it with
passive audits for security headers, JWT weaknesses, exposed secrets, outdated components and SRI.

```bash
# One-shot OWASP sweep, gated for CI — exit 2 if anything High or worse lands
anvil -t "https://target.com" --owasp --crawl --fail-on high --format json

# Run as an MCP server so agents can call it as a native tool
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
Built-in <b>MCP server</b> exposes<br><code>anvil_scan</code> to AI agents.
</td>
<td width="33%" align="center">
<h3>🚦 CI-ready</h3>
Deterministic <code>--fail-on</code> exit codes.<br>Stable JSON schema for triage.
</td>
</tr>
</table>

<div align="center">
<a href="https://github.com/siddhantbhattarai/anvil">
<img src="https://img.shields.io/badge/Explore_the_source-→-00D9FF?style=for-the-badge&labelColor=0F2027&logo=github" />
</a>
</div>

---

<!-- ═══════════════════════ OTHER WORK ═══════════════════════ -->
<h2 align="center">📦 &nbsp;Selected Repositories</h2>

<div align="center">

<a href="https://github.com/siddhantbhattarai/anvil">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=siddhantbhattarai&repo=anvil&theme=tokyonight&hide_border=true&bg_color=0F2027&title_color=00D9FF&icon_color=00D9FF&border_radius=10" />
</a>
<a href="https://github.com/siddhantbhattarai/Fullstack-PHP-Application-Docker">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=siddhantbhattarai&repo=Fullstack-PHP-Application-Docker&theme=tokyonight&hide_border=true&bg_color=0F2027&title_color=00D9FF&icon_color=00D9FF&border_radius=10" />
</a>
<a href="https://github.com/siddhantbhattarai/AWS-Cloud-Foundational-Lab">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=siddhantbhattarai&repo=AWS-Cloud-Foundational-Lab&theme=tokyonight&hide_border=true&bg_color=0F2027&title_color=00D9FF&icon_color=00D9FF&border_radius=10" />
</a>
<a href="https://github.com/siddhantbhattarai/Azure-Function-Demo">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=siddhantbhattarai&repo=Azure-Function-Demo&theme=tokyonight&hide_border=true&bg_color=0F2027&title_color=00D9FF&icon_color=00D9FF&border_radius=10" />
</a>

</div>

---

<!-- ═══════════════════════ ARSENAL ═══════════════════════ -->
<h2 align="center">🧰 &nbsp;Arsenal</h2>

<table align="center">
<tr>
<td align="right" width="30%"><b>Security & Offensive</b></td>
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
<td align="right"><b>Data & ML</b></td>
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

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=siddhantbhattarai&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&border_radius=10&theme=tokyonight&bg_color=0F2027&title_color=00D9FF&icon_color=00D9FF&text_color=c9d1d9" />
<img width="42%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=siddhantbhattarai&layout=compact&langs_count=8&hide_border=true&border_radius=10&theme=tokyonight&bg_color=0F2027&title_color=00D9FF&text_color=c9d1d9&hide=php,scss,css,html,batchfile,gherkin,freemarker,xslt,tsql,ruby" />

<img width="92%" src="https://streak-stats.demolab.com?user=siddhantbhattarai&theme=tokyonight&hide_border=true&border_radius=10&background=0F2027&ring=00D9FF&fire=00D9FF&currStreakLabel=00D9FF&sideLabels=c9d1d9&dates=8b949e" />

<img width="92%" src="https://github-readme-activity-graph.vercel.app/graph?username=siddhantbhattarai&theme=tokyo-night&hide_border=true&radius=10&bg_color=0F2027&color=00D9FF&line=00D9FF&point=ffffff&area=true&area_color=00D9FF" />

</div>

<!-- Contribution snake — auto-regenerated daily by .github/workflows/snake.yml -->
<div align="center">
  <img width="95%" src="https://raw.githubusercontent.com/siddhantbhattarai/siddhantbhattarai/output/snake-dark.svg" alt="Contribution snake" />
</div>

---

<!-- ═══════════════════════ WRITING ═══════════════════════ -->
<h2 align="center">✍️ &nbsp;Writing & Teaching</h2>

<div align="center">

Long-form breakdowns of DevSecOps pipelines, AWS architecture and CI/CD — plus free curriculum
for engineers moving into cloud and security roles.

<a href="https://siddhantbhattarai.hashnode.dev"><img src="https://img.shields.io/badge/Hashnode-72_posts-2962FF?style=for-the-badge&logo=hashnode&logoColor=white&labelColor=0F2027" /></a>
<a href="https://www.youtube.com/@siddhantacademy101"><img src="https://img.shields.io/badge/Siddhant_Academy-Courses-FF0000?style=for-the-badge&logo=youtube&logoColor=white&labelColor=0F2027" /></a>

</div>

<!-- BLOG-POST-LIST:START -->
<!-- Latest posts appear here automatically — see .github/workflows/blog-posts.yml -->
<!-- BLOG-POST-LIST:END -->

---

<!-- ═══════════════════════ CURRENTLY ═══════════════════════ -->
<h2 align="center">🛰️ &nbsp;Currently</h2>

<div align="center">

`Extending ANVIL's detection coverage` &nbsp;·&nbsp; `Deepening agent/MCP integration`
&nbsp;·&nbsp; `Publishing cloud security curriculum`

</div>

---

<!-- ═══════════════════════ CONNECT ═══════════════════════ -->
<h2 align="center">🤝 &nbsp;Let's Build Something Secure</h2>

<div align="center">

<a href="ADD_YOUR_LINKEDIN_URL"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://siddhantbhattarai.hashnode.dev"><img src="https://img.shields.io/badge/Hashnode-2962FF?style=for-the-badge&logo=hashnode&logoColor=white" /></a>
<a href="https://www.youtube.com/@siddhantacademy101"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" /></a>
<a href="https://www.instagram.com/siddhantacademy101"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
<a href="mailto:ADD_YOUR_EMAIL"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<br><br>

<i>Open to DevSecOps consulting, cloud security architecture, and security tooling collaboration.</i>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=130&section=footer" />
