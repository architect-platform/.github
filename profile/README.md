# 🏗️ Architect Platform

**Your software architect in a box.**  
Architect helps developers build consistent, production-ready software with structure, standards, and automation — from the first commit to deployment.

---

## 🚀 What Does Architect Do?

- 📦 Scaffold projects with opinionated templates (e.g. Spring Boot, Kotlin).
- 🔐 Enforce architectural rules, code quality, and security checks.
- ⚙️ Automate CI/CD, testing, and versioning.
- 📈 Grow with your project — from local development to full cloud deployment.

Whether you're working solo or with a team, Architect helps you write better software faster.

---

### One‑Line Installer Script

```bash
curl -sSL https://raw.githubusercontent.com/architect-platform/architect-cli/main/.installers/bash | bash
```

## Install & Run the Engine
```bash
architect engine install
architect engine start
# architet engine stop/clean
```

## Setup Architect Project

Add an `architect.yml` file configuring the project name and the plugins>
```yaml
project:
  name: architect-cli
  description: "A command-line architect for your projects."

plugins:
  - name: gradle-architected
  - name: github-architected
```

You can then configure the plugins either in the `architect.yml` file or under the `.architect` folder in any `.yml` file
```yaml
æ .architect/gradle.yml
gradle:
  projects:
    - name: architect-cli
      path: cli
```

## Run Architect wherever you want
```bash
architect <command>?
```
---

## 📚 Docs & Getting Started

- 📖 [Documentation](https://your-docs-url.com)
- 🧪 [Quick Start](https://your-docs-url.com/start)
- 💬 [Community Discussions](https://github.com/orgs/YOUR_ORG_NAME/discussions)

---

