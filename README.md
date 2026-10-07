# Awesome-Container-Application-Hosting

# Awesome-Container-Application-Hosting 🚢 ☁️

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Container Application Hosting Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Container-Application-Hosting"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Container-Application-Hosting?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Container-Application-Hosting/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Container-Application-Hosting?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Container-Application-Hosting/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Container-Application-Hosting?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Container Application Hosting Ecosystem

**Curated List of Commercial PaaS Platforms & Open-Source Self-Hosted Application Hosting Tools**  
*Focused on Git-Push Deploys, Serverless Containers, Scale-to-Zero, Preview Environments, Managed Databases & Self-Hosted PaaS*

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary
Welcome to the ultimate curated directory of **container application hosting platforms**, **open-source PaaS alternatives**, and **self-hosted deployment tools**. Whether you are looking for enterprise-grade commercial solutions (such as *Google Cloud Run*, *Render*, and *Railway*), or self-hostable open-source alternatives (like *Coolify*, *Dokploy*, and *OpenRun*), this list covers category leaders, GitOps workflows, and privacy-respecting application deployment.

**Key Market Context:**
- **Coolify** has emerged as the **leading open-source PaaS** with **62,000+ GitHub stars**, offering **Heroku/Vercel/Netlify alternative** functionality on your own infrastructure .
- **OpenRun** is the **declarative GitOps alternative to Cloud Run and App Runner**, with **scale-to-zero** and **OAuth/SAML RBAC** built in .
- **Homerun** provides a **single-user PaaS for homelab users**, with **live deploy progress**, **automatic SSL**, and **S3 backups** .

---

## 📑 Table of Contents
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS & Commercial Platforms

The container application hosting market spans **hyperscaler serverless containers** (Cloud Run, App Runner, Azure Container Apps) that provide **scale-to-zero and pay-per-use billing**, and **developer-focused PaaS platforms** (Render, Railway, Fly.io) that offer **simplified deployment with managed infrastructure**. **Google Cloud Run** charges **per request and CPU/memory usage**, with **$0 floor when idle** . **Render** starts at **$7/month per service**. **Railway** uses **usage-based pricing** starting at **$5/month**. **Fly.io** charges **per second of VM runtime** with **free allowances**. **DigitalOcean App Platform** starts at **$5/month for static sites** and **$12/month for apps**.

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Google Cloud Run](https://cloud.google.com/run)** 🌐 | Google (Alphabet) | ~$2.0 Trillion | **Pay-per-use**; **$0 floor when idle**  | **Free tier: 2M requests/month**  | **GCP-native serverless containers** — **Scale-to-zero** with **$0 idle cost** . **GCP Cloud Run** estimated at **~$50–80/mo for 1k users** . **Built on Knative** for portability. |
| **[AWS App Runner](https://aws.amazon.com/apprunner/)** ☁️ | Amazon | ~$2.0 Trillion | **Pay-per-use** (vCPU + memory) | **Free tier: limited** | **AWS-native container hosting** — **Build from source or container image**. **Automatic scaling** and **load balancing**. |
| **[Azure Container Apps](https://azure.microsoft.com/en-us/products/container-apps/)** 🔷 | Microsoft | ~$3.90 Trillion | **Pay-per-use** (vCPU + memory) | **Free tier: 180,000 vCPU-seconds/month**  | **Azure-native serverless containers** — **Built on Kubernetes, KEDA, Dapr, and Envoy** . **Scale-to-zero** and **event-driven scaling**. **Estimated at ~$100–130/mo for 1k users** . |
| **[Render](https://render.com/)** 🚀 | Render | Private | **$7/month** per service | **Free tier: static sites**  | **Developer-friendly PaaS** — **Git-push deploys**, **managed databases**, and **automatic SSL**. **Preview environments** per PR. |
| **[Railway](https://railway.app/)** 🚂 | Railway | Private | **$5/month** (usage-based) | **$5 free credit/month**  | **Modern application hosting** — **Instant deploys from Git**. **Managed databases** and **cron jobs**. **Template marketplace**. |
| **[Fly.io](https://fly.io/)** ✈️ | Fly.io | Private | **Pay-per-second** (VM runtime) | **Free allowances** for small apps | **Edge application hosting** — **Runs apps close to users** on custom hardware. **Proprietary platform** — not open source . |
| **[Heroku](https://www.heroku.com/)** 🟣 | Salesforce | ~$250 Billion | **$7/month** per dyno | **Free tier retired** (November 2022)  | **The original PaaS** — **Buildpacks**, **add-ons**, and **Heroku Postgres**. **Mature ecosystem** but **expensive at scale**. |
| **[DigitalOcean App Platform](https://www.digitalocean.com/products/app-platform)** 🌊 | DigitalOcean | ~$3 Billion | **$5/month** (static); **$12/month** (apps) | **Free tier: 3 static sites**  | **Simple PaaS** — **Git-push deploys**, **managed databases**, and **global CDN**. **No SA region** — closest is London . |
| **[Koyeb](https://www.koyeb.com/)** ⚡ | Koyeb | Private | **$7/month** (Hobby) | **Free tier available**  | **Global application hosting** — **Edge deployments** and **serverless GPUs**. |
| **[Porter](https://porter.run/)** 🚪 | Porter | Private | **Cluster licensing** (BYOC) | **Free trial available**  | **Kubernetes-native PaaS** — **Deploys to your own K8s cluster** (AWS, GCP, Azure). **GitOps workflows** . |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub_Stars_Count (Descending)* 🌟

- **[Coolify](https://github.com/coollabsio/coolify)** [![Stars](https://img.shields.io/github/stars/coollabsio/coolify?style=social&color=white)](https://github.com/coollabsio/coolify/stargazers)  
  **The leading open-source PaaS alternative to Vercel, Heroku, and Netlify**, Apache-2.0 licensed. **62,000+ GitHub stars** — **the most popular self-hosted PaaS** . **Deploy apps, databases, and 280+ one-click services** (Plausible, Gitea, Minio, n8n, and more) . **Git-push deploys** with GitHub, GitLab, Bitbucket, or Gitea — plus **preview deployments per PR**. **Nixpacks auto-detection** builds your stack without config. **Automatic SSL** via Let's Encrypt. **S3-compatible backups**. **Docker Swarm support** for multi-server. **Real-time terminal** in the browser. **Self-hosted version completely free** — no server limits, no feature restrictions. **Cloud dashboard from $5/month** (2 servers) . **The most complete open-source application hosting platform** . 🚀

- **[Kubero](https://github.com/kubero-dev/kubero)** [![Stars](https://img.shields.io/github/stars/kubero-dev/kubero?style=social&color=white)](https://github.com/kubero-dev/kubero/stargazers)  
  **Free and self-hosted PaaS alternative to Heroku/Netlify/Vercel**, Apache-2.0 licensed. **4,422 GitHub stars** . **Runs on Kubernetes** — deploys apps to your K8s cluster. **Git-push deploys** with preview environments. **The Kubernetes-native open-source PaaS** . ☸️

- **[Dokploy](https://github.com/Dokploy/dokploy)** [![Stars](https://img.shields.io/github/stars/Dokploy/dokploy?style=social&color=white)](https://github.com/Dokploy/dokploy/stargazers)  
  **Open-source alternative to Vercel, Netlify, and Heroku**, source-available licensed. **37,381 GitHub stars** . **Runs on Docker with Traefik** for routing and SSL. **Native GitHub, GitLab, Bitbucket, and Gitea integrations**. **Heroku Buildpacks, Nixpacks, and Paketo** support. **Built-in metrics**, **AI-powered Docker Compose templates**, and **Docker Swarm support**. **Self-hosted free**; managed from **$4.50/month** . **The most efficient single-server PaaS** . 🎯

- **[CapRover](https://github.com/caprover/caprover)** [![Stars](https://img.shields.io/github/stars/caprover/caprover?style=social&color=white)](https://github.com/caprover/caprover/stargazers)  
  **Scalable PaaS (automated Docker + nginx)**, Apache-2.0 licensed. **15,168 GitHub stars** . **"Heroku on Steroids"** — **one-click apps**, **Git-push deploys**, and **Nginx reverse proxy**. **The original open-source PaaS** — battle-tested for years. ⚓

- **[Dokku](https://github.com/dokku/dokku)** [![Stars](https://img.shields.io/github/stars/dokku/dokku?style=social&color=white)](https://github.com/dokku/dokku/stargazers)  
  **Docker-powered PaaS for building and managing app lifecycles**, MIT licensed. **32,147 GitHub stars** . **"Heroku on a VPS"** — **Git-push deploys**, **buildpacks**, and **plugin system**. **No UI** — CLI-only. **The simplest minimal PaaS** . 🐳

- **[OpenRun](https://github.com/openrundev/openrun)** [![Stars](https://img.shields.io/github/stars/openrundev/openrun?style=social&color=white)](https://github.com/openrundev/openrun/stargazers)  
  **Declarative GitOps web app deployment**, Apache-2.0 licensed. **Open-source alternative to Google Cloud Run and AWS App Runner** . **Declarative config in Starlark** (Python-like) — **no YAML hell**. **Scale-to-zero** for idle apps. **OAuth/OIDC/SAML with RBAC**. **Atomic updates** across multiple apps. **Single binary, Docker/Podman dependency only**. **The most declarative open-source PaaS** . 📝

- **[Kamal](https://github.com/basecamp/kamal)** [![Stars](https://img.shields.io/github/stars/basecamp/kamal?style=social&color=white)](https://github.com/basecamp/kamal/stargazers)  
  **Deploy web apps anywhere**, MIT licensed. **14,585 GitHub stars** . **From Basecamp** — **zero-downtime deploys**, **rolling restarts**, and **multi-server support**. **The simplest way to deploy containers to bare metal** . 🚂

- **[Komodo](https://github.com/moghtech/komodo)** [![Stars](https://img.shields.io/github/stars/moghtech/komodo?style=social&color=white)](https://github.com/moghtech/komodo/stargazers)  
  **Tool to build and deploy software on many servers**, open-source. **12,344 GitHub stars** . **Multi-server deployments** with **build and deploy workflows**. **The most scalable open-source deployment tool** . 🦎

- **[Piku](https://github.com/piku/piku)** [![Stars](https://img.shields.io/github/stars/piku/piku?style=social&color=white)](https://github.com/piku/piku/stargazers)  
  **The tiniest PaaS you've ever seen**, MIT licensed. **6,605 GitHub stars** . **Git-push deployments to your own servers**. **~1000 lines of Python**. **The most minimal open-source PaaS** . 🐜

- **[SwiftWave](https://github.com/swiftwave-org/swiftwave)** [![Stars](https://img.shields.io/github/stars/swiftwave-org/swiftwave?style=social&color=white)](https://github.com/swiftwave-org/swiftwave/stargazers)  
  **Self-hosted lightweight PaaS for any VPS**, Apache-2.0 licensed. **890 GitHub stars** . **Install on bare metal, Raspberry Pi, Hetzner, DigitalOcean**. **Docker Swarm mode** for scaling. **The most lightweight open-source PaaS** . 🌊

- **[Frost](https://github.com/elitan/frost)** [![Stars](https://img.shields.io/github/stars/elitan/frost?style=social&color=white)](https://github.com/elitan/frost/stargazers)  
  **Open-source alternative to Vercel, Netlify, Railway, Render, and Neon**, open-source. **Build, deploy, and run from one platform**. **Git push deploy workflow**. **Docker-native, no Kubernetes**. **S3-compatible object storage**. **REST API and MCP support for AI agents**. **The most comprehensive open-source deployment platform** . ❄️

- **[Homerun](https://github.com/orochibraru/homerun)** [![Stars](https://img.shields.io/github/stars/orochibraru/homerun?style=social&color=white)](https://github.com/orochibraru/homerun/stargazers)  
  **Self-hosted, single-user PaaS for homelab users**, open-source. **Click-config form** for deploying Docker containers. **Point at an image or git repo, fill in env vars/port/resources, hit deploy** — Traefik routes it with TLS . **Live deploy progress** streamed to UI. **Deployment history** with full logs. **Templates for Redis, Postgres, MySQL, MongoDB, Adminer, Uptime Kuma, n8n, Vaultwarden**. **The most accessible open-source PaaS for homelabs** . 🏠

- **[Miabi](https://github.com/miabi-io/miabi)** [![Stars](https://img.shields.io/github/stars/miabi-io/miabi?style=social&color=white)](https://github.com/miabi-io/miabi/stargazers)  
  **Self-hosted PaaS with true workspace isolation and RBAC**, open-source. **Multiple clusters & locations** — one control plane drives many clusters . **Pipelines (pipeline-as-code CI/CD)**, **build runners**, and **GitOps with declarative manifests**. **Marketplace** with WordPress, Ghost, Nextcloud, n8n, Gitea, and more. **Privacy-first analytics** — cookieless, no consent banner, IPs never stored. **Enterprise features**: SAML 2.0, SCIM, LDAP/AD. **The most enterprise-ready open-source PaaS** . 🏢

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new container hosting platforms or open-source PaaS software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Container-Application-Hosting&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Container-Application-Hosting&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

If you find this container application hosting repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow developers, DevOps engineers, and open-source advocates.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **Google Cloud Run and Azure Container Apps scale to zero** — **$0 floor when idle** . **Azure Container Apps is built on Kubernetes, KEDA, Dapr, and Envoy** . **Cloud Run is built on Knative** for portability.
- **Coolify is the most popular open-source PaaS** with **62,000+ GitHub stars** . **Dokploy focuses on efficiency** with **37,381 GitHub stars** . **OpenRun brings declarative GitOps** to web app deployment .
- **Open-source PaaS tools (Coolify, Dokploy, OpenRun) are not turnkey** — they require **server provisioning, DNS configuration, and ongoing maintenance**. **Always validate deployment workflows with a proof-of-concept** before production deployment. 🚢

---

<p align="center">
  <b>Made with ❤️ for developers, DevOps engineers, and open-source application hosting advocates.</b>
</p>
