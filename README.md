# Diogo Angelim

I've spent eight years building software where correctness matters — payment systems, financial platforms, enterprise ERP, high-traffic web infrastructure. Over time I noticed a pattern: the hardest problems weren't in the code. They were in the decisions behind it — whether an operation was safe to retry, whether a state change was auditable, whether a judgment was based on reviewable evidence or untraceable assumptions. That pattern became the thread running through everything I've built.

I'm a full-stack engineer. Founder experience sharpened my judgment — it didn't replace my engineering identity.

<p>
  <a href="https://www.codementor.io/@diogo_angelim?refer=badge">
    <img src="https://www.codementor.io/m-badges/diogo_angelim/find-me-on-cm-b.svg" width="200" alt="Find me on Codementor — view my profile"/>
  </a>
</p>

<br>

---

## Experience

<br>

**Founding Engineer — [Naubly](https://naubly.com)** &nbsp;·&nbsp; *2019 – present*

**Problem:** Retail investors make portfolio decisions under significant uncertainty, with no traceable record of what evidence informed a decision or what assumptions failed.

**Constraint:** Building a reliable financial system as a solo founder means correctness failures aren't caught by a team. Every architectural decision carries full weight.

**What I built:** An investment decision-support platform that tracks evidence quality, surfaces contradictions and unknowns, and maintains reviewable learning across decisions. The system models a complete judgment lifecycle — from evidence assessment through assumption tracking to outcome review and lesson extraction — so a user can see not just *what* was decided, but *why*, and whether those reasons held up.

To support the financial operation layer safely, I designed [Signal](https://github.com/DiogoAngelim/signal) — a production correctness standard I later open-sourced — to make dangerous backend mutations idempotency-safe, replay-protected, and auditable by construction.

**Outcome:** A financial decision-support application in [Signal's Stocks Optimizer example](https://github.com/DiogoAngelim/signal/tree/main/examples/stocks-optimizer), plus a generalized infrastructure library addressing correctness problems beyond fintech.

**Additional engineering work:** Built [Neural Configuration Lab](https://github.com/DiogoAngelim/neural-configuration-lab), a local-first neural-network experimentation tool for numeric tabular classification and regression. It combines configurable candidate-space search, train/validation/test separation, training-only preprocessing, naive-baseline comparison, bounded multi-fidelity search, and exportable experiment reports. Its seeded benchmark harness covers binary classification, multiclass classification, and regression; synthetic benchmarks validate reproducibility and workflow behavior, not real-world predictive quality.

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

[Documentation](https://github.com/DiogoAngelim/signal/blob/main/docs/README.md) &nbsp;·&nbsp; [Stocks Optimizer source](https://github.com/DiogoAngelim/signal/tree/main/examples/stocks-optimizer) &nbsp;·&nbsp; [AlgAI dashboard source](https://github.com/DiogoAngelim/signal/tree/main/examples/algai-parent-dashboard)

<br>

**[html-to-gutenberg](https://github.com/DiogoAngelim/html-to-gutenberg)**

Converts arbitrary HTML into fully editable WordPress Gutenberg blocks. Published on npm. Supports Cloudflare R2 output, in-memory bundling, a job manifest API, TypeScript types, test coverage, and backwards compatibility for existing toolchains.


<br>

---

## Portfolio

<br>

<table>
  <tr>
    <td align="center" width="50%" valign="top">
      <a href="https://github.com/DiogoAngelim/signal/tree/main/examples/stocks-optimizer">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/capitalIQ-hero.png" alt="capitalIQ investment decision platform screenshot" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://github.com/DiogoAngelim/signal/tree/main/examples/stocks-optimizer">capitalIQ / Stocks Optimizer</a></strong>
      <br/>
      <sub>Investment decision-support platform · <a href="https://github.com/DiogoAngelim/signal/tree/main/examples/stocks-optimizer">source ↗</a></sub>
    </td>
    <td align="center" width="50%" valign="top">
      <a href="https://neural-configuration-lab.vercel.app/">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/neural-configuration-lab.svg" alt="Neural Configuration Lab project cover" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://github.com/DiogoAngelim/neural-configuration-lab">Neural Configuration Lab</a></strong>
      <br/>
      <sub>Neural-network experiments for tabular data · <a href="https://neural-configuration-lab.vercel.app/">live app ↗</a> · <a href="https://github.com/DiogoAngelim/neural-configuration-lab">source ↗</a></sub>
    </td>
  </tr>
  <tr><td colspan="2"><br/></td></tr>
  <tr>
    <td align="center" width="50%" valign="top">
      <a href="https://github.com/DiogoAngelim/signal/tree/main/examples/algai-parent-dashboard">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/algAI.png" alt="AlgAI adaptive learning assistant screenshot" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://github.com/DiogoAngelim/signal/tree/main/examples/algai-parent-dashboard">AlgAI</a></strong>
      <br/>
      <sub>Adaptive learning assistant · <a href="https://github.com/DiogoAngelim/signal/tree/main/examples/algai-parent-dashboard">source ↗</a></sub>
    </td>
    <td align="center" width="50%" valign="top">
      <a href="https://web.archive.org/web/20241001053257/https://webdifferent.com.au/">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/w2.gif" alt="Web Different high-traffic agency platform recording" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://web.archive.org/web/20241001053257/https://webdifferent.com.au/">Web Different</a></strong>
      <br/>
      <sub>High-traffic agency platform · <a href="https://web.archive.org/web/20241001053257/https://webdifferent.com.au/">archived site ↗</a></sub>
    </td>
  </tr>
  <tr><td colspan="2"><br/></td></tr>
  <tr>
    <td align="center" width="50%" valign="top">
      <a href="https://web.archive.org/web/20230326034929/https://myfreight.com.au/">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/myfreight.gif" alt="My Freight logistics platform recording" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://web.archive.org/web/20230326034929/https://myfreight.com.au/">My Freight</a></strong>
      <br/>
      <sub>Logistics platform · <a href="https://web.archive.org/web/20230326034929/https://myfreight.com.au/">archived site ↗</a></sub>
    </td>
    <td align="center" width="50%" valign="top">
      <a href="https://web.archive.org/web/20220301044510/https://blitzmdesign.com.au/">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/blitz-2.0.gif" alt="Blitz Design 2.0 website recording" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://web.archive.org/web/20220301044510/https://blitzmdesign.com.au/">Blitz Design 2.0</a></strong>
      <br/>
      <sub>Design studio platform · <a href="https://web.archive.org/web/20220301044510/https://blitzmdesign.com.au/">archived site ↗</a></sub>
    </td>
  </tr>
  <tr><td colspan="2"><br/></td></tr>
  <tr>
    <td align="center" width="50%" valign="top">
      <a href="https://codepen.io/digelim/pen/wbOggK">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/blitzdesign.gif" alt="Blitz Design frontend concept recording" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://codepen.io/digelim/pen/wbOggK">Blitz Design</a></strong>
      <br/>
      <sub>Frontend concept · <a href="https://codepen.io/digelim/pen/wbOggK">CodePen ↗</a></sub>
    </td>
    <td align="center" width="50%" valign="top">
      <a href="https://web.archive.org/web/20200811001303/https://www.prophecy.io/product-page">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/prophecy.png" alt="Prophecy product marketing page screenshot" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://web.archive.org/web/20200811001303/https://www.prophecy.io/product-page">Prophecy</a></strong>
      <br/>
      <sub>Product marketing page · <a href="https://web.archive.org/web/20200811001303/https://www.prophecy.io/product-page">archived site ↗</a></sub>
    </td>
  </tr>
  <tr><td colspan="2"><br/></td></tr>
  <tr>
    <td align="center" width="50%" valign="top">
      <a href="https://b2bsoftwareadvisors.com/">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/b2b.png" alt="B2B Software Advisors advisory platform screenshot" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://b2bsoftwareadvisors.com/">B2B Software Advisors</a></strong>
      <br/>
      <sub>Advisory platform · <a href="https://b2bsoftwareadvisors.com/">live site ↗</a></sub>
    </td>
    <td width="50%"></td>
  </tr>
</table>

<br>

---

## Certifications & Recognition

<br>

<table>
  <tr>
    <td align="center" width="50%">
      <a href="https://www.credential.net/58930281-2568-48db-a5df-a85e40244d6e?record_view=true" target="_blank">
        <img src="https://github.com/DiogoAngelim/DiogoAngelim/blob/main/codeable.png?raw=true" alt="Codeable WordPress Expert" width="200px"/>
      </a>
      <br/><br/>
      <sub><a href="https://www.credential.net/58930281-2568-48db-a5df-a85e40244d6e?record_view=true">Codeable WordPress Expert ↗</a></sub>
    </td>
    <td align="center" width="50%">
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
