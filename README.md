# Anonymousyz

## Applied AI deployment and governance portfolio

<p align="center">
  <img src="assets/portfolio-map.svg" alt="Anonymousyz portfolio: discover tools, test AI workflow readiness, prepare a human decision" width="100%">
</p>

**Start with the problem you have:** [find tools and standards](https://github.com/Anonymousyz/awesome-ai-production-readiness), [review an AI workflow](https://github.com/Anonymousyz/ai-prototype-to-production-toolkit), [turn evidence into a decision packet](https://github.com/Anonymousyz/research-to-decision-toolkit), or [red-team a launch plan inside your editor](https://github.com/Anonymousyz/ai-launch-red-team).

This profile contains practical methods and local tools for a specific operational question:

> An AI prototype works in a demonstration. What evidence, controls, and decision rights are required before it is allowed to affect a real workflow?

The work is aimed at the point where product design, engineering, risk, compliance, and operating ownership meet. In a real organization, model quality is only one input to that conversation. The decision also depends on the workflow being changed, authorized data, evaluation evidence, human override design, auditability, cost, incident ownership, and rollback.

The repositories use a pseudonymous public handle. They publish methods, fictional cases, public sources, schemas, and executable local tools while deliberately excluding client, employer, personal, and confidential operational material.

## Portfolio architecture

| Operating question | Public repository | Primary deliverables | Typical reviewer |
|---|---|---|---|
| Is an AI prototype structurally prepared for a bounded pilot or production decision? | [AI Prototype-to-Production Toolkit](https://github.com/Anonymousyz/ai-prototype-to-production-toolkit) | Current public v0.6.0: fixed 70-point local CLI, eight vetoes, migration, Markdown/static HTML reports, governance artifacts, and synthetic cases. | Product owner, FDE, solutions architect, security or risk lead |
| Which tools and standards can close a known gap in evaluation, observability, guardrails, governance, or deployment? | [Awesome AI Production Readiness](https://github.com/Anonymousyz/awesome-ai-production-readiness) | Current public v0.3.4: versioned 57-resource catalog, deterministic export, strict canonical/archive metadata validation, and link evidence. | Architect, AI platform lead, governance practitioner, technical researcher |
| How should readiness and research evidence become a decision packet for accountable humans? | [Research-to-Decision Toolkit](https://github.com/Anonymousyz/research-to-decision-toolkit) | Current public v0.6.0: fixed 24-point structural check plus unscored argument-quality and judgment-writing records, evidence matrix, CLI, and fictional packet. | Consultant, policy analyst, product leader, governance or investment committee member |
| Can a launch plan survive a first red-team pass, before anyone opens a spreadsheet? | [AI Launch Red Team](https://github.com/Anonymousyz/ai-launch-red-team) | Zero-code bilingual agent skill for Claude Code, Cursor, and Codex: an eight-veto launch card with quoted evidence, a seven-dimension check, and a meeting-ready question list. | Anyone about to approve an AI launch; conversational entry point to the toolkit above |

```mermaid
flowchart LR
    A[Business problem or AI capability] --> B[Find relevant tools and standards]
    B --> C[Assess workflow readiness, evidence, and controls]
    C --> D[Prepare alternatives and a decision packet]
    D --> E[Accountable human decision]
    E --> F[Operate, monitor, learn, and revise]

    B --- R1[Awesome AI Production Readiness]
    C --- R2[Prototype-to-Production Toolkit]
    C --- R4["AI Launch Red Team skill<br/>(conversational first pass)"]
    D --- R3[Research-to-Decision Toolkit]
```

## Operating method

The portfolio follows a repeatable sequence rather than a generic AI checklist.

1. **Bound the workflow.** Name the user, decision point, input sources, prohibited data, downstream action, operating owner, and rollback condition.
2. **Create evidence.** Define evaluation cases, acceptance criteria, known failure modes, residual gaps, and the evidence that could change the conclusion.
3. **Design controls.** Specify human review, access rights, logging, escalation, monitoring, cost ownership, and incident response.
4. **Separate review from approval.** A score or validation result can make omissions visible. It cannot authenticate evidence, prove a reviewer is independent, or approve a deployment.
5. **Keep a usable artifact.** The output should survive the original conversation: a decision memo, risk register, system card, evaluation plan, operating handover, or versioned tool.

This sequence is useful in regulated and high-consequence settings, but it is intentionally portable. The tools do not assert legal applicability or replace sector-specific review.

## What a reviewer can inspect

The public repositories provide more than a framework description:

- executable Python CLIs with no model API-key dependency;
- fixed schemas and explicit input contracts;
- unit tests for invalid input, veto conditions, missing evidence, reviewer metadata, report generation, and README link integrity;
- active GitHub Actions validation on every push, published from documented workflow templates;
- full Chinese READMEs alongside the English ones, with Mermaid maps of each scoring contract;
- `AGENTS.md` guardrails that bind coding agents to each repository's frozen contracts and changelog discipline;
- generated Markdown and static HTML reports from fictional cases in current public releases;
- NIST AI RMF and OWASP mappings with explicit scope limits;
- complete licenses, changelogs, release notes, security boundaries, and reproducible commands;
- a machine-readable resource catalog with duplicate checks, a consumption guide, and committed link evidence.

For a detailed file-by-file review path, start with the flagship repository's [portfolio evidence map](https://github.com/Anonymousyz/ai-prototype-to-production-toolkit/blob/main/docs/portfolio_evidence_map.md).

## Releases and verification

### Current public releases

| Repository | Current public release | Verified public boundary |
|---|---|---|
| Prototype-to-Production | [v0.6.0](https://github.com/Anonymousyz/ai-prototype-to-production-toolkit/releases/tag/v0.6.0) | Canonical 70-point assessment contract, migration, Markdown/static HTML reports, governance artifacts, and synthetic examples |
| Awesome AI Production Readiness | [v0.3.4](https://github.com/Anonymousyz/awesome-ai-production-readiness/releases/tag/v0.3.4) | Versioned 57-resource catalog, strict canonical/archive metadata validation, deterministic export, and release-time link evidence |
| Research-to-Decision | [v0.6.0](https://github.com/Anonymousyz/research-to-decision-toolkit/releases/tag/v0.6.0) | Canonical 24-point decision-packet contract plus unscored argument-quality and judgment-writing records |

### Release verification

The three releases above were independently checked through their public, unauthenticated GitHub surfaces on 2026-07-16:

- every release is non-draft and non-prerelease;
- all 18 attached assets were downloaded anonymously and matched the locally generated SHA256 values;
- both public wheels installed in fresh virtual environments and their CLI entry points ran successfully.

Since 2026-07-20, verification also runs continuously: all three repositories execute their validation workflows on every push (the two CLI toolkits across Python 3.9, 3.11, and 3.12), and the Awesome list's committed link evidence comes from an authenticated strict run on CI infrastructure — 57/57 URLs responding, 46/46 GitHub metadata records verified, zero hard failures — with a regression test that keeps the committed report a clean release gate.

Each release documents reproducible commands and attaches provenance plus checksums. Public examples are fictional or use public sources; a successful test run confirms code and declared structure, not a real-world outcome.

## Review boundaries

The repositories do **not** claim:

- that a passing score proves safety, compliance, security, fairness, or production approval;
- that a source reference has been authenticated by the local CLI;
- that a reviewer declaration proves a person's identity, independence, or authority;
- that fictional examples demonstrate client deployment outcomes;
- that a listed project in the Awesome catalog is endorsed or secure for every use case.

These limits are part of the design. In AI deployment work, overstating evidence can be more damaging than documenting an unresolved gap.

## 中文简介

这是一个聚焦"AI 原型如何进入真实业务流程"的作品集,用化名维护。三个公开工具仓库构成一条操作链:**发现工具**([Awesome AI Production Readiness](https://github.com/Anonymousyz/awesome-ai-production-readiness),57 项经核验的资源目录)→ **评审就绪度**([AI Prototype-to-Production Toolkit](https://github.com/Anonymousyz/ai-prototype-to-production-toolkit),70 分制 + 8 条一票否决)→ **形成决策**([Research-to-Decision Toolkit](https://github.com/Anonymousyz/research-to-decision-toolkit),24 分制决策包)。

想最快体验,装 [AI 上线否决卡](https://github.com/Anonymousyz/ai-launch-red-team)技能:在 Claude Code / Cursor / Codex 里粘贴一段上线方案,30 秒拿到一张否决卡。三个工具仓库都有完整中文 README、每次 push 自动运行的 CI,以及写明"分数不等于批准"的方法边界。

## Current professional focus

- AI deployment workflows for regulated and high-consequence environments
- Evaluation, human review, auditability, operating ownership, incident response, and rollback
- AI governance translated into product, engineering, and decision artifacts
- Evidence-backed research and decision design for policy, consulting, and applied AI work

Each linked repository states its own license and operating boundary.