# Awesome-Document-Management-System-DMS

# Top Document Management System (DMS) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Document Capture, Records Management & Enterprise Content Governance*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Document Management Systems (DMS)**. These tools enable organizations to capture, index, store, and retrieve documents at scale—from enterprise content platforms with workflow automation and compliance controls to self-hosted archivers that turn physical paper into searchable digital libraries.

**Examples** include Adobe Acrobat, Kofax, DocuWare, OpenText Documentum, Hyland OnBase, Laserfiche, Box Enterprise, M-Files, FileNet, and NetDocuments (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, OCR-powered indexing, and open records management—ideal for organizations seeking transparent, data-sovereign document infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Adobe Acrobat](https://www.adobe.com/acrobat.html)**  
  PDF-centric document platform with editing, e-signatures, and cloud storage. **Pricing**: Standard **$12.99/month** (annual) or **$19.99/month** (monthly); Pro **$19.99/month** annual (or **$29.99** monthly). **Free tier**: **7-day free trial** with full features; limited free tools available online. **Best for**: teams needing PDF editing and e-signature workflows.

- **[Kofax (Tungsten Automation)](https://www.tungstenautomation.com/)**  
  Intelligent automation platform with document capture, OCR, and workflow. **Pricing**: Quote-only enterprise contracts; no public pricing. **Free tier**: No free tier; demo and trial available on request. **Best for**: high-volume document capture and AP automation.

- **[DocuWare](https://start.docuware.com/)**  
  Cloud document management and workflow automation. **Pricing**: **Cloud Base from $125/month** (5 users, 20 GB storage); **On-Premise from ~$2,500 one-time** for 5 users. **Free tier**: **30-day free trial** with full features. **Best for**: SMBs wanting cloud DMS with workflow.

- **[OpenText Documentum](https://www.opentext.com/)**  
  Enterprise content management platform for regulated industries. **Pricing**: Quote-only; no public pricing. **Free tier**: No free tier; evaluation on request. **Best for**: large enterprises with complex compliance needs.

- **[Hyland OnBase](https://www.hyland.com/)**  
  Enterprise content services platform with workflow, capture, and records management. **Pricing**: Quote-only; no public pricing. **Free tier**: No free tier; demo available. **Best for**: healthcare, government, and financial services.

- **[Laserfiche](https://www.laserfiche.com/)**  
  Cloud and self-hosted DMS with workflow, forms, and analytics. **Pricing**: **Cloud from $165/month** (5 users); **Self-hosted from ~$1,200 one-time**. **Free tier**: **Free trial** available; limited free plan for education. **Best for**: mid-market organizations wanting configurable DMS.

- **[Box Enterprise](https://www.box.com/)**  
  Cloud content management and collaboration platform. **Pricing**: **Business Starter from $5/user/month** (annual); **Business from $15/user/month**. **Free tier**: **Free plan** with 10 GB storage and 250 MB file upload limit. **Best for**: teams wanting content collaboration with governance.

- **[M-Files](https://www.m-files.com/)**  
  Metadata-driven DMS with intelligent information management. **Pricing**: Quote-only; no public pricing. **Free tier**: **Free trial** available; no perpetual free tier. **Best for**: organizations wanting metadata-based organization.

- **[FileNet (IBM)](https://www.ibm.com/products/filenet)**  
  Enterprise content management platform for high-volume document processing. **Pricing**: Quote-only; no public pricing. **Free tier**: No free tier; evaluation on request. **Best for**: large enterprises with existing IBM infrastructure.

- **[NetDocuments](https://www.netdocuments.com/)**  
  Cloud DMS for legal and professional services. **Pricing**: Quote-only; typically **$30-50/user/month**. **Free tier**: No free tier; demo available. **Best for**: law firms and legal departments.

## Open-Source GitHub Projects

- **[Paperless-ngx](https://github.com/paperless-ngx/paperless-ngx)**  
  **Community-supported supercharged digital document archiver** (GPL-3.0) — **the most widely adopted open-source DMS** . **Transforms physical documents into a searchable online archive**—scan, index, and retrieve from a web interface. **Features**: **OCR** for scanned documents, **full-text search**, **tags and correspondents** for organization, **email integration**, and **machine learning** for automatic tagging. **Docker Compose deployment** with one-line install script . **The reference implementation for personal and small-team document archiving**—**choose when you want a battle-tested, actively maintained DMS with a large community**. **Note**: **data is stored in clear text without encryption**—run only on trusted hosts .

- **[Mayan EDMS](https://github.com/mayan-edms/Mayan-EDMS)**  
  **Leading enterprise-grade free and open source electronic document management system** (Apache-2.0) — **the enterprise-scale choice** . **Continuous development since 2011**, **200+ releases**, **100+ contributors**, and **millions of container downloads** . **Proven at scale**—documented multi-million-document government migrations, and the Event Horizon Telescope collaboration (first black hole image) used a customized deployment . **90+ application modules** covering capture, processing, organization, search, automation, and security . **Fine-grained permissions, document versions, workflows, retention policies, metadata, and indexing** . **REST API** for integration. **The reference implementation for enterprise open-source DMS**—**choose when you need mature document controls and proven scale** .

- **[Docspell](https://github.com/eikek/docspell)**  
  **Open-source personal document organizer and DMS** (GPL-3.0) — **the smart-tagging choice** . **Simplifies organization of scanned papers, emails, and files**—associates tags, correspondents, and custom metadata, with **machine learning** automating metadata addition . **Features**: **OCR**, **full-text search**, **email integration**, **REST/HTTP API**, **webhooks**, **periodic queries**, **sharing**, and **multi-organization/person management** . **Best for**: families, households, and smaller groups or companies wanting intelligent document organization .

- **[LogicalDOC Community Edition](https://github.com/logicaldoc/logicaldoc)**  
  **Web-based open-source document management software** (LGPL-3.0) — **the mature Java choice** . **Version 9.2** adds **API Key Authentication**, **Markdown file support**, **PREVIEW permission layer**, **customizable log levels**, and **Java 21 support** . **Features**: **multi-language full-text indexing**, **version control**, **workflow light**, **SOAP/REST APIs**, **WebDAV and CMIS interfaces**, and **native mobile apps** . **Docker image available** . **Best for**: organizations wanting a mature, Java-based DMS with standard integrations .

- **[OpenKM Community Edition](https://github.com/openkm/document-management-system)**  
  **Open-source document management system** (GPL-2.0 for versions prior to 7.0) — **the legacy choice with a caveat** . **15+ years of development**—centralized repository, version control, metadata, search, permissions, auditing, and workflow . **Important change**: **starting with v7.0 (March 2026), OpenKM CE is distributed as a free binary without source code access**—earlier versions retain their original licenses . **Best for**: teams wanting a free binary DMS; **those needing source code should use versions prior to 7.0 or choose another project** .

- **[Teedy](https://github.com/sismics/docs)**  
  **Lightweight document management system packed with all the features you can expect from big expensive solutions** (GPL-2.0) — **the lightweight choice** . **Open-source DMS for individuals and businesses** with document management, OCR, and search capabilities . **Best for**: small teams wanting a lightweight, self-hosted DMS without the overhead of enterprise platforms .

- **[Nuxeo Platform](https://github.com/nuxeo/nuxeo)**  
  **Open-source enterprise content management platform** (Apache-2.0) — **the extensible Java EE choice** . **Service-oriented architecture** with components providing configurable services—build complex ECM applications by assembling components . **Features**: **document management, collaboration, versioning, relations, access rights, and publication workflows** . **Web Services (SOAP, REST, WebDAV)** for integration with non-Java technologies . **Clustering and high-availability** support for large-scale deployments . **Best for**: enterprises wanting a highly extensible ECM platform .

- **[Alfresco Community Edition](https://github.com/Alfresco/alfresco-community-repo)**  
  **Open-source enterprise content management** (LGPL-3.0) — **the document management heritage choice** . **Used by the European Commission's CIRCABC platform**—migrated from Alfresco Enterprise to Community Edition for long-term maintainability and technological independence . **Features**: **document management, records management, workflow, and collaboration** . **Best for**: organizations wanting a mature ECM platform with European open-source governance validation .

### Additional Strong Open-Source Options

- **[ScanTailor-Experimental](https://github.com/ImageProcessing-ElectronicPublications/scantailor-experimental)** — **Interactive post-processing tool for scanned pages** (GPL-3.0) — **the scanning companion** . **Page splitting, deskewing, border adjustments, and content selection**—turns raw scans into print-ready pages for PDF or DJVU . **Best for**: digitization projects that need to clean up scans before archiving .
- **Tesseract OCR** — **Open-source OCR engine** (Apache-2.0) — **the text extraction standard** beneath most open-source DMS. **Best for**: extracting searchable text from scanned documents.
- Community **n8n** workflows for document ingestion automation and retention policy alerts.

**Frameworks for building custom systems**: Combine **Paperless-ngx** for personal and small-team archiving with **Mayan EDMS** for enterprise-scale document controls, **Docspell** for smart-tagging workflows, **LogicalDOC** for Java-based standard integrations, and **Tesseract** for OCR—creating a comprehensive open-source DMS stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Document management systems handling enterprise records must comply with data protection regulations (GDPR, CCPA, HIPAA, etc.) and records retention requirements.
- **The "personal archiver vs. enterprise EDMS" distinction matters.** **Paperless-ngx and Docspell** are optimized for **personal and small-team document archiving**—fast setup, OCR, and search, but **not designed for enterprise records management** . **Mayan EDMS, LogicalDOC, and Nuxeo** are **enterprise-grade**—fine-grained permissions, workflows, retention policies, and proven scale . **Choose based on whether you're digitizing a household or managing regulated records.**
- **Paperless-ngx stores data in clear text without encryption**—the documentation explicitly warns against running it on untrusted hosts . **If you need encryption at rest, Mayan EDMS or a self-hosted stack with encrypted storage is the safer choice.**
- **OpenKM CE's distribution model changed in v7.0.** **Starting March 2026, it's a free binary without source code access**—earlier versions remain open source . **If source code access matters for your compliance or customization needs, choose another project.**
- **Mayan EDMS is the enterprise open-source leader.** **Continuous development since 2011, 90+ modules, and proven multi-million-document deployments**—including the Event Horizon Telescope collaboration . **The trade-off is complexity**—more configuration than Paperless-ngx.
- Self-hosted open-source solutions require proper backup strategies, storage provisioning, and ongoing maintenance. **Documents are your institutional memory**—data loss is often irreversible.

---

**Made for records managers, IT administrators, and organizations building transparent document management solutions.**  
Let's make Document Management Systems more open, data-driven, and searchable.
