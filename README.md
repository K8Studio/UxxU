<p align="center">
  <a href="https://uxxu.io/">
    <img src="https://uxxu.io/logotext.webp" alt="UXXU" width="220" />
  </a>
</p>

<h1 align="center">UxxU</h1>

<p align="center">
  <strong>Model your architecture once. Keep every C4 view connected.</strong>
</p>

<p align="center">
  <a href="https://app.uxxu.io/signup"><strong>Start free</strong></a>
  ·
  <a href="https://uxxu.io/">Website</a>
  ·
  <a href="https://uxxu.io/c4-model/">C4 Model Hub</a>
  ·
  <a href="https://uxxu.io/llm-diagrams/">MCP and AI</a>
  ·
  <a href="https://uxxu.io/code-to-c4/">codeToC4 beta</a>
</p>

<p align="center">
  <a href="https://app.uxxu.io/signup">
    <img src="https://raw.githubusercontent.com/K8Studio/UxxU/main/product-model.webp" alt="UXXU connected C4 model editor showing software systems, people, containers, technologies, and relationships" width="1200" />
  </a>
</p>

<p align="center"><em>A connected C4 architecture model in UXXU.</em></p>

---

UXXU is a software architecture workspace built around the [C4 model](https://c4model.com/). Instead of storing isolated drawings, UXXU stores the people, systems, containers, components, technologies, and relationships behind them. Each diagram is a focused view of the same connected architecture model.

Change an element once, reuse it across views, and let people and AI agents work from shared architectural context.

## Why UXXU?

Architecture documentation often becomes a collection of disconnected canvases, stale wiki pages, and screenshots that neither developers nor AI tools can reliably understand. UXXU turns that documentation into a structured, navigable model.

With UXXU you can:

- Create connected System Context, Container, and Component diagrams.
- Reuse the same architecture elements and relationships across multiple views.
- Navigate from a system overview into the implementation detail that matters.
- Branch and merge architecture changes with conflict handling.
- Collaborate from a shared architecture workspace.
- Analyze technologies, dependencies, lifecycle status, exposure, and model coverage.
- Publish live, embeddable diagrams instead of static screenshots.
- Give MCP-compatible AI coding agents structured access to the architecture.

## See UXXU in action

<table>
  <tr>
    <td width="50%" align="center">
      <img src="https://raw.githubusercontent.com/K8Studio/UxxU/main/product-model.webp" alt="UXXU C4 architecture model editor" width="100%" />
      <br />
      <strong>Connected C4 modeling</strong><br />
      Model systems, people, containers, components, technologies, and relationships.
    </td>
    <td width="50%" align="center">
      <img src="https://raw.githubusercontent.com/K8Studio/UxxU/main/product-projects.webp" alt="UXXU architecture projects workspace" width="100%" />
      <br />
      <strong>Architecture projects</strong><br />
      Keep diagrams organized inside their complete project context.
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="https://raw.githubusercontent.com/K8Studio/UxxU/main/product-object-model.webp" alt="UXXU reusable architecture object model" width="100%" />
      <br />
      <strong>Reusable object model</strong><br />
      Manage the architecture elements shared across every view.
    </td>
    <td width="50%" align="center">
      <img src="https://raw.githubusercontent.com/K8Studio/UxxU/main/product-diagram-map.webp" alt="UXXU connected architecture diagram map" width="100%" />
      <br />
      <strong>Connected diagram map</strong><br />
      Navigate from the system landscape to the detail that matters.
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="https://raw.githubusercontent.com/K8Studio/UxxU/main/product-versioning.webp" alt="UXXU architecture branch and version management" width="100%" />
      <br />
      <strong>Architecture versioning</strong><br />
      Branch, review, and merge architecture changes with confidence.
    </td>
    <td width="50%" align="center">
      <img src="https://raw.githubusercontent.com/K8Studio/UxxU/main/product-analytics.webp" alt="UXXU software architecture analytics" width="100%" />
      <br />
      <strong>Architecture intelligence</strong><br />
      Understand technology usage, lifecycle, exposure, and model coverage.
    </td>
  </tr>
</table>

## AI agents and MCP

The UXXU MCP server lets tools such as Codex, Claude Code, and OpenClaw inspect UXXU projects and create or update C4 diagrams through the UXXU API.

Run it without a global installation:

```bash
npx -y uxxu-mcp
```

The server can read project context, inspect existing diagrams, create C4 views, lay out diagrams, and match model elements with the UXXU technology catalog.

See the [UXXU MCP documentation](./mcp/README.md) for configuration and available tools.

## From repository to architecture

We are building toward a workflow where the architecture lives alongside the software it describes:

1. Open a local or connected Git repository.
2. Detect an existing architecture model or analyze the codebase.
3. Explore the result as connected C4 views.
4. Ask an AI agent to explain the system or propose architecture changes.
5. Review the evidence and generated changes before accepting them.
6. Keep the model in Git, publish it to UXXU, or use both.

The [`codeToC4` beta](https://uxxu.io/code-to-c4/) is the first step in this direction. It is being developed to generate a baseline from repository evidence, which architects and engineers can then review and refine.

## Structurizr compatibility: product direction

We want teams to be able to keep `workspace.dsl` as their source of truth while using UXXU as a better visual, analytical, and collaborative environment.

The planned workflow includes:

- Opening `workspace.dsl` and `workspace.json` online or from a local project.
- Resolving local includes and refreshing views when files change.
- Exploring large Structurizr workspaces visually.
- Analyzing the model for missing, stale, or inconsistent architecture information.
- Generating new Structurizr DSL from repository evidence with an AI agent.
- Proposing reviewable DSL patches instead of silently rewriting source files.
- Letting each team choose a Structurizr-native, hybrid, or UXXU-native workflow.

These capabilities are product direction and should not yet be treated as generally available features.

## Start modeling

Every organization can start with one user and up to 400 architecture items without a credit card.

- [Create a free UXXU workspace](https://app.uxxu.io/signup)
- [Explore UXXU features](https://uxxu.io/features/)
- [View pricing](https://uxxu.io/pricing/)
- [Browse architecture templates](https://uxxu.io/architecture-templates/)
- [Learn the C4 model](https://uxxu.io/c4-model/)

## Repository status

This repository contains the UXXU product code, integrations, utilities, and documentation. We are preparing the appropriate parts of the project for public development. Build instructions, contribution guidelines, package boundaries, and public APIs will be documented as those parts are opened.

Please do not report security vulnerabilities through a public issue. Use the contact information on the [UXXU security page](https://uxxu.io/security/) instead.

## License

A repository-wide open-source license has not yet been selected. Individual packages may contain their own license files. Unless a package explicitly states otherwise, the code is not currently licensed for reuse or redistribution.

---

<p align="center">
  Built by <a href="https://uxxu.io/">UXXU</a> for teams that want architecture humans and AI agents can understand.
</p>
