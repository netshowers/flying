# 🚀 Flying

> A curated collection of **Mihomo (Clash Meta)** configuration resources, including custom Rule Providers, streaming media rules, icons and related utilities.
>
> This repository focuses on **modularity**, **maintainability**, and **long-term evolution** rather than simply storing configuration files.

---

## ✨ Features

- 📦 Modular Rule Providers
- 🎬 Streaming Media Rule Collections
- 🌐 DNS & Routing Resources
- 🖼 Icon Collections
- 🔧 Mihomo (Clash Meta) Optimized
- ⚡ Sparkle Compatible
- 📚 Git Version Controlled
- 🧩 Easy to Maintain
- 🚀 Continuously Improved

---

# 📂 Repository Structure

```text
Flying
│
├── Clash
│   ├── RuleSet/
│   │   ├── CustomAR.yaml
│   │   ├── CustomAU.yaml
│   │   ├── CustomDirect.yaml
│   │   ├── CustomForeign.yaml
│   │   ├── CustomGoogle.yaml
│   │   ├── CustomHK.yaml
│   │   ├── CustomJP.yaml
│   │   ├── CustomMicrosoft.yaml
│   │   ├── CustomSkyGo.yaml
│   │   └── CustomUS.yaml
│   │
│   ├── StreamingMedia/
│   │
│   ├── IconSet/
│   │
│   └── ...
│
├── subconverter/
│
└── README.md
```

---

# 📦 Repository Philosophy

This repository is designed around the idea that configuration should be treated as software.

Instead of maintaining a large monolithic configuration, resources are organized into reusable modules that can evolve independently.

Core principles include:

- Separation of responsibilities
- Reusable rule providers
- Modular repository structure
- Version-controlled configuration
- Long-term maintainability

---

# 📦 Rule Providers

The `Clash/RuleSet` directory contains public Rule Providers used by Mihomo.

Current rule providers include:

| Rule Provider | Purpose |
|---------------|----------|
| CustomDirect | Direct routing |
| CustomForeign | General proxy traffic |
| CustomGoogle | Google services |
| CustomMicrosoft | Microsoft services |
| CustomHK | Hong Kong nodes |
| CustomJP | Japan nodes |
| CustomUS | United States nodes |
| CustomAU | Australia nodes |
| CustomAR | Argentina nodes |
| CustomSkyGo | Sky Go services |

Each Rule Provider is maintained independently and can be updated without modifying the main configuration.

---

# 🎬 Streaming Media

The `StreamingMedia` directory contains streaming media related resources.

Examples include:

- Regional unlock rules
- Streaming service rule sets
- GEO related resources
- Custom media routing

Keeping these resources separate makes maintenance much easier as streaming services evolve over time.

---

# 🛠 Supported Clients

This repository is primarily maintained for:

| Client | Status |
|----------|---------|
| Mihomo | ✅ |
| Clash Meta | ✅ |
| Sparkle | ✅ |
| Other Rule Provider Compatible Clients | ⚠️ May Work |

---

# 🔒 Public vs Private Resources

This repository intentionally contains **only reusable public resources**.

The following resources are **NOT** included:

- Personal subscriptions
- Proxy Providers
- Main configuration
- Personal DNS configuration
- Private Rule Providers
- Authentication information
- Personal proxy nodes

This separation allows the repository to remain clean while protecting sensitive information.

---

# 🏗 Design Philosophy

Configuration should not become increasingly difficult to maintain over time.

This repository adopts several engineering principles:

- Small reusable modules
- Independent Rule Providers
- Git-based version control
- Clear directory hierarchy
- Separation of public and private resources

The objective is to make future maintenance easier instead of continuously increasing complexity.

---

# 🔄 Workflow

Repository changes generally follow this workflow:

```text
Develop
      │
      ▼
Local Testing
      │
      ▼
Git Commit
      │
      ▼
GitHub
      │
      ▼
Sparkle / Mihomo Validation
```

Every significant structural change should be verified before deployment.

---

# 📚 Documentation

Additional documentation may be added in the future.

Possible topics include:

- DNS Configuration
- Routing Strategy
- Rule Provider Development
- Streaming Media Rules
- GEO Resources
- Sparkle Configuration
- Mihomo Best Practices

---

# 🛣 Roadmap

Current progress:

- ✅ Rule Provider modularization
- ✅ Repository restructuring
- ✅ Sparkle compatibility
- ✅ Git managed Rule Providers

Future plans:

- ⏳ VPS hosted private Rule Providers
- ⏳ Improved DNS documentation
- ⏳ Rule Provider Wiki
- ⏳ Better Streaming Media organization
- ⏳ Automated validation
- ⏳ CI/CD workflow
- ⏳ Repository documentation improvements

---

# 📜 Changelog

## 2026

### July

- Moved custom Rule Providers into `Clash/RuleSet`
- Cleaned repository structure
- Removed legacy root Rule Providers
- Improved repository organization
- Sparkle compatibility verified

---

# 🤝 Contributing

This repository is primarily maintained for personal use.

Suggestions and discussions are always welcome.

---

# 📄 License

Unless otherwise specified, this repository is intended for learning, personal use and public sharing of reusable configuration resources.

Users are responsible for complying with the licenses and terms of use of any third-party resources referenced by this repository.

---

# ❤️ Acknowledgements

Special thanks to:

- Mihomo
- Clash Meta
- Sparkle
- Open-source community

for making a modular configuration ecosystem possible.

---

# ⭐ Project Vision

This repository is not intended to be a simple collection of YAML files.

Its long-term goal is to become a well-organized, maintainable and reusable configuration resource repository for Mihomo users.

As the project evolves, more reusable modules, documentation and engineering practices will be introduced to keep the configuration clean, scalable and easy to maintain.