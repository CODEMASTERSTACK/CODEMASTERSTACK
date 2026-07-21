<!--
  Replace before publishing:
  you@example.com          → your email
  your-linkedin            → your LinkedIn handle
  your-site.dev            → your portfolio URL (delete the badge if you don't have one)
  repo-name-two/three      → the exact (case-sensitive) repo names for the pinned-project cards

  Note on // 05 · metrics:
  The stats/top-langs/pin cards call the public github-readme-stats.vercel.app instance,
  which is shared across thousands of profiles and rate-limits during peak hours — a known,
  widely-reported issue with that free service, not a bug in this file. cache_seconds=86400
  below reduces how often it re-hits the limit. If it still breaks often, self-hosting your
  own instance (documented at github.com/anuraghazra/github-readme-stats) fixes it for good.
  The activity graph below runs on a separate service and isn't affected by this.

  IMPORTANT — the whoami card below is a real file, not embedded data:
  GitHub strips data:// image URIs when it renders a README, so this points to
  assets/whoami.svg instead. Keep that file in an `assets/` folder next to this
  README.md when you push the repo, or the image won't resolve.
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,100:161B26&height=210&section=header&text=CODEMASTERSTACK&fontSize=52&fontColor=6EE7F9&fontAlignY=38&desc=Software%20Engineer%20%C2%B7%20Big%20Data%20Analytics&descAlignY=58&descSize=16&descColor=8B949E" width="100%"/>

<a href="https://github.com/CODEMASTERSTACK">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=3200&pause=1200&color=A78BFA&center=true&vCenter=true&width=560&lines=Building+SaaS+products+end-to-end;Backend+%E2%86%92+auth+%E2%86%92+data+model+%E2%86%92+UI;Systems-first%2C+detail-obsessed" />
</a>

</div>

<br>

<div align="center">
<img src="assets/whoami.svg" width="560" alt="Kripal Singh — whoami terminal card"/>
</div>

<br>

##### `// 01 · overview`

Most of what I build sits at the intersection of two disciplines — the data-and-systems thinking from a Big Data Analytics degree, and the day-to-day discipline of an operations internship spent inside Zoho CRM, coordinating people rather than just code. That combination shows up in how I approach engineering: I'd rather spend an extra evening getting a gating transaction correct than ship something that only works when nothing goes wrong.

Outside of backend work, I spend time on SEO strategy and structured, zero-budget growth planning — the same instinct for "what actually moves the number" applied to a different system.

<br>

##### `// 02 · stack`

<table>
<tr>
<td valign="top" width="33%">

**Frontend**

<img src="https://skillicons.dev/icons?i=html,css,js,ts,react,tailwind&theme=dark" /><br/>

</td>
<td valign="top" width="33%">

**Backend**

<img src="https://skillicons.dev/icons?i=nodejs,py,firebase,gcp,mysql,postgres&theme=dark" /><br/><br/>
<img src="https://img.shields.io/badge/Cloudflare_Workers-0D1117?style=flat-square&logo=cloudflareworkers&logoColor=F38020" />
<img src="https://img.shields.io/badge/Gemini_API-0D1117?style=flat-square&logo=googlegemini&logoColor=6EE7F9" />

</td>
<td valign="top" width="33%">

**Tools / Platforms**

<img src="https://skillicons.dev/icons?i=git,github,vscode,figma&theme=dark" /><br/><br/>
<img src="https://img.shields.io/badge/Excel-0D1117?style=flat-square&logo=microsoftexcel&logoColor=217346" />
<img src="https://img.shields.io/badge/Power_BI-0D1117?style=flat-square&logo=powerbi&logoColor=F2C811" />
<img src="https://img.shields.io/badge/Zoho_CRM-0D1117?style=flat-square&logo=zoho&logoColor=E42527" />

</td>
</tr>
</table>

<br>

##### `// 03 · featured work`

<table>
<tr>
<td width="100%">

**Resume Builder — AI resume generation, from auth to output**
A full-stack SaaS app on a serverless backend: Google Sign-In through Firebase, resume content generated through Gemini with an OpenRouter / Claude fallback, and usage metered through a points-based gating system.

<img src="https://img.shields.io/badge/Cloudflare_Workers-0D1117?style=flat-square&logo=cloudflareworkers&logoColor=F38020" />
<img src="https://img.shields.io/badge/Firebase_Auth-0D1117?style=flat-square&logo=firebase&logoColor=FFCA28" />
<img src="https://img.shields.io/badge/Firestore-0D1117?style=flat-square&logo=firebase&logoColor=A78BFA" />
<img src="https://img.shields.io/badge/Gemini-0D1117?style=flat-square&logo=googlegemini&logoColor=6EE7F9" />

- Points-based gating enforced through atomic Firestore transactions, closing a race condition on the refund path
- Removed dead and insecure code paths after a full security pass on the gating logic

</td>
</tr>
</table>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/pin/?username=CODEMASTERSTACK&repo=repo-name-two&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=6EE7F9&icon_color=A78BFA&text_color=8B949E&cache_seconds=86400" height="150"/>
<img src="https://github-readme-stats.vercel.app/api/pin/?username=CODEMASTERSTACK&repo=repo-name-three&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=6EE7F9&icon_color=A78BFA&text_color=8B949E&cache_seconds=86400" height="150"/>

</div>

<br>

##### `// 04 · currently`

- Hardening the resume builder's gating system — atomic transactions, refund race-condition fixes
- Working through a structured SEO exercise — backlink research, outreach strategy, zero-budget growth planning
- Reading through Big Data Analytics coursework alongside the build work

<br>

##### `// 05 · metrics`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=CODEMASTERSTACK&show_icons=true&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=6EE7F9&icon_color=A78BFA&text_color=8B949E&cache_seconds=86400" height="165" alt="Kripal Singh's GitHub stats"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CODEMASTERSTACK&layout=compact&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=6EE7F9&text_color=8B949E&cache_seconds=86400" height="165" alt="Kripal Singh's most used languages"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=CODEMASTERSTACK&theme=github-compact&bg_color=0D1117&color=6EE7F9&line=A78BFA&point=8B949E&hide_border=true" width="100%" alt="Kripal Singh's contribution activity"/>

</div>

<br>

##### `// 06 · connect`

<div align="center">

<a href="mailto:you@example.com"><img src="https://img.shields.io/badge/Email-0D1117?style=flat-square&logo=gmail&logoColor=6EE7F9" /></a>
<a href="https://linkedin.com/in/your-linkedin"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=flat-square&logo=linkedin&logoColor=A78BFA" /></a>
<a href="https://your-site.dev"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=flat-square&logo=vercel&logoColor=8B949E" /></a>

</div>

<br>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,100:161B26&height=70&section=footer" width="100%"/>
<sub>building in public, one commit at a time</sub>
</div>
