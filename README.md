<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Aditya%20Bhagwat&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Software%20Engineer%20in%20Test%20%C2%B7%20Quality%20%C3%97%20AI&descAlignY=58&descSize=18&animation=fadeIn" alt="Aditya Bhagwat banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/baggy2797">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=36BCF7&center=true&vCenter=true&width=620&lines=I+break+things+so+your+users+don't+%F0%9F%90%9B;SDET+II+%40+Okta+%F0%9F%94%90;ex-Apple+%C2%B7+ex-Twitter+%C2%B7+ex-Infosys;Teaching+LLMs+to+hunt+flaky+tests+%F0%9F%A4%96;Ask+me+about+football+%E2%9A%BD" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Okta-SDET_II-007DC1?style=flat-square&logo=okta&logoColor=white" />
  <img src="https://img.shields.io/badge/ex-Apple-000000?style=flat-square&logo=apple&logoColor=white" />
  <img src="https://img.shields.io/badge/ex-Twitter-1DA1F2?style=flat-square&logo=x&logoColor=white" />
  <img src="https://img.shields.io/badge/ex-Infosys-007CC3?style=flat-square&logo=infosys&logoColor=white" />
  <img src="https://img.shields.io/badge/📍-Bengaluru-FF6F61?style=flat-square" />
  <img src="https://komarev.com/ghpvc/?username=baggy2797&style=flat-square&color=blueviolet&label=Profile+views" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/adibhagwat/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:bhagwataditya226@gmail.com"><img src="https://img.shields.io/badge/Email-Say_hi-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<p align="center">
  <b>🧭 Jump to:</b>
  <a href="#-the-lab">🛠 The Lab</a> •
  <a href="#-quest-log">🗺 Quest Log</a> •
  <a href="#-the-archive">📦 Archive</a> •
  <a href="#-inventory">🎒 Inventory</a> •
  <a href="#-by-the-numbers">📊 Stats</a> •
  <a href="#-bonus-round">🎲 Bonus</a>
</p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🧙 About me

<table>
<tr>
<td width="60%" valign="top">

I build the machinery that says **"yes, ship it"**, or more often, **"absolutely not, here's why"**.

That's five years of end-to-end automation for **iOS, Android, web and APIs** at Twitter, Apple and now Okta, where a bug can lock someone out of everything.

Lately I've been chasing one question:

> **Where does an LLM actually help QA, and where does it just add more flakiness?**

Everything in **The Lab** below is an attempt to answer it.

</td>
<td width="40%" valign="top">

```yaml
name: Aditya Bhagwat
role: SDET II @ Okta
based_in: Bengaluru, India
degrees:
  - M.S. Artificial Intelligence
  - M.S. Computer Science
  - B.Tech Information Technology
focus:
  - mobile + web E2E automation
  - CI reliability & security
  - LLMs for testing
fuel: ☕ + ⚽
```

</td>
</tr>
</table>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🛠 The Lab

<p align="center"><i>Four tools that each fix one annoying part of test infrastructure, plus a demo that wires them together.</i><br><sub>🔒 = private while I polish it · ↗ = public</sub></p>

<table>
<tr>
<td width="50%" valign="top">

### 🧪 flakewatch 🔒
**A detective for flaky tests.**
Reads the JUnit XML your CI already produces, scores every test across runs, and explains *why* each one is flaky with Selenium-aware rules and an optional LLM. Then it quarantines tests with an expiry date.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Anthropic](https://img.shields.io/badge/-Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)

</td>
<td width="50%" valign="top">

### 🧭 journeyprobe 🔒
**Persona tests written by an LLM, replayed without one.**
*"Maya, a budget-conscious student, wants a mug"* becomes a reviewable YAML plan. Playwright replays it deterministically, and broken locators get suggested fixes as a diff that's never applied automatically.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Pydantic](https://img.shields.io/badge/-Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡 hardened-actions-template 🔒
**Least-privilege CI you can copy.**
SHA-pinned actions and locked-down permissions, scanned by zizmor, CodeQL, gitleaks and Trivy. Includes `audit.py`, a stdlib-only auditor that checks *any* repo's workflows and runs on the template itself.

![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Security](https://img.shields.io/badge/-DevSecOps-E34F26?style=flat-square&logo=springsecurity&logoColor=white)

</td>
<td width="50%" valign="top">

### ⏰ token-expiry-watch 🔒
**No more 3 a.m. "token expired" failures.**
A GitHub Action that reads a token's expiry header and fails the build, or opens an issue, *N days before* the token expires. Handles multiple named tokens and providers other than GitHub.

![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎛 qa-suite-demo 🔒
**All four tools, one pipeline.**
An offline end-to-end harness: journeyprobe → flakewatch → token-expiry-watch → hardened-actions-template. You can watch the whole QA loop run without cloud credentials.

![Pipeline](https://img.shields.io/badge/-End--to--End-6E40C9?style=flat-square&logo=githubactions&logoColor=white)

</td>
<td width="50%" valign="top">

### 🛒 [LLM-Selenium-ecommerce ↗](https://github.com/baggy2797/LLM-OpenAI-Selenium-ecommerce)
**Plain English in, browser actions out.**
> *"Search for matte lipstick and add the first product to the cart."*

An LLM turns the sentence into structured steps and Selenium executes them. This is the prototype that grew into journeyprobe.

![Selenium](https://img.shields.io/badge/-Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

</td>
</tr>
</table>

<details>
<summary><b>🔬 Deep dive: how flakewatch works</b> (click to expand)</summary>

<br>

```mermaid
flowchart LR
  X[JUnit XML<br/>pytest · TestNG · jest] --> P[parse + merge<br/>retries & shards]
  P --> H[(history.db)]
  H --> A[score<br/>flip rate · retry-pass<br/>same-commit pass+fail]
  A --> C{classify}
  C --> R[Selenium-aware rules]
  C --> L[LLM<br/>redacted + JSON-validated]
  L -. any failure .-> R
  R --> Q[quarantine.json<br/>TTL per entry]
  R --> PR[PR comment +<br/>job summary]
```

It catches `StaleElementReferenceException`, `TimeoutException`, `ElementClickInterceptedException` and others. "Is this really a stale-element race?" is usually the first question UI teams ask.

</details>

<details>
<summary><b>🔬 Deep dive: journeyprobe's author → replay → heal loop</b> (click to expand)</summary>

<br>

```mermaid
flowchart LR
  P[👤 Persona] --> G[✍️ generate<br/>LLM, once]
  G --> Y[📄 plan.yaml<br/>reviewed in PR]
  Y --> R[▶️ replay<br/>Playwright, no LLM]
  R -- locator breaks --> H[🩹 heal<br/>LLM proposes diff]
  H -. human approves .-> Y
```

```yaml
- name: 'maya: Buy a ceramic mug'
  steps:
  - {action: search, query: Mug}
  - {action: click, target: {role: link, name: Ceramic Mug}}
  - {action: add_to_cart}
  - {action: assert_text, text: Added to cart}
```

</details>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🗺 Quest Log

```mermaid
timeline
    2015-2019 : 🎓 B.Tech IT, University of Mumbai
              : 💻 Web Dev Intern, DBIT
    2019-2021 : 🎓 M.S. Computer Science, Binghamton
    2021-2023 : 🐦 Twitter, Software Engineer
    2023-2024 : 💼 Software Engineer, SF Bay Area
    2024      : 🍎 Apple, Software Engineer
              : 🏢 Infosys, IT Architect
    2025      : 🎓 M.S. AI, Univ. of the Cumberlands
              : 🔐 Okta, SDET II
```

<table>
<tr>
<th>🏢</th><th>Role</th><th>When</th><th>Highlights</th>
</tr>
<tr>
<td><img src="https://img.shields.io/badge/-Okta-007DC1?style=for-the-badge&logo=okta&logoColor=white" /></td>
<td>Software Engineer in Test II</td>
<td>Aug 2025 → now<br><sub>Bengaluru</sub></td>
<td>Testing identity, where a bug can lock someone out of everything. No pressure.</td>
</tr>
<tr>
<td><img src="https://img.shields.io/badge/-Infosys-007CC3?style=for-the-badge&logo=infosys&logoColor=white" /></td>
<td>IT Architect</td>
<td>Oct 2024 → May 2025<br><sub>Austin</sub></td>
<td>Architecture and delivery for enterprise clients, at the point where test strategy meets system design.</td>
</tr>
<tr>
<td><img src="https://img.shields.io/badge/-Apple-000000?style=for-the-badge&logo=apple&logoColor=white" /></td>
<td>Software Engineer</td>
<td>Mar 2024 → Sep 2024<br><sub>Seattle</sub></td>
<td>End-to-end iOS automation with XCUITest, wired into CI.</td>
</tr>
<tr>
<td><img src="https://img.shields.io/badge/-Undisclosed-555555?style=for-the-badge&logo=letsencrypt&logoColor=white" /></td>
<td>Software Engineer</td>
<td>Feb 2023 → Feb 2024<br><sub>SF Bay Area</sub></td>
<td>🤐 Can't say. It was good though.</td>
</tr>
<tr>
<td><img src="https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=x&logoColor=white" /></td>
<td>Software Engineer</td>
<td>Jul 2021 → Jan 2023<br><sub>San Francisco</sub></td>
<td>
• E2E framework on <b>XCUITest + Espresso</b>, integrated with Selenium and Appium<br>
• <b>Platform-agnostic test plans</b> driving iOS and Android from one design<br>
• Visual regression testing with <b>Applitools</b>, plus BrowserStack and Sauce Labs<br>
• 🏆 <b>Tweeps' Choice Award</b> at HackWeek 2021 with the Music Spaces team
</td>
</tr>
<tr>
<td><img src="https://img.shields.io/badge/-DBIT-8B0000?style=for-the-badge&logo=googlescholar&logoColor=white" /></td>
<td>Website Developer Intern</td>
<td>Jun 2018 → Jan 2019<br><sub>Mumbai</sub></td>
<td>Built pages for the Training & Placement Cell. My first time shipping to real users.</td>
</tr>
</table>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📦 The Archive

<details>
<summary><b>Grad school and side projects</b> (click to open the vault 🗝)</summary>

<br>

| Project | What it does | Stack |
|---|---|---|
| [📺 TV Shows Muster & Analysis](https://github.com/baggy2797/TV-Shows-Muster-and-Analysis) | Sentiment analysis, topic modeling and social-network analysis of tweets and IMDb reviews, with a web dashboard. Team project. | Python · NLP · Jupyter |
| [💳 Credit Card Digit Recognition](https://github.com/baggy2797/Credit-Card-Digit-Recognition-and-Provider-Identification-using-Correlation-based-Template-Matching-) | Finds a card in an image, OCRs all 16 digits with template matching, and identifies Visa, Mastercard or Amex. | OpenCV · Python |
| [🛍 eBay Website Automation](https://github.com/baggy2797/Ebay-Website-Automation) | UI automation suite for eBay flows. | Java · Selenium |
| [💰 CryptoCurrency Tracker](https://github.com/baggy2797/CryptoCurrency-Tracker) | Five CLI apps on the CoinMarketCap API: live prices, portfolio tracking and Excel export. | Python |
| [⭐ Star Wars Tic-Tac-Toe](https://github.com/baggy2797/Star-Wars-Themed-Tic-Tac-Toe) | Tic-tac-toe, but the Force decides. | Python |
| [🧠 Computer Organization & Architecture](https://github.com/baggy2797/Computer-Organization-and-Architecture) | CS 520 coursework at Binghamton. | — |
| [🧩 LeetCode](https://github.com/baggy2797/Leetcode) | Interview prep, preserved in amber. | Java · Python |

</details>

## 🎒 Inventory

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,python,swift,js,aws,docker,githubactions,jenkins,selenium,postman,git,linux&perline=6&theme=dark" alt="Skill icons" />
</p>

<table align="center">
<tr><td><b>📱 Mobile</b></td><td>XCUITest · Espresso · Appium</td></tr>
<tr><td><b>🌐 Web</b></td><td>Selenium · Playwright</td></tr>
<tr><td><b>👀 Visual / devices</b></td><td>Applitools · Sauce Labs · BrowserStack</td></tr>
<tr><td><b>☁️ Cloud</b></td><td>AWS Lambda · API Gateway · SQS · DynamoDB</td></tr>
<tr><td><b>🔁 CI/CD + security</b></td><td>Jenkins · GitHub Actions · Docker · CodeQL · gitleaks · Trivy</td></tr>
<tr><td><b>🔌 API + tooling</b></td><td>REST · Postman · TestRail · Git</td></tr>
<tr><td><b>🤖 AI</b></td><td>LLMs · Generative AI · OpenAI + Anthropic APIs · AI ethics</td></tr>
<tr><td><b>🗣 Spoken</b></td><td>English · Hindi · Marathi · a little Sanskrit</td></tr>
</table>

## 📊 By the numbers

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=baggy2797&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=baggy2797&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top languages" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=baggy2797&theme=tokyonight&hide_border=true" alt="Streak" />
</p>
<p align="center">
  <img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=baggy2797&theme=tokyo-night&hide_border=true&area=true" alt="Contribution graph" />
</p>

## 🎲 Bonus round

<p align="center"><i>Click to reveal 👇</i></p>

<details>
<summary>❓ <b>What's my favorite sound?</b></summary>
<br>🐞➡️✅ A red test turning green. A close second: a flaky test getting quarantined with an expiry date.
</details>

<details>
<summary>❓ <b>What's my most dangerous topic of conversation?</b></summary>
<br>⚽ Football. I can do 24 hours on it. Bring a chair.
</details>

<details>
<summary>❓ <b>What do I believe?</b></summary>
<br>🌏 <i>वसुधैव कुटुम्बकम्</i>: the world is one family. So say hi, I like meeting new people.
</details>

<br>

<p align="center">
  <b>Got a flaky test, a wild idea, or a hot football take?</b><br><br>
  <a href="https://www.linkedin.com/in/adibhagwat/"><img src="https://img.shields.io/badge/Let's_talk-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" width="100%" />
