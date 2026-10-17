# Diogo Angelim

**Senior Software Engineer · Full-Stack Engineering · Fintech & Complex Systems**

I build and improve software where correctness, performance, and maintainability matter: financial applications, backend APIs, complex integrations, and web platforms. I work across the stack—from architecture and data models to user-facing experiences and production operations—and can join as an independent engineer or as an ongoing delivery partner for an agency.

- **Availability:** Immediately
- **Engagement:** Project-based or ongoing retainer
- **Target rate:** US$15/hour or US$1,000/month retainer, depending on scope
- **Working language:** English
- **Core stack:** TypeScript/JavaScript, React, Next.js, Node.js, Python, SQL, Rust, AWS, Docker, Cloudflare

<p>
  <a href="https://www.codementor.io/@diogo_angelim?refer=badge">
    <img src="https://www.codementor.io/m-badges/diogo_angelim/find-me-on-cm-b.svg" width="200" alt="Find me on Codementor — view my profile"/>
  </a>
</p>

---

## Selected work

### Signal — decision-processing infrastructure

**[Repository](https://github.com/DiogoAngelim/signal) · [Documentation](https://github.com/DiogoAngelim/signal/blob/main/docs/README.md)**

Signal is an open-source TypeScript platform for applications that need decisions and their execution history to be explicit, reviewable, and replay-safe. It models a lifecycle around events, evidence, assessment, decisions, learning, memory, replay, and audit.

- Separates protocol/runtime infrastructure from domain-specific decision logic.
- Defines Queries, Mutations, and Events as explicit contracts.
- Implements capabilities including idempotency, replay protection, subscriber deduplication, structured audit evidence, and versioned operation names.
- Includes a runnable reference proof for payment capture, retry, replay, conflict handling, and audit evidence.
- Provides reusable packages and examples intended to reduce duplicated infrastructure when building new applications.

Signal is an open-source engineering project. The repository documents its current implementation and proof workflows; it should not be interpreted as a claim that every capability is deployed in a commercial production environment.

### Stocks Optimizer — investment research and portfolio decisions

**[Source in Signal](https://github.com/DiogoAngelim/signal/tree/main/examples/stocks-optimizer) · [Signal](https://github.com/DiogoAngelim/signal)**

An investment-focused application example for researching portfolio decisions and strategy-based trading opportunities. It applies a structured decision workflow to investment concepts and evaluates strategy signals through backtesting.

Machine learning can complement Modern Portfolio Theory (MPT), for example by supporting return estimates or identifying patterns, but it does **not** guarantee better risk-adjusted performance. I do not claim a numerical improvement over MPT without a reproducible, out-of-sample comparison that accounts for transaction costs, slippage, and risk.

### Neural Configuration Lab — neural-network experimentation

**[Repository](https://github.com/DiogoAngelim/neural-configuration-lab) · [Live application](https://neural-configuration-lab.vercel.app/)**

A tool for controlled experiments with scikit-learn multilayer perceptrons on numeric tabular classification and regression tasks.

- Configurable candidate search with bounded trial and time budgets.
- Train/validation/test separation, with preprocessing fitted on training data only.
- Task-appropriate metrics and comparison against a naive baseline.
- Seeded benchmark scenarios, repeat runs, and exportable experiment reports.
- CSV checks and explicit reporting of the evaluation protocol.

Synthetic benchmark scenarios validate the experiment workflow and reproducibility; they are **not evidence of real-world predictive superiority**. Credible model comparisons require representative data and a predeclared evaluation protocol.

### AlgAI — learning and independent understanding

**[Project source within Signal](https://github.com/DiogoAngelim/signal/tree/main/examples/algai-parent-dashboard) · [Public project repository](https://github.com/DiogoAngelim/algai-landing)**

AlgAI is a learning experience designed to help learners move from confusion toward independent understanding through a question, expectation, and explanation flow. The related application code describes a TypeScript/Fastify backend, PostgreSQL with Drizzle ORM, Redis integration, a Next.js learner experience, Google sign-in, and teacher-defined symbol mappings. The application repository is private, so the public landing repository is provided for navigation rather than as a source-code link.

### HTML to Gutenberg — editable WordPress blocks

**[Public repository](https://github.com/DiogoAngelim/html-to-gutenberg)**

An open-source tool that converts HTML into editable WordPress Gutenberg blocks. It supports editing content such as text, images, links, and other block elements, and generates a preview to help users understand how the result will appear in the WordPress editor.

- **Reported adoption:** approximately 600 downloads per week.
- **Reported workflow improvement:** conversion work that could take hours is reduced to seconds.
- Published as a reusable package for WordPress-related workflows.

The download figure is approximate and may vary over time. These adoption and workflow metrics are based on my reports and should be checked against current package statistics before being quoted as independently verified figures.

---

## Experience

### Founder & Software Engineer — Naubly
*2019–present*

I build software products and reusable engineering tools alongside freelance and platform-based client work. Projects include Signal and its application examples, AlgAI, Neural Configuration Lab, and developer tooling such as HTML to Gutenberg.

My work spans product definition, system architecture, backend and frontend implementation, data modeling, integration design, automated testing, and delivery. I focus on maintainable foundations that make new product work more efficient without obscuring correctness or operational constraints.

### Software Engineer — Union Sistemas de Desenvolvimento
*2025*

Worked on a .NET ERP used by customers across southeastern Brazil. I delivered improvements, proposed solutions, and investigated complex bugs in critical application paths. The business's clients have performed **billions of transactions cumulatively**, according to the scale information available to me; this refers to aggregate historical transaction volume, not transactions per second or a benchmark I independently measured.

### Software Engineer — Codeable
*2021–2022 · [Credential](https://www.credential.net/58930281-2568-48db-a5df-a85e40244d6e?record_view=true)*

Delivered custom WordPress and backend work for approximately 10 clients, including APIs, ecommerce functionality, performance optimization, and payment-related migrations.

- **Reported performance result:** improved a client site's Google Lighthouse score from 22 to 98.
- **Reported payment migration:** completed a payment integration migration in under 24 hours, with zero reported service disruption.
- **Subscriber migration:** helped migrate more than 300 active paying subscribers between payment processors. The migration was critical because disruption could have led to lost revenue.

These outcomes reflect my project records and recollection; private supporting evidence is available where client confidentiality permits.

### Software Engineer — On Purpose Projects
*2017–2021*

Worked across the agency delivery lifecycle, from scoping and client communication to implementation and production support.

- Built custom PHP and JavaScript pages and templates using multiple frameworks.
- Developed reusable templates and an internal framework to improve delivery efficiency.
- Integrated CMS functionality so clients could customize their pages.
- Helped diagnose server disruptions, resolve client issues, and coordinate technical communication.
- Contributed to defining a scoped, repeatable service-delivery process.

---

## Engineering approach

- **Make correctness explicit:** clear contracts, idempotency, replay-safe operations, and auditable state changes where needed.
- **Measure before claiming:** distinguish benchmarks from production outcomes and use evaluation methods appropriate to the problem.
- **Test failure modes:** automated tests should cover edge cases and operational boundaries, not only happy paths.
- **Optimize for maintainability:** prefer clear interfaces, dependency boundaries, and reusable components over unnecessary complexity.
- **Design for operation:** consider security, observability, deployment, and recovery—not just whether code runs locally.

For published libraries, I aim for approximately 99% automated test coverage where that metric is meaningful. Coverage varies by repository; consult each project's current CI and coverage report for its actual result.

---

## Portfolio

<table>
  <tr>
    <td align="center" width="50%" valign="top">
      <a href="https://github.com/DiogoAngelim/signal/tree/main/examples/stocks-optimizer">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/capitalIQ-hero.png" alt="Stocks Optimizer investment application preview" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://github.com/DiogoAngelim/signal/tree/main/examples/stocks-optimizer">Stocks Optimizer</a></strong>
      <br/>
      <sub>Portfolio research and structured investment decisions</sub>
    </td>
    <td align="center" width="50%" valign="top">
      <a href="https://neural-configuration-lab.vercel.app/">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/neural-configuration-lab.svg" alt="Neural Configuration Lab project preview" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://github.com/DiogoAngelim/neural-configuration-lab">Neural Configuration Lab</a></strong>
      <br/>
      <sub>Controlled neural-network experiments · <a href="https://neural-configuration-lab.vercel.app/">Live app ↗</a></sub>
    </td>
  </tr>
  <tr><td colspan="2"><br/></td></tr>
  <tr>
    <td align="center" width="50%" valign="top">
      <a href="https://github.com/DiogoAngelim/signal/tree/main/examples/algai-parent-dashboard">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/algAI.png" alt="AlgAI learning application preview" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://github.com/DiogoAngelim/algai-landing">AlgAI</a></strong>
      <br/>
      <sub>Learning experience and independent understanding</sub>
    </td>
    <td align="center" width="50%" valign="top">
      <a href="https://github.com/DiogoAngelim/html-to-gutenberg">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/w2.gif" alt="HTML-to-Gutenberg and web tooling portfolio preview" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://github.com/DiogoAngelim/html-to-gutenberg">HTML to Gutenberg</a></strong>
      <br/>
      <sub>HTML-to-block conversion for WordPress</sub>
    </td>
  </tr>
  <tr><td colspan="2"><br/></td></tr>
  <tr>
    <td align="center" width="50%" valign="top">
      <a href="https://web.archive.org/web/20241001053257/https://webdifferent.com.au/">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/w2.gif" alt="Web Different agency website preview" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://web.archive.org/web/20241001053257/https://webdifferent.com.au/">Web Different</a></strong>
      <br/>
      <sub>Agency web platform · archived reference</sub>
    </td>
    <td align="center" width="50%" valign="top">
      <a href="https://web.archive.org/web/20230326034929/https://myfreight.com.au/">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/myfreight.gif" alt="My Freight logistics website preview" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://web.archive.org/web/20230326034929/https://myfreight.com.au/">My Freight</a></strong>
      <br/>
      <sub>Logistics platform · archived reference</sub>
    </td>
  </tr>
  <tr><td colspan="2"><br/></td></tr>
  <tr>
    <td align="center" width="50%" valign="top">
      <a href="https://web.archive.org/web/20220301044510/https://blitzmdesign.com.au/">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/blitz-2.0.gif" alt="Blitz Design 2.0 website preview" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://web.archive.org/web/20220301044510/https://blitzmdesign.com.au/">Blitz Design 2.0</a></strong>
      <br/>
      <sub>Design studio platform · archived reference</sub>
    </td>
    <td align="center" width="50%" valign="top">
      <a href="https://codepen.io/digelim/pen/wbOggK">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/blitzdesign.gif" alt="Blitz Design frontend concept preview" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://codepen.io/digelim/pen/wbOggK">Blitz Design</a></strong>
      <br/>
      <sub>Frontend concept · CodePen</sub>
    </td>
  </tr>
  <tr><td colspan="2"><br/></td></tr>
  <tr>
    <td align="center" width="50%" valign="top">
      <a href="https://web.archive.org/web/20200811001303/https://www.prophecy.io/product-page">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/prophecy.png" alt="Prophecy product page preview" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://web.archive.org/web/20200811001303/https://www.prophecy.io/product-page">Prophecy</a></strong>
      <br/>
      <sub>Product marketing page · archived reference</sub>
    </td>
    <td align="center" width="50%" valign="top">
      <a href="https://b2bsoftwareadvisors.com/">
        <img src="https://raw.githubusercontent.com/DiogoAngelim/DiogoAngelim/main/b2b.png" alt="B2B Software Advisors website preview" width="400"/>
      </a>
      <br/><br/>
      <strong><a href="https://b2bsoftwareadvisors.com/">B2B Software Advisors</a></strong>
      <br/>
      <sub>Advisory website</sub>
    </td>
  </tr>
</table>

---

## Client feedback

> “He worked until all hours of the night getting a mission-critical project finished and anticipated possible challenges. I'm ready to hire him for my next project.”

**Robert Johnson** · PaidMembershipPro migration

> “Diogo is very efficient. He listened patiently to all my needs and helped me accomplish exactly what I wanted. He always replied within an hour.”

**Carman Chung**

> “Diogo delivered above and beyond what was expected.”

**Paul Morin** · Date filtering plugin

> “Fast and super easy to work with. Work was completed to a high standard.”

**Adam Selley**

---

## Certifications & education

- **Codeable WordPress Expert** — [credential](https://www.credential.net/58930281-2568-48db-a5df-a85e40244d6e?record_view=true)
- **Machine Learning** — [Coursera certificate](https://www.coursera.org/account/accomplishments/verify/5TLHGJPFYLGR)
- **Academic studies:** Computer Science, Software Engineering, and Economics. I do not claim completed degrees.
- **English:** Professional working proficiency.

---

## Contact

Available immediately for remote project work or ongoing engineering partnerships.

- **Email:** [hello@diogoangelim.dev](mailto:hello@diogoangelim.dev)
- **LinkedIn:** [linkedin.com/in/diogoangelim](https://linkedin.com/in/diogoangelim)
- **Codementor:** [codementor.io/@diogo_angelim](https://www.codementor.io/@diogo_angelim?refer=badge)
- **Website:** [naubly.com](https://naubly.com)
- **GitHub:** [github.com/DiogoAngelim](https://github.com/DiogoAngelim)
