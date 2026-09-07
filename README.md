# Hi, I'm Fabian 👋

### Industrial IoT & Enterprise Platforms - Cloud-Native on Azure

I build cloud systems for industrial IoT and enterprise platforms on Azure. My work runs from **Azure Functions to AKS, in .NET, and private networking** is the part that ties it together.

More than 15 years in distributed systems, the last ten of them on Microsoft Azure. My samples are written for production questions rather than hello-world demos: what breaks during a migration, how a service behaves behind Private Link, what a landing zone has to provide before a workload can go in.

Articles on [blog.fzankl.de](https://blog.fzankl.de) · Expert Distributed IIoT Software Solutions at WITTENSTEIN SE, Germany

---

## 🛠️ Core technologies

![Microsoft Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=flat-square)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square)

**Azure:** Functions · Flex Consumption · Container Apps · AKS · Virtual Network · Private Link · Log Analytics  
**Microsoft Fabric:** Eventstream · Private connectivity · Event Grid integration  
**.NET:** C# · ASP.NET Core · Azure Functions isolated worker · Azure SDKs for .NET  
**Engineering:** Terraform · Azure CLI  · Azure DevOps · GitHub Actions · CI/CD

---

## 📝 Currently writing about

**Azure Functions: in-process to isolated worker**  
What breaks, what goes away without replacement, and why the .NET 10 retarget depends on it. Support for .NET 8, .NET 9 and the in-process model ends on 10 November 2026.

**Leaving Linux Consumption**  
Migration paths to Flex Consumption, Functions on Container Apps and plain Container Apps, with cold-start and cost measurements.

**Private connectivity**  
Private Link, hub-spoke landing zones, third-party Private Link Services, and what Microsoft Fabric does and does not support behind them.

---

## 🚀 Featured projects

### ☁️ [dotnet-10-azure-migration-path](https://github.com/fzankl/dotnet-10-azure-migration-path)

**.NET 10 · Azure Functions · App Service · Container Apps · Shell**

Companion code for the article ".NET 10 in Azure: A Path Through Your Estate". A two-pass inventory script (Resource Graph first, then an ARM fan-out for what Graph cannot see) lists every app and its runtime version as CSV. Alongside it, before/after configuration pairs for the moves the article describes: Functions from in-process to isolated worker on Consumption, Flex Consumption and Elastic Premium, App Service with a staging slot, and a containerised API with a weighted traffic split on Container Apps. The Terraform and application code is there to be read and diffed, not deployed.

### 🔗 [microsoft-fabric-eventstream-event-grid-integration](https://github.com/fzankl/microsoft-fabric-eventstream-event-grid-integration)

**Microsoft Fabric · Eventstream · Azure Event Grid**

Companion sample for the article "Fabric: The Hidden Destination". Turns a Fabric Eventstream into a two-way participant in an Azure event-driven architecture, using a Unified Namespace as the shared topic convention: one isolated-worker Function moves events out to Event Grid, a second one brings them back in through the Eventstream's ingestion endpoint. A .NET Aspire AppHost runs the whole round trip on one machine with the Event Hubs and Event Grid emulators standing in for the cloud, so it needs neither an Azure subscription nor a Fabric workspace.

### 📄 [docsify-plugin-flexible-alerts](https://github.com/fzankl/docsify-plugin-flexible-alerts)

**JavaScript · docsify**

docsify plugin that turns Markdown blockquotes into configurable alert blocks with preconfigured or custom styles and alert types. 143 stars, 15 forks.

---

## 🌐 Where to find me

Long-form articles on [blog.fzankl.de](https://blog.fzankl.de), samples here on GitHub.  
On [LinkedIn](https://www.linkedin.com/in/zanfab) I write shorter pieces on the same topics a few times a week.

[LinkedIn](https://www.linkedin.com/in/zanfab) · [fzankl.de](https://www.fzankl.de) · [Medium](https://medium.com/@fzankl) · fabian@fzankl.de
