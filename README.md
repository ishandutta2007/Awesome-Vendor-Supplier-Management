# Awesome-Vendor-Supplier-Management

# Awesome Vendor & Supplier Management

> A curated list of top Vendor and Supplier Management platforms — both SaaS/Hosted commercial solutions and open-source alternatives for managing supplier relationships, procurement workflows, and vendor risk.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Coupa Supplier Management](#coupa-supplier-management)
  - [SAP Ariba Supplier Management](#sap-ariba-supplier-management)
  - [Tipalti Supplier Portal](#tipalti-supplier-portal)
  - [Precoro](#precoro)
  - [Gatekeeper](#gatekeeper)
  - [Jaggaer](#jaggaer)
  - [Ivalua](#ivalua)
  - [Vendr](#vendr)
- [Open-Source Software](#-open-source-software)
  - [Procuman Community Edition](#procuman-community-edition)
  - [Shillinq](#shillinq)
  - [Supplier MCP Server](#supplier-mcp-server)
  - [VendorBridge AI](#vendorbridge-ai)
  - [VendSync](#vendsync)
  - [SevenSquare Vendor Management System](#sevensquare-vendor-management-system)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Vendor and Supplier Management platforms. These are not open-source but are included as reference points for feature comparison.

### Coupa Supplier Management
**Type:** Enterprise spend management and supplier portal  
Coupa provides a comprehensive supplier management module within its broader spend management platform, covering supplier onboarding, information management, performance tracking, and risk monitoring. The platform is widely adopted by large enterprises for procurement and spend control.

### SAP Ariba Supplier Management
**Type:** Enterprise supplier lifecycle and risk management  
SAP Ariba offers supplier lifecycle management, qualification, segmentation, and risk monitoring as part of its extensive procurement suite. Deeply integrated with SAP ERP and widely used in large, complex organizations requiring global supplier governance.

### Tipalti Supplier Portal
**Type:** Supplier onboarding and payment automation  
Tipalti provides a supplier portal focused on onboarding, tax compliance (W-9/W-8), payment method collection, and mass payment automation. Suited for finance teams managing high volumes of supplier payments across borders.

### Precoro
**Type:** Procurement and supplier management for mid-market  
Precoro offers procurement automation with supplier management, purchase orders, approvals, and budget control. Positioned for mid-sized companies wanting accessible procurement software without enterprise complexity.

### Gatekeeper
**Type:** Vendor and contract lifecycle management  
Gatekeeper combines vendor management with contract lifecycle management, focusing on supplier onboarding, due diligence, renewals, and spend visibility. Suited for organizations needing unified vendor and contract governance.

### Jaggaer
**Type:** Enterprise procurement and supplier network  
Jaggaer provides a suite of procurement solutions including supplier management, sourcing, contract management, and spend analytics. Often deployed in manufacturing, healthcare, and public sector organizations.

### Ivalua
**Type:** Source-to-pay and supplier management platform  
Ivalua offers a unified source-to-pay platform with supplier management, sourcing, contracts, and procurement. Known for configurability and used by large enterprises with complex supply chains.

### Vendr
**Type:** SaaS procurement and negotiation (now part of Vertice)  
Vendr was acquired by Vertice and is now part of Vertice's Intake-to-Procure platform. Focused on SaaS vendor negotiation and renewal management rather than general supplier management. Included here as a reference for the SaaS procurement category.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Vendor and Supplier Management tools. The open-source ecosystem for enterprise-grade SRM is limited; most available projects are procurement-focused extensions, hackathon projects, or early-stage platforms.

### Procuman Community Edition
**Stack:** PHP (EspoCRM extension) | **License:** Open Source (Community Edition)  
A free e-Procurement extension for the EspoCRM platform, providing supplier management, product catalog, and purchase order management . Features include a comprehensive supplier database with contact information and categorization, product catalog with supplier associations and pricing, streamlined PO creation with automated tax calculations, and professional PDF generation with customizable templates . Requires EspoCRM installed with PHP 8.3+ and MySQL/MariaDB. The Professional Edition adds requisitions, supplier portal, contract management, and e-tendering .  
**Best for:** Organizations already using EspoCRM wanting free procurement and supplier management capabilities without a separate platform.

### Shillinq
**Stack:** PHP (Nextcloud app) | **License:** Open Source  
A comprehensive open-source business administration suite for Nextcloud that includes procurement, supplier management, and contract management alongside bookkeeping and invoicing . Features include purchase orders and procurement workflows, supplier management with approval chains, supplier qualification management with configurable questionnaires and document requirements, supplier document management with certificate and compliance tracking, and contract repository with full-text search . Requires the OpenRegister app. The free plan provides basic procurement management without cost.  
**Best for:** Organizations running Nextcloud wanting integrated supplier and procurement management within their existing self-hosted environment.

### Supplier MCP Server
**Stack:** Rust | **License:** Apache-2.0  
A Supplier Relationship Management (SRM) platform modeled as an MCP server for enterprise procurement and supply-chain agents, with 34 MCP tools spanning the full supply base lifecycle . Features include supplier lifecycle status (prospect → active → on-hold/suspended/disqualified), qualification tracking, certifications with expiry tracking, product catalog with multi-supplier pricing, purchase orders with approval gates (PO cannot be issued to unapproved suppliers), RFQ/sourcing with quote comparison, quality audits with auto-generated SCARs, performance scorecards (A–D rating), and supply-risk monitoring . Includes a full audit trail and governance gates on high-impact writes. Available on crates.io.  
**Best for:** Developers building AI agent-driven procurement systems who need a structured SRM backbone with governance and audit capabilities.

### VendorBridge AI
**Stack:** React / Node.js / MongoDB | **License:** Open Source (per GitHub)  
An AI-powered procurement and vendor management ERP built as a hackathon project . Features include vendor management with AI-powered risk scoring based on performance metrics, RFQ management, quotation management, AI quotation comparison with vendor ranking (price, delivery speed, reliability), multi-stage approval workflows, purchase orders auto-generated from accepted quotations, invoice management, and activity logs for audit trails . Role-based access covers Admin, Manager, Procurement Officer, and Vendor.  
**Note:** This is a hackathon project; review maturity and security before production use.  
**Best for:** Teams wanting a reference implementation or starting point for AI-assisted vendor management workflows.

### VendSync
**Stack:** React / Node.js / MongoDB | **License:** Open Source (per GitHub)  
A full-stack Procurement and Vendor Management ERP built for a hackathon, digitizing the purchasing process from RFQ creation to invoice generation . Features include role-based access (Admin, Manager, Procurement Officer, Vendor), vendor portal for self-service quotation submission, RFQ management, quotation engine with side-by-side comparison, multi-tier approval workflows with remarks, auto-generated purchase orders, invoice generation with tax calculations, PDF export, and real-time analytics with audit trail .  
**Note:** Hackathon project; evaluate maturity before production.  
**Best for:** Teams wanting a functional reference for procurement workflows with vendor portal and approval chains.

### SevenSquare Vendor Management System
**Stack:** Laravel (PHP) / Electron / MySQL | **License:** Open Source (per GitHub)  
A vendor management system packaged as a desktop application via Electron, designed to manage suppliers, contracts, and purchase orders . Features include vendor profiles with contact details and payment terms, contract management with renewal alerts and document uploads, purchase order management with status tracking, and reporting for vendor performance and contract renewals .  
**Best for:** Small organizations wanting a desktop-packaged vendor management tool with contract tracking and PO management.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Supplier Portal | PO/Procurement | Self-Hosted | Best For |
|----------|---------|-------|-----------------|----------------|-------------|----------|
| **Coupa** | Proprietary | Cloud | ✅ | ✅ | ❌ | Enterprise spend management |
| **SAP Ariba** | Proprietary | Cloud | ✅ | ✅ | ❌ | Global supplier governance |
| **Tipalti** | Proprietary | Cloud | ✅ | (Payments) | ❌ | Supplier payments + tax |
| **Precoro** | Proprietary | Cloud | ✅ | ✅ | ❌ | Mid-market procurement |
| **Gatekeeper** | Proprietary | Cloud | ✅ | (Contracts) | ❌ | Vendor + contract lifecycle |
| **Jaggaer** | Proprietary | Cloud | ✅ | ✅ | ❌ | Enterprise procurement suite |
| **Ivalua** | Proprietary | Cloud | ✅ | ✅ | ❌ | Source-to-pay configurability |
| **Procuman CE** | Open Source | PHP/EspoCRM | ❌ | ✅ | ✅ | EspoCRM users |
| **Shillinq** | Open Source | PHP/Nextcloud | (Approval chains) | ✅ | ✅ | Nextcloud + procurement |
| **Supplier MCP** | Apache-2.0 | Rust | ❌ | ✅ (Gated) | ✅ | AI agent SRM backbone |
| **VendorBridge AI** | Open Source | React/Node | ✅ (Vendor role) | ✅ | ✅ | Reference implementation |
| **VendSync** | Open Source | React/Node | ✅ (Vendor role) | ✅ | ✅ | Reference implementation |
| **SevenSquare VMS** | Open Source | Laravel/Electron | ❌ | ✅ | ✅ (Desktop) | Desktop vendor + contracts |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Vendor or Supplier Management tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem for dedicated enterprise Supplier Relationship Management (SRM) is very limited; most available projects are procurement extensions for existing platforms (EspoCRM, Nextcloud), AI/agent-focused tools, or early-stage hackathon implementations rather than mature Coupa/Ariba alternatives.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
