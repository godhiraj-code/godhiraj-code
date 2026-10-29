# Dhiraj Das

**Automation architecture · Python engineering · Agent reliability**

I’m an automation consultant with over a decade of experience across web, mobile, APIs, and enterprise workflows. I design test architectures, diagnose difficult failures, and build tools that make engineering decisions easier to verify.

My current work brings that discipline to AI agents: capture what happened, check the outcome, and make failures understandable.

[Portfolio & experience](https://www.dhirajdas.dev) · [The Automation Architect’s Playbook](https://www.dhirajdas.dev/automation-book) · [LinkedIn](https://www.linkedin.com/in/dhiraj-das-614509168)

## What I work on

- **Automation architecture:** framework design, browser and API testing, mobile automation, and CI delivery.
- **Failure diagnosis:** UI stability signals, visual comparisons, test reports, and reproducible evidence.
- **Agent reliability:** controlled LLM tests, execution records, explicit agent contracts, and outcome verification.

## Selected engineering work

### [GreenBuild](https://x.ai/bot/Y4m1o1g_TWG5he7mG1ZHb)

A custom Grok bot I created for testers and development teams. It helps turn requirements into test plans, investigate flaky tests, review Playwright, Selenium and Appium code, draft bug reports, and discuss release risks.

I evaluated it across six real-world QA scenarios. Its recommendations and generated code still require engineering review and execution checks; it is not an autonomous release approval gate.

[Try GreenBuild on Grok](https://x.ai/bot/Y4m1o1g_TWG5he7mG1ZHb)


### [Hermes DoctorPack](https://github.com/godhiraj-code/hermes-doctorpack)

Local-first diagnostics, plugin health checks, safety signals, and incident
postmortems for Hermes Agent, listed in the official Hermes plugin catalog. It
correlates config, plugin state, and logs into redacted `ok`/`warn`/`fail`/`unknown`
findings with concrete recommendations. Missing evidence is reported as unknown,
and log keywords are treated as evidence, not root cause.

### [SB Stealth Wrapper](https://github.com/godhiraj-code/stealthautomation)

A reliability wrapper around SeleniumBase UC Mode for authorized browser testing on
applications with modern bot defenses. It standardizes browser setup, bounded
challenge recovery, fallback clicks, and screenshots, and raises explicit errors
instead of silently continuing. It does not make automation undetectable.

`pip install sb-stealth-wrapper`

### [Waitless](https://github.com/godhiraj-code/waitless)

Reduce timing-related Selenium failures with configurable UI stability checks and diagnostics. Application-specific assertions still decide whether the outcome is correct.

`pip install waitless` · [Technical walkthrough](https://www.dhirajdas.dev/blog/waitless-eliminate-flaky-tests)

### [pytest-mockllm](https://github.com/godhiraj-code/pytest-mockllm)

Fixture-scoped mocks for supported LLM SDK calls, including typed responses, streaming scenarios, and repeatable failures. Active fixtures intercept supported calls; installing the plugin alone does not block network access.

`pip install "pytest-mockllm[openai]"` · [Testing boundaries](https://www.dhirajdas.dev/blog/pytest-mockllm-true-fidelity)

### [pytest-glow-report](https://github.com/godhiraj-code/pytest-glow-report)

HTML reports for pytest and unittest with test-phase results, step details, and screenshot evidence to help investigate failures.

`pip install pytest-glow-report` · [Project walkthrough](https://www.dhirajdas.dev/project/pytest-glow-report)

### [Selenium Teleport](https://github.com/godhiraj-code/selenium-teleport)

Save and restore current-origin cookies and web storage, with optional encryption and explicit restore validation. Session reuse complements dedicated login tests.

`pip install selenium-teleport` · [Session reuse guide](https://www.dhirajdas.dev/blog/selenium-teleport-v2-security)

## Starlight Protocol

**A general-purpose agent platform for turning goals into inspectable outcomes.**

Starlight coordinates domain agents working with code, data, APIs, browsers, devices, or language models. It bounds mission execution and returns reports with agent identity, attempts, results, and evidence. Agents own their domain logic and outcome checks.

The current **5.x alpha** includes a Node.js 22+ runtime, local CLI, and authenticated remote-agent protocol. A browser or model provider is not required. The earlier browser-specific implementation is legacy.

[Repository](https://github.com/starlight-protocol/starlight) · [Demo & documentation](https://starlight-protocol.github.io/starlight/) · [Start with the architecture](https://www.dhirajdas.dev/blog/constellation-based-automation-starlight-protocol) · [Selected for XERJ Corpus Hub](https://hub.xerj.org/contributors/godhiraj-code)

## More tools

- [pytest-why](https://github.com/godhiraj-code/pytest-why): a pytest plugin that classifies common failures with local, deterministic rules and writes concise explanations.
- [Agent Safety Doctor](https://github.com/godhiraj-code/agent-safety-doctor): an early alpha, local-first scanner for AI coding-agent workspaces with redacted evidence reports.
- [Agent Blackbox](https://github.com/godhiraj-code/agent-blackbox): a local-first flight recorder and CI diagnostic gate for AI-agent runs.
- [Project Vandal](https://github.com/godhiraj-code/vandal): runtime UI mutation testing for Playwright to check whether tests catch regressions.
- [Visual Guard](https://github.com/godhiraj-code/visual-guard): screenshot baselines, visual comparisons, region masking, and reviewable differences.
- [Visual Sonar](https://github.com/godhiraj-code/wvdautomation): computer-vision automation for WVD and Citrix environments without DOM access.

[Explore the full portfolio](https://www.dhirajdas.dev/#projects)

## Writing and research

- **[The Automation Architect’s Playbook](https://www.dhirajdas.dev/automation-book):** a free guide to framework design, browser internals, failure analysis, and AI-assisted testing.
- My writing on Waitless was featured in **[PyCoder’s Weekly #714](https://pycoders.com/issues/714)**.
- My work on Starlight was selected for the **[XERJ Corpus Hub](https://hub.xerj.org/contributors/godhiraj-code)**, a reference library that AI coding agents search for worked examples.
- My background includes **[published research in spatial clustering](https://www.researchgate.net/profile/Dhiraj-Das-4)**, which informs how I approach algorithms and automation design.

[Read the engineering articles](https://www.dhirajdas.dev/blog)

## Discuss an engineering challenge

Working through an unreliable test suite, an automation architecture decision, or an AI-agent workflow that needs better evidence?

[Share your challenge](https://www.dhirajdas.dev/#contact) · [Connect on LinkedIn](https://www.linkedin.com/in/dhiraj-das-614509168)
