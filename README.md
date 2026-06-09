


[![header](https://capsule-render.vercel.app/api?type=venom&height=200&section=header&text=Nice%20to%20meet%20you.%20I%20'm%20Diogo.&fontSize=42)](https://linkedin.com/in/diogoangelim)

<br><br>

I've spent eight years building software where correctness matters — payment systems, financial platforms, enterprise ERP, high-traffic web infrastructure. Over time I noticed a pattern: the hardest problems weren't in the code. They were in the decisions behind it — whether an operation was safe to retry, whether a state change was auditable, whether a judgment was based on reviewable evidence or untraceable assumptions. That pattern became the thread running through everything I've built.

I'm a full-stack engineer. Founder experience sharpened my judgment — it didn't replace my engineering identity.

<br>

---

## Experience

<br>

**Founding Engineer — [Naubly](https://naubly.com)** &nbsp;·&nbsp; *2019 – present*

**Problem:** Retail investors make portfolio decisions under significant uncertainty, with no traceable record of what evidence informed a decision or what assumptions failed.

**Constraint:** Building a reliable financial system as a solo founder means correctness failures aren't caught by a team. Every architectural decision carries full weight.

**What I built:** An investment decision-support platform that tracks evidence quality, surfaces contradictions and unknowns, and maintains reviewable learning across decisions. The system models a complete judgment lifecycle — from evidence assessment through assumption tracking to outcome review and lesson extraction — so a user can see not just *what* was decided, but *why*, and whether those reasons held up.

To support the financial operation layer safely, I designed [Signal](https://github.com/DiogoAngelim/signal) — a production correctness standard I later open-sourced — to make dangerous backend mutations idempotency-safe, replay-protected, and auditable by construction.

**Outcome:** A live application at [stocks-optimizer.vercel.app](https://stocks-optimizer.vercel.app) and a generalized infrastructure library that solves a class of correctness problems beyond fintech.

<br>

**Software Engineer — Union Sistemas de Desenvolvimento** &nbsp;·&nbsp; *2025*

**Problem:** A high-volume .NET ERP system with accounting logic distributed across a large codebase, where silent discrepancies in critical transaction paths don't surface immediately.

**What I did:** Added features, resolved complex bugs, and worked directly with domain experts to translate accounting rules into reliable code. Identified and corrected accounting mismatches in critical transaction paths — errors that would have produced material financial discrepancies if left undetected.

<br>

**Software Engineer — Codeable** &nbsp;·&nbsp; *2021 – 2022* &nbsp;·&nbsp; [credential](https://www.credential.net/58930281-2568-48db-a5df-a85e40244d6e?record_view=true)

Codeable admits engineers through a multi-stage technical screening process. Work here meant operating under client expectations, tight delivery constraints, and zero tolerance for regressions.

**Defining project:** Migrated 300+ active paying subscribers from one payment processor to another. The constraint was zero data loss and no service interruption during active billing cycles. Designed the migration sequence, handled edge cases in subscriber state, and delivered on schedule.

<br>

**Software Engineer — On Purpose Projects** &nbsp;·&nbsp; *2017 – 2021*

Four years building and operating client web platforms — from initial architecture through scaling to sustained high-traffic production. Learned early that performance problems, security gaps, and maintainability failures are rarely surprises: they're the result of decisions made earlier under different constraints. Developed a habit of designing for the operational state, not just the build state.

<br>

---

## Open Source

<br>

**[Signal](https://github.com/DiogoAngelim/signal)**

Signal started as internal infrastructure for Naubly's financial operations and became a generalized standard for backend correctness.

The core insight: most backend reliability failures aren't bugs in individual handlers — they're failures of contract. Operations lack stable names. Mutations aren't declared idempotent. Events describe hoped-for futures instead of recorded facts. Audit evidence isn't produced. Retries cause duplicate state changes. Signal addresses these as a unified correctness layer, not as individual patches.

It defines explicit contracts for Queries (reads), Mutations (intentional state changes), and Events (recorded facts), with enforced idempotency, replay protection, subscriber dedupe, structured audit evidence, and versioned operation names. Ships with a Postgres-backed idempotency store, a Fastify HTTP binding, a full protocol spec, CI/CD, and a runnable reference proof — payment capture, retry, replay, conflict, and audit observation — completable in under five minutes.

[Documentation](https://github.com/DiogoAngelim/signal/blob/main/docs/README.md) &nbsp;·&nbsp; [stocks-optimizer.vercel.app](https://stocks-optimizer.vercel.app) &nbsp;·&nbsp; [aware-guide.vercel.app](https://aware-guide.vercel.app)

<br>

**[html-to-gutenberg](https://github.com/DiogoAngelim/html-to-gutenberg)**

Converts arbitrary HTML into fully editable WordPress Gutenberg blocks. Published on npm. Supports Cloudflare R2 output, in-memory bundling, a job manifest API, TypeScript types, test coverage, and backwards compatibility for existing toolchains.

<br>

**[fetch-page-assets](https://github.com/DiogoAngelim/fetch-page-assets)**

Node.js utility for extracting and normalizing CSS, JS, fonts, and images from HTML pages and remote URLs, with R2 upload support. Used as a dependency within html-to-gutenberg.

<br>

---

## Portfolio

<br>

<table>
  <tr>
    <td align="center" width="50%">
      <a href="https://stocks-optimizer.vercel.app/" target="_blank">
        <img src="capitalIQ-hero.png" alt="capitalIQ" height="300"/>
      </a>
      <br/><br/>
      <strong>capitalIQ</strong>
      <br/>
      <sub>AI investment decision platform &nbsp;·&nbsp; <a href="https://stocks-optimizer.vercel.app/">live ↗</a></sub>
    </td>
    <td align="center" width="50%">
      <a href="#" target="_blank">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/refs/heads/main/algai.gif" alt="AlgAI" width="400"/>
      </a>
      <br/><br/>
      <strong>AlgAI</strong>
      <br/>
      <sub>Adaptive learning assistant</sub>
    </td>
  </tr>
  <tr><td colspan="2"><br/></td></tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://web.archive.org/web/20241001053257/https://webdifferent.com.au/" target="_blank">
        <img src="https://github.com/DiogoAngelim/DiogoAngelim/blob/main/w2.gif?raw=true" alt="Web Different" width="400"/>
      </a>
      <br/><br/>
      <strong>Web Different</strong>
      <br/>
      <sub>High-traffic agency platform &nbsp;·&nbsp; <a href="https://web.archive.org/web/20241001053257/https://webdifferent.com.au/">archive ↗</a></sub>
    </td>
    <td align="center" width="50%">
      <a href="https://web.archive.org/web/20230326034929/https://myfreight.com.au/" target="_blank">
        <img src="https://github.com/DiogoAngelim/DiogoAngelim/blob/main/myfreight.gif?raw=true" alt="My Freight" width="400"/>
      </a>
      <br/><br/>
      <strong>My Freight</strong>
      <br/>
      <sub>Logistics platform &nbsp;·&nbsp; <a href="https://web.archive.org/web/20230326034929/https://myfreight.com.au/">archive ↗</a></sub>
    </td>
  </tr>
  <tr><td colspan="2"><br/></td></tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://web.archive.org/web/20220301044510/https://blitzmdesign.com.au/" target="_blank">
        <img src="https://github.com/DiogoAngelim/DiogoAngelim/blob/main/blitz-2.0.gif?raw=true" alt="Blitz Design 2.0" width="400"/>
      </a>
      <br/><br/>
      <strong>Blitz Design 2.0</strong>
      <br/>
      <sub>Design studio platform &nbsp;·&nbsp; <a href="https://web.archive.org/web/20220301044510/https://blitzmdesign.com.au/">archive ↗</a></sub>
    </td>
    <td align="center" width="50%">
      <a href="https://codepen.io/digelim/pen/wbOggK" target="_blank">
        <img src="https://github.com/DiogoAngelim/DiogoAngelim/blob/main/blitzdesign.gif?raw=true" alt="Blitz Design" width="400"/>
      </a>
      <br/><br/>
      <strong>Blitz Design</strong>
      <br/>
      <sub>Frontend concept &nbsp;·&nbsp; <a href="https://codepen.io/digelim/pen/wbOggK">CodePen ↗</a></sub>
    </td>
  </tr>
  <tr><td colspan="2"><br/></td></tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://web.archive.org/web/20200811001303/https://www.prophecy.io/product-page" target="_blank">
        <img src="https://github.com/DiogoAngelim/DiogoAngelim/blob/main/prophecy.png?raw=true" alt="Prophecy" width="400"/>
      </a>
      <br/><br/>
      <strong>Prophecy</strong>
      <br/>
      <sub>Product marketing page &nbsp;·&nbsp; <a href="https://web.archive.org/web/20200811001303/https://www.prophecy.io/product-page">archive ↗</a></sub>
    </td>
    <td align="center" width="50%">
      <a href="https://b2bsoftwareadvisors.com/" target="_blank">
        <img src="https://github.com/DiogoAngelim/DiogoAngelim/blob/main/b2b.png?raw=true" alt="B2B Software Advisors" width="400"/>
      </a>
      <br/><br/>
      <strong>B2B Software Advisors</strong>
      <br/>
      <sub>Advisory platform &nbsp;·&nbsp; <a href="https://b2bsoftwareadvisors.com/">live ↗</a></sub>
    </td>
  </tr>
</table>

<br>

---

## Certifications & Recognition

<br>

<table>
  <tr>
    <td align="center" width="33%">
      <a href="https://www.codementor.io/@diogo_angelim?refer=badge">
        <img src="https://www.codementor.io/m-badges/diogo_angelim/find-me-on-cm-b.svg" width="200px" alt="Codementor badge"/>
      </a>
      <br/><br/>
      <sub><a href="https://www.codementor.io/@diogo_angelim?refer=badge">Codementor</a></sub>
    </td>
    <td align="center" width="33%">
      <a href="https://www.credential.net/58930281-2568-48db-a5df-a85e40244d6e?record_view=true" target="_blank">
        <img src="https://github.com/DiogoAngelim/DiogoAngelim/blob/main/codeable.png?raw=true" alt="Codeable WordPress Expert" width="200px"/>
      </a>
      <br/><br/>
      <sub><a href="https://www.credential.net/58930281-2568-48db-a5df-a85e40244d6e?record_view=true">Codeable WordPress Expert ↗</a></sub>
    </td>
    <td align="center" width="33%">
      <a href="https://www.coursera.org/account/accomplishments/verify/5TLHGJPFYLGR" target="_blank">
        <img src="https://github.com/DiogoAngelim/DiogoAngelim/blob/main/machine-learning.png?raw=true" alt="Machine Learning — Coursera" width="200px"/>
      </a>
      <br/><br/>
      <sub><a href="https://www.coursera.org/account/accomplishments/verify/5TLHGJPFYLGR">Machine Learning — Coursera ↗</a></sub>
    </td>
  </tr>
</table>

<br>

---

## Client Reviews

<br>

> *"He worked until all hours of the night getting a mission-critical project finished and anticipated possible challenges. I'm ready to hire him for my next project."*

<img src="https://github.com/DiogoAngelim/DiogoAngelim/blob/main/robert.png?raw=true" alt="Robert Johnson" width="32"/> &nbsp; **Robert Johnson** &nbsp;·&nbsp; PaidMembershipPro migration

<br>

> *"Diogo is very efficient. He listened patiently to all my needs and helped me accomplish exactly what I wanted. He always replied within an hour."*

<img src="https://github.com/DiogoAngelim/DiogoAngelim/blob/main/carman.png?raw=true" alt="Carman Chung" width="32"/> &nbsp; **Carman Chung**

<br>

> *"Diogo delivered above and beyond what was expected."*

**Paul Morin** &nbsp;·&nbsp; Date filtering plugin

<br>

> *"Fast and super easy to work with. Work was completed to a high standard."*

<img src="https://github.com/DiogoAngelim/DiogoAngelim/blob/main/adam.png?raw=true" alt="Adam Selley" width="32"/> &nbsp; **Adam Selley**

<br>

---

## Education

<br>

Three technical programs — Computer Science, Software Engineering, and Economics — each left early to take on production engineering work. The economics coursework directly informed Naubly's quantitative modeling. Full professional English fluency (six years, Associação Cultural Brasil–Estados Unidos).

<br>

---

<br>

[![Email](https://img.shields.io/badge/hello%40diogoangelim.dev-blue?style=flat&logo=gmail&logoColor=white)](mailto:hello@diogoangelim.dev) &nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-diogoangelim-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/diogoangelim) &nbsp;
[![Website](https://img.shields.io/badge/naubly.com-1f2937?style=flat&logo=google-chrome&logoColor=white)](https://naubly.com) &nbsp;
[![GitHub](https://img.shields.io/badge/diogoangelim-181717?style=flat&logo=github&logoColor=white)](https://github.com/diogoangelim)

<br/><br/>
