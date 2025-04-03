# 🤖 Awesome DevOps MCP Servers / Agentic DevOps Toolkit

List of Awesome MCP Servers and Clients for building Agentic Devops


[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Discord](https://img.shields.io/discord/1312302100125843476?logo=discord&label=discord)](https://discord.gg/your-discord-link)

A curated list of awesome [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) servers for DevOps practitioners, enabling AI assistants like Claude to interact with your infrastructure, monitoring tools, containers, cloud resources, and more. Build your own agentic DevOps workflows and level up your AIOps game!

## 📋 Contents

- [What is MCP?](#-what-is-mcp)
- [Cloud Platforms](#️-cloud-platforms)
- [Kubernetes & Containers](#-kubernetes--containers)
- [Infrastructure as Code](#️-infrastructure-as-code)
- [Monitoring & Observability](#-monitoring--observability)
- [CI/CD & Version Control](#-cicd--version-control)
- [Operating Systems & Command Line](#-operating-systems--command-line)
- [DevOps Productivity](#-devops-productivity)
- [DevOps Tooling](#️-devops-tooling)
- [Databases](#️-databases)
- [Miscellaneous](#-miscellaneous)
- [Resources](#-resources)
- [Contributing](#contributing)

## 🔍 What is MCP?

[MCP](https://modelcontextprotocol.io/) (Model Context Protocol) is an open protocol that enables AI models to securely interact with local and remote resources through standardized server implementations. For DevOps practitioners, this means your AI assistants can help with infrastructure management, monitoring, debugging, automation, and much more.

Want to use these tools? Check out [Claude Desktop](https://claude.ai/desktop), [Cursor](https://cursor.sh/), or other [MCP-compatible clients](https://github.com/punkpeye/awesome-mcp-clients/).

## ☁️ Cloud Platforms

Servers for interacting with various cloud providers and services.

- [alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server) - Secure AWS CLI command execution with pipes and templates for common AWS tasks in a Docker environment
- [alexei-led/k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server) - Securely execute Kubernetes CLI commands (`kubectl`, `helm`, `istioctl`, `argocd`) using pipes in a Docker environment
- [bright8192/esxi-mcp-server](https://github.com/bright8192/esxi-mcp-server) - VMware ESXi/vCenter management server providing REST API interfaces for VM management
- [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) - Integration with Cloudflare services including Workers, KV, R2, and D1
- [flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) - Typescript implementation for Kubernetes cluster operations on pods, deployments, services
- [jdubois/azure-cli-mcp](https://github.com/jdubois/azure-cli-mcp) - Wrapper around the Azure CLI to interact directly with Azure
- [johnneerdael/netskope-mcp](https://github.com/johnneerdael/netskope-mcp) - Access to Netskope Private Access components with setup information and usage examples
- [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp) - Terraform MCP server for managing and operating Terraform environments
- [rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) - Enables AI assistants to interact with Kubernetes clusters through natural language
- [thunderboltsid/mcp-nutanix](https://github.com/thunderboltsid/mcp-nutanix) - Go-based MCP Server for interfacing with Nutanix Prism Central resources
- [weibaohui/k8m](https://github.com/weibaohui/k8m) - Multi-cluster Kubernetes management with built-in tools covering DevOps and development scenarios
- [rishikavikondala/mcp-server-aws](https://github.com/rishikavikondala/mcp-server-aws) - Perform operations on your AWS resources using an LLM
- [lishenxydlgzs/aws-athena-mcp](https://github.com/lishenxydlgzs/aws-athena-mcp) - MCP server for AWS Athena to run SQL queries on Glue Catalog
- [aarora79/aws-cost-explorer-mcp-server](https://github.com/aarora79/aws-cost-explorer-mcp-server) - Optimize AWS spend with cost analysis across regions, services, and instance types

## 🐳 Kubernetes & Containers

Servers focused on container orchestration, Kubernetes management, and related tools.

- [ckreiling/mcp-server-docker](https://github.com/ckreiling/mcp-server-docker) - Docker integration for managing containers, images, volumes, and networks
- [manusa/podman-mcp-server](https://github.com/manusa/podman-mcp-server) - MCP server for Podman container management with support for images, containers, volumes, pods, and networks
- [manusa/kubernetes-mcp-server](https://github.com/manusa/kubernetes-mcp-server) - Powerful Kubernetes MCP server with OpenShift support and CRUD operations for any Kubernetes resource, plus specialized tools for cluster interaction
- [QuantGeekDev/docker-mcp](https://github.com/QuantGeekDev/docker-mcp) - Docker container management and operations through MCP
- [strowk/mcp-k8s-go](https://github.com/strowk/mcp-k8s-go) - Golang-based Kubernetes server for browsing pods, logs, events, and namespaces
- [wenhuwang/mcp-k8s-eye](https://github.com/wenhuwang/mcp-k8s-eye) - Kubernetes management server for analyzing cluster and application health
- [yanmxa/multicluster-mcp-server](https://github.com/yanmxa/multicluster-mcp-server) - Gateway for GenAI systems to interact with multiple Kubernetes clusters
- [weibaohui/kom](https://github.com/weibaohui/kom) - SDK for multi-cluster Kubernetes management with built-in DevOps tools
- [yangkyeongmo/mcp-server-apache-airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow) - MCP server connecting to Apache Airflow using official client

## 🏗️ Infrastructure as Code

Servers for managing infrastructure as code tools like Terraform, CloudFormation, etc.

- [dogukanakkaya/pulumi-mcp-server](https://github.com/dogukanakkaya/pulumi-mcp-server) - Interact with Pulumi API, create and list Stacks
- [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp) - Terraform MCP server allowing AI assistants to manage Terraform environments
- [lciesielski/mcp-salesforce](https://github.com/lciesielski/mcp-salesforce-example) - Demonstrate interactions with Salesforce instances

## 📊 Monitoring & Observability

Servers for monitoring, logging, and observability tools and platforms.

- [Coment-ML/Opik-MCP](https://github.com/comet-ml/opik-mcp) - Access to LLM observability, traces and monitoring captured by Opik
- [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) - Search dashboards, investigate incidents and query datasources in Grafana
- [hyperb1iss/lucidity-mcp](https://github.com/hyperb1iss/lucidity-mcp) - Analyze AI-generated code quality across 10 critical dimensions
- [last9/last9-mcp-server](https://github.com/last9/last9-mcp-server) - Bring real-time production context (logs, metrics, traces) into local environments
- [metoro-io/metoro-mcp-server](https://github.com/metoro-io/metoro-mcp-server) - Query and interact with Kubernetes environments monitored by Metoro
- [modelcontextprotocol/server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun) - Integration with Raygun for crash reporting and real user monitoring
- [modelcontextprotocol/server-sentry](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry) - Sentry.io integration for error tracking and performance monitoring
- [pydantic/logfire-mcp](https://github.com/pydantic/logfire-mcp) - Access to OpenTelemetry traces and metrics through Logfire
- [seekrays/mcp-monitor](https://github.com/seekrays/mcp-monitor) - System monitoring tool for real-time metrics on CPU, memory, disk, network, hosts, and processes
- [pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server) - Query and analyze Prometheus monitoring system

## 🔄 CI/CD & Version Control

Servers for continuous integration, continuous deployment, and version control systems.

- [ddukbg/github-enterprise-mcp](https://github.com/ddukbg/github-enterprise-mcp) - GitHub Enterprise API integration
- [kopfrechner/gitlab-mr-mcp](https://github.com/kopfrechner/gitlab-mr-mcp) - Interact with GitLab issues and merge requests
- [modelcontextprotocol/server-git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) - Git repository operations including reading, searching, and analyzing
- [modelcontextprotocol/server-github](https://github.com/modelcontextprotocol/servers/tree/main/src/github) - GitHub API integration for repository management, PRs, and issues
- [modelcontextprotocol/server-gitlab](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) - GitLab platform integration for project management and CI/CD
- [oschina/mcp-gitee](https://github.com/oschina/gitee) - Gitee API integration for repository, issue, and PR management
- [Tiberriver256/mcp-server-azure-devops](https://github.com/Tiberriver256/mcp-server-azure-devops) - Azure DevOps integration for repository management, work items, and pipelines
- [ko1ynnky/github-actions-mcp-server](https://github.com/ko1ynnky/github-actions-mcp-server) - Interact with GitHub Actions
- [adhikasp/mcp-git-ingest](https://github.com/adhikasp/mcp-git-ingest) - Read and analyze GitHub repositories with your LLM

## 💻 Operating Systems & Command Line

Servers for interacting with operating systems, command line tools, and shell environments.

- [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) - Access to iTerm terminal for running commands and asking questions
- [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands) - Run any command with `run_command` and `run_script` tools
- [maxim-saplin/mcp_safe_local_python_executor](https://github.com/maxim-saplin/mcp_safe_local_python_executor) - Safe Python interpreter based on HF Smolagents
- [MladenSU/cli-mcp-server](https://github.com/MladenSU/cli-mcp-server) - Command line interface with secure execution and security policies
- [OthmaneBlial/term_mcp_deepseek](https://github.com/OthmaneBlial/term_mcp_deepseek) - DeepSeek MCP-like Server for Terminal
- [tumf/mcp-shell-server](https://github.com/tumf/mcp-shell-server) - Secure shell command execution server
- [SecretiveShell/MCP-timeserver](https://github.com/SecretiveShell/MCP-timeserver) - Access time in any timezone and get current local time
- [andybrandt/mcp-simple-timeserver](https://github.com/andybrandt/mcp-simple-timeserver) - Check local time on client or current UTC time from NTP server
- [allenporter/mcp-server-home-assistant](https://github.com/allenporter/mcp-server-home-assistant) - Expose Home Assistant voice intents through MCP for home control

## 🚀 DevOps Productivity

Servers that enhance DevOps workflows and productivity.

- [jasonjmcghee/claude-debugs-for-you](https://github.com/jasonjmcghee/claude-debugs-for-you) - VS Code Extension for automatic debugging via breakpoints and expression evaluation
- [awwaiid/mcp-server-taskwarrior](https://github.com/awwaiid/mcp-server-taskwarrior) - Basic local taskwarrior usage for task management
- [mrexodia/user-feedback-mcp](https://github.com/mrexodia/user-feedback-mcp) - Enable human-in-the-loop workflow in tools like Cline and Cursor
- [anaisbetts/mcp-installer](https://github.com/anaisbetts/mcp-installer) - Install other MCP servers automatically
- [lamemind/mcp-server-multiverse](https://github.com/lamemind/mcp-server-multiverse) - Middleware server enabling multiple isolated instances of MCP servers
- [mullerhai/sakura-mcp](https://github.com/mullerhai/sakura-mcp) - Scala MCP Framework for building agents with MCP servers and clients
- [zcaceres/fetch-mcp](https://github.com/zcaceres/fetch-mcp) - Flexibly fetch JSON, text, and HTML data
- [pskill9/website-downloader](https://github.com/pskill9/website-downloader) - Download entire websites using wget while preserving structure

## 🛠️ DevOps Tooling

Servers for specific DevOps tools and operations.

- [api7/apisix-mcp](https://github.com/api7/apisix-mcp) - Support for querying and managing resources in Apache APISIX
- [automation-ai-labs/mcp-link](https://github.com/automation-ai-labs/mcp-link) - Seamlessly integrate any API with AI agents using OpenAPI Schema
- [delano/postman-mcp](https://github.com/delano/postman-mcp) - Interact with Postman API
- [flipt-io/mcp-server-flipt](https://github.com/flipt-io/mcp-server-flipt) - Enable AI assistants to interact with feature flags in Flipt
- [gofireflyio/firefly-mcp](https://github.com/gofireflyio/firefly-mcp) - Integrate, discover, manage, and codify cloud resources with Firefly
- [higress-group/higress-ops-mcp-server](https://github.com/higress-group/higress-ops-mcp-server) - Tools for managing Higress gateway configurations and operations
- [hungthai1401/bruno-mcp](https://github.com/hungthai1401/bruno-mcp) - Interact with Bruno API Client
- [IlyaGulya/gradle-mcp-server](https://github.com/IlyaGulya/gradle-mcp-server) - Gradle integration for project inspection, task execution, and test running
- [j4c0bs/mcp-server-sql-analyzer](https://github.com/j4c0bs/mcp-server-sql-analyzer) - SQL analysis, linting, and dialect conversion using SQLGlot
- [Jktfe/serveMyAPI](https://github.com/Jktfe/serveMyAPI) - Securely store and access API keys across projects using macOS Keychain
- [joshuarileydev/app-store-connect-mcp-server](https://github.com/JoshuaRileyDev/app-store-connect-mcp-server) - Communicate with App Store Connect API for iOS Developers

## 🧩 Miscellaneous

Other useful servers for DevOps practitioners.

- [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP) - Integration with Ghidra for binary analysis, decompilation, and function inspection
- [atomicchonk/roadrecon_mcp_server](https://github.com/atomicchonk/roadrecon_mcp_server) - Analyze ROADrecon results from Azure tenant enumeration
- [BurtTheCoder/mcp-dnstwist](https://github.com/BurtTheCoder/mcp-dnstwist) - DNS fuzzing tool for detecting typosquatting and phishing
- [BurtTheCoder/mcp-maigret](https://github.com/BurtTheCoder/mcp-maigret) - OSINT tool for collecting user account information from public sources
- [BurtTheCoder/mcp-shodan](https://github.com/BurtTheCoder/mcp-shodan) - Query Shodan API for IP lookups, device searches, and vulnerability queries
- [BurtTheCoder/mcp-virustotal](https://github.com/BurtTheCoder/mcp-virustotal) - Query VirusTotal API for URL scanning and file hash analysis
- [fr0gger/MCP_Security](https://github.com/fr0gger/MCP_Security) - Query ORKL API for threat reports and intelligence
- [qianniuspace/mcp-security-audit](https://github.com/qianniuspace/mcp-security-audit) - Audit npm package dependencies for security vulnerabilities
- [semgrep/mcp-security-audit](https://github.com/semgrep/mcp-security-audit) - Scan code for security vulnerabilities using Semgrep
- [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) - IDA Pro integration for binary analysis, disassembly, and malware report generation
- [PipedreamHQ/pipedream](https://github.com/PipedreamHQ/pipedream/tree/master/modelcontextprotocol) - Connect with 2,500+ APIs with 8,000+ prebuilt tools

## 🗄️ Databases

Servers for managing and interacting with various databases used in DevOps environments.

- [bytebase/dbhub](https://github.com/bytebase/dbhub) - Universal database MCP server supporting MySQL, PostgreSQL, SQLite, DuckDB and more
- [modelcontextprotocol/server-postgres](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) - PostgreSQL database integration with schema inspection and query capabilities
- [modelcontextprotocol/server-sqlite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) - SQLite database operations with built-in analysis features
- [cr7258/elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server) - MCP Server implementation that provides Elasticsearch interaction
- [idoru/influxdb-mcp-server](https://github.com/idoru/influxdb-mcp-server) - Run queries against InfluxDB OSS API v2
- [isaacwasserman/mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server) - Snowflake integration implementing read and (optional) write operations
- [kiliczsh/mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server) - A Model Context Protocol Server for MongoDB
- [TheRaLabs/legion-mcp](https://github.com/TheRaLabs/legion-mcp) - Universal database MCP server supporting multiple database types including PostgreSQL, Redshift, MySQL, Microsoft SQL Server, BigQuery, Oracle DB, and SQLite
- [runekaagaard/mcp-alchemy](https://github.com/runekaagaard/mcp-alchemy) - Universal SQLAlchemy-based database integration supporting many database types
- [clickhouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) - Query your ClickHouse database server
- [tinybirdco/mcp-tinybird](https://github.com/tinybirdco/mcp-tinybird) - Interact with Tinybird serverless ClickHouse platform
- [quarkiverse/quarkus-mcp-servers/jdbc](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jdbc) - Connect to any JDBC-compatible database and query, insert, update, delete, and more

## 📚 Resources

Useful resources for learning about and working with MCP servers in DevOps.

- [MCP Official Documentation](https://modelcontextprotocol.io/) - Official documentation and guides for MCP
- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) - A comprehensive list of MCP servers across various domains
- [MCP Clients](https://github.com/punkpeye/awesome-mcp-clients/) - A list of clients compatible with MCP servers
- [Discord Community](https://discord.gg/your-discord-link) - Join our Discord server to discuss DevOps with MCP
- [Claude Desktop](https://claude.ai/desktop) - AI assistant with MCP support

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request to add new MCP servers for DevOps or improve existing entries.

1. Fork this repository
2. Create a new branch (`git checkout -b feature/add-new-server`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add new DevOps MCP server'`)
5. Push to the branch (`git push origin feature/add-new-server`)
6. Open a Pull Request

Please ensure your submission follows our [contribution guidelines](CONTRIBUTING.md).

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Created and maintained by [AgenticDevOps](https://github.com/agenticdevops) community. If you find this project helpful, please consider giving it a star ⭐
