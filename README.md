# Eligibility Checking Engine vPrototype - education eligibility checking prototype 2026

> **Eligibility Checking Engine is a browser-based prototype for school and local authority eligibility checks, with separate prototype journeys for free school meals and childcare.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-vPrototype-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/bakervictor93/eligibility-checking-web-prototype?style=flat-square)](https://github.com/bakervictor93/eligibility-checking-web-prototype)

---

<p align="center">
  <a href="https://bakervictor93.github.io/eligibility-checking-web-prototype/">
    <img src="https://img.shields.io/badge/Download-Eligibility%20Checking%20Engine%20Latest-brightgreen?style=for-the-badge" alt="Download Eligibility Checking Engine">
  </a>
</p>

> **[Direct Download - Eligibility Checking Engine vPrototype](https://bakervictor93.github.io/eligibility-checking-web-prototype/)**

---

[Download Latest Build](https://bakervictor93.github.io/eligibility-checking-web-prototype/)

---

## What this project is

Eligibility Checking Engine is a prototype designed for education eligibility screening across schools and local authorities. The experience centers on guided decision flows that help users work through family and child eligibility checks, especially for free school meals and childcare.

It is delivered as a web app concept and is well suited to exploring policy-led forms, branching journeys, and handoff points in a GOV.UK and DfE setting. This is intentionally a prototype, not a production-ready service, so it is aimed at demos, internal feedback, and iterative service design.

---

## Key capabilities

- Run structured prototype journeys for family and child eligibility assessment
- Cover free school meals application routes
- Provide an appeal route for eligibility outcomes
- Complete FSM application end steps
- Keep FSM and childcare as separate prototype paths
- Access the prototype through a web browser
- Focus on school and local authority eligibility use cases
- Follow GOV.UK and DfE-style service patterns

---

## Getting started

This project is distributed as a web prototype. You can use it by cloning the repository or by downloading the files to your own machine.

1. Clone the repository:
   `git clone https://github.com/bakervictor93/eligibility-checking-web-prototype.git
2. Open the project folder:
   `cd check-your-eligibility-prototype`
3. Serve it with your preferred static web server or local preview tool.

If you are using a hosted build, open the latest available version through the download link above.

---

## How to use it

Open the prototype in a browser and work through the eligibility journey that fits the scenario you want to test.

Typical workflow:
1. Begin with the family or child eligibility check.
2. Move into the free school meals or childcare route as required.
3. Check the eligibility result.
4. Use the appeal or completion steps when the journey includes them.

As this is a prototype, the precise route can differ depending on the scenario and build version. Use it to exercise service logic, compare user journeys, or review content and interaction design.

---

## Configuration notes

Any configuration for the prototype is expected to sit within the project files used to build it.

If you are changing the service, inspect the HTML assets and the related flow definitions for:
- eligibility rules
- form copy
- decision outcomes
- journey separation for FSM and childcare

There is no single runtime config file called out in the extracted metadata, so some settings may be built into the prototype structure itself.

---

## Requirements

- Web browser
- HTML-capable hosting or local preview environment
- A local machine for development or review
- Repository files from `check-your-eligibility-prototype`

Optional for editing:
- A code editor
- Static file server or browser preview extension

---

## FAQ

**Is this a final service?**  
No. The metadata describes it as a prototype for education eligibility checking.

**Which journeys are included?**  
The extracted feature list includes family and child eligibility checks, free school meals, appeals, finalization, and separate FSM and childcare flows.

**How do I get the latest version?**  
Use the download link above or pull the newest repository changes when they are published.

**How can I adjust the flow?**  
Update the prototype HTML and the supporting files that define the eligibility journey and its content.

**What if the page fails to load?**  
Make sure you are opening it in a browser, that the files downloaded fully, and that your local server or hosting setup is serving the project root.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
