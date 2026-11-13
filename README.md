# Awesome-Desktop-Cross-Browser-Cloud

# Top Desktop Cross-Browser Cloud Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Cloud Browser Grids, Parallel Test Execution & Open-Source Alternatives*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Desktop Cross-Browser Clouds**. These tools provide remote access to browser and OS combinations—enabling teams to run automated Selenium, Playwright, Cypress, and Puppeteer tests, or perform manual live testing, without maintaining physical device labs or local virtual machines.

**Examples** include BrowserStack, Sauce Labs, TestMu AI (formerly LambdaTest), TestingBot, Browserling, BitBar, CrossBrowserTesting, Moon by Aerokube, Comparium, and Experitest (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted browser grids, open-source automation frameworks, and community-driven testing infrastructure—ideal for teams seeking data sovereignty and predictable costs over per-session cloud billing. The open-source landscape has matured significantly: **WebSummoner** offers a lightweight Selenoid successor in a ~10 MB Go binary [citation:5], **Moon** provides Kubernetes-native orchestration for Selenium, Playwright, and Cypress [citation:2][citation:8], and **Selenium Grid** remains the reference implementation for distributed WebDriver execution.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[BrowserStack](https://www.browserstack.com/)** | Industry-standard cloud grid with 3,500+ real desktop and mobile browser combinations. Automate runs Selenium, Playwright, Cypress, and Puppeteer tests. Percy handles visual review. AI agents include test case generation, self-healing locators, and failure analysis [citation:7]. | Quote-only for Automate; Live from ~$12.50/user/month (annual) | No permanent free tier; free trial on signup; free for qualifying open-source projects |
| **[Sauce Labs](https://saucelabs.com/)** | Enterprise cloud with 3,000+ OS/browser combinations and 10,000+ real devices. AURA platform describes AI agents that generate tests from natural language into Selenium, Cypress, Appium, and Playwright, then run, analyze, and heal them [citation:7]. | Virtual Device Cloud: $149/month (annual); Real Device Cloud: $199/month (annual) | No permanent free tier; 28-day trial with 60 testing minutes and real devices included [citation:13] |
| **[TestMu AI (formerly LambdaTest)](https://www.lambdatest.com/)** | Cloud grid with 3,000+ browser combinations and 50,000+ real devices. Rebranded from LambdaTest in January 2026. KaneAI agent plans and writes tests from text, tickets, or docs. HyperExecute provides test orchestration [citation:7]. | Live from ~$15/month; Automation from ~$79–99/month per parallel | **Free tier**: 100 automation minutes, 300 HyperExecute minutes, and five 2-minute real device sessions per month [citation:13] |
| **[TestingBot](https://testingbot.com/)** | Cloud grid with real devices and browsers. Supports Selenium, Cypress, Playwright, Puppeteer, and k6 Browser testing via CDP. EU-hosted options available [citation:12]. | Contact sales for current plans (billing based on test minutes and parallel tests) | **14-day free trial** (no credit card); free forever for qualifying open-source projects [citation:13] |
| **[Browserling](https://www.browserling.com/)** | Online browser testing with real browsers and OS versions. **Free Sandbox** provides limited Windows-based sessions with temporary isolated environments and screenshot capture. Paid plans add macOS, Android, iOS, file uploads, and network controls [citation:4]. | Paid plans from monthly/annual billing (exact rates via sales) | **Free Sandbox**: limited sessions, 3-minute limit, screenshot capture [citation:4][citation:10] |
| **[BitBar (SmartBear)](https://smartbear.com/product/bitbar/)** | Cloud device and browser testing with real mobile devices and desktop browsers. Live Testing and BitBar Unlimited (live + automated) available. | Live: €45/parallel/month (annual); Unlimited: €202/parallel/month (annual) | **14-day free trial** (no credit card) [citation:13]; free for open-source projects |
| **[CrossBrowserTesting (SmartBear)](https://smartbear.com/product/crossbrowsertesting/)** | Cloud testing with 1,500+ real desktop and mobile browsers. Manual testing, screenshot comparison, and parallel automated tests. Acquired by SmartBear. | Standard: ~$104/month (third-party listing) | **7-day free trial**; no free version |
| **[Moon by Aerokube (Cloud)](https://aerokube.com/moon/)** | Kubernetes-native browser automation cloud supporting Selenium, Playwright, Puppeteer, and Cypress in a single cluster. Deploys via Helm with official Chrome, Firefox, and Edge images [citation:2][citation:8]. | **$5 per parallel session per month** [citation:8] | **Free evaluation license keys** of any size until production via Moon Assistance Program [citation:8] |
| **[Comparium](https://comparium.app/)** | Website compatibility testing platform with four screenshot comparison modes and live testing. Supports all modern operating systems and browsers [citation:3]. | **$15/user/month** (Capterra) [citation:3][citation:15] | **Free version available** [citation:3]; no free trial per Capterra [citation:15] |
| **[Experitest (SeeTest)](https://experitest.com/)** | Mobile-focused test automation grid with desktop browser support. Integrates with Selenium/WebDriver, Jenkins, and ALM tools. | Quote-only (enterprise contract) | No published free tier; trial via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Selenium Grid 4](https://github.com/SeleniumHQ/selenium)** | [![Stars](https://img.shields.io/github/stars/SeleniumHQ/selenium?style=social&color=white)](https://github.com/SeleniumHQ/selenium/stargazers) | Reference hub-and-node architecture for distributed WebDriver execution. The foundation for most self-hosted browser grids. Supports distributed tracing and GraphQL status queries. |
| **[docker-selenium](https://github.com/SeleniumHQ/docker-selenium)** | [![Stars](https://img.shields.io/github/stars/SeleniumHQ/docker-selenium?style=social&color=white)](https://github.com/SeleniumHQ/docker-selenium/stargazers) | Official Docker images for Grid 4 with Chrome, Firefox, and Edge nodes. Ready-to-run hub and node containers for self-hosted testing infrastructure. |
| **[WebSummoner](https://github.com/WebSummoner/websummoner)** | [![Stars](https://img.shields.io/github/stars/WebSummoner/websummoner?style=social&color=white)](https://github.com/WebSummoner/websummoner/stargazers) | **Selenoid successor maintained by RIADVICE.** Fast Selenium hub summoning browsers in ephemeral Docker containers. **~10 MB Go binary with no Java dependency**, consuming 10x less memory than Java-based Selenium under load. Includes VNC, video recording, session logs, and a rich UI. Backwards compatible with Selenoid client APIs. Apache 2.0 [citation:5]. |
| **[Moon by Aerokube](https://github.com/aerokube/moon)** | [![Stars](https://img.shields.io/github/stars/aerokube/moon?style=social&color=white)](https://github.com/aerokube/moon/stargazers) | **Kubernetes-native browser automation for Selenium, Playwright, Puppeteer, and Cypress.** Deploys via Helm. Benchmarks: ~3s startup per session (K8s pod scheduling), ~250 MB memory per browser, **30+ max sessions on a 4-core host** when cluster-scaled. Free tier supports up to **3 concurrent users**; paid adds RBAC, audit logging, SSO, and priority queues [citation:2]. |
| **[Playwright](https://github.com/microsoft/playwright)** | [![Stars](https://img.shields.io/github/stars/microsoft/playwright?style=social&color=white)](https://github.com/microsoft/playwright/stargazers) | Microsoft's cross-browser automation framework (Apache-2.0) with built-in test runner supporting Chromium, Firefox, and WebKit. Can be self-hosted or pointed at cloud grids. Native parallel execution and trace viewer. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Selenoid (Archived)](https://github.com/aerokube/selenoid)** | [![Stars](https://img.shields.io/github/stars/aerokube/selenoid?style=social&color=white)](https://github.com/aerokube/selenoid/stargazers) | Original Go-based Docker-container-per-session Selenium hub. Archived December 2024; existing deployments should evaluate **WebSummoner** or **Moon** as migration targets. |
| **[Puppeteer](https://github.com/puppeteer/puppeteer)** | [![Stars](https://img.shields.io/github/stars/puppeteer/puppeteer?style=social&color=white)](https://github.com/puppeteer/puppeteer/stargazers) | Chrome/Firefox automation library maintained by the Chrome team. Provides a reference implementation for CDP and WebDriver BiDi protocols. |

**Frameworks for building custom systems**: Combine **Selenium Grid 4** or **docker-selenium** for standards-compliant WebDriver routing, **WebSummoner** for a lightweight Docker-native Selenoid successor (~10 MB binary, no Java) [citation:5], and **Moon** for Kubernetes-native Playwright/Puppeteer/Cypress orchestration with cluster-wide scaling [citation:2]—creating a fully self-hosted cross-browser cloud without per-session SaaS fees.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Cross-browser clouds execute arbitrary browser automation; enforce proper authentication, session isolation, and cleanup to prevent resource abuse.
- **Free tiers vary significantly.** TestMu AI publishes a genuine monthly free allowance (100 automation minutes) [citation:13]. Browserling offers a 3-minute-per-session free sandbox [citation:4][citation:10]. Comparium has a free version but no free trial [citation:3][citation:15]. **Open-source alternatives have different trade-offs**: WebSummoner is lightweight and Docker-native but explicitly **not suitable for Kubernetes** [citation:5]; Moon requires Kubernetes but provides cluster-wide scaling and Playwright/Cypress support [citation:2]. Always validate current capabilities and pricing against vendor pages before committing.

---

**Made for QA engineers, test automation architects, and developers building cross-browser testing infrastructure.**  
Let's make desktop cross-browser clouds more open, accessible, and cost-predictable.
